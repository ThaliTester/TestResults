#### Test 50650278654db8c_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 6428): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6428):  
I/SELinux ( 6428):  
I/SELinux ( 6428): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6428): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6428): >>>>> Normal User
E/dalvikvm( 6428): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6428): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6428): in addTimaSignatureService
D/TimaKeyStoreProvider( 6428): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6428): Added TimaKesytore provider
D/com.sec.android.app.shealth.SHealthApplication( 6410): Success during batch insertion in App registry:0
D/dalvikvm( 6428): GC_CONCURRENT freed 3001K, 31% free 9569K/13732K, paused 3ms+2ms, total 21ms
D/dalvikvm( 6428): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/MediaPlayer( 6410): decode(56, 30565892, 48105)
V/MediaPlayerService( 1925): decode(26, 30565892, 48105)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30565892, 48105)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3220, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f3220, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3220, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3220, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3220, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3220, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3220, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3220, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x36, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(58, 30501792, 10421)
V/MediaPlayerService( 1925): decode(26, 30501792, 10421)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30501792, 10421)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad228, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x441ad228, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad228, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad228, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad228, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad228, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad228, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad228, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(59, 34044116, 34198)
V/MediaPlayerService( 1925): decode(26, 34044116, 34198)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 34044116, 34198)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6b30, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x442b6b30, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6b30, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6b30, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6b30, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6b30, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6b30, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6b30, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(60, 30449260, 7405)
V/MediaPlayerService( 1925): decode(27, 30449260, 7405)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(27, 30449260, 7405)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad800, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x441ad800, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad800, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad800, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad800, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad800, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad800, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ad800, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(61, 34134748, 5555)
V/MediaPlayerService( 1925): decode(27, 34134748, 5555)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(27, 34134748, 5555)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444ef0e0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444ef0e0, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444ef0e0, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444ef0e0, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444ef0e0, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444ef0e0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444ef0e0, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444ef0e0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(62, 26954540, 5085)
V/MediaPlayerService( 1925): decode(26, 26954540, 5085)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 26954540, 5085)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f1698, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f1698, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f1698, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f1698, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f1698, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f1698, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f1698, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): addBatteryData
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f1698, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(63, 26959684, 21552)
V/MediaPlayerService( 1925): decode(26, 26959684, 21552)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 26959684, 21552)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3328, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f3328, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3328, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3328, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3328, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3328, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3328, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): addBatteryData
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f3328, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(64, 34130460, 4230)
V/MediaPlayerService( 1925): decode(26, 34130460, 4230)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 34130460, 4230)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbe28, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444fbe28, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbe28, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbe28, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 1925): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbe28, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbe28, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbe28, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbe28, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(65, 26923896, 9400)
V/MediaPlayerService( 1925): decode(26, 26923896, 9400)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 26923896, 9400)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2330, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x442b2330, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2330, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2330, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 1925): open(44100, 1, 0x0, 1, 4)
I/SELinux ( 6490): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6490):  
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2330, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
--------- beginning of /dev/log/system
I/ActivityManager( 2400): Killing 5178:com.android.email/u0a157 (adj 15): empty #43
I/ActivityManager( 2400): Killing 5105:com.sec.android.app.camera/u0a149 (adj 15): empty #44
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2330, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2330, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2330, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
I/SELinux ( 6490): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6490):  
I/SELinux ( 6490):  
I/SELinux ( 6490): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
E/SELinux ( 6490): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6490): >>>>> Normal User
E/dalvikvm( 6490): >>>>> com.policydm [ userId:0 | appId:1000 ]
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(66, 30512272, 44276)
V/MediaPlayerService( 1925): decode(26, 30512272, 44276)
E/SELinux ( 6490): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30512272, 44276)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b0088, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x442b0088, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b0088, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b0088, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b0088, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
D/dalvikvm( 6428): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4241b9f8, skipping init
I/SecureStorage( 6428): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6428): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage( 1963): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 6428
I/SecureStorage( 1963): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 6428): [INFO]: SPID(0x00000000)SS Daemon is running
D/TimaKeyStoreProvider( 6490): in addTimaSignatureService
D/TimaKeyStoreProvider( 6490): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6490): Added TimaKesytore provider
I/SecureStorage( 6428): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1963): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 6428
I/SecureStorage( 1963): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b0088, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b0088, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b0088, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(67, 30472480, 29256)
V/MediaPlayerService( 1925): decode(26, 30472480, 29256)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30472480, 29256)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ae108, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x441ae108, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ae108, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ae108, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ae108, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ae108, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ae108, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441ae108, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(68, 34078380, 52024)
V/MediaPlayerService( 1925): decode(26, 34078380, 52024)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 34078380, 52024)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f42c0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f42c0, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f42c0, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f42c0, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f42c0, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
D/dalvikvm( 6490): GC_CONCURRENT freed 3003K, 31% free 9564K/13732K, paused 3ms+1ms, total 21ms
D/dalvikvm( 6490): WAIT_FOR_CONCURRENT_GC blocked 13ms
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f42c0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f42c0, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f42c0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(69, 30556608, 9226)
V/MediaPlayerService( 1925): decode(26, 30556608, 9226)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30556608, 9226)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cdb10, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cdb10, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cdb10, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cdb10, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cdb10, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cdb10, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cdb10, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): addBatteryData
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cdb10, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6410): decode(70, 26989388, 4509)
V/MediaPlayerService( 1925): decode(26, 26989388, 4509)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 26989388, 4509)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6ed0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x442b6ed0, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6ed0, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6ed0, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6ed0, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/AudioPlayer( 1925): First fillBuffer call!!
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6ed0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6ed0, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6ed0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
D/AndroidRuntime( 6508): 
D/AndroidRuntime( 6508): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6508): CheckJNI is OFF
D/AndroidRuntime( 6508): setted country_code = Poland
D/AndroidRuntime( 6508): setted countryiso_code = PL
D/AndroidRuntime( 6508): setted sales_code = PLS
D/AndroidRuntime( 6508): readGMSProperty: start
D/AndroidRuntime( 6508): readGMSProperty: already setted!!
D/AndroidRuntime( 6508): readGMSProperty: end
D/AndroidRuntime( 6508): addProductProperty: start
D/dalvikvm( 6508): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6508): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6508): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6508): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6508): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 6537): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6537):  
I/ActivityManager( 2400): Killing 5170:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
I/SELinux ( 6537): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6537):  
I/SELinux ( 6537):  
I/SELinux ( 6537): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6537): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6537): >>>>> Normal User
E/dalvikvm( 6537): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux ( 6537): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 6537): in addTimaSignatureService
D/TimaKeyStoreProvider( 6537): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6537): Added TimaKesytore provider
E/memtrack( 6508): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6508): failed to load memtrack module: -2
D/dalvikvm( 6537): GC_CONCURRENT freed 2995K, 31% free 9567K/13728K, paused 4ms+1ms, total 26ms
D/dalvikvm( 6537): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/dalvikvm( 6508): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6508): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2400): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2400): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2400  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1921): id=17 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2400): mDVFSHelper.acquire()
I/SurfaceFlinger( 1921): id=18 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 6554): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6554):  
D/PointerIcon( 2400): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2400): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2400): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2400): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6508): Shutting down VM
D/dalvikvm( 6508): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 6554): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6554):  
I/SELinux ( 6554):  
I/SELinux ( 6554): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6554): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6554): >>>>> Normal User
E/dalvikvm( 6554): >>>>> com.test.thalitest [ userId:0 | appId:10550 ]
E/SELinux ( 6554): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6554): in addTimaSignatureService
D/TimaKeyStoreProvider( 6554): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6554): Added TimaKesytore provider
V/WindowManager( 2400): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4137): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4137): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (-2/10)
D/Launcher( 2775): onTrimMemory. Level: 20
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
D/dalvikvm( 6554): GC_CONCURRENT freed 3006K, 31% free 9563K/13732K, paused 2ms+2ms, total 22ms
D/dalvikvm( 6554): WAIT_FOR_CONCURRENT_GC blocked 19ms
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6537): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/ActivityManager( 2400): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6537): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/SELinux ( 6572): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6572):  
,V/WebViewChromium( 6554): Binding Chromium to the background looper Looper (main, tid 1) {42427450}
,I/chromium( 6554): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6554): Initializing chromium process, renderers=0
,I/SELinux ( 6572): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6572):  
I/SELinux ( 6572):  
,I/SELinux ( 6572): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6572): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6572): >>>>> Normal User
,E/dalvikvm( 6572): >>>>> com.osp.app.signin [ userId:0 | appId:10044 ]
,E/SELinux ( 6572): [DEBUG] seapp_context_lookup: seinfoCategory = default
,W/chromium( 6554): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/SecureStorage( 1963): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1963): [INFO]: SPID(0x00000003)PID: 6428, TID: 6441
,D/libEGL  ( 6554): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6554): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6554): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 6554): Mali API Version : 401
,I/Mali    ( 6554): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/TimaKeyStoreProvider( 6572): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6572): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6572): Added TimaKesytore provider
,D/dalvikvm( 6572): GC_CONCURRENT freed 2985K, 31% free 9580K/13728K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 6572): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/dalvikvm( 6554): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 6554): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6554): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6554): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6554): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6554): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2400): tr p:6554,o:f
W/dalvikvm( 6554): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6554): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6554): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6554): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6554): VFY: replacing opcode 0x6f at 0x001a
I/SecureStorage( 6428): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 6428): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 6428): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 6428): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 6428): Open platform.db in secure mode
W/dalvikvm( 6554): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6554): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6554): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 6554): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6554): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6554): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 6554): VFY: replacing opcode 0x6e at 0x0000
,I/ActivityManager( 2400): Killing 5201:com.sec.modem.settings/1000 (adj 15): empty #43
D/SystemWebViewEngine( 6554): CordovaWebView is running on device made by: samsung
,I/SA      ( 6572): [SSP] onCreated
,I/SA      ( 6572): [TPM] There is no property file
,I/SA      ( 6572): [SCU] isHaveSA() - false
,I/SA      ( 6572): [TPM] getModelProperty : null
,I/SA      ( 6572): [TPM] getCSCProperty : null
,I/SA      ( 6572): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 6572): [DM] init START
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2400): semi p:6554,o:f
,I/SA      ( 6572): [DM] This device is not a Vodafone
,I/SA      ( 6572): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6572): support phone number id : false
I/SA      ( 6572): [DM] init END
I/SA      ( 6572): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 6572): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager( 2400): Killing 4615:com.sec.android.provider.badge/u0a76 (adj 15): empty #43
,I/SQLiteSecureOpenHelper( 6428): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 6428): ...getDatabaseLocked(b,b,pwd)
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
,D/STATUSBAR-StatusBarManagerService( 2400): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2400): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2400): stay LED for fully charged
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/PointerIcon( 2400): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2400): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2400): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2400): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 6554): EGLImpl-HWUI Protected EGL context created
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/OpenGLRenderer( 6554): Enabling debug mode 0
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,W/AwContents( 6554): nativeOnDraw failed; clearing to background color.
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/Mms/PackageInstallReceiver( 5581): loadAuthorityPref(): sEnableAuthority = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/Icing.InternalIcingCorporaProvider( 5935): Updating corpora: A: com.test.thalitest, C: MAYBE
,W/AwContents( 6554): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2400): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2400  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2400): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2400): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2400  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 6554): showStatusIcon on inactive InputConnection
,I/SELinux ( 6619): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6619):  
,I/SELinux ( 6619): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6619):  
I/SELinux ( 6619):  
,I/SELinux ( 6619): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6619): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6619): >>>>> Normal User
,E/dalvikvm( 6619): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 6619): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6619): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6619): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6619): Added TimaKesytore provider
,D/dalvikvm( 6619): GC_CONCURRENT freed 3003K, 31% free 9567K/13732K, paused 6ms+2ms, total 29ms
,D/dalvikvm( 6619): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/Icing.InternalIcingCorporaProvider( 5935): UpdateCorporaTask done [took 224 ms] updated apps [took 224 ms] 
,W/ContextImpl( 6619): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 6634): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6634):  
,I/ActivityManager( 2400): Killing 5219:tv.peel.smartremote/u0a165 (adj 15): empty #43
,I/SELinux ( 6634): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6634):  
I/SELinux ( 6634):  
,I/SELinux ( 6634): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6634): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6634): >>>>> Normal User
,E/dalvikvm( 6634): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
,E/SELinux ( 6634): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 6634): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6634): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6634): Added TimaKesytore provider
,D/dalvikvm( 6634): GC_CONCURRENT freed 2994K, 31% free 9563K/13724K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 6634): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/CapabilityManagerService New( 6634): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
,D/JsMessageQueue( 6554): Set native->JS mode to OnlineEventsBridgeMode
,I/SELinux ( 6649): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6649):  
I/ActivityManager( 2400): Killing 5238:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,I/SELinux ( 6649): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6649):  
I/SELinux ( 6649):  
,I/SELinux ( 6649): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6649): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6649): >>>>> Normal User
,E/dalvikvm( 6649): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
,E/SELinux ( 6649): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6649): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6649): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6649): Added TimaKesytore provider
,D/dalvikvm( 6649): GC_CONCURRENT freed 2998K, 31% free 9564K/13724K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 6649): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/PackageIntentReceiver( 6649): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 6649): Not GearManger package! 
,D/dalvikvm( 6554): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4241e6e0
,I/SELinux ( 6661): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6661):  
D/dalvikvm( 6554): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4241e6e0
D/jxcore_app_log( 6554): JniHelper::setJavaVM(0x419ab220), pthread_self() = 2030916312
,D/JX-Cordova( 6554): jxcore cordova android initializing
I/ActivityManager( 2400): Killing 5264:com.sec.android.app.taskmanager/u0a168 (adj 15): empty #43
,I/SELinux ( 6661): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6661):  
I/SELinux ( 6661):  
,I/SELinux ( 6661): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6661): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6661): >>>>> Normal User
,E/dalvikvm( 6661): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
,E/SELinux ( 6661): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6661): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6661): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6661): Added TimaKesytore provider
,D/dalvikvm( 6661): GC_CONCURRENT freed 2995K, 31% free 9571K/13728K, paused 4ms+1ms, total 21ms
,D/dalvikvm( 6661): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/MagazineService Version( 6661): Magazine-Channel: 13
,D/MagazineService Version( 6661): Magazine-Provider: 13
,D/MagazineService Version( 6661): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 6661): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 6661): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,I/MagazineService::MagazineService( 6661): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/SELinux ( 6674): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6674):  
,D/MagazineService::MagazineService( 6661): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/SELinux ( 6674): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6674):  
I/SELinux ( 6674):  
,I/SELinux ( 6674): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6674): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6674): >>>>> Normal User
,E/dalvikvm( 6674): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 6674): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 12% free 9500K/10708K, paused 2ms+3ms, total 35ms
I/ActivityManager( 2400): Killing 5276:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
,D/dalvikvm( 6554): GC_CONCURRENT freed 1290K, 18% free 11346K/13796K, paused 4ms+27ms, total 92ms
,D/dalvikvm( 6554): WAIT_FOR_CONCURRENT_GC blocked 71ms
,D/TimaKeyStoreProvider( 6674): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9500K/10708K, paused 2ms+3ms, total 29ms
,D/TimaKeyStoreProvider( 6674): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6674): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9500K/10708K, paused 2ms+3ms, total 23ms
,D/dalvikvm( 6554): WAIT_FOR_CONCURRENT_GC blocked 93ms
,D/dalvikvm( 6674): GC_CONCURRENT freed 3004K, 31% free 9567K/13732K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 6674): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/CustomFrequencyManagerService( 2400): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2400  tag : ACTIVITY_RESUME_BOOSTER@8
,I/SELinux ( 6687): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6687):  
,I/ActivityManager( 2400): Killing 5303:com.gameloft.android.GloftGF2H/u0a179 (adj 15): empty #43
,I/SELinux ( 6687): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6687):  
I/SELinux ( 6687):  
,I/SELinux ( 6687): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6687): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6687): >>>>> Normal User
,E/dalvikvm( 6687): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
,E/SELinux ( 6687): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6687): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6687): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6687): Added TimaKesytore provider
,D/dalvikvm( 6687): GC_CONCURRENT freed 2990K, 31% free 9574K/13728K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 6687): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/KidsPlatformStub( 6687): Package not found : com.sec.android.app.kidshome
,I/Icing   ( 3313): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,I/SELinux ( 6699): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6699):  
I/ActivityManager( 2400): Killing 5316:com.gameloft.android.GloftKLMF/u0a180 (adj 15): empty #43
,I/SELinux ( 6699): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6699):  
I/SELinux ( 6699):  
,I/SELinux ( 6699): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6699): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6699): >>>>> Normal User
,E/dalvikvm( 6699): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 6699): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6699): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6699): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6699): Added TimaKesytore provider
,D/dalvikvm( 6699): GC_CONCURRENT freed 2994K, 31% free 9567K/13728K, paused 3ms+1ms, total 29ms
,D/dalvikvm( 6699): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/SELinux ( 6711): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6711):  
,I/ActivityManager( 2400): Killing 5329:com.gameloft.android.GloftPSHU/u0a181 (adj 15): empty #43
,I/SELinux ( 6711): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6711):  
I/SELinux ( 6711):  
,I/SELinux ( 6711): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6711): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6711): >>>>> Normal User
,E/dalvikvm( 6711): >>>>> com.sec.enterprise.knox.cloudmdm.smdms [ userId:0 | appId:10171 ]
,E/SELinux ( 6711): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6711): in addTimaSignatureService
,I/Icing   ( 3313): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,D/TimaKeyStoreProvider( 6711): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6711): Added TimaKesytore provider
,D/dalvikvm( 6554): GC_CONCURRENT freed 1916K, 18% free 14965K/18052K, paused 3ms+5ms, total 61ms
,D/dalvikvm( 6554): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 6711): GC_CONCURRENT freed 2998K, 31% free 9564K/13724K, paused 4ms+1ms, total 26ms
,D/dalvikvm( 6711): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/UMC:Core( 6711): onCreate(): 
,D/USER_AGENT( 6711): UMC/1.0.12 (SM-G800F) SAFE-5 KNOX-2.0
,D/[SAMSUNG SMARCART NATIVE]( 6711): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 6711): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/TZ_CCM_C_GetFunctionList: ( 6711): TZ_CCM_C_GetFunctionList was called
,D/[SAMSUNG SMARCART NATIVE]( 6711): FINISHED: initialize rv:0
,D/dalvikvm( 6711): GC_CONCURRENT freed 1856K, 22% free 10764K/13780K, paused 4ms+2ms, total 47ms
,D/UMC:SecurityUtils( 6711): Loaded server certificates: 0
,D/UMC:SecurityUtils( 6711): Loaded server certificates: 0
,D/UMC:CloudMDMSecurity( 6711): New Flow
D/TimaService( 2400): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService( 2400): TIMA: in getTimaVersion
I/        ( 2400): CCM JNI: In ccm_register_for_default_cert
I/        ( 2400): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: ( 2400): &ctx = 0x7bc74618
I/TLC_TZ_CCM: ( 2400): creating new ccm context...
I/TLC_TZ_CCM: ( 2400): initializing ccm context...
I/TLC_TZ_CCM: ( 2400): root = 0, root_strlen = 1
I/TLC_TZ_CCM: ( 2400): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2400): input max_sendmsg_size = 19420
I/TZ: client_server_communication( 2400): input max_recvmsg_size = 19420
I/TZ: client_server_communication( 2400): root = 0, root_len = 1
I/TZ: client_server_communication( 2400): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2400): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication( 2400): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication( 2400): Client_Server_Open was called
I/TZ: client_server_communication( 2400): IClientServer::IClientServer()
I/TZ: client_server_communication( 2400): BpClientServer::BpClientServer()
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 2509): creating new ccm context...
I/TZ_CCM_SERVER( 2509): initializing ccm context...
I/TZ_CCM_SERVER( 2509): root = 0, root_strlen = 1
I/TZ_CCM_SERVER( 2509): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2509): input max_sendmsg_size = 19420
I/TZ: mc_tlc_communication( 2509): input max_recvmsg_size = 19420
I/TZ: mc_tlc_communication( 2509): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2509): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2509): aligned max_sendmsg_size = 19456
I/TZ: mc_tlc_communication( 2509): aligned max_recvmsg_size = 19456
I/TZ: mc_tlc_communication( 2509): device_id = 0x0
I/TZ: mc_tlc_communication( 2509): tlc_open() was called
I/TZ: mc_tlc_communication( 2509): Opening MobiCore device
I/TZ: mc_tlc_communication( 2509): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2509): Opening the session
,I/TZ: mc_tlc_communication( 2509): tlc_open() succeeded
I/TZ: client_server_communication( 2400): Client_Server_Open succeeded
I/TZ_CCM_C_Initialize: ( 2400): ctx = 0x7ba35b38, comm = 0x7ba35b48, sendmsg = 0x7f3ee008, recvmsg = 0x7f3f2c08
,I/TZ_init: ( 2400): TZ_init: sending initialization request...
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(2) 16
,E/Parcel  ( 2509): nm 19456
E/Parcel  ( 2400): nm 19456
E/TZ_init: ( 2400): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 2400): trustlet initialization failed
,I/TZ_init: ( 2400): TZ_init_START...
,I/TZ_init: ( 2400): TZ_init_with_data: sending initialization request...
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(2) 16
,E/Parcel  ( 2509): nm 19456
,E/Parcel  ( 2400): nm 19456
I/TZ_init: ( 2400): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: ( 2400): Exercising TZ_DB_INIT in TLC
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(2) 16
,E/Parcel  ( 2509): nm 19456
E/Parcel  ( 2400): nm 19456
I/TZ_COMMON: tlc_key_db_util: ( 2400): DB Operation suceeded
,I/TLC_TZ_CCM: register for default cert: ( 2400): Exercising TZ_CCM_register_default_TLC
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(2) 16
,E/Parcel  ( 2509): nm 19456
,E/Parcel  ( 2400): nm 19456
I/TLC_TZ_CCM: register for default cert: ( 2400): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: ( 2400): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
,I/TZ_CCM_C_Finalize: ( 2400): Exercising TZ_CCM_C_Finalize_TLC
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(2) 16
,E/Parcel  ( 2509): nm 19456
,E/Parcel  ( 2400): nm 19456
I/TZ: client_server_communication( 2400): Client_Server_Close was called
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(1) 16
,I/TZ: mc_tlc_communication( 2509): tlc_close() was called
,I/TZ: mc_tlc_communication( 2509): Closing the session
,I/TZ: mc_tlc_communication( 2509): Free WSM
,I/TZ: mc_tlc_communication( 2509): Closing MobiCore device
,I/TZ: mc_tlc_communication( 2509): tlc_close() succeeded,
I/TZ: client_server_communication( 2400): Client_Server_Close succeeded
,D/UMC:CloudMDMSecurity( 6711): TIMA service call for password change success!!,
,D/UMC:AdminManager( 6711): init - start,
,D/UMC:AdminManager( 6711): loadAdmins,
,D/UMC:AdminManager( 6711): removeOutOfSyncProxyAdmins,
,D/UMC:AdminManager( 6711): startPolicyHandlers
,I/UMC:TestPolicyHandler( 6711): Setup is called in testpolicyhandler,
,D/UMC:AdminManager( 6711): init - end,
,V/UMC:AlarmHandler( 6711): Enter loadList,
,D/EnterpriseDeviceManagerService( 2400): Creating context as user 0,
,D/SPPApp  ( 6711): [SppMessageReceiver] onReceive,
,D/SPPApp  ( 6711): [SppMessageReceiver] onReceive. ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest,
,I/SELinux ( 6725): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6725):  
I/ActivityManager( 2400): Killing 5367:com.google.android.youtube/u0a175 (adj 15): empty #43
,D/dalvikvm( 6554): GC_FOR_ALLOC freed 5400K, 30% free 16206K/22988K, paused 55ms, total 62ms,
,I/SELinux ( 6725): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6725):  
I/SELinux ( 6725):  
I/SELinux ( 6725): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 6725): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6725): >>>>> Normal User
,E/dalvikvm( 6725): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ],
,E/SELinux ( 6725): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 6725): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6725): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6725): Added TimaKesytore provider,
,D/dalvikvm( 6725): GC_CONCURRENT freed 3002K, 31% free 9564K/13728K, paused 3ms+1ms, total 24ms,
,D/dalvikvm( 6725): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,D/ApplicationPromenada( 6725): Application OnCreate start,
,D/ApplicationPromenada( 6725): Application OnCreate po on Create,
D/CrashReporter( 6725): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@42415820
D/CrashReporter( 6725): Swaping uncaught exception handler,
,D/ApplicationPromenada( 6725): Application OnCreate App Loader start,
,D/ApplicationPromenada( 6725): Application OnCreate App Loader finish,
,D/p2.ApplicationLoader( 6725): ############################## cached apps: ,
,V/WebViewChromium( 6725): Binding Chromium to the background looper Looper (main, tid 1) {42426260},
,I/chromium( 6725): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserProcessMain( 6725): Initializing chromium process, renderers=0,
D/SSRMv2:SIOP( 2400): SIOP:: AP = 360, Delta = 20
,W/chromium( 6725): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation,
,D/libEGL  ( 6725): loaded /system/lib/egl/libEGL_mali.so,
,D/libEGL  ( 6725): loaded /system/lib/egl/libGLESv1_CM_mali.so,
,D/libEGL  ( 6725): loaded /system/lib/egl/libGLESv2_mali.so,
,I/Mali    ( 6725): Mali API Version : 401
,I/Mali    ( 6725): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,D/ApplicationPromenada( 6725): Application OnCreate Finish,
,I/SELinux ( 6756): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6756):  
I/ActivityManager( 2400): Killing 5515:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,I/SELinux ( 6756): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6756):  
I/SELinux ( 6756):  
,I/SELinux ( 6756): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6756): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,E/dalvikvm( 6756): >>>>> Normal User
E/dalvikvm( 6756): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10041 ]
,E/SELinux ( 6756): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 6756): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6756): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6756): Added TimaKesytore provider
,D/dalvikvm( 6756): GC_CONCURRENT freed 2999K, 31% free 9574K/13732K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 6756): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/ActivityManager( 2400): Killing 5606:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/PackageBroadcastService( 3313): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest,
D/ChimeraCfgMgr( 3313): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3313): Module APK com.google.android.play.games already loaded,
,D/ChimeraCfgMgr( 3313): Loading module com.google.android.gms.games from APK com.google.android.play.games,
,D/ChimeraModuleLdr( 3313): Module APK com.google.android.play.games already loaded,
,D/ChimeraCfgMgr( 3313): Loading module com.google.android.gms.gass from APK com.google.android.gms,
,D/AsyncTaskServiceImpl( 3313): Submit a task: k,
,D/dalvikvm( 6725): GC_CONCURRENT freed 1761K, 22% free 10827K/13736K, paused 2ms+3ms, total 74ms,
,D/ChimeraCfgMgr( 3313): Loading module com.google.android.gms.gass from APK com.google.android.gms,
,D/ChimeraCfgMgr( 3313): Loading module com.google.android.gms.vision from APK com.google.android.gms,
,D/k       ( 3313): Processing package: com.test.thalitest,
,D/GassUtils( 3313): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe,
,D/k       ( 3313): Found info for package com.test.thalitest in db.
D/dalvikvm( 6554): GC_CONCURRENT freed 6696K, 31% free 17671K/25560K, paused 1ms+16ms, total 87ms
,D/dalvikvm( 6554): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/dalvikvm( 2400): GC_EXPLICIT freed 23862K, 72% free 24484K/87256K, paused 22ms+19ms, total 323ms
,D/Finsky  ( 3879): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/AmoledAdjustTimer( 2400): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/dalvikvm( 6554): GC_FOR_ALLOC freed 1476K, 33% free 17363K/25560K, paused 40ms, total 40ms
,I/dalvikvm-heap( 6554): Grow heap (frag case) to 21.627MB for 3713210-byte allocation
,D/dalvikvm( 6554): GC_FOR_ALLOC freed 24K, 29% free 20965K/29188K, paused 37ms, total 37ms
,W/jxcore-log( 6554): Initializing JXcore engine
,W/jxcore-log( 6554): JXcore engine is ready
,W/jxcore-log( 6554): Starting JXcore engine
,D/dalvikvm( 6725): GC_CONCURRENT freed 2360K, 26% free 10416K/13948K, paused 2ms+2ms, total 27ms
,W/ResourceType( 6725): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75)
,W/PackageManager( 6725): Failure retrieving text 0x7f060000 in package com.android.keyguard
W/PackageManager( 6725): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 6725): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 6725): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 6725): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 6725): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 6725): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 6725): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 6725): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125)
W/PackageManager( 6725): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 6725): 	at java.lang.Thread.run(Thread.java:841)
,W/jxcore-log( 6554): Platform android
W/jxcore-log( 6554): 
,W/jxcore-log( 6554): Process ARCH arm
W/jxcore-log( 6554): 
,D/dalvikvm( 6725): GC_CONCURRENT freed 2073K, 26% free 10364K/13948K, paused 4ms+2ms, total 46ms
,I/Icing   ( 3313): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/Icing   ( 3313): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/p2.ApplicationLoader( 6725): Process time: 2521
,D/p2.ApplicationLoader( 6725): ##############################  apps after loading: 
,D/dalvikvm( 6725): GC_CONCURRENT freed 2196K, 28% free 10107K/13948K, paused 3ms+2ms, total 33ms
,I/jxcore-log( 6554): JXcore Cordova bridge is ready!
I/jxcore-log( 6554): 
,W/jxcore-log( 6554): JXcore engine is started
,I/chromium( 6554): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6554): Toggling radios to true
I/jxcore-log( 6554): 
,W/ActivityManager( 2400): Permission Denial: getCurrentUser() from pid=6554, uid=10550 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 2400): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 2400): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6554, uid=10550 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 2400): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/BluetoothManagerService( 2400): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService( 2400): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 2400): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService( 2400): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService( 2400): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService( 2400): foregroundUser: 0
,E/BluetoothManagerService( 2400): Package is exist.
I/WifiManager( 6554): packageName : com.test.thalitest
,D/BluetoothAdapterState( 5090): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 5090): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5090): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5090): updateAdapterState state is 11
D/BluetoothAdapterService( 5090): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 5090): Autoconnection is available 
,D/BluetoothAdapterService( 5090): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 5090): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5090): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5090): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/InputMethodManagerService( 2400): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2400): [BT Setting State] State =11
W/BluetoothAdapterService( 5090): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
I/SamsungIME( 2976): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService( 5090): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
I/WifiManager( 6554): setWifiEnabled : true
I/QuickConnect[1.1][2] ( 5064): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
,I/WifiService( 2400): setWifiEnabled: true pid=6554, uid=10550
W/BluetoothAdapterService( 5090): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/ActivityManager( 2400): Permission Denial: getCurrentUser() from pid=6554, uid=10550 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2400): Failed getting userId using ActivityManagerNative
W/WifiService( 2400): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6554, uid=10550 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2400): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2400): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2400): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2400): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2400): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2400): 	at dalvik.system.NativeStart.run(Native Method)
W/BluetoothAdapterService( 5090): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5090): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
I/WifiService( 2400): disconnect: pid=6554, uid=10550
E/WifiHW  ( 2400): ##################### set firmware type 0 #####################
W/BluetoothAdapterService( 5090): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5090): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 5090): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5090): Not skipping com.android.bluetooth.hfp.HeadsetService
I/jxcore-log( 6554): Radios toggled
I/jxcore-log( 6554): 
I/WifiHW  ( 1915): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
E/WifiHW  ( 1915): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 1915): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 1915): TEMP_FAILURE_RETRY complete
,D/SoftapController( 1915): Softap fwReload - Ok
,W/BluetoothAdapterService( 5090): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5090): Not skipping com.android.bluetooth.a2dp.A2dpService
D/CommandListener( 1915): Setting iface cfg
,D/CommandListener( 1915): Trying to bring down wlan0
,I/jxcore-log( 6554): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 6554): 
,W/BluetoothAdapterService( 5090): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5090): Not skipping com.android.bluetooth.hid.HidService
D/WifiHW  ( 2400): Skip the update_ctrl_interface
,D/WifiHW  ( 2400): Skip the update_ctrl_interface
W/BluetoothAdapterService( 5090): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5090): Not skipping com.android.bluetooth.hdp.HealthService
,I/jxcore-log( 6554): Perf Test app loaded loaded
I/jxcore-log( 6554): 
W/BluetoothAdapterService( 5090): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,I/jxcore-log( 6554): check test folder
I/jxcore-log( 6554): 
,W/BluetoothAdapterService( 5090): Not skipping com.android.bluetooth.pan.PanService
,D/HeadsetService( 5090): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 5090): classInitNative: succeeds
D/HeadsetStateMachine( 5090): Version 1.5
,D/HeadsetStateMachine( 5090): make
,I/jxcore-log( 6554): found test : ./testFindPeers.js
I/jxcore-log( 6554): 
,D/BluetoothNotiBroadcastReceiver( 5566): onReceive
,E/WifiHW  ( 2400): supplicant_name : p2p_supplicant
,E/HeadsetStateMachine( 5090): # of Max HF connection is 2
,D/WifiMonitor( 2400): startMonitoring(wlan0) with mConnected = false
,W/BluetoothAdapterService( 5090): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5090): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/QuickConnect[1.1][2] ( 5064): HeadsetProfile.onServiceConnected - Bluetooth service connected
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/wpa_supplicant( 6781): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
W/BluetoothAdapterService( 5090): check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5090): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5090): Not skipping com.broadcom.bt.service.sap.SapService
I/wpa_supplicant( 6781): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6781): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 6781): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 6781): getIMSI cannot open file
,E/wpa_supplicant( 6781): Interworking config: - SIM READ ERROR
,I/SELinux ( 6782): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6782):  
,I/bluedroid( 5090): get_profile_interface handsfree
,I/BluetoothAdapterState( 5090): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/jxcore-log( 6554): found test : ./testSendData.js
I/jxcore-log( 6554): 
I/SELinux ( 6782): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6782):  
I/SELinux ( 6782):  
,I/SELinux ( 6782): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6782): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6782): >>>>> Normal User
,E/dalvikvm( 6782): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ]
,E/SELinux ( 6782): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/dalvikvm( 6782): Enabling JNI app bug workarounds for target SDK version 7...
,D/BluetoothAtMessage( 5090): createCMTIContentObservers
,D/HeadsetStateMachine( 5090): Enter Disconnected: -2
,E/HeadsetStateMachine( 5090): set to mRemoteBrsf = 0
,D/TimaKeyStoreProvider( 6782): in addTimaSignatureService
,D/HeadsetStateMachine( 5090): map size, before remove : 0
D/HeadsetStateMachine( 5090): map size, after remove: 0
,D/HeadsetStateMachine( 5090): mNextConnectingDevice : null
,D/BluetoothA2dp( 2400): Proxy object connected
D/A2dpService( 5090): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 5090): classInitNative: succeeds
,D/A2dpStateMachine( 5090): make
,D/TimaKeyStoreProvider( 6782): Cannot add TimaSignature Service, License check Failed
,D/BluetoothA2dp( 5064): Proxy object connected
,D/ActivityThread( 6782): Added TimaKesytore provider
,D/QuickConnect[1.1][2] ( 5064): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/BluetoothA2dp( 4137): Proxy object connected
,I/bluedroid( 5090): get_profile_interface a2dp
,I/GKI_LINUX( 5090): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 5090): Enter Disconnected: -2
,I/BluetoothAvrcpServiceJni( 5090): classInitNative: succeeds
,I/bluedroid( 5090): get_profile_interface avrcp
,D/MediaFocusControl( 2400): >>> registerRemoteControlDisplay
,I/wpa_supplicant( 6781): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 6781): getIMSI cannot open file
,E/wpa_supplicant( 6781): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 6781): >>>>> Not GET KEY, IV <<<<<
,I/BluetoothHidServiceJni( 5090): classInitNative: succeeds
,I/wpa_supplicant( 6781): rfkill: Cannot open RFKILL control device
,D/BluetoothInputDevice( 5064): Proxy object connected
D/HidService( 5090): Received start request. Starting profile...
,I/bluedroid( 5090): get_profile_interface hidhost
,D/HidService( 5090): setHidService(): set to: null
I/BluetoothHealthServiceJni( 5090): classInitNative: succeeds
,D/QuickConnect[1.1][2] ( 5064): HidProfile.onServiceConnected - Bluetooth service connected
,D/HealthService( 5090): Received start request. Starting profile...
,I/bluedroid( 5090): get_profile_interface health
,I/BluetoothPanServiceJni( 5090): classInitNative(L105): succeeds
,D/BluetoothPan( 2400): BluetoothPAN Proxy object connected
,D/PanService( 5090): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5090): initializeNative(L110): pan
,I/bluedroid( 5090): get_profile_interface pan
,D/BluetoothTethering( 2400): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 5090): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 5090): mAccount : null
,I/BluetoothSAPServiceJni( 5090): classInitNative(L204): succeeds
,D/SapService( 5090): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 5090): initializeNative(L209): sap
,I/bluedroid( 5090): get_profile_interface sap
,D/HeadsetStateMachine( 5090): Try to query the phonestate on bind
D/BluetoothPhoneService( 2753): handleMessage: 4
,V/BluetoothPhoneService( 2753): Call state Converted2: IDLE/IDLE -> 6
,W/BluetoothHeadset( 2753): Proxy not attached to service
,D/HeadsetStateMachine( 5090): Proxy object connected
,D/HeadsetPhoneState( 5090): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 5090): sendDeviceDataStateChanged
D/HeadsetStateMachine( 5090): Disconnected process message: 11
,D/HeadsetStateMachine( 5090): Disconnected process message: 20
D/HeadsetPhoneState( 5090): Signal level : previous=0 curr=0
V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
D/HeadsetPhoneState( 5090): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5090): Disconnected process message: 11
D/BluetoothAdapterService( 5090): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5090): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5090): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5090): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5090): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5090): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterState( 5090): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5090): enable
,D/GKI_LINUX( 5090): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 5090): Calling BTA_HhEnable
,E/bt-btif ( 5090): btif_storage_get_adapter_property service_mask:0x160040
,E/BluetoothServiceJni( 5090): populateRssiValuesNative
I/bluedroid( 5090): getModelRssiValues
,E/BluetoothServiceJni( 5090): model_rssi_values_callback: low = -75, mid = -65, high = 127
,D/dalvikvm( 6782): GC_CONCURRENT freed 3002K, 31% free 9564K/13728K, paused 4ms+1ms, total 29ms
,D/dalvikvm( 6782): WAIT_FOR_CONCURRENT_GC blocked 20ms
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 5090): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,D/BtConfig.SecureMode( 5090): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,D/BtConfig.SecureMode( 5090): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
,D/BtConfig.SecureMode( 5090): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 241
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BtConfig.SecureMode( 5090): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 241
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BtConfig.SecureMode( 5090): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
,W/System.err( 6782): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 5090): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,W/System.err( 6782): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 6782): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 6782): 	at java.util.Scanner.<init>(Scanner.java:158)
W/System.err( 6782): 	at java.util.Scanner.<init>(Scanner.java:138)
W/System.err( 6782): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
W/System.err( 6782): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
W/System.err( 6782): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
,W/System.err( 6782): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
W/System.err( 6782): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
W/System.err( 6782): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
,E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
W/System.err( 6782): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 6782): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6782): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
,D/BtConfig.SecureMode( 5090): isSecureModeOn:false
W/System.err( 6782): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6782): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6782): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,W/System.err( 6782): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/BluetoothRemoteDevices( 5090): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 5090): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 5090): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 5090): btif_sock_init: !radio_req && !rfc_init
D/IOP_DB_BT( 5090): db_open: file /etc/bluetooth/iop_bt.db
,W/System.err( 6782): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6782): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6782): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6782): 	at dalvik.system.NativeStart.main(Native Method)
D/IOP_DB_BT( 5090): db_open: db_open : handle 2010063916l, read 9734 bytes onto local cache
D/IOP_DB_BT( 5090): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5090): db_query: result 1
I/        ( 5090): iop_db_open: iop_db_open status 0
,I/bte_conf( 5090): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 5090): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 5090): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 5090): Attempt to load did conf from /etc/bluetooth/bt_did.conf
W/System.err( 6782): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
D/BluetoothAdapterState( 5090): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5090): ScanMode =  20
,D/BluetoothAdapterProperties( 5090): State =  11
W/System.err( 6782): 	at libcore.io.Posix.open(Native Method)
D/BtConfig.SecureMode( 5090): isSecureModeOn:false
D/BtConfig.SecureMode( 5090): isSecureModeOn:false
D/BtConfig.SecureMode( 5090): isSecureModeOn:false
D/BtConfig.SecureMode( 5090): isSecureModeOn:false
D/BtConfig.SecureMode( 5090): isSecureModeOn:false
D/BtConfig.SecureMode( 5090): isSecureModeOn:false
D/BtConfig.SecureMode( 5090): isSecureModeOn:false
D/BtConfig.SecureMode( 5090): isSecureModeOn:false
,I/BluetoothAdapterState( 5090): Bluetooth adapter state changed: 11-> 12
W/System.err( 6782): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6782): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 6782): 	... 20 more
D/BluetoothAdapterService( 5090): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5090): updateAdapterState state is 12
W/System.err( 6782): file res dir: /data/data/pl.k2.droidoaudioteka/files
,W/System.err( 6782): Excternal dir: /mnt/sdcard
,D/BluetoothAdapterService( 5090): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService(1111652016)( 5090): Register RemoteMessageListener
,D/HeadsetService( 5090): registerMessageListener
D/BluetoothAdapterService( 5090): Autoconnection is available 
D/HeadsetStateMachine( 5090): Disconnected process message: 70
,D/HeadsetStateMachine( 5090): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@42416a70
D/BluetoothAdapterService( 5090): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 5090): starting service from this receiver
,W/ContextImpl( 5090): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,I/BluetoothAdapterState( 5090): Entering On State from state = 11
,D/BluetoothA2dp( 4137): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 2400): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 5064): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 5064): onBluetoothStateChange: up=true
,D/BluetoothAdapterService( 5090): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
D/BluetoothPanServiceJni( 5090): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,D/bluedroid( 5090): init_wake_lock lock_fd:85, unlock_fd:86
,I/BluetoothPbapService( 5090): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
W/InputMethodManagerService( 2400): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2400): [BT Setting State] State =12
,I/InputMethodManagerService( 2400): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/BluetoothAdapterService(1111652016)( 5090): Get Bonded Devices being called
,I/SamsungIME( 2976): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
,I/QuickConnect[1.1][2] ( 5064): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
,D/BluetoothHeadset( 2753): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@4258f498, true
,D/BluetoothHeadset( 2753): registerMessageListener
,D/HeadsetService( 5090): registerMessageListener
D/HeadsetService( 5090): registerMessageListener
D/HeadsetStateMachine( 5090): Disconnected process message: 70
,D/HeadsetStateMachine( 5090): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@4250eb98
,D/PhoneApp( 2753): registerMessageListener
,I/BluetoothPbapService( 5090): Handler(): got msg=1
,V/BluetoothPbapService( 5090): PBAP Service initSocket try: 0
,D/BluetoothMapMasInstance( 5090): set MAP SDP message type : 1
,W/BluetoothAdapter( 5090): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5090): SOCK FLAG = 3 ***********************
,W/BluetoothAdapter( 5090): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5090): SOCK FLAG = 1 ***********************
,D/BluetoothPbapService( 5090): PBAP Socket is BluetoothServerSocket
D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:2
,I/chromium( 6554): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/MaBo    ( 6782): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6782): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6782): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6782): moge zapisać w resDir?true
,V/MaBo    ( 6782): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,D/GKI_LINUX( 5090): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/System.out( 6782): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6782): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,W/GAV2    ( 6782): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GAV2    ( 6782): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 6782): init tracking...
,I/AUDIOTEKA_GA( 6782): app started!
,I/BugSenseHandler( 6782): Registering default exceptions handler
,D/AuthorizationBluetoothService( 2850): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/DownloadService( 6782): Tworzenie serwisu - onCreate()
,I/DownloadService( 6782): Start serwisu - onStart()
,I/BugSenseHandler( 6782): Registering default exceptions handler
,D/dalvikvm( 5566): GC_EXPLICIT freed 589K, 29% free 9788K/13732K, paused 4ms+5ms, total 37ms
,I/PlayerService( 6782): Tworzenie serwisu - onCreate()
,I/BugSenseHandler( 6782): Flushing...
,I/BugSenseHandler( 6782): Registering default exceptions handler
,I/MediaFocusControl( 2400):   Remote Control   registerMediaButtonIntent() for PendingIntent{42d1e520: PendingIntentRecord{463df0a0 pl.k2.droidoaudioteka broadcastIntent}}
,I/knox    ( 5004): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,V/KeyguardUpdateMonitor( 2581): handleSetGenerationId(g=2, clear=true)
,V/AUDIOTEKA_MB( 6782): new AudioManagerFocusWrapper in playerservice oncreate
W/ContextImpl( 5004): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 5004): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/PlayerService( 6782): Start serwisu - onStart()
D/knox    ( 5004): KNOXAgentService : onCreate()
,D/knox    ( 5004): KNOXAgentService : set alarms for deniallog and usage data upload
,I/BugSenseHandler( 6782): Flushing...
,I/BugSenseHandler( 6782): Registering default exceptions handler
,D/knox    ( 5004): KNOXAgentService. startJobThread() start
,D/knox    ( 5004): KNOXAgentService. JobThread()
,D/knox    ( 5004): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5004): KNOXAgentService. startJobThread() wait
,I/SELinux ( 6825): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6825):  
,D/knox    ( 5004): KNOXAgentService : onDestroy().
,D/knox    ( 5004): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 6825): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6825):  
I/SELinux ( 6825):  
,I/SELinux ( 6825): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6825): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6825): >>>>> Normal User
,E/dalvikvm( 6825): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 6825): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6825): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6825): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6825): Added TimaKesytore provider
,D/dalvikvm( 6825): GC_CONCURRENT freed 2989K, 31% free 9574K/13728K, paused 4ms+1ms, total 28ms
,D/dalvikvm( 6825): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/ContextImpl( 5566): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/LocalBluetoothProfileManager( 5566): Adding local A2DP profile
,W/ContextImpl( 5566): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
D/LocalBluetoothProfileManager( 5566): Adding local HEADSET profile
,E/BluetoothHeadset( 5566): BTStateChangeCB is registed
,E/BluetoothHeadset( 5566): BluetoothHeadset service is binded
W/ContextImpl( 5566): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,W/ContextImpl( 5566): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 5566): bindService called to Bluetooth SAP Service
,W/ContextImpl( 5566): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 5566): PANU : true
W/ContextImpl( 5566): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
,D/LocalBluetoothProfileManager( 5566): Adding local MAP profile
,D/BluetoothMap( 5566): Create BluetoothMap proxy object
,W/ContextImpl( 5566): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 5566): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 5566): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 5566): LocalBluetoothProfileManager construction complete
W/ContextImpl( 5566): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/DockEventReceiver( 5566): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 5566): onReceive
,D/BluetoothA2dp( 5566): Proxy object connected
,D/A2dpProfile( 5566): Bluetooth service connected
,D/BtConfig.SecureMode( 5090): isSecureModeOn:false
,D/AuthorizationBluetoothService( 2850): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 2850): Proximity feature is not enabled.
,D/HeadsetProfile( 5566): Bluetooth service connected
,I/System.out( 6782): Thread-606(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/Bluetoothsap( 5566): BluetoothSAP Proxy object connected
D/SapProfile( 5566): Bluetooth service connected
,D/Bluetoothsap( 5566): getConnectedDevices()
,D/BluetoothInputDevice( 5566): Proxy object connected
,I/System.out( 6782): Thread-601(ApacheHTTPLog):isShipBuild true
,I/System.out( 6782): Thread-601(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6782): Thread-606(ApacheHTTPLog):isShipBuild true,
,I/System.out( 6782): Thread-606(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,D/Tethering( 2400): interfaceLinkStateChanged wlan0, true,
,D/Tethering( 2400): interfaceStatusChanged wlan0, true,
,E/Tethering( 2400): No numeric data,
D/Tethering( 2400): sendTetherStateChangedBroadcast 1, 0, 0,
,D/HidProfile( 5566): Bluetooth service connected,
,D/NtpTrustedTime( 2400): forceRefresh() from cache miss,
,I/ConnectivityService( 2400): defaultVal : 1, tetherEnabledInSettings : true,
D/Tethering( 2400): interfaceLinkStateChanged wlan0, true,
D/Tethering( 2400): interfaceStatusChanged wlan0, true
D/NtpTrustedTime( 2400): forceRefresh Fail.
,V/NetworkStats( 2400): performPollLocked(flags=0x1),
W/BluetoothAdapter( 5090): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothPan( 5566): BluetoothPAN Proxy object connected
E/BluetoothServiceJni( 5090): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 5090): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
I/BtOppRfcommListener( 5090): Accept thread started.
,I/wpa_supplicant( 6781): wlan0: Setting scan request: 0 sec 100000 usec,
,D/PanProfile( 5566): Bluetooth service connected,
,D/NtpTrustedTime( 2400): forceRefresh() from cache miss,
,V/NetworkStats( 2400): performPollLocked() took 16ms,
D/NtpTrustedTime( 2400): forceRefresh Fail.
D/BluetoothMap( 5566): Proxy object connected
D/MapProfile( 5566): Bluetooth service connected
D/BluetoothPbap( 5566): Proxy object connected
D/PbapServerProfile( 5566): Bluetooth service connected,
D/Bluetoothsap( 5566): BluetoothSAP Proxy object connected
D/SapProfile( 5566): Bluetooth service connected
D/Bluetoothsap( 5566): getConnectedDevices()
I/System.out( 6782): pool-1-thread-1 calls detatch()
,W/BugSenseHandler( 6782): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname,
I/System.out( 6782): pool-1-thread-2 calls detatch()
,W/BugSenseHandler( 6782): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname,
I/ActivityManager( 2400): Killing 5701:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/wpa_supplicant( 6781): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 6781): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 6781): rfkill: Cannot open RFKILL control device
D/Tethering( 2400): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2400): interfaceStatusChanged p2p0, true,
D/Tethering( 2400): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2400): interfaceStatusChanged p2p0, true,
,I/wpa_supplicant( 6781): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,D/GKI_LINUX( 5090): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1,
I/wpa_supplicant( 6781): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 6781): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
,D/WifiStateMachine( 2400): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,I/wpa_supplicant( 6781): Skip scan - bUseNetwork false
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
D/WifiNative( 2400): callSECApiString - ID [21]
I/wpa_supplicant( 6781): HOTSPOT20_ENABLE called
I/wpa_supplicant( 6781): wlan0: HS20_DISABLED_COMPLETE normal
,I/knox    ( 5004): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 5004): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/WifiNative( 2400): callSECApiInt - ID [65]
I/knox    ( 5004): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 5004): KNOXAgentService : onCreate()
,D/knox    ( 5004): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 5004): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,D/knox    ( 5004): KNOXAgentService. startJobThread() start
D/knox    ( 5004): KNOXAgentService. JobThread()
D/knox    ( 5004): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5004): KNOXAgentService. startJobThread() wait
,D/knox    ( 5004): KNOXAgentService : onDestroy().
D/knox    ( 5004): ModuleBase.cancelAllAlarmManageModule()
,E/WifiConfigStore( 2400): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative( 2400): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 6781): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6781): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6781): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 6781): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6781): First Scan Start
,W/Settings( 5342): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/wpa_supplicant( 6781): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 2400): Set the Nv default ccode
,D/WifiStateMachine( 2400): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine( 2400): HS20_DISABLED_COMPLETEnormal
D/WifiP2pService( 2400): P2pDisabledState{ what=131203 }
,D/CommandListener( 1915): Setting iface cfg
,D/CommandListener( 1915): Trying to bring up p2p0
,I/wpa_supplicant( 6781): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,D/WifiMonitor( 2400): startMonitoring(p2p0) with mConnected = true
,E/WifiStateMachine( 2400): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService( 2400): P2pEnablingState
D/WifiP2pService( 2400): P2pEnablingState{ what=147457 }
D/WifiP2pService( 2400): P2p socket connection successful
D/WifiP2pService( 2400): P2pEnabledState
,D/QuickConnect[1.1][2] ( 5064): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
D/WifiP2pService( 2400): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController( 2400): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 2400): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2400): disconnect
D/WifiDisplayController( 2400): updateConnection
D/WifiDisplayController( 2400): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 2400): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 5064): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiDisplayAdapter( 2400): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 5064): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
W/WifiP2pStateTracker( 2400): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2400): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/QuickConnect[1.1][2] ( 5064): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/WifiDisplayController( 2400): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
D/WifiDisplayController( 2400):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiDisplayController( 2400):  primary type: 10-0050F204-5
D/WifiDisplayController( 2400):  secondary type: null
D/WifiDisplayController( 2400):  wps: 0
D/WifiDisplayController( 2400):  grpcapab: 0
D/WifiDisplayController( 2400):  devcapab: 0
D/WifiDisplayController( 2400):  status: 3
D/WifiDisplayController( 2400):  wfdInfo: null
D/WifiDisplayController( 2400):  groupownerAddress: null
D/WifiDisplayController( 2400):  GOdeviceName: null
D/WifiDisplayController( 2400):  interfaceAddress: 
D/WifiDisplayController( 2400):  SConnectInfo : null
,D/NearbySettings( 5566): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 5566): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 5566): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 5566): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiP2pService( 2400): DeviceAddress: 02:e0:6d
V/NearbySettings( 5566): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 5566): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 5566): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5566): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5566): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 5566): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService( 2400): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 2400): InactiveState
,D/WifiP2pService( 2400): InactiveState{ what=139287 }
,D/WifiP2pService( 2400): P2pEnabledState{ what=139287 }
,D/QuickConnect[1.1][2] ( 5064): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,D/FileShare-Server( 5949): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/WifiP2pService( 2400): DefaultState{ what=139287 }
,D/FileShare-Server( 5949): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,D/PackageManager( 2400): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/wpa_supplicant( 6781): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 6781): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 6781): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 6781): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6781): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 6781): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2400): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2400): interfaceStatusChanged wlan0, true
,E/WifiStateMachine( 2400): Error! unhandled message{ when=-4ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 6781): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 6781): Associated with C0.AA.48
D/Tethering( 2400): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2400): interfaceStatusChanged wlan0, true
D/Tethering( 2400): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2400): interfaceStatusChanged wlan0, true
D/Tethering( 2400): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2400): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6781): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 6781): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 6781): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 6781): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6781): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2400): interfaceLinkStateChanged wlan0, true
D/Tethering( 2400): interfaceStatusChanged wlan0, true
,D/WifiNative( 2400): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6858): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6858):  
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6858): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6858):  
I/SELinux ( 6858):  
,I/SELinux ( 6858): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6858): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6858): >>>>> Normal User
,E/dalvikvm( 6858): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 6858): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6858): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6858): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6858): Added TimaKesytore provider
,D/WifiP2pService( 2400): InactiveState{ what=143375 }
,D/WifiP2pService( 2400): P2pEnabledState{ what=143375 }
,D/dalvikvm( 6858): GC_CONCURRENT freed 3003K, 31% free 9560K/13724K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 6858): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/System.out( 6858): Inside WakeupProvider
,I/System.out( 6858): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 6858): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 6858): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 6858): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2400): stay LED for fully charged
D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,I/dhcpcd  ( 6873): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6873): bssid match
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NearbySettings( 5566): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5566): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5566): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 5566): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5566): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5566): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5566): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2400): Killing 5775:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,D/DialogFlow( 6858): initQueue()
,I/HarmonyEASService( 2400): Updating for all 1
,D/WifiP2pService( 2400): InactiveState{ what=143375 }
,D/WifiP2pService( 2400): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2400): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2400): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2400): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2400): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2400): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2400): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2400): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2400): evaluateTrafficStatsPolling
D/ConnectivityService( 2400): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2400): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2400): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/NearbySettings( 5566): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 2400): handleConnectivityChange: setting default proxy info 
,I/NearbySettings( 5566): MountReceiver.onReceive - Keep current state,
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1,
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,D/NearbySettings( 5566): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5566): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5566): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 5566): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5566): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5566): MountReceiver.onReceive - Keep current state
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1,
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1,
,D/NtpTrustedTime( 2400): forceRefresh() from cache miss,
V/NetworkStats( 2400): updateIfacesLocked()
V/NetworkStats( 2400): performPollLocked(flags=0x1)
,V/NetworkStats( 2400): performPollLocked() took 22ms,
,D/NearbySettings( 5566): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,I/NearbySettings( 5566): MountReceiver.onReceive - Keep current state,
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast,
,D/NtpTrustedTime( 2400): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1450201757375 mCachedNtpElapsedRealtime : 158480 mCachedNtpCertainty : 12,
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit,
D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit,
D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,V/NetworkStats( 2400): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit,
D/PowerManagerService( 2400): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2400
,D/PackageManager( 2400): [MSG] SEND_PENDING_BROADCAST,
,D/PackageManager( 2400): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.sec.enterprise.knox.cloudmdm.smdms.core.CoreReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10171, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@4649a6d0, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}],
,I/jxcore-log( 6554): BLE advertisement not supported: Bluetooth LE advertising is not supported,
I/jxcore-log( 6554): 
,D/RegisteredServicesCache( 2757): empty dynamic service,
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT",
,I/PackageManager( 2400):   Scheme: "sms",
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2400):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "smsto",
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/InputReader( 2400): Reconfiguring input devices.  changes=0x00000010,
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "mms",
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/Icing.InternalIcingCorporaProvider( 5935): Updating corpora: A: com.sec.enterprise.knox.cloudmdm.smdms, C: MAYBE
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "mmsto"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4666): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/DBG_DM  ( 4666): [3.19.140541][Line:609][onReceive] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 4666): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
,I/DBG_DM  ( 4666): [3.19.140541][Line:432][xdmInitAdpWaitSystemRootingCheck] Check completed.
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/DBG_DM  ( 4666): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
D/SSRMv2:SIOP( 2400): SIOP:: AP = 360, Delta = 0
,I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "sms"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4666): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4666): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
,D/FileShare-Server( 5949): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "smsto"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "mms"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/Icing.InternalIcingCorporaProvider( 5935): UpdateCorporaTask done [took 365 ms] updated apps [took 365 ms] 
,I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2400):   Scheme: "mmsto"
,I/GAV2    ( 6782): Thread[GAThread,5,main]: connecting to Analytics service
,W/ContextImpl( 6782): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:529 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 6782): Thread[GAThread,5,main]: connect: bindService returned true for Intent { act=com.google.android.gms.analytics.service.START (has extras) }
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BezelQuickConnect( 5076): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 5076): BezelBroadcastReceiver - packageName : com.sec.enterprise.knox.cloudmdm.smdms
,I/GAV2    ( 6782): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 6782): Thread[GAThread,5,main]: putHit called
,D/GAV2    ( 6782): Thread[main,5,main]: service connected, binder: android.os.BinderProxy@425f8d48
D/GAV2    ( 6782): Thread[main,5,main]: bound to service
,I/GAV2    ( 6782): Thread[main,5,main]: Connected to service
,I/GAV2    ( 6782): Thread[GAThread,5,main]: Sending hit to service
,I/PCWCLIENTTRACE_PushUtil( 6382): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6382): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6382): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6382): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/PackageBroadcastService( 3313): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,D/Tethering( 2400): Tethering got CONNECTIVITY_ACTION
,I/dalvikvm( 4666): Total arena pages for JIT: 11
I/dalvikvm( 4666): Total arena pages for JIT: 12
,D/Tethering( 2400): MasterInitialState.processMessage what=3
,I/dalvikvm( 4666): Total arena pages for JIT: 13
I/dalvikvm( 4666): Total arena pages for JIT: 14
I/dalvikvm( 4666): Total arena pages for JIT: 15
I/dalvikvm( 4666): Total arena pages for JIT: 16
,I/dalvikvm( 4666): Total arena pages for JIT: 17
,D/CaptivePortalTracker( 2400): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,D/        ( 2400): Setting time of day to sec=1450201758
,D/        ( 2400): Trying to open a file
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/        ( 2400): File Open Success
D/        ( 2400): File Close Success
,I/        ( 2400): DRM_TIME_PATH CHMOD 660 for resetState done 
I/DBG_DM  ( 4666): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
V/AlarmManager( 2400): waitForAlarm result :65536
,I/SELinux ( 6931): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6931):  
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
D/StatusBar-DoNotDistrub( 2581): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 2581): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/NotificationMgr( 2753): updateNotificationsAtStartup()...
D/NotificationMgr( 2753): - start call log query...
,W/Settings( 2400): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SELinux ( 6931): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6931):  
I/SELinux ( 6931):  
,I/SELinux ( 6931): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6931): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6931): >>>>> Normal User
,E/dalvikvm( 6931): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,I/AudioService( 2400): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 2581): sendBroadcast android.intent.action.DORMANT_MODE_OFF
D/StatusBar-DoNotDistrub( 2581): The STREAM NOTIFICATION volume is 0
,D/STATUSBAR-StatusBarManagerService( 2400): manageDisableList what=0x0 pkg=com.android.systemui
E/Parcel  ( 2400): nm 23
E/SELinux ( 6931): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PrGenericPlugin( 1924): [A] ENTER onAcquireDrmInfo : 0x11
I/PrGenericPlugin( 1924): [A] LEAVE onAcquireDrmInfo : 0x11
,I/DrmEventService( 2400):  no response from SecureClock 
D/STATUSBAR-NotificationService( 2400): received android.intent.action.DORMANT_MODE_OFF
,I/SensorManagerA( 2400): getReportingMode :: sensor.mType = 5
D/LightsService( 2400): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2400) 
,D/LightsService( 2400): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/Sensors ( 2400): LightSensor setDelay = 200000000
D/Sensors ( 2400): LightSensor setSensorDelay = 200000000
D/Sensors ( 2400): Light sensor flush: not enabled 0
D/Sensors ( 2400): LightSensor enable = 1
D/Sensors ( 2400): LightSensor enableSensor = 1
D/SensorManager( 2400): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
D/NotificationMgr( 2753): call log query complete.
D/NotificationMgr( 2753): call log cursor count : 0
D/NotificationMgr( 2753): call log cursor count2 : null
D/TimaKeyStoreProvider( 6931): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6931): Cannot add TimaSignature Service, License check Failed
D/dalvikvm( 3313): GC_CONCURRENT freed 1985K, 21% free 12327K/15472K, paused 31ms+10ms, total 413ms
D/dalvikvm( 3313): WAIT_FOR_CONCURRENT_GC blocked 87ms
,D/dalvikvm( 3313): WAIT_FOR_CONCURRENT_GC blocked 77ms
D/dalvikvm( 3313): WAIT_FOR_CONCURRENT_GC blocked 78ms
,D/dalvikvm( 3313): WAIT_FOR_CONCURRENT_GC blocked 78ms
,D/ActivityThread( 6931): Added TimaKesytore provider
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_DM  ( 4666): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_DM  ( 4666): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/DBG_DM  ( 4666): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,I/DBG_DM  ( 4666): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,E/DBG_DM  ( 4666): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
,D/dalvikvm( 6931): GC_CONCURRENT freed 2997K, 31% free 9565K/13728K, paused 3ms+3ms, total 46ms
,D/dalvikvm( 6931): WAIT_FOR_CONCURRENT_GC blocked 44ms
,I/DBG_DM  ( 4666): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 4666): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4666): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4666): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
,I/DBG_DM  ( 4666): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4666): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,I/DBG_DM  ( 4666): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,D/dalvikvm( 2400): GC_CONCURRENT freed 3485K, 72% free 24770K/87256K, paused 9ms+18ms, total 209ms
,D/dalvikvm( 2400): WAIT_FOR_CONCURRENT_GC blocked 124ms
D/dalvikvm( 2400): WAIT_FOR_CONCURRENT_GC blocked 126ms
D/dalvikvm( 2400): WAIT_FOR_CONCURRENT_GC blocked 123ms
,D/dalvikvm( 2400): WAIT_FOR_CONCURRENT_GC blocked 124ms
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2400): WAIT_FOR_CONCURRENT_GC blocked 126ms
,D/dalvikvm( 2400): WAIT_FOR_CONCURRENT_GC blocked 71ms
D/Sensors ( 2400): LightSensor enable = 0
,D/Sensors ( 2400): LightSensor enableSensor = 0
,D/SensorManager( 2400): unregisterListener ::   
,D/dalvikvm( 2400): WAIT_FOR_CONCURRENT_GC blocked 127ms
D/dalvikvm( 2400): WAIT_FOR_CONCURRENT_GC blocked 91ms
D/LightsService( 2400): [SvcLED]  onSensorChanged::light value = 0
,D/LightsService( 2400): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/dalvikvm( 2400): WAIT_FOR_CONCURRENT_GC blocked 100ms
I/DBG_DM  ( 4666): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
I/DBG_DM  ( 4666): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,W/ApplicationsProvider( 2950): Could not fetch usage stats
W/ApplicationsProvider( 2950): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2950): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2950): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2950): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2950): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2950): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2950): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2950): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2950): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2950): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2950): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2950): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DBG_DM  ( 4666): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,I/DBG_DM  ( 4666): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4666): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,E/DBG_DM  ( 4666): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@42531050
,I/DBG_DM  ( 4666): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/dalvikvm( 4666): Total arena pages for JIT: 18
,I/DBG_DM  ( 4666): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/AmoledAdjustTimer( 2400): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/btif_config_util( 5090): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/DBG_DM  ( 4666): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2400): sendNotification(1) - 4
I/VacuumService( 2735): Vacuum at: now=1450201759124 tag=VacuumService
,W/ResourceType( 2581): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
,W/ResourceType( 2581): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/PhoneStatusBar( 2581): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42472e88
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SELinux ( 6958): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6958):  
,I/SELinux ( 6958): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6958):  
I/SELinux ( 6958):  
,I/SELinux ( 6958): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6958): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6958): >>>>> Normal User
,E/dalvikvm( 6958): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 6958): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6958): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6958): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6958): Added TimaKesytore provider
,I/SELinux ( 6974): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6974):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 12% free 9500K/10708K, paused 6ms+5ms, total 52ms,
,D/dalvikvm( 6958): GC_CONCURRENT freed 3001K, 31% free 9563K/13724K, paused 4ms+3ms, total 65ms,
D/dalvikvm( 6958): WAIT_FOR_CONCURRENT_GC blocked 63ms
I/SELinux ( 6974): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6974):  
I/SELinux ( 6974):  
I/SELinux ( 6974): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6974): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 6974): >>>>> Normal User
,E/dalvikvm( 6974): >>>>> com.android.chrome [ userId:0 | appId:10085 ],
,E/SELinux ( 6974): [DEBUG] seapp_context_lookup: seinfoCategory = chrome,
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9500K/10708K, paused 4ms+5ms, total 39ms,
,D/TimaKeyStoreProvider( 6974): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6974): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6974): Added TimaKesytore provider,
,D/dalvikvm( 2850): GC_EXPLICIT freed 1791K, 22% free 10768K/13792K, paused 13ms+15ms, total 94ms
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9500K/10708K, paused 4ms+4ms, total 38ms
,D/libgps  ( 2400): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 6974): GC_CONCURRENT freed 3004K, 31% free 9564K/13728K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 6974): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/SELinux ( 6988): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6988):  
,I/SELinux ( 6988): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6988):  
I/SELinux ( 6988):  
,I/SELinux ( 6988): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6988): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6988): >>>>> Normal User
,E/dalvikvm( 6988): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 6988): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6988): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6988): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6988): Added TimaKesytore provider
,D/dalvikvm( 6988): GC_CONCURRENT freed 3014K, 31% free 9556K/13732K, paused 4ms+3ms, total 34ms
,D/dalvikvm( 6988): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/KLMS-2.3.201 : ( 6988): KLMSValidator() : checkQATesting()
,I/Icing   ( 3313): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/Icing   ( 3313): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,I/KLMS-2.3.201 : ( 6988): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450201760049
,I/KLMS-2.3.201 : ( 6988): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/ActivityManager( 2400): Killing 5808:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/System.out( 6958): Thread-603(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/SELinux ( 7003): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7003):  
,I/System.out( 6958): Thread-603(ApacheHTTPLog):isShipBuild true
,I/System.out( 6958): Thread-603(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/LocationTagReadyService( 3469): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3469): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3469): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3469): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3596): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query,
,I/SELinux ( 7008): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7008):  
I/SELinux ( 7003): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7003):  
I/SELinux ( 7003):  
,I/SELinux ( 7003): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7003): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7003): >>>>> Normal User
,E/dalvikvm( 7003): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ],
,E/SELinux ( 7003): [DEBUG] seapp_context_lookup: seinfoCategory = release,
,D/TimaKeyStoreProvider( 7003): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7003): Cannot add TimaSignature Service, License check Failed
,I/SELinux ( 7020): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7020):  
,D/ActivityThread( 7003): Added TimaKesytore provider
I/SELinux ( 7008): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7008):  
I/SELinux ( 7008):  
,I/SELinux ( 7008): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7008): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7008): >>>>> Normal User
,E/dalvikvm( 7008): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7008): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7008): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7008): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7008): Added TimaKesytore provider
,I/SELinux ( 7020): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7020):  
I/SELinux ( 7020):  
,I/SELinux ( 7020): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7020): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7020): >>>>> Normal User
,E/dalvikvm( 7020): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7020): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7020): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7020): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7020): Added TimaKesytore provider
,D/dalvikvm( 7003): GC_CONCURRENT freed 2993K, 31% free 9574K/13732K, paused 4ms+5ms, total 57ms
,D/dalvikvm( 7003): WAIT_FOR_CONCURRENT_GC blocked 46ms
,I/System.out( 6958): AsyncTask #1 calls detatch()
,D/SO_AGENT( 7003): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,D/dalvikvm( 7008): GC_CONCURRENT freed 2991K, 31% free 9578K/13732K, paused 13ms+4ms, total 52ms
,D/dalvikvm( 7008): WAIT_FOR_CONCURRENT_GC blocked 39ms
,I/SO_AGENT( 7003): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,E/WifiStateMachine( 2400): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/dalvikvm( 7020): GC_FOR_ALLOC freed 3024K, 31% free 9540K/13728K, paused 31ms, total 31ms
,D/dalvikvm( 7020): GC_CONCURRENT freed 208K, 15% free 9559K/11236K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7020): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/SA      ( 6572): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,V/KVNProvider( 7020): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,W/System.err( 6958): com.sec.android.fota.osp.http.RestClientException
W/System.err( 6958): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 6958): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
,W/System.err( 6958): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 6958): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 6958): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 6958): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 6958): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 6958): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 6958): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 6958): Caused by: java.lang.NullPointerException
,V/KVNProvider( 7020): getFindoCursor query string : 
I/SA      ( 6572): [BDLM] already registered in spp
,W/System.err( 6958): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 6958): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 6958): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 6958): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 6958): 	... 8 more
,I/SA      ( 6572): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6572): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/ActivityManager( 2400): Killing 5834:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/dalvikvm( 6490): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42426270, skipping init
I/ActivityManager( 2400): Killing 5881:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,V/KVNProvider( 7020): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 6572): [SLFUCHKMGR] constructor called
D/libgps  ( 2400): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2400): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2400): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2400): agps_ril_update_network_availability: Waiting for IPC connection...,
I/ActivityManager( 2400): Killing 5527:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SA      ( 6572): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN,
,I/SA      ( 6572): [OR] == isSIMCardReady false ==
,I/SA      ( 6572): [SCU] == networkStateCheck == true
I/SA      ( 6572): [DM] getCountryCodeFromCSC : PL
I/SecureStorage( 6490): [INFO]: SPID(0x00000000)Processing data
I/SA      ( 6572): isChinaCountryCode : false
,I/SA      ( 6572): [OR] == networkStateCheck true ==,
I/SecureStorage( 1963): [INFO]: SPID(0x00000004)Credentials: uid 1000, gid 1000, pid 6490
,I/SecureStorage( 1963): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
,I/SA      ( 6572): [OR] GetMyCountryZoneTask
,I/SA      ( 6572): [OR] onReceive END
,I/SA      ( 6572): [SRS] prepareGetMyCountryZone
,I/SA      ( 6572): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6572): [SSP] query invoked
I/ActivityManager( 2400): Killing 5759:com.sec.phone/1001 (adj 15): empty #43
,I/SA      ( 6572): [TPMU] GetMccFromDB : null
,I/SA      ( 6572): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6572): [TPM] isNoProxy(default) : true
,I/SA      ( 6572): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SELinux ( 7048): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7048):  
,I/ActivityManager( 2400): Killing 5633:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/SELinux ( 7048): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7048):  
I/SELinux ( 7048):  
,I/SELinux ( 7048): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7048): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7048): >>>>> Normal User
,E/dalvikvm( 7048): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
,E/SELinux ( 7048): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
,D/PowerManagerService( 2400): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2400) eventTime = 161954
,D/PowerManagerService( 2400): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2400 (0x0)
,D/PowerManagerService( 2400): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2400, ws=WorkSource{1000}) (elapsedTime=3469)
,D/TimaKeyStoreProvider( 7048): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7048): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7048): Added TimaKesytore provider
,I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2400): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2400
,D/dalvikvm( 7048): GC_CONCURRENT freed 3006K, 31% free 9561K/13732K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 7048): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/System.out( 6572): Thread-563(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6572): Thread-563(ApacheHTTPLog):isShipBuild true
,I/System.out( 6572): Thread-563(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/sCloudBackupApp( 7048): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7048): Other Intent
,I/ActivityManager( 2400): Killing 5781:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7062): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7062):  
,I/SELinux ( 7062): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7062):  
I/SELinux ( 7062):  
,I/SELinux ( 7062): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7062): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7062): >>>>> Normal User
,E/dalvikvm( 7062): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7062): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7062): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7062): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7062): Added TimaKesytore provider
,D/dalvikvm( 7062): GC_CONCURRENT freed 3010K, 31% free 9561K/13732K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 7062): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/com.samsung.app( 7062): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7062): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7062): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7062): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7062): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7062): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5288): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7062): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5288): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7062): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5288): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7062): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7062): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2400): Killing 5830:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/SELinux ( 7074): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7074):  
,I/SELinux ( 7074): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7074):  
I/SELinux ( 7074):  
,I/SELinux ( 7074): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7074): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7074): >>>>> Normal User
,E/dalvikvm( 7074): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10110 ]
,E/SELinux ( 7074): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7074): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7074): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7074): Added TimaKesytore provider
,D/dalvikvm( 7074): GC_CONCURRENT freed 2989K, 31% free 9574K/13728K, paused 4ms+2ms, total 27ms
,D/dalvikvm( 7074): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/HeadlinesChannelApplication( 7074): [onCreate]
,D/Headlines( 7074): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7074): getCountryCode(): countryCode = PL
,D/Headlines( 7074): Breath.onCreate
,D/HeadlinesCardManager( 7074): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 7074): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 7074): CardProvider Library : 13
,I/SELinux ( 7086): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7086):  
,D/MagazineService::CardProviderContentProvider( 6661): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 6661): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 7074): registerCardProvider: provider already exists.
,I/Headlines( 7074): HeadlinesDataCenter ctor
,I/Headlines( 7074): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 7074): getCountryCode(): countryCode = PL
I/SELinux ( 7086): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7086):  
I/SELinux ( 7086):  
,I/SELinux ( 7086): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7086): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7086): >>>>> Normal User
E/dalvikvm( 7086): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,D/HeadlinesCardManager( 7074): HeadlinesCardManager : constructor welcome :YES
,E/SELinux ( 7086): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/libgps  ( 2400): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2400): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2400): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/TimaKeyStoreProvider( 7086): in addTimaSignatureService
,D/Headlines( 7074): Breath timer started. interval : 30000
,D/TimaKeyStoreProvider( 7086): Cannot add TimaSignature Service, License check Failed
D/Headlines( 7074): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 7074): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 7074): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/ActivityThread( 7086): Added TimaKesytore provider
D/Headlines( 7074): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 7074): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7074): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7074): requestUpdateNewsWelcomeCard !!! no welcome card
,I/dalvikvm( 3313): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 3313): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3313): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 7086): GC_CONCURRENT freed 2993K, 31% free 9569K/13724K, paused 5ms+2ms, total 25ms
,D/dalvikvm( 7086): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/SA      ( 6572): [RC New] [v2liruge] api execute + 1130
,I/SA      ( 6572): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6572): AsyncTask #1 calls detatch()
,I/SA      ( 6572): [TPMU] getNetworkMcc : 
,I/SA      ( 6572): [SCU] saveMccToPreferece Start
,I/SA      ( 6572): [SCU] RegionMCC : 260
,I/SA      ( 6572): [SSP] query invoked
,I/SA      ( 6572): [TPMU] GetMccFromDB : null
,I/SA      ( 6572): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6572): [SCU] saveMccToPreferece End
I/SA      ( 6572): [RC New] executeRequest [v2liruge] end. 1176
,I/SA      ( 6572): [RC New] Execute end
,I/SA      ( 6572): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6572): [OR] GetMyCountryZoneTask Success
,E/Auth.Api.Credentials( 3313): [CredentialSyncAdapter] Unknown sync event.
I/SecureStorage( 1963): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1963): [INFO]: SPID(0x00000004)PID: 6490, TID: 6526
,V/WebViewChromium( 7086): Binding Chromium to the background looper Looper (main, tid 1) {4242a188}
,I/chromium( 7086): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7086): Initializing chromium process, renderers=0
,W/chromium( 7086): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7086): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7086): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7086): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7086): Mali API Version : 401
,I/Mali    ( 7086): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/SecureStorage( 6490): [INFO]: SPID(0x00000000)Processing data has been completed
,W/GAV2    ( 7086): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 2400): GC_EXPLICIT freed 1763K, 72% free 24653K/87256K, paused 11ms+24ms, total 287ms
E/ActivityThread( 3313): Failed to find provider info for com.android.contacts.metadata
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7086): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,D/DelayedSyncController( 6974): Delaying sync.
,D/NtpTrustedTime( 2400): getCachedNtpTime() cache hit
,W/WifiP2pStateTracker( 2400): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2400): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2400):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2400): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2400): updateSourceRoutes : no source routing conditions
,I/NSApplication( 7086): Starting up...
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/ImageResourceManager( 5718): ImageResourceManager: uninitalized
,D/dalvikvm( 5718): GC_FOR_ALLOC freed 1085K, 28% free 9903K/13724K, paused 27ms, total 27ms
,I/dalvikvm-heap( 5718): Grow heap (frag case) to 12.833MB for 2129936-byte allocation
,D/dalvikvm( 5718): GC_FOR_ALLOC freed 2K, 25% free 11980K/15808K, paused 15ms, total 15ms
,D/SyncManager( 2400): failed sync operation 
,D/SyncManager( 2400): not retrying sync operation because the error is a hard error: 
,I/iu.Environment( 5718): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 5718): SYNC; picasa accounts
,I/ActivityManager( 2400): Killing 5342:com.google.android.talk/u0a109 (adj 15): empty #43
D/dalvikvm( 5718): GC_CONCURRENT freed 32K, 25% free 11960K/15808K, paused 2ms+6ms, total 36ms
D/dalvikvm( 5718): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/QuickConnect[1.1][2] ( 5064): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/dalvikvm-heap( 5718): Grow heap (frag case) to 14.840MB for 2129936-byte allocation
I/QuickConnect[1.1][2] ( 5064): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 5064): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42435758
,D/dalvikvm( 5718): GC_FOR_ALLOC freed 8K, 22% free 14031K/17892K, paused 23ms, total 24ms
,I/SELinux ( 7137): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7137):  
,I/ActivityManager( 2400): Killing 5855:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7137): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7137):  
I/SELinux ( 7137):  
,I/SELinux ( 7137): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7137): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/iu.UploadsManager( 5718): num queued entries: 0
E/dalvikvm( 7137): >>>>> Normal User
,E/dalvikvm( 7137): >>>>> com.android.email [ userId:0 | appId:10157 ]
,I/iu.UploadsManager( 5718): num updated entries: 0
,E/SELinux ( 7137): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/iu.SyncManager( 5718): NEXT; no task
,D/TimaKeyStoreProvider( 7137): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7137): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7137): Added TimaKesytore provider
,D/dalvikvm( 7137): GC_CONCURRENT freed 2997K, 31% free 9572K/13732K, paused 4ms+2ms, total 43ms
,D/dalvikvm( 7137): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
,D/PicasaService( 3596): start picasa sync
,D/PicasaService( 3596): end picasa sync
,D/DelayedSyncController( 6974): Delaying sync.
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
,I/SELinux ( 7162): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7162):  
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
W/ActivityManager( 2400): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7162): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7162):  
I/SELinux ( 7162):  
,I/SELinux ( 7162): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7162): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7162): >>>>> Normal User
,E/dalvikvm( 7162): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
E/SELinux ( 7162): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 7162): in addTimaSignatureService
D/TimaKeyStoreProvider( 7162): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7162): Added TimaKesytore provider
I/dalvikvm( 2735): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2735): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x003d
I/SELinux ( 7178): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7178):  
D/dalvikvm( 1922): WAIT_FOR_CONCURRENT_GC blocked 1ms
I/ActivityManager( 2400): Killing 6325:com.android.defcontainer/u0a6 (adj 15): empty #43
D/dalvikvm( 7162): GC_CONCURRENT freed 3001K, 31% free 9563K/13724K, paused 4ms+2ms, total 40ms
D/dalvikvm( 7162): WAIT_FOR_CONCURRENT_GC blocked 35ms
D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 12% free 9500K/10708K, paused 3ms+5ms, total 50ms
I/SELinux ( 7178): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7178):  
I/SELinux ( 7178):  
I/SELinux ( 7178): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7178): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7178): >>>>> Normal User
E/dalvikvm( 7178): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
E/SELinux ( 7178): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/BadgeProvider( 7162): onCreate
D/BadgeProvider( 7162): DatabaseHelper
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9500K/10708K, paused 3ms+5ms, total 40ms
D/TimaKeyStoreProvider( 7178): in addTimaSignatureService
D/TimaKeyStoreProvider( 7178): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7178): Added TimaKesytore provider
D/BadgeProvider( 7162): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9500K/10708K, paused 4ms+5ms, total 39ms
D/Launcher.Model( 2775): reloadBadges entered.
D/BadgeProvider( 7162): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7162): sendNotify, [notify] : null
D/BadgeProvider( 7162): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7162): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7162): update, [UpdateCount] : 1
I/ActivityManager( 2400): Killing 5955:com.google.android.partnersetup/u0a14 (adj 15): empty #43
D/dalvikvm( 7178): GC_CONCURRENT freed 3005K, 31% free 9563K/13728K, paused 3ms+2ms, total 34ms
D/dalvikvm( 7178): WAIT_FOR_CONCURRENT_GC blocked 29ms
I/SELinux ( 7192): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7192):  
I/ActivityManager( 2400): Killing 6354:com.samsung.groupcast/u0a15 (adj 15): empty #43
V/AlarmManager( 2400): waitForAlarm result :4
V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
I/SELinux ( 7192): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7192):  
I/SELinux ( 7192):  
I/SELinux ( 7192): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7192): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7192): >>>>> Normal User
E/dalvikvm( 7192): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
E/SELinux ( 7192): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 7192): in addTimaSignatureService
I/PCWCLIENTTRACE_SYSTEMReceiver( 6382): mConnectivityHandler : connected
D/TimaKeyStoreProvider( 7192): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7192): Added TimaKesytore provider
W/PCWCLIENTTRACE_AccountUtil( 6382): [hasSamungAccount] - No Samsung Account
D/dalvikvm( 3879): GC_CONCURRENT freed 1546K, 22% free 10747K/13704K, paused 8ms+6ms, total 88ms
D/dalvikvm( 3879): WAIT_FOR_CONCURRENT_GC blocked 19ms
V/AlarmManager( 2400): waitForAlarm result :4
V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/dalvikvm( 7192): GC_CONCURRENT freed 2990K, 31% free 9574K/13724K, paused 6ms+1ms, total 34ms
D/dalvikvm( 7192): WAIT_FOR_CONCURRENT_GC blocked 24ms
E/PCWCLIENTTRACE_SecurePreferencesJNI( 6382): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6382): [GetString-S]
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6382): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6382): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6382): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6382): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6382): [ensureRegistration] - No Samsung account
I/dalvikvm( 7192): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7192): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7192): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
D/dalvikvm( 7192): VFY: replacing opcode 0x22 at 0x0000
E/dalvikvm( 7192): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
D/dalvikvm( 7192): VFY: replacing opcode 0x22 at 0x0037
W/dalvikvm( 7192): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7192): Link of class 'Ldqp;' failed
W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7192): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7192): Link of class 'Ldqp;' failed
I/dalvikvm( 7192): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x0000
E/dalvikvm( 7192): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
D/dalvikvm( 7192): VFY: replacing opcode 0x22 at 0x0000
W/dalvikvm( 7192): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7192): Link of class 'Ldqp;' failed
W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7192): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7192): Link of class 'Ldqp;' failed
I/dalvikvm( 7192): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7192): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
D/dalvikvm( 7192): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7192): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7192): Link of class 'Ldqp;' failed
,W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7192): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7192): Link of class 'Ldqp;' failed
I/dalvikvm( 7192): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 7192): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7192): Link of class 'Lax;' failed
E/dalvikvm( 7192): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7192): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7192): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7192): Link of class 'Laz;' failed
E/dalvikvm( 7192): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7192): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 7192): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7192): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7192): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 7192): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7192): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 7192): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7192): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
,W/dalvikvm( 7192): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 7192): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7192): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7192): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7192): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm( 7192): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7192): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7192): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 7192): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7192): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x0009
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/dalvikvm( 7192): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
,W/dalvikvm( 7192): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7192): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7192): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7192): VFY: replacing opcode 0x1c at 0x0002
,E/dalvikvm( 7192): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7192): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7192): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 7192): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7192): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7192): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7192): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7192): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7192): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7192): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7192): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 7192): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7192): Link of class 'Lax;' failed
,D/dalvikvm( 7192): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7192): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7192): Link of class 'Laz;' failed
,D/dalvikvm( 7192): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7192): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7192): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 7192): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4241c178
,D/Finsky  ( 3879): [220] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/dalvikvm( 7192): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4241c178
,D/Finsky  ( 3879): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/dalvikvm( 7192): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7192): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7192): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7192): MmsConfig.loadMmsSettings
I/SurfaceFlinger( 1921): id=21 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (-2/11)
I/Babel_SMS( 7192): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7192): MmsConfig.loadFromDatabase
D/PowerManagerService( 2400): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2400) eventTime = 165448
D/PowerManagerService( 2400): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2400 (0x0)
D/PowerManagerService( 2400): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2400, ws=WorkSource{1000}) (elapsedTime=3454)
,I/System.out( 3313): Thread-187(HTTPLog):isShipBuild true
,I/System.out( 3313): Thread-187(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/Babel_SMS( 7192): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7192): MmsConfig.loadFromResources
,E/Babel_SMS( 7192): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7192): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7192): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7192): Link of class 'Lfzc;' failed
E/dalvikvm( 7192): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7192): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7192): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,I/dalvikvm( 7192): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7192): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7192): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 7192): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7192): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x0033
,I/dalvikvm( 7192): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7192): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7192): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7192): Link of class 'Lfzc;' failed
,D/dalvikvm( 7192): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,E/SensorService( 2400): Permission Denial : SEC Private Sensor 
,E/SensorService( 2400): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,W/Settings( 7192): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7192): startup - clean
,D/dalvikvm( 7192): GC_CONCURRENT freed 1775K, 22% free 10874K/13808K, paused 6ms+3ms, total 37ms
D/dalvikvm( 7192): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 7192): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/dalvikvm( 7192): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 7192): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x000d
,I/Babel   ( 7192): deleted: false for 0
,W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 7192): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7192): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7192): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7192): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7192): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7192): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7192): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7192): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7192): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7192): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/dalvikvm( 7192): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7192): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7192): VFY: replacing opcode 0x6e at 0x0074
,D/WaitQueueForNetworkActivate( 6756): notifyNetworkActivated
,I/vclib   ( 7192): onServiceConnected
,W/Babel   ( 7192): Attempted to change video mute state without an active call.
,W/ContextImpl( 6756): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 2400): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/dalvikvm( 3313): GC_FOR_ALLOC freed 1564K, 21% free 12412K/15524K, paused 59ms, total 60ms
,D/dalvikvm( 7192): GC_CONCURRENT freed 830K, 15% free 12091K/14084K, paused 6ms+4ms, total 64ms,
D/dalvikvm( 7192): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 7192): WAIT_FOR_CONCURRENT_GC blocked 28ms,
,I/System.out( 7192): Thread-653(HTTPLog):isShipBuild true,
,I/System.out( 7192): Thread-653(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,D/dalvikvm( 7192): GC_FOR_ALLOC freed 876K, 17% free 12622K/15076K, paused 42ms, total 43ms,
,D/hcjo    ( 6756): AutoUpdateManager:IDLE:execute,
,I/dalvikvm( 6756): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
,W/dalvikvm( 6756): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6756): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6756): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6756): exit::IDLE
,D/InitializeManagerStateMachine( 6756): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6756): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6756): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6756): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6756): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6756): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6756): entry::SUCCESS
,D/hcjo    ( 6756): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6756): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 6756): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6756): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6756): exit::SUCCESS
,D/InitializeManagerStateMachine( 6756): entry::IDLE
,D/dalvikvm( 7192): GC_FOR_ALLOC freed 1847K, 23% free 12983K/16732K, paused 40ms, total 40ms
,I/Babel   ( 7192): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager( 2400): Killing 6368:com.android.musicfx/u0a24 (adj 15): empty #43
,I/iu.SyncManager( 3313): SYNC; picasa accounts
,D/NetworkLogImpl( 3313): Loaded NetworkSpeedPredictor
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,I/iu.Environment( 3313): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/BatteryService( 2400): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5090): Disconnected process message: 10
,I/iu.UploadsManager( 3313): num queued entries: 0
,I/iu.UploadsManager( 3313): num updated entries: 0
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/iu.SyncManager( 3313): NEXT; no task
,E/SPPClientService( 5486): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5486): [SystemStateMoniter] Current Time : 166487
,E/SPPClientService( 5486): [SystemStateMoniter] No Connect : false
,I/SELinux ( 7232): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7232):  
,I/SELinux ( 7232): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7232):  
I/SELinux ( 7232):  
,I/SELinux ( 7232): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7232): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7232): >>>>> Normal User
,E/dalvikvm( 7232): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 7232): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7232): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7232): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7232): Added TimaKesytore provider
,I/GCM     ( 2850): GCM config loaded
,D/dalvikvm( 7232): GC_CONCURRENT freed 2994K, 31% free 9570K/13724K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7232): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/ActivityManager( 2400): Killing 6394:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/BootCompletedReceiver( 2400): onReceive
,I/KLMS-2.3.201 : ( 6988): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 6988): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1450201765928
,I/KLMS-2.3.201 : ( 6988): StateImplV2() : dateTimeChanged() : Tue Dec 15 18:49:25 CET 2015
,D/SO_AGENT( 7003): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 7003): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 6572): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/Mms/MessagingNotification( 5581): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 5581): sDisableVibrateForCamera = false
,D/Mms/MessagingNotification( 5581): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 5581): isDefault true
,I/PhenotypeConfigurator( 2735): Scheduling Phenotype for one-off execution 7126 seconds from now (1450201766109)
,D/TP/MmsSmsProvider( 2753): match 8:Elapsed time : 11.314 ms
,I/SELinux ( 7261): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7261):  
,D/TP/MmsSmsProvider( 2753): match 200:Elapsed time : 2.646 ms
,I/SELinux ( 7261): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7261):  
I/SELinux ( 7261):  
,I/SELinux ( 7261): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7261): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7261): >>>>> Normal User
,E/dalvikvm( 7261): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10064 ]
,E/SELinux ( 7261): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/GetConfigurationSnapshotOperation( 2735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
D/ConnectivityService( 2400): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/TimaKeyStoreProvider( 7261): in addTimaSignatureService
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/TimaKeyStoreProvider( 7261): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7261): Added TimaKesytore provider
,D/dalvikvm( 2400): GC_EXPLICIT freed 2581K, 72% free 24621K/87004K, paused 16ms+21ms, total 266ms
,D/BadgeProvider( 7162): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/PhenotypeFlagCommitter( 2735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/BadgeProvider( 7162): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7162): sendNotify, [notify] : null
D/BadgeProvider( 7162): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7162): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7162): update, [UpdateCount] : 1
D/Launcher.Model( 2775): reloadBadges entered.
,D/Mms/MessagingNotification( 5581): setBadgeCount(), count=0
,D/MessagingNotification( 5581): remove alarm
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/Mms/MessagingNotification( 5581): updateAllHistoryAsRead()
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2735): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2735): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x00bb
,D/Mms/MessagingNotification( 5581): [end]    nonBlockingUpdateMessageIndicator()
,I/GoogleURLConnFactory( 2735): Using platform SSLCertificateSocketFactory
D/dalvikvm( 7261): GC_CONCURRENT freed 2998K, 31% free 9567K/13732K, paused 5ms+3ms, total 43ms
,D/dalvikvm( 7261): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 2850): null clazz in OP_INSTANCE_OF, single-stepping
,D/com.samsung.app( 7062): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 7062): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 7261): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 7279): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7279):  
I/ActivityManager( 2400): Killing 6428:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/dalvikvm( 2735): GC_EXPLICIT freed 1641K, 20% free 11685K/14556K, paused 6ms+11ms, total 102ms
,I/SELinux ( 7279): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7279):  
I/SELinux ( 7279):  
,I/SELinux ( 7279): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7279): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7279): >>>>> Normal User
,E/dalvikvm( 7279): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
,E/SELinux ( 7279): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7279): in addTimaSignatureService
,D/LocationManagerService( 2400): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/TimaKeyStoreProvider( 7279): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7279): Added TimaKesytore provider
,D/dalvikvm( 7279): GC_CONCURRENT freed 3002K, 31% free 9566K/13732K, paused 4ms+2ms, total 44ms
,D/dalvikvm( 7279): WAIT_FOR_CONCURRENT_GC blocked 40ms
,I/System.out( 2735): Thread-125(HTTPLog):isShipBuild true
,I/System.out( 2735): Thread-125(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/Watchdog( 2400): !@Sync 5
,I/GAV2    ( 7086): Thread[GAThread,5,main]: No campaign data found.
,I/SELinux ( 7295): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7295):  
,I/ActivityManager( 2400): Killing 6537:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,I/SELinux ( 7295): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7295):  
I/SELinux ( 7295):  
,I/SELinux ( 7295): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7295): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7295): >>>>> Normal User
,E/dalvikvm( 7295): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7295): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7295): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7295): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7295): Added TimaKesytore provider
,D/dalvikvm( 7295): GC_CONCURRENT freed 3005K, 31% free 9563K/13732K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7295): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/elm:14132( 7295): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 7295): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7295): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7295): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14132( 7295): ElmAgentService : onCreate()
,D/elm:14132( 7295): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,I/knox    ( 5004): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 7295): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14132( 7295): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14132( 7295): ModuleBase.resetCalllogAPIAlarm()
W/ContextImpl( 5004): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,D/knox    ( 5004): MainReceiver.listeningToTimeDateChanges( context, intent ).
,I/knox    ( 5004): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/knox    ( 5004): KNOXAgentService : onCreate()
D/knox    ( 5004): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 5004): KNOXAgentService. startJobThread() start
D/knox    ( 5004): KNOXAgentService. JobThread()
D/knox    ( 5004): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5004): KNOXAgentService. startJobThread() wait
,D/elm:14132( 7295): ModuleBase.ModifySetAlarm()
D/elm:14132( 7295): MDMBridge.getInstance()
,D/elm:14132( 7295): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7310): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7310):  
,D/elm:14132( 7295): ElmAgentService : onDestroy().
,D/knox    ( 5004): KNOXAgentService : onDestroy().
,D/knox    ( 5004): ModuleBase.cancelAllAlarmManageModule()
I/ActivityManager( 2400): Killing 6619:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,I/SELinux ( 7310): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7310):  
I/SELinux ( 7310):  
,I/SELinux ( 7310): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7310): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7310): >>>>> Normal User
,E/dalvikvm( 7310): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
,E/SELinux ( 7310): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7310): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7310): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7310): Added TimaKesytore provider
,D/dalvikvm( 7310): GC_CONCURRENT freed 3009K, 31% free 9557K/13728K, paused 4ms+3ms, total 39ms
,D/dalvikvm( 7310): WAIT_FOR_CONCURRENT_GC blocked 34ms
,I/SELinux ( 7322): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7322):  
I/ActivityManager( 2400): Killing 6634:com.sec.android.service.cm/u0a82 (adj 15): empty #43
,I/SELinux ( 7322): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7322):  
I/SELinux ( 7322):  
,I/SELinux ( 7322): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7322): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7322): >>>>> Normal User
,E/dalvikvm( 7322): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 7322): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7322): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7322): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7322): Added TimaKesytore provider
,D/dalvikvm( 7322): GC_CONCURRENT freed 3013K, 31% free 9557K/13732K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/ActivityManager( 2400): Killing 6649:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5288): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5288): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5288): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 5288): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5288): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5288): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5288): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5288): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5288): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/LocationManagerService( 2400): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5288): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 5288): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 5288): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
D/SSRMv2:SIOP( 2400): SIOP:: AP = 350, Delta = -10
,D/LocationManagerService( 2400): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/CheckinService( 3313): Checkin interval check for package: unspecified last checkin: 1450135146850 min interval config: 0 actual interval: 66621190
,D/Headlines( 7074): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 7074): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7074): Breath 6469 latestRequest time : 1450201761705 current time : 1450201768174
,I/SELinux ( 7335): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7335):  
,I/ActivityManager( 2400): Waited long enough for: ServiceRecord{45f71e80 u0 pl.k2.droidoaudioteka/.services.DownloadService}
,I/ActivityManager( 2400): Waited long enough for: ServiceRecord{45f3cdc0 u0 pl.k2.droidoaudioteka/.services.PlayerService}
,D/LocationManagerService( 2400): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
I/SELinux ( 7335): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7335):  
I/SELinux ( 7335):  
,I/SELinux ( 7335): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7335): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7335): >>>>> Normal User
,E/dalvikvm( 7335): >>>>> com.android.providers.calendar [ userId:0 | appId:10045 ]
,E/SELinux ( 7335): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7335): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7335): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7335): Added TimaKesytore provider
,D/LocationManagerService( 2400): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 7335): GC_CONCURRENT freed 2999K, 31% free 9570K/13732K, paused 4ms+3ms, total 32ms
,D/dalvikvm( 7335): WAIT_FOR_CONCURRENT_GC blocked 27ms
,E/SPPClientService( 5486): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/CaptivePortalTracker( 2400): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 2400): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2400): Checking http://216.58.209.46/generate_204
W/ActivityThread( 2400): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,V/AlarmManager( 2400):  next == MAX_VALUE
,I/System.out( 2400): Thread-161(HTTPLog):isShipBuild true
,I/System.out( 2400): Thread-161(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2735): GC_CONCURRENT freed 1583K, 19% free 12122K/14936K, paused 11ms+24ms, total 165ms
,E/SPPClientService( 5486): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/CaptivePortalTracker( 2400): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2400): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2400): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2400): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 2400): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,E/SPPClientService( 5486): [a] [ConnectionManager] Connection is already disconnected.
V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Mms/MessagesLockscreen( 5581): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0,
,W/Binder  ( 2581): Caught a RuntimeException from the binder stub implementation.,
W/Binder  ( 2581): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
W/Binder  ( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2581): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2581): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2581): 	,at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2581): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2581): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2581): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2581): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2581): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2581): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239),
W/Binder  ( 2581): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2581): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2581): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2581): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2581): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2581): 	... 16 more
W/Binder  ( 2581): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2581): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2581): ,	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2581): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2581): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2581): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2581): 	... 19 more
,E/JavaBinder( 2581): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.),
E/JavaBinder( 2581): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498),
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2581): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 2581): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2581): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2581): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2581): 	,at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2581): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2581): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2581): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2581): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2581): 	... 16 more
E/JavaBinder( 2581): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2581): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2581): 	at android.os.Handler.<init>(Handler.java:114),
E/JavaBinder( 2581): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2581): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2581): 	... 19 more
,D/AmoledAdjustTimer( 2400): prevTemp = 298, currTemp = 301, prevStep = 4, currStep = 4,
,E/SPPClientService( 5486): [g] getNetMCC return empty string,
,E/SPPClientService( 5486): [g] getNetMNC return empty string,
,E/SPPClientService( 5486): [b] __ProvisionReply__,
,V/AlarmManager( 2400):  next == MAX_VALUE,
,E/SPPClientService( 5486): [g] getPLMN return empty string,
,E/SPPClientService( 5486): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE,
,E/SPPClientService( 5486): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5486): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5486): [g] getNetMCC return empty string
,D/dalvikvm( 5486): GC_CONCURRENT freed 2122K, 25% free 10415K/13724K, paused 4ms+5ms, total 57ms
,I/PowerManagerService( 2400): [PWL] Off : 105s ago
,E/SPPClientService( 5486): [b] __InitReply__,
,D/PreloadUpdateManagerStateMachine( 6756): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6756): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6756): entry::CHECK_TIMEOUT_FOR_UPDATE,
,D/hcjo    ( 6756): AutoUpdateTriggerManager:IDLE:setInterval:86400000,
,D/hcjo    ( 6756): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6756): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6756): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6756): entry::IDLE
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2400): stay LED for fully charged
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2400): Waited long enough for: ServiceRecord{432d0720 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 340, Delta = -10,
,D/AmoledAdjustTimer( 2400): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 2400): Waited long enough for: ServiceRecord{463e6e08 u0 com.sec.spp.push/.PushClientService},
,D/BatteryService( 2400): level:100, scale:100, status:3, health:9, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 2400): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
,D/LightsService( 2400): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/lights  ( 2400): led_pattern : 0 +
,D/lights  ( 2400): led_pattern : 0 -
D/LightsService( 2400): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/BatteryService( 2400): turn off LED
D/PowerManagerService( 2400): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2400): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2400): Waking up from sleep...
D/PowerManagerService( 2400): Screen Readiness Inspection requested: mNestCount=1
D/LightsService( 2400): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PowerManagerService( 2400): [PWL] sb acquire: PowerManagerService.Broadcasts
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/PowerManagerService( 2400): [s] WAKEFULNESS_AWAKE
,D/lights  ( 2400): button : 1 +
I/SensorManagerA( 2400): getReportingMode :: sensor.mType = 5
,D/lights  ( 2400): button : 1 -
D/Sensors ( 2400): LightSensor setDelay = 200000000
D/PowerManagerService( 2400): [s] UserActivityState : 0 -> 1
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2400): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2400): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController( 2400): [DAB] setLightSensorEnabled : registerListener mLightSensor
I/DisplayPowerController( 2400): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
,I/DisplayPowerController( 2400): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/Sensors ( 2400): LightSensor setSensorDelay = 200000000
D/Sensors ( 2400): Light sensor flush: not enabled 0
D/Sensors ( 2400): LightSensor enable = 1
,D/Sensors ( 2400): LightSensor enableSensor = 1
,D/SensorManager( 2400): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2400): getReportingMode :: sensor.mType = 1
D/DisplayPowerController( 2400): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2400): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2400): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2400): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 7ms
,D/PowerManagerService( 2400): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 186678
,I/Sensors ( 2400): HAL: batch Dry Run is complete
I/Sensors ( 2400): HAL:resetDataRates mEnabled=4
,I/libsuspend( 2400): !@[s] autosuspend_autosleep_disable
I/libsuspend( 2400): !@[s] autosuspend_autosleep_disable done
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
D/PowerManagerService( 2400): unblankAllDisplays() is called.
,D/PowerManagerService( 2400): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
I/SensorManagerA( 2400): getReportingMode :: sensor.mType = 65558
D/SurfaceFlinger( 1921): Screen acquired, type=0 flinger=0x404f8008
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
D/SensorService( 2400): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2400): AutoRotationSensor::activate (ident=0x7aa689c8, enabled=1)
D/SensorService( 2400): AutoRotationSensor::AR_init
,I/Sensors ( 2400): HAL: batch Dry Run is complete
D/UsbDeviceManager( 2400): handleMessage -> MSG_POWER_STATE = 0
D/UiModeManager( 2400): mCoverManager.getCoverState() : true
W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
,D/SensorManager( 2400): registerListener :: 2, MPL Accelerometer, 200000, 0,  
,I/Sensors ( 2400): HAL:resetDataRates mEnabled=4
D/RampAnimator( 2400): Light Animator Finished currentValue=8
D/PowerManagerService( 2400): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 22ms
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/UsbDeviceManager( 2400): sending intent : ACTION_USB_CABLE_STATE : connected = false
,D/NotificationService( 2400): cancelNotificationLocked
D/NotificationService( 2400):  hasClearableItems
D/NotificationService( 2400):  has clearable items no 
D/NotificationService( 2400): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2400): cancelNotificationLocked: cancel alarm
,D/STATUSBAR-StatusBarManagerService( 2400): sendNotification(3) - 5,
D/SensorManager( 2400): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
V/KeyguardServiceDelegate( 2400): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@43370e98)
,D/KeyguardViewMediator( 2581): onScreenTurnedOn, seq = 2,
,D/KeyguardViewMediator( 2581): notifyScreenOnLocked,
D/KeyguardViewMediator( 2581): handleNotifyScreenOn
D/KeyguardViewManager( 2581): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2581): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2581): KeyguardEffectViewParticleSpace : screenTurnedOn
,V/KeyguardServiceDelegate( 2400): **** SHOWN CALLED ****
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
V/KeyguardViewManager( 2581): send wm null token: host was null
,D/InputDispatcher( 2400): setInputDispatchMode: enabled=1, frozen=0
,D/VisualEffectParticleEffect( 2581): screenOnAnimationStart
I/WindowManager( 2400): No lock screen! windowToken=null
D/PowerManagerNotifier( 2400): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,D/PowerManagerService( 2400): Screen Readiness Inspection completed: mNestCount=0
,I/SELinux ( 7477): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7477):  
D/DisplayPowerController( 2400): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 2400): !@ElectronBeam exit
,I/SurfaceFlinger( 1921): id=14 Removed FlectronBea (10/10)
,D/LockPatternUtils( 2581): isPcwEnable = 10
,I/SurfaceFlinger( 1921): id=14 Removed FlectronBea (-2/10)
,D/lights  ( 2400): lcd : 8 +
,D/lights  ( 2400): lcd : 8 -
D/DisplayPowerController( 2400): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2400): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
,I/SELinux ( 7477): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7477):  
I/SELinux ( 7477):  
,I/SELinux ( 7477): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7477): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7477): >>>>> Normal User
,E/dalvikvm( 7477): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,E/SELinux ( 7477): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/SensorService( 2400): AutoRotationSensor::process: Acc  eventTimestamp = 186778648216, previousAccTimestamp = 68606592968, difference = 118172055248 
,D/SensorService( 2400): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/TimaKeyStoreProvider( 7477): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7477): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7477): Added TimaKesytore provider
,D/DisplayPowerController( 2400): [api] [DAB] onSensorChanged : 1st lux : 0.0
,D/DisplayPowerController( 2400): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/SensorService( 2400): AutoRotationSensor::process: Acc  eventTimestamp = 186845311027, previousAccTimestamp = 68606592968, difference = 118238718059 
D/SensorService( 2400):  [AR] 0.3 0.0 9.9
,D/SensorService( 2400): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2400): Excessive delay in unblankDisplay() while turning screen on: 242ms
D/MISC PowerHAL( 2400): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2400): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2400): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 244ms
,D/LightsService( 2400): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2400) 
,D/LightsService( 2400): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/UsbDeviceManager( 2400): received ACTION_POWER_DISCONNECTED = -1
D/LightsService( 2400): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2400): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/MISC PowerHAL( 2400): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2400): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2400): sysfs_write +: /sys/class/input/input0/enabled: 1
,I/chromium( 6554): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/LightsService( 2400): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2400) 
D/LightsService( 2400): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2400): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2400): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PalmMotionService( 2400): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2400): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 2400):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/SSRMv2:TSP:AirViewOnOff( 2400): SettingsAirViewInfo:: 000000000
I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.USER_PRESENT
I/NfcService( 2757): applyRouting return - 2 
,D/SamsungIME( 2976): showDlgMsgBox : false true true
,E/NfcService( 2757): callback == null
,I/chromium( 6554): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/WifiTrafficPoller( 2400): evaluateTrafficStatsPolling
,E/libGLESv2( 6554): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 6554): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
D/STATUSBAR-NotificationService( 2400): ACTION_SCREEN_ON
D/LightsService( 2400): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2400) 
D/LightsService( 2400): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2400): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2400): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 2400): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController( 2400): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2400): Bridge Server is not available
D/MISC PowerHAL( 2400): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2400): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2400): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2400): Excessive delay in MISC setInteractive(true) while turning screen on: 164ms
D/SEC PowerHAL( 2400): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2400): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2400): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2400): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2400): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2400): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2400): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2400): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/PowerManagerService( 2400): Excessive delay in nativeSetInteractive(true): 165ms
D/PowerManagerService( 2400): SecHardwareInterface.setBatteryADC : true
,D/PersonaManagerService( 2400): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2400): MSG_ACTION_SCREEN_ON called
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/StatusBarManagerService( 2400): semi p:6554,o:f
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,E/libGLESv2( 6554): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 6554): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
I/NfcService( 2757): NFC: Screen On & Cover Open
E/libGLESv2( 6554): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 6554): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,I/NfcService( 2757): applyRouting return - 2 
D/dalvikvm( 7477): GC_CONCURRENT freed 3002K, 31% free 9563K/13728K, paused 5ms+8ms, total 82ms
,D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 74ms
,E/NfcService( 2757): callback == null
,D/STATUSBAR-NetworkController( 2581): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,I/KIES_RECEIVE( 7477): [APK BnR] Receive KIES_USB_DISCONNECT
W/ContextImpl( 7477): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,E/TranscodeReceiver( 7008): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/videowall-Global( 7008): core_num = 4
,D/dalvikvm( 7008): No JNI_OnLoad found in /system/lib/libsavsff.so 0x42471838, skipping init
,W/linker  ( 7008): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = -10
D/videowall-Global( 7008): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
D/videowall-Global( 7008): dsp : 720, swkey : false, Cores : 4, Clock : 0
,D/QuickConnect[1.1][2] ( 5064): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,V/QuickConnect[1.1][2] ( 5064): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5064): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5064): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42435758
V/QuickConnect[1.1][2] ( 5064): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42435758
V/QuickConnect[1.1][2] ( 5064): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5064): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42435758
,V/QuickConnect[1.1][2] ( 5064): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42435758
V/QuickConnect[1.1][2] ( 5064): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42435758
D/QuickConnect[1.1][2] ( 5064): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5064): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5064): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5064): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,I/SELinux ( 7493): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7493):  
,D/PowerManagerService( 2400): [PWL] sb release: PowerManagerService.Broadcasts
,I/SELinux ( 7493): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7493):  
I/SELinux ( 7493):  
,I/SELinux ( 7493): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7493): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7493): >>>>> Normal User
,E/dalvikvm( 7493): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 7493): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7493): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7493): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7493): Added TimaKesytore provider
,D/dalvikvm( 5935): GC_CONCURRENT freed 2529K, 27% free 10068K/13756K, paused 3ms+4ms, total 61ms
,D/dalvikvm( 7493): GC_CONCURRENT freed 3010K, 31% free 9555K/13732K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 7493): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/iu.Environment( 5718): update battery state; isPlugged? false*
,I/iu.UploadsManager( 5718): num queued entries: 0
I/ActivityManager( 2400): Killing 6674:com.samsung.helphub/1000 (adj 15): empty #43
,I/iu.Environment( 3313): update battery state; isPlugged? false*
,I/iu.UploadsManager( 3313): num queued entries: 0
,I/iu.UploadsManager( 3313): num updated entries: 0
,I/iu.SyncManager( 3313): NEXT; no task
,I/iu.UploadsManager( 5718): num updated entries: 0
,I/GCoreUlr( 2735): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/iu.SyncManager( 5718): NEXT; no task
,I/GCoreUlr( 2735): DispatchingService.onCreate()
,D/PicasaUploader( 7493):    wifiOnlyPhoto changed to true
,D/PicasaUploader( 7493):    wifiOnlyVideo changed to true
,D/PicasaUploader( 7493):    syncOnBattery changed to true
,D/PicasaUploaderSync( 7493): sync account database
,D/PicasaUploaderSync( 7493): accounts in DB=1
,D/PicasaUploaderSyncManager( 7493): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 7493): background data: true
,D/PicasaUploaderSyncManager( 7493): battery info: false
,D/LockPatternUtils( 2581): isPcwEnable = 10
,I/GCoreUlr( 2735): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5288): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5288): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5288): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5288): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5288): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5288): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5288): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5288): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5288): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5288): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5288): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 5288): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1450210920000
,D/daemonapp( 5288): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1450201786592
,D/daemonapp( 5288): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5288): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5288): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/GCoreUlr( 2735): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,I/GCoreUlr( 2735): DispatchingService.onDestroy()
,I/GCoreUlr( 2735): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,D/dalvikvm( 2400): GC_EXPLICIT freed 2033K, 72% free 24682K/87004K, paused 9ms+18ms, total 200ms
,D/SSRMv2:TSP:AirViewOnOff( 2400): SettingsAirViewInfo:: 000000000
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/lights  ( 2400): button : 0 +
,D/lights  ( 2400): button : 0 -
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2400):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2400): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2400): waitForAlarm result :8
,D/Headlines( 7074): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7074): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7074): Breath 30016 latestRequest time : 1450201761705 current time : 1450201791721
,D/SensorService( 2400):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2400):   0.3 -0.0 9.9
,D/BatteryService( 2400): level:100, scale:100, status:2, health:2, present:true, voltage: 4362, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/PowerManagerService( 2400): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2400): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 196604
,D/PowerUI ( 2581): playSound : 1
I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5090): Disconnected process message: 10
I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
V/Vibrator( 2581): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
V/Vibrator( 2581): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
V/VibratorService( 2400): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
D/UsbDeviceManager( 2400): handleMessage -> MSG_POWER_STATE = 1
D/UiModeManager( 2400): mCoverManager.getCoverState() : true
V/VibratorService( 2400): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2400): JNI vibratorOff()
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
I/EntropyMixer( 2400): Writing entropy...
D/VibratorService( 2400): JNI vibratorOn() : 100
D/PowerUI ( 2581): RINGER_MODE_VIBRATE
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,D/UsbDeviceManager( 2400): sending intent : ACTION_USB_CABLE_STATE : connected = true
E/TranscodeReceiver( 7008): onReceive : android.intent.action.ACTION_POWER_CONNECTED
I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
D/BatteryMeterView( 2581): onDraw batteryColor : -1
,I/SCloudBackupReceiver( 7048): Other Intent
,D/TranscodeService( 7008): onCreate()
,D/PicasaUploaderSyncManager( 7493): battery info: true
,D/dalvikvm( 7008): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x42471838, skipping init
,D/dalvikvm( 7008): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x42471838, skipping init
,I/iu.Environment( 5718): update battery state; isPlugged? true*
,D/dalvikvm( 7008): No JNI_OnLoad found in /system/lib/libsthmb.so 0x42471838, skipping init
,I/iu.UploadsManager( 5718): num queued entries: 0
D/TranscodeService( 7008): power? : true / screen off : false
,I/iu.UploadsManager( 5718): num updated entries: 0
,D/TranscodeService( 7008): releaseTranscodeThread.
,I/iu.SyncManager( 5718): NEXT; no task
D/VibratorService( 2400): JNI vibratorOff()
,I/iu.FingerprintManager( 5718): Start processing all media
,I/iu.FingerprintManager( 5718): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5718): Start processing media store URI: content://media/external/video/media
,I/iu.Environment( 3313): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3313): num queued entries: 0
,I/iu.UploadsManager( 3313): num updated entries: 0
,I/iu.SyncManager( 3313): NEXT; no task
,E/NetworkScheduler.SchedulerReceiver( 2850): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2850): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/iu.FingerprintManager( 5718): Start processing media store URI: content://media/phoneStorage/images/media
,I/GCoreUlr( 2735): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/iu.FingerprintManager( 3313): Start processing all media
,I/iu.FingerprintManager( 5718): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3313): Start processing media store URI: content://media/external/images/media
,I/GCoreUlr( 2735): DispatchingService.onCreate()
I/iu.FingerprintManager( 5718): Finished generating fingerprints; 0.064 seconds
,I/iu.FingerprintManager( 5718):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3313): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 3313): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3313): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3313): Finished generating fingerprints; 0.053 seconds
,I/iu.FingerprintManager( 3313):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2735): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2735): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,I/GCoreUlr( 2735): DispatchingService.onDestroy()
,I/GCoreUlr( 2735): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 340, Delta = 10
,E/Watchdog( 2400): !@Sync 6
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2400):   0.3 -0.0 9.9
,D/AmoledAdjustTimer( 2400): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5288): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2400): Waited long enough for: ServiceRecord{43271560 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/SensorService( 2400):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2400):   0.3 -0.0 9.9
,D/BatteryService( 2400): level:100, scale:100, status:2, health:2, present:true, voltage: 4377, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 340, Delta = 0
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2400):   0.3 0.0 9.9
,D/AmoledAdjustTimer( 2400): prevTemp = 301, currTemp = 302, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2400): Waited long enough for: ServiceRecord{46443c18 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2400):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2400):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/PowerManagerService( 2400): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581
W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NotificationService( 2400): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/STATUSBAR-StatusBarManagerService( 2400): sendNotification(1) - 5
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/RCPManagerService( 2400): NotificationReceiver onReceive()
D/RCPManagerService( 2400):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService( 2400): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298400
D/RCPManagerService( 2400): getPolicy: policy value returned = false
D/RCPManagerService( 2400): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2400): app label == com.android.systemui
,D/RCPManagerService( 2400): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298400
D/RCPManagerService( 2400): getPolicy: policy value returned = true
,D/RCPManagerService( 2400): Calling User is -1
,D/RCPManagerService( 2400): userid of SBN ==-1
D/UserManagerService( 2400): User -1does not exists!!
,E/PersonaManagerService( 2400): returning null in  getPersonasForUser
D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2581): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42472e88
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = -10
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2400):   0.3 0.0 9.9
,D/AmoledAdjustTimer( 2400): prevTemp = 302, currTemp = 303, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/PowerManagerService( 2400): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2400): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2400): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2400): lcd : 2 +
D/RampAnimator( 2400): Light Animator Finished currentValue=2
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/lights  ( 2400): lcd : 2 -
,E/ActivityThread( 3313): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 2400): failed sync operation 
,D/SyncManager( 2400): not retrying sync operation because the error is a hard error: 
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2400):   0.3 -0.0 9.9
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2400): waitForAlarm result :8
,D/Headlines( 7074): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7074): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7074): Breath 60022 latestRequest time : 1450201761705 current time : 1450201821727
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2400):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2400): [s] UserActivityState : 2 -> 0
,I/PowerManagerService( 2400): [PWL] On : 186664 (39937 ms ago)
I/PowerManagerService( 2400): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2400): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2581, ws=null) (elapsedTime=9886)
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 340, Delta = 10
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 7
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2400):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2400): prevTemp = 303, currTemp = 304, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2400):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2400):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2400): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581 (0x0)
,I/PowerManagerService( 2400): Nap time...
D/PowerManagerService( 2400): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2400): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2400): Going to sleep due to screen timeout...,
,D/PowerManagerService( 2400): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2400): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2400): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/Sensors ( 2400): LightSensor enable = 0
,D/Sensors ( 2400): LightSensor enableSensor = 0
D/DisplayPowerController( 2400): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/DisplayPowerController( 2400): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/SurfaceFlinger( 1921): id=22 createSurf (720x1280),-1 flag=20004, FlectronBea
D/SensorManager( 2400): unregisterListener ::   
,I/Sensors ( 2400): HAL:resetDataRates mEnabled=4
,D/DisplayPowerController( 2400): !@ElectronBeam entry
D/SensorManager( 2400): unregisterListener ::   
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2400): lcd : 0 +
,D/lights  ( 2400): lcd : 0 -
D/PowerManagerService( 2400): blankAllDisplays() is called.
D/MISC PowerHAL( 2400): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2400): sysfs_write +: /sys/class/input/input1/enabled: 0
V/WindowOrientationListener( 2400): WindowOrientationListener disabled
D/SensorService( 2400): AutoRotationSensor::activate (ident=0x7aa689c8, enabled=0)
,I/Sensors ( 2400): HAL: batch Dry Run is complete
D/PowerManagerService( 2400): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2400): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2400): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2400): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2400): miscpower_set_interactive: /sys/class/input/input0/enabled
D/KeyguardViewMediator( 2581): onScreenTurnedOff(3)
D/MISC PowerHAL( 2400): sysfs_write +: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2400): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2400): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2400): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2400): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2400): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2400): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2400): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2400): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2400): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2400): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SensorManager( 2400): unregisterListener ::   
D/InputDispatcher( 2400): setInputDispatchMode: enabled=0, frozen=0
,D/SEC PowerHAL( 2400): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/PowerManagerService( 2400): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x404f8008
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/SurfaceControl( 2400): Excessive delay in blankDisplay() while turning screen off: 210ms
,I/libsuspend( 2400): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2400): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2400): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 214ms
D/PowerManagerService( 2400): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2400): [PWL] Off : 0s ago
I/PowerManagerService( 2400): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2400): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2400): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2400, ws=null) (elapsedTime=212)
I/PowerManagerService( 2400): [PWL]   PowerManagerService.Broadcasts: ref count=1
,I/SQLiteSecureOpenHelper( 4137): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4137): getDatabaseLocked(b,b,pwd)...
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = -10
,D/KeyguardViewMediator( 2581): setting alarm to turn off keyguard, seq = 2
,D/LightsService( 2400): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2400) 
,I/SensorManagerA( 2400): getReportingMode :: sensor.mType = 5
D/Sensors ( 2400): LightSensor setDelay = 200000000
,D/Sensors ( 2400): LightSensor setSensorDelay = 200000000
,D/LightsService( 2400): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors ( 2400): Light sensor flush: not enabled 0
D/Sensors ( 2400): LightSensor enable = 1
D/Sensors ( 2400): LightSensor enableSensor = 1
,D/SensorManager( 2400): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2400): turn on LED for fully charged
D/VibratorService( 2400): JNI vibratorOff()
,I/WifiTrafficPoller( 2400): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2400): ACTION_SCREEN_OFF
D/LightsService( 2400): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2400) 
,D/LightsService( 2400): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2400): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2400): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2400): Bridge Server is not available
,D/PersonaManagerService( 2400): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2400): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2581): makeExpandedInvisible
D/PhoneStatusBarView( 2581): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2757): applyRouting return - 2 
,E/NfcService( 2757): callback == null
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = 0
D/QuickConnect[1.1][2] ( 5064): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 5064): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5064): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5064): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42435758
V/QuickConnect[1.1][2] ( 5064): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42435758
D/QuickConnect[1.1][2] ( 5064): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5064): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5064): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5064): stopLeScan()
D/QuickConnect[1.1][2] ( 5064): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 7008): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 7008): power? : true / screen off : true
,D/PowerManagerService( 2400): [PWL] sb release: PowerManagerService.Broadcasts
D/TranscodeService( 7008): Music is = false
D/TranscodeService( 7008): runvideoplayer is false
,D/TranscodeService( 7008): Thread start
,D/TranscodeService( 7008): WakeLock.acquire()
,D/videowall-FileMgr( 7008): thumbnailDBSync -1
,D/Sensors ( 2400): LightSensor enable = 0
,D/Sensors ( 2400): LightSensor enableSensor = 0
,D/LightsService( 2400): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager( 2400): unregisterListener ::   
D/lights  ( 2400): led_pattern : 5 +
,D/lights  ( 2400): led_pattern : 5 -
D/LightsService( 2400): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/WVMDrmPlugIn( 1924): WVMDrmPlugin::onInitialize : 2654
D/WVMDrmPlugIn( 1924): WVMDrmPlugin::onSetOnInfoListener : add 2654
I/PrGenericPlugin( 1924): [A] ENTER onInitialize : 0xa5e
,I/PrGenericPlugin( 1924): [A] LEAVE onInitialize : 0xa5e
,D/TranscodeService( 7008): Thread end
,D/TranscodeService( 7008): WakeLock.release()
D/TranscodeService( 7008): onDestroy()
,D/TranscodeService( 7008): releaseTranscodeThread.
,V/ApplicationPolicy( 2400): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,D/AmoledAdjustTimer( 2400): prevTemp = 304, currTemp = 305, prevStep = 4, currStep = 4,
,V/AlarmManager( 2400): waitForAlarm result :4,
,D/KeyguardViewMediator( 2581): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2,
,D/LockPatternUtils( 2581): isPcwEnable = 10,
,D/KeyguardViewMediator( 2581): in doKeyguardLocked mIsRollUp false null,
,D/PersonaManager( 2581): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2581): isPcwEnable = 10,
D/LockPatternUtils( 2581): isPcwEnable = 10
,D/KeyguardViewMediator( 2581): doKeyguard: not showing because lockscreen is off,
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/PowerManagerService( 2400): [PWL] Off : 5s ago,
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2400): stay LED for fully charged,
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2400): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,V/AlarmManager( 2400): waitForAlarm result :4,
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/PowerManagerService( 2400): [PWL] Off : 15s ago,
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2400): mCoverManager.getCoverState() : true,
,D/BatteryService( 2400): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5090): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2400): !@Sync 8,
,D/AmoledAdjustTimer( 2400): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,V/AlarmManager( 2400): waitForAlarm result :8,
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5090): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2400): [PWL] Off : 30s ago,
,V/AlarmManager( 2400): waitForAlarm result :4,
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = 0,
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 7074): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 7074): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7074): Breath 104673 latestRequest time : 1450201761705 current time : 1450201866379
,D/AmoledAdjustTimer( 2400): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5090): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2400): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5090): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2400): [PWL] Off : 50s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = -10
,E/Watchdog( 2400): !@Sync 9,
,D/AmoledAdjustTimer( 2400): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,V/AlarmManager( 2400): waitForAlarm result :4,
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 7074): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 7074): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 7074): Breath 130222 latestRequest time : 1450201761705 current time : 1450201891927
,D/Headlines( 7074): stop 
,I/SELinux ( 7785): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7785):  
,D/Headlines( 7074): Breath.onDestroy : 
,I/ActivityManager( 2400): Killing 6687:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 12% free 9500K/10708K, paused 4ms+5ms, total 46ms
,I/SELinux ( 7785): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7785):  
I/SELinux ( 7785):  
,I/SELinux ( 7785): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7785): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 7785): >>>>> Normal User
,E/dalvikvm( 7785): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9500K/10708K, paused 3ms+4ms, total 35ms
,E/SELinux ( 7785): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 7785): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7785): Cannot add TimaSignature Service, License check Failed
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9500K/10708K, paused 3ms+4ms, total 36ms
,D/ActivityThread( 7785): Added TimaKesytore provider
,D/dalvikvm( 7785): GC_CONCURRENT freed 2997K, 31% free 9571K/13732K, paused 5ms+3ms, total 41ms
,D/dalvikvm( 7785): WAIT_FOR_CONCURRENT_GC blocked 35ms
,E/SPPClientService( 7785): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7785): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7785): PushLog.txt file is not deleted.
D/SPPClientService( 7785): PushLog.txt file is not deleted.
,D/SPPClientService( 7785): ============PushLog. stop!
,E/SPPClientService( 5486): [b] __PingReply__
,I/ActivityManager( 2400): Killing 6699:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,D/TimaService( 2400): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2400): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2400): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 2400): initializing...
,I/TLC_TIMA_PKM_initialize( 2400): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2400): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2400): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2400): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2400): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2400): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2400): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2400): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2400): device_id = 0x0
,I/TZ: mc_tlc_communication( 2400): tlc_open() was called
,I/TZ: mc_tlc_communication( 2400): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2400): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2400): Opening the session
,I/TZ: mc_tlc_communication( 2400): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2400): Trustlet response is completed
,I/PowerManagerService( 2400): [PWL] Off : 75s ago
I/PowerManagerService( 2400): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2400): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2400): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2400, ws=null) (elapsedTime=312)
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2400): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2400): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2400): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2581): GC_CONCURRENT freed 15679K, 34% free 33912K/50748K, paused 19ms+8ms, total 81ms
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/dalvikvm( 2400): GC_CONCURRENT freed 3006K, 71% free 25372K/87004K, paused 25ms+19ms, total 267ms
,I/PowerManagerService( 2400): [PWL] Off : 105s ago
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2400): !@Sync 11
,D/AmoledAdjustTimer( 2400): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 8220): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8220):  
,I/SELinux ( 8220): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8220):  
I/SELinux ( 8220):  
,I/SELinux ( 8220): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8220): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8220): >>>>> Normal User
,E/dalvikvm( 8220): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 8220): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 8220): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8220): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8220): Added TimaKesytore provider
,D/dalvikvm( 8220): GC_CONCURRENT freed 2990K, 31% free 9573K/13728K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 8220): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/ActivityManager( 2400): Killing 6711:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2400): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 140s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2400): !@Sync 12
,D/AmoledAdjustTimer( 2400): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,I/jxcore-log( 6554): Connected to the server!
I/jxcore-log( 6554): 
,I/chromium( 6554): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6554): --- start :testFindPeers.js---
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): testFindPeers created [object Object]
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): serverPort is 8876
I/jxcore-log( 6554): 
I/dalvikvm( 6554): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 6554): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6554): VFY: replacing opcode 0x6e at 0x0019
I/dalvikvm( 6554): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 6554): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6554): VFY: replacing opcode 0x6e at 0x0020
D/AndroidRuntime( 6554): Shutting down VM
,W/dalvikvm( 6554): threadid=1: thread exiting with uncaught exception (group=0x419bec08)
E/AndroidRuntime( 6554): FATAL EXCEPTION: main
E/AndroidRuntime( 6554): Process: com.test.thalitest, PID: 6554
E/AndroidRuntime( 6554): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 6554): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 6554): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 6554): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 6554): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 6554): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 6554): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 6554): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 6554): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 6554): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 6554): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 6554): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6554): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6554): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 6554): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 6554): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 6554): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 6554): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 6554): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2400):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2400): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2400): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2400): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2400): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 2400): Killing 6725:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty #43
,D/CrashAnrDetector( 2400): processName: com.test.thalitest
,D/CrashAnrDetector( 2400): broadcastEvent : com.test.thalitest data_app_crash
,I/Process ( 6554): Sending signal. PID: 6554 SIG: 9
W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/ActivityManager( 2400): Process com.test.thalitest (pid 6554) (adj 9) has died.
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/10)
,I/WindowState( 2400): WIN DEATH: Window{45027d88 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
I/SurfaceFlinger( 1921): id=18 Removed EimLayer (6/9)
I/SurfaceFlinger( 1921): id=18 Removed EimLayer (-2/9)
I/SurfaceFlinger( 1921): id=17 Removed EimLayer (5/8)
I/SurfaceFlinger( 1921): id=17 Removed EimLayer (-2/8)
,V/WindowManager( 2400): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2775): onRestart, Launcher: 1111863048
D/Launcher( 2775): onStart, Launcher: 1111863048
,D/Launcher.HomeView( 2775): onStart
,I/SurfaceFlinger( 1921): id=23 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2400): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2400): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2400): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2400): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2400): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2400): setHoveringSpenCustomIcon IconType is same.1
,D/StatusBarManagerService( 2400): tr p:2775,o:f
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2400): semi p:2775,o:f
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2400): Got RemoteException sending setActive(false) notification to pid 6554 uid 10550
,D/AmoledAdjustTimer( 2400): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2400): !@Sync 13
,D/AmoledAdjustTimer( 2400): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 180s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2400): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2400): !@Sync 14
,D/AmoledAdjustTimer( 2400): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 225s ago
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2400): !@Sync 15
,D/AmoledAdjustTimer( 2400): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2400): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 16
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 275s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2400): !@Sync 17
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2400): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 18
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2400): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2400): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2400): !@Sync 19
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2400): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2400): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/TimaService( 2400): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2400): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2400): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2400): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2400): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2400): !@Sync 21
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5090): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2400): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 22
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2400): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2400): <AppSync3 Whitelist>
,V/AlarmManager( 2400): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 23
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 24
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5090): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4062): GC_CONCURRENT freed 2884K, 30% free 9723K/13768K, paused 7ms+4ms, total 56ms
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2400): GC_CONCURRENT freed 3906K, 71% free 25347K/87004K, paused 18ms+17ms, total 239ms
,I/GAV2    ( 6782): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 6782): Thread[disconnect check,5,main]: Disconnected from service
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 525s ago
,E/Watchdog( 2400): !@Sync 25
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 26
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 27
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 28
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 29
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,I/SensorManagerA( 2400): getReportingMode :: sensor.mType = 5
,D/LightsService( 2400): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2400): LightSensor setDelay = 200000000
D/Sensors ( 2400): LightSensor setSensorDelay = 200000000
D/Sensors ( 2400): Light sensor flush: not enabled 0
D/Sensors ( 2400): LightSensor enable = 1
D/Sensors ( 2400): LightSensor enableSensor = 1
,D/SensorManager( 2400): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5486): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2400): LightSensor enable = 0
,D/Sensors ( 2400): LightSensor enableSensor = 0
,D/LightsService( 2400): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2400): unregisterListener ::   
D/LightsService( 2400): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaService( 2400): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2400): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2400): TimaServiceHandler.handleMessage what =1
,I/PowerManagerService( 2400): [PWL] Off : 680s ago
I/PowerManagerService( 2400): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2400): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2400): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2400, ws=null) (elapsedTime=5464)
,E/Watchdog( 2400): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 31
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 32
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 765s ago
,E/Watchdog( 2400): !@Sync 33
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 34
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/ConnectivityService( 2400): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,E/Watchdog( 2400): !@Sync 35
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 855s ago
,E/Watchdog( 2400): !@Sync 36
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 37
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 38
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 950s ago
,E/Watchdog( 2400): !@Sync 39
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5486): [b] __PingReply__
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/dalvikvm( 2400): GC_CONCURRENT freed 3854K, 71% free 25353K/86932K, paused 19ms+19ms, total 237ms
,D/TimaService( 2400): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2400): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2400): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2400): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2400): !@Sync 41
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 42
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2400): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2400): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2400): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 43
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 44
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 45
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 1155s ago
,E/Watchdog( 2400): !@Sync 46
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 47
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 48
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4062): GC_CONCURRENT freed 2050K, 30% free 9721K/13768K, paused 11ms+4ms, total 52ms
,D/dalvikvm( 4062): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 49
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,I/SensorManagerA( 2400): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2400): LightSensor setDelay = 200000000
,D/LightsService( 2400): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2400): LightSensor setSensorDelay = 200000000
D/Sensors ( 2400): Light sensor flush: not enabled 0
D/Sensors ( 2400): LightSensor enable = 1
D/Sensors ( 2400): LightSensor enableSensor = 1
D/SensorManager( 2400): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/LightsService( 2400): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2400): LightSensor enable = 0
D/Sensors ( 2400): LightSensor enableSensor = 0
,D/SensorManager( 2400): unregisterListener ::   
D/LightsService( 2400): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2400): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2400): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2400): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2400): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 51
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2400): !@Sync 52
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2400): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2400): !@Sync 53
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2400): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2400): !@Sync 54
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2400): GC_CONCURRENT freed 3906K, 71% free 25339K/86932K, paused 21ms+18ms, total 233ms
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 55
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 56
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 5486): GC_CONCURRENT freed 1921K, 25% free 10414K/13708K, paused 7ms+3ms, total 55ms
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 57
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 58
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 59
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5486): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3313): Aggregate from 1450201548557 (log), 1450201548557 (data)
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2400): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2400): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2400): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/Watchdog( 2400): !@Sync 60
,D/TimaService( 2400): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2400): Prepared write state in 43ms
,I/ProcessStatsService( 2400): Pruning old procstats: /data/system/procstats/state-2015-12-15-04-21-05.bin
,I/ProcessStatsService( 2400): Prepared write state in 59ms
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 61
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :4
,V/NetworkStats( 2400): performPollLocked(flags=0x3)
D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
V/NetworkStats( 2400): performPollLocked() took 53ms
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,I/SELinux (11628): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11628):  
,I/SELinux (11628): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11628):  
I/SELinux (11628):  
,I/SELinux (11628): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (11628): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(11628): >>>>> Normal User
,E/dalvikvm(11628): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (11628): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(11628): in addTimaSignatureService
,D/TimaKeyStoreProvider(11628): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(11628): Added TimaKesytore provider
,D/dalvikvm(11628): GC_CONCURRENT freed 3004K, 31% free 9553K/13724K, paused 3ms+2ms, total 27ms
,D/dalvikvm(11628): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/@ WidgetProvider(11628): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(11628): onUpdate called for widgetId : 0
,D/@ WidgetProvider(11628): Widget random data : 4
,D/@ WidgetProvider(11628): onUpdate called for widgetId : 5
,D/@ WidgetProvider(11628): Widget random data : 4
,E/dalvikvm(11628): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(11628): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11628): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11628): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11628): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11628): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11628): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11628): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11628): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11628): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(11628): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11628): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(11628): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(11628): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(11628): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(11628): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2850): GC_EXPLICIT freed 986K, 22% free 10805K/13792K, paused 5ms+7ms, total 69ms
,I/System.out(11628): Thread-678(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11628): Thread-678(ApacheHTTPLog):isShipBuild true
,I/System.out(11628): Thread-678(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/dalvikvm( 2850): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 2850): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 2850): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 2850): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 2850): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2850): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2850): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 2850): Thread-56(HTTPLog):isShipBuild true
,I/System.out( 2850): Thread-56(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(11628): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(11628): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(11628): Max ALLOWED memory (MB): 128
,V/ImageManager(11628): Max SHOULD USE memory (MB): 128
,V/ImageManager(11628): Max Image Cache memory (MB): 32
,D/skia    (11628): getTotalSize : Do not get file length
,D/@ WidgetProvider(11628): Building widget : 5
,D/dalvikvm( 2775): GC_CONCURRENT freed 8389K, 34% free 18812K/28364K, paused 6ms+9ms, total 83ms
,D/dalvikvm( 2775): WAIT_FOR_CONCURRENT_GC blocked 73ms
,E/Watchdog( 2400): !@Sync 62
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2400): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2400): <AppSync3 Whitelist>
,V/AlarmManager( 2400): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5090): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5090): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 63
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 64
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/ActivityManager( 2400): Killing 6988:com.samsung.klmsagent/u0a18 (adj 15): empty for 1800s
,I/ActivityManager( 2400): Killing 6958:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1800s
,I/ActivityManager( 2400): Killing 7178:com.samsung.android.service.travel/u0a170 (adj 15): empty for 1802s
,I/ActivityManager( 2400): Killing 6825:tv.peel.smartremote/u0a165 (adj 15): empty for 1802s
,I/ActivityManager( 2400): Killing 7162:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1802s
,I/ActivityManager( 2400): Killing 7137:com.android.email/u0a157 (adj 15): empty for 1803s
,I/ActivityManager( 2400): Killing 7086:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1804s
,I/ActivityManager( 2400): Killing 6661:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1804s
,I/ActivityManager( 2400): Killing 6490:com.policydm/1000 (adj 15): empty for 1805s
,I/ActivityManager( 2400): Killing 7020:com.sec.android.app.voicenote/1000 (adj 15): empty for 1805s
,I/ActivityManager( 2400): Killing 6858:com.vlingo.midas/u0a34 (adj 15): empty for 1805s
,I/ActivityManager( 2400): Killing 5999:com.sec.android.diagmonagent/1000 (adj 15): empty for 1806s
,I/ActivityManager( 2400): Killing 6382:com.sec.pcw.device/1000 (adj 15): empty for 1807s
,I/ActivityManager( 2400): Killing 5978:com.sec.knox.bridge/1000 (adj 15): empty for 1807s
,I/ActivityManager( 2400): Killing 5949:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1807s
,I/ActivityManager( 2400): Killing 5898:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1817s
,I/ActivityManager( 2400): Killing 6410:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1800s
,I/ActivityManager( 2400): Killing 6572:com.osp.app.signin/u0a44 (adj 15): empty for 1800s
,I/ActivityManager( 2400): Killing 7003:com.sec.android.soagent/u0a38 (adj 15): empty for 1800s
,I/ActivityManager( 2400): Killing 5566:com.android.settings/1000 (adj 15): empty for 1800s
,D/ConnectivityService( 2400): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,E/Watchdog( 2400): !@Sync 65
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
