#### Test 50650278dbf8a2a_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 6483): GC_CONCURRENT freed 2994K, 32% free 9567K/13960K, paused 3ms+1ms, total 21ms
D/dalvikvm( 6483): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/com.sec.android.app.shealth.SHealthApplication( 6465): Success during batch insertion in App registry:0
V/MediaPlayer( 6465): decode(56, 30565892, 48105)
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
V/AudioCache( 1925): notify(0x44188988, 8, 0, 0)
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
V/AudioCache( 1925): notify(0x44188988, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188988, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188988, 1, 0, 0)
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
V/AudioCache( 1925): notify(0x44188988, 6, 0, 0)
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
V/AudioCache( 1925): notify(0x44188988, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188988, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188988, 8, 0, 0)
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
V/MediaPlayer( 6465): decode(58, 30501792, 10421)
V/MediaPlayerService( 1925): decode(27, 30501792, 10421)
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
V/StagefrightPlayer( 1925): setDataSource(27, 30501792, 10421)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188c58, 8, 0, 0)
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
V/AudioCache( 1925): notify(0x44188c58, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188c58, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188c58, 1, 0, 0)
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
V/AudioCache( 1925): notify(0x44188c58, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/AudioPlayer( 1925): First fillBuffer call!!
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188c58, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188c58, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188c58, 8, 0, 0)
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
V/MediaPlayer( 6465): decode(59, 34044116, 34198)
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
V/AudioCache( 1925): notify(0x444d2898, 8, 0, 0)
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
V/AudioCache( 1925): notify(0x444d2898, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444d2898, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444d2898, 1, 0, 0)
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
V/AudioCache( 1925): notify(0x444d2898, 6, 0, 0)
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
V/AudioCache( 1925): notify(0x444d2898, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444d2898, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444d2898, 8, 0, 0)
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
V/MediaPlayer( 6465): decode(60, 30449260, 7405)
V/MediaPlayerService( 1925): decode(26, 30449260, 7405)
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
V/StagefrightPlayer( 1925): setDataSource(26, 30449260, 7405)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 8, 0, 0)
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
V/AudioCache( 1925): notify(0x442b6d20, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 1, 0, 0)
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
V/AudioCache( 1925): notify(0x442b6d20, 6, 0, 0)
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
V/AudioCache( 1925): notify(0x442b6d20, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 8, 0, 0)
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
V/MediaPlayer( 6465): decode(61, 34134748, 5555)
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
V/AudioCache( 1925): notify(0x442bc110, 8, 0, 0)
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
V/AudioCache( 1925): notify(0x442bc110, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bc110, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bc110, 1, 0, 0)
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
V/AudioCache( 1925): notify(0x442bc110, 6, 0, 0)
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
V/AudioCache( 1925): notify(0x442bc110, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bc110, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bc110, 8, 0, 0)
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
V/MediaPlayer( 6465): decode(62, 26954540, 5085)
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
V/AudioCache( 1925): notify(0x442b6d20, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0),
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
V/AudioCache( 1925): notify(0x442b6d20, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 1, 0, 0)
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
V/AudioCache( 1925): notify(0x442b6d20, 6, 0, 0)
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
V/AudioCache( 1925): notify(0x442b6d20, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 8, 0, 0)
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
V/MediaPlayer( 6465): decode(63, 26959684, 21552)
V/MediaPlayerService( 1925): decode(25, 26959684, 21552)
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
V/StagefrightPlayer( 1925): setDataSource(25, 26959684, 21552)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bd8b0, 8, 0, 0)
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
V/AudioCache( 1925): notify(0x442bd8b0, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bd8b0, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bd8b0, 1, 0, 0)
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
V/AudioCache( 1925): notify(0x442bd8b0, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/AudioPlayer( 1925): First fillBuffer call!!
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bd8b0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bd8b0, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bd8b0, 8, 0, 0)
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
V/MediaPlayer( 6465): decode(64, 34130460, 4230)
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
V/AudioCache( 1925): notify(0x441502e8, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
--------- beginning of /dev/log/system
D/SSRMv2:SIOP( 2402): SIOP:: AP = 350, Delta = 10
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
V/AudioCache( 1925): notify(0x441502e8, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441502e8, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441502e8, 1, 0, 0)
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
V/AudioCache( 1925): notify(0x441502e8, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441502e8, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441502e8, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x441502e8, 8, 0, 0)
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
V/MediaPlayer( 6465): decode(65, 26923896, 9400)
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
V/AudioCache( 1925): notify(0x442b1960, 8, 0, 0)
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
V/AudioCache( 1925): notify(0x442b1960, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1960, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1960, 1, 0, 0)
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
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1960, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/SELinux ( 6545): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6545):  
I/ActivityManager( 2402): Killing 5183:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
I/ActivityManager( 2402): Killing 5187:com.android.email/u0a157 (adj 15): empty #44
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1960, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1960, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1960, 8, 0, 0)
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
V/MediaPlayer( 6465): decode(66, 30512272, 44276)
V/MediaPlayerService( 1925): decode(26, 30512272, 44276)
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
V/AudioCache( 1925): notify(0x442b6d20, 8, 0, 0)
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
V/AudioCache( 1925): notify(0x442b6d20, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 1, 0, 0)
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
V/AudioCache( 1925): notify(0x442b6d20, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/SELinux ( 6545): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6545):  
I/SELinux ( 6545):  
I/SELinux ( 6545): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6545): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6545): >>>>> Normal User
E/dalvikvm( 6545): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 6545): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 6483): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x422a3d00, skipping init
I/SecureStorage( 6483): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6483): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 6483
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 6483): [INFO]: SPID(0x00000000)SS Daemon is running
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
D/TimaKeyStoreProvider( 6545): in addTimaSignatureService
D/TimaKeyStoreProvider( 6545): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6545): Added TimaKesytore provider
I/SecureStorage( 6483): [INFO]: SPID(0x00000000)Processing data
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 6483
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 8, 0, 0)
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
V/MediaPlayer( 6465): decode(67, 30472480, 29256)
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
V/AudioCache( 1925): notify(0x442bb0a0, 8, 0, 0)
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
V/AudioCache( 1925): notify(0x442bb0a0, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bb0a0, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bb0a0, 1, 0, 0)
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
V/AudioCache( 1925): notify(0x442bb0a0, 6, 0, 0)
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
V/AudioCache( 1925): notify(0x442bb0a0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bb0a0, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bb0a0, 8, 0, 0)
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
V/MediaPlayer( 6465): decode(68, 34078380, 52024)
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
V/AudioCache( 1925): notify(0x442b6d20, 8, 0, 0)
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
V/AudioCache( 1925): notify(0x442b6d20, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 1, 0, 0)
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
V/AudioCache( 1925): notify(0x442b6d20, 6, 0, 0)
I/AudioPlayer( 1925): First fillBuffer call!!
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
V/AudioCache( 1925): notify(0x442b6d20, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 8, 0, 0)
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
V/MediaPlayer( 6465): decode(69, 30556608, 9226)
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
V/AudioCache( 1925): notify(0x442b6d20, 8, 0, 0)
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
V/AudioCache( 1925): notify(0x442b6d20, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 1, 0, 0)
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
V/AudioCache( 1925): notify(0x442b6d20, 6, 0, 0)
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
V/AudioCache( 1925): notify(0x442b6d20, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b6d20, 8, 0, 0)
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
D/AndroidRuntime( 6562): 
D/AndroidRuntime( 6562): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 6465): decode(70, 26989388, 4509)
V/MediaPlayerService( 1925): decode(26, 26989388, 4509)
V/MediaPlayerService( 1925): player type = 3
D/AndroidRuntime( 6562): CheckJNI is OFF
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
D/AndroidRuntime( 6562): setted country_code = Poland
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
D/AndroidRuntime( 6562): setted countryiso_code = PL
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 26989388, 4509)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2350, 8, 0, 0)
D/AndroidRuntime( 6562): setted sales_code = PLS
D/AndroidRuntime( 6562): readGMSProperty: start
D/AndroidRuntime( 6562): readGMSProperty: already setted!!
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
D/AndroidRuntime( 6562): readGMSProperty: end
D/AndroidRuntime( 6562): addProductProperty: start
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
V/AudioCache( 1925): notify(0x442b2350, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2350, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2350, 1, 0, 0)
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
D/dalvikvm( 6562): Trying to load lib libjavacore.so 0x0
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2350, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2350, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
D/dalvikvm( 6562): Added shared lib libjavacore.so 0x0
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2350, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b2350, 8, 0, 0)
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
D/dalvikvm( 6562): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6562): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6562): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
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
D/dalvikvm( 6545): GC_CONCURRENT freed 3004K, 32% free 9565K/13968K, paused 3ms+34ms, total 224ms
D/dalvikvm( 6545): WAIT_FOR_CONCURRENT_GC blocked 216ms
I/SELinux ( 6594): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6594):  
I/ActivityManager( 2402): Killing 5212:com.sec.modem.settings/1000 (adj 15): empty #43
E/memtrack( 6562): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6562): failed to load memtrack module: -2
I/SELinux ( 6594): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6594):  
I/SELinux ( 6594):  
I/SELinux ( 6594): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6594): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6594): >>>>> Normal User
E/dalvikvm( 6594): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux ( 6594): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 6594): in addTimaSignatureService
D/TimaKeyStoreProvider( 6594): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6594): Added TimaKesytore provider
D/dalvikvm( 6562): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6562): Calling main entry com.android.commands.am.Am
D/dalvikvm( 6594): GC_CONCURRENT freed 2996K, 32% free 9576K/13968K, paused 3ms+1ms, total 40ms
D/dalvikvm( 6594): WAIT_FOR_CONCURRENT_GC blocked 35ms
D/dalvikvm( 6594): WAIT_FOR_CONCURRENT_GC blocked 1ms
V/ApplicationPolicy( 2402): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2402): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2402  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2402): mDVFSHelper.acquire()
I/SurfaceFlinger( 1921): id=17 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1921): id=18 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 6609): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6609):  
D/PointerIcon( 2402): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2402): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2402): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2402): setHoveringSpenCustomIcon IconType is same.1
D/AmoledAdjustTimer( 2402): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
D/AndroidRuntime( 6562): Shutting down VM
D/dalvikvm( 6562): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 4ms
I/SELinux ( 6609): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6609):  
I/SELinux ( 6609):  
I/SELinux ( 6609): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6609): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6609): >>>>> Normal User
E/dalvikvm( 6609): >>>>> com.test.thalitest [ userId:0 | appId:10552 ]
E/SELinux ( 6609): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6609): in addTimaSignatureService
D/TimaKeyStoreProvider( 6609): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6609): Added TimaKesytore provider
V/WindowManager( 2402): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4125): getWritableDatabase(pwd)
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (-2/10)
D/Launcher( 2769): onTrimMemory. Level: 20
I/SQLiteSecureOpenHelper( 4125): getDatabaseLocked(b,b,pwd)...
D/dalvikvm( 6609): GC_CONCURRENT freed 3016K, 32% free 9548K/13964K, paused 2ms+1ms, total 20ms
D/dalvikvm( 6609): WAIT_FOR_CONCURRENT_GC blocked 17ms
V/WebViewChromium( 6609): Binding Chromium to the background looper Looper (main, tid 1) {422ae440}
I/chromium( 6609): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 6609): Initializing chromium process, renderers=0
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 6594): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,W/chromium( 6609): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,W/ActivityManager( 2402): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,D/libEGL  ( 6609): loaded /system/lib/egl/libEGL_mali.so
,W/ContextImpl( 6594): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
D/libEGL  ( 6609): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 6609): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6609): Mali API Version : 401
,I/Mali    ( 6609): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/SELinux ( 6642): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6642):  
,I/SELinux ( 6642): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6642):  
I/SELinux ( 6642):  
,I/SELinux ( 6642): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6642): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6642): >>>>> Normal User
,E/dalvikvm( 6642): >>>>> com.osp.app.signin [ userId:0 | appId:10044 ]
,E/SELinux ( 6642): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6642): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6642): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6642): Added TimaKesytore provider
,I/dalvikvm( 6609): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6609): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6609): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6609): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6609): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6609): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2402): tr p:6609,o:f
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)PID: 6483, TID: 6494
W/dalvikvm( 6609): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6609): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6609): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6609): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6609): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6609): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6609): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6609): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6609): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6609): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6609): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6609): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6609): CordovaWebView is running on device made by: samsung
,D/dalvikvm( 6642): GC_CONCURRENT freed 2985K, 32% free 9582K/13968K, paused 4ms+1ms, total 22ms
,D/dalvikvm( 6642): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/SA      ( 6642): [SSP] onCreated
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2402): semi p:6609,o:f
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2402): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2402): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2402): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2402): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2402): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 6609): EGLImpl-HWUI Protected EGL context created
,I/SecureStorage( 6483): [INFO]: SPID(0x00000000)Processing data has been completed,
,I/SecureStorage( 6483): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SQLiteSecureOpenHelper( 6483): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 6483): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 6483): Open platform.db in secure mode,
,D/STATUSBAR-StatusBarManagerService( 2402): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/SA      ( 6642): [TPM] There is no property file
D/OpenGLRenderer( 6609): Enabling debug mode 0
I/SA      ( 6642): [SCU] isHaveSA() - false
I/SA      ( 6642): [TPM] getModelProperty : null
I/SA      ( 6642): [TPM] getCSCProperty : null
W/AwContents( 6609): nativeOnDraw failed; clearing to background color.
,I/SA      ( 6642): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 6642): [DM] init START
,I/SA      ( 6642): [DM] This device is not a Vodafone
,W/IInputConnectionWrapper( 6609): showStatusIcon on inactive InputConnection
,I/SA      ( 6642): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6642): support phone number id : false
,I/SA      ( 6642): [DM] init END
,I/SA      ( 6642): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 6642): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
,I/ActivityManager( 2402): Killing 4613:com.sec.android.provider.badge/u0a76 (adj 15): empty #43
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2402): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2402  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2402): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2402): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2402  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/Mms/PackageInstallReceiver( 5592): loadAuthorityPref(): sEnableAuthority = true
,I/SQLiteSecureOpenHelper( 6483): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 6483): ...getDatabaseLocked(b,b,pwd)
,I/Icing.InternalIcingCorporaProvider( 5943): Updating corpora: A: com.test.thalitest, C: MAYBE
,W/ContextImpl( 4825): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 6676): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6676):  
,I/SELinux ( 6676): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6676):  
I/SELinux ( 6676):  
,I/SELinux ( 6676): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6676): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6676): >>>>> Normal User
,E/dalvikvm( 6676): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
,E/SELinux ( 6676): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 6676): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6676): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6676): Added TimaKesytore provider
,D/dalvikvm( 6676): GC_CONCURRENT freed 3013K, 32% free 9558K/13968K, paused 3ms+9ms, total 47ms
,D/dalvikvm( 6676): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/CapabilityManagerService New( 6676): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
,I/SELinux ( 6692): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6692):  
I/ActivityManager( 2402): Killing 5231:tv.peel.smartremote/u0a165 (adj 15): empty #43
,I/SELinux ( 6692): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6692):  
I/SELinux ( 6692):  
,I/SELinux ( 6692): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6692): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6692): >>>>> Normal User
,E/dalvikvm( 6692): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
,E/SELinux ( 6692): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/Icing.InternalIcingCorporaProvider( 5943): UpdateCorporaTask done [took 275 ms] updated apps [took 275 ms] 
,D/TimaKeyStoreProvider( 6692): in addTimaSignatureService
,I/ActivityManager( 2402): Killing 5249:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
D/TimaKeyStoreProvider( 6692): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6692): Added TimaKesytore provider
,D/JsMessageQueue( 6609): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 6692): GC_CONCURRENT freed 3000K, 32% free 9569K/13968K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 6692): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/PackageIntentReceiver( 6692): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 6692): Not GearManger package! 
,I/SELinux ( 6706): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6706):  
,I/ActivityManager( 2402): Killing 5275:com.sec.android.app.taskmanager/u0a168 (adj 15): empty #43
,I/SELinux ( 6706): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6706):  
I/SELinux ( 6706):  
,I/SELinux ( 6706): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6706): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6706): >>>>> Normal User
,E/dalvikvm( 6706): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
,E/SELinux ( 6706): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6706): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6706): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6706): Added TimaKesytore provider
,D/dalvikvm( 6609): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422a6948
,D/dalvikvm( 6609): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422a6948
D/jxcore_app_log( 6609): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030947392
,D/JX-Cordova( 6609): jxcore cordova android initializing
,D/dalvikvm( 6706): GC_CONCURRENT freed 2990K, 32% free 9580K/13968K, paused 5ms+1ms, total 34ms
,D/dalvikvm( 6706): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/MagazineService Version( 6706): Magazine-Channel: 13
,D/MagazineService Version( 6706): Magazine-Provider: 13
,D/MagazineService Version( 6706): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 6706): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 6706): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,I/SELinux ( 6719): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6719):  
,I/MagazineService::MagazineService( 6706): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,D/MagazineService::MagazineService( 6706): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/ActivityManager( 2402): Killing 5287:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
,I/SELinux ( 6719): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6719):  
I/SELinux ( 6719):  
,I/SELinux ( 6719): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6719): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6719): >>>>> Normal User
,E/dalvikvm( 6719): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 6719): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6719): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6719): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6719): Added TimaKesytore provider
,D/dalvikvm( 6609): GC_CONCURRENT freed 1279K, 20% free 11344K/14016K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 6609): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 6719): GC_CONCURRENT freed 2999K, 32% free 9569K/13964K, paused 4ms+1ms, total 27ms
,D/dalvikvm( 6719): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/SELinux ( 6732): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6732):  
I/ActivityManager( 2402): Killing 5314:com.gameloft.android.GloftGF2H/u0a179 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 14% free 9502K/10944K, paused 2ms+3ms, total 28ms
,I/SELinux ( 6732): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6732):  
I/SELinux ( 6732):  
,I/SELinux ( 6732): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6732): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6732): >>>>> Normal User
,E/dalvikvm( 6732): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
,E/SELinux ( 6732): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9502K/10944K, paused 2ms+3ms, total 24ms
,D/TimaKeyStoreProvider( 6732): in addTimaSignatureService
,D/CustomFrequencyManagerService( 2402): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2402  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9502K/10944K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 6732): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6732): Added TimaKesytore provider
,D/dalvikvm( 6732): GC_CONCURRENT freed 2998K, 32% free 9572K/13964K, paused 5ms+2ms, total 25ms
,D/dalvikvm( 6732): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/KidsPlatformStub( 6732): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 6744): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6744):  
I/ActivityManager( 2402): Killing 5327:com.gameloft.android.GloftKLMF/u0a180 (adj 15): empty #43
,I/SELinux ( 6744): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6744):  
I/SELinux ( 6744):  
,I/SELinux ( 6744): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6744): >>>>> Normal User
,E/dalvikvm( 6744): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 6744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6744): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6744): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6744): Added TimaKesytore provider
,D/dalvikvm( 6744): GC_CONCURRENT freed 2990K, 32% free 9579K/13968K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 6744): WAIT_FOR_CONCURRENT_GC blocked 9ms
,I/SELinux ( 6756): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6756):  
,I/ActivityManager( 2402): Killing 5341:com.gameloft.android.GloftPSHU/u0a181 (adj 15): empty #43
,I/SELinux ( 6756): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6756):  
I/SELinux ( 6756):  
,I/SELinux ( 6756): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6756): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6756): >>>>> Normal User
,E/dalvikvm( 6756): >>>>> com.sec.enterprise.knox.cloudmdm.smdms [ userId:0 | appId:10171 ]
,E/SELinux ( 6756): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6756): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6756): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6756): Added TimaKesytore provider
,I/Icing   ( 3310): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,D/dalvikvm( 6756): GC_CONCURRENT freed 3001K, 32% free 9570K/13968K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 6756): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 6609): GC_CONCURRENT freed 1959K, 19% free 14917K/18284K, paused 3ms+3ms, total 83ms
,D/dalvikvm( 6609): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/Icing   ( 3310): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,D/UMC:Core( 6756): onCreate(): 
,D/USER_AGENT( 6756): UMC/1.0.12 (SM-G800F) SAFE-5 KNOX-2.0
,D/[SAMSUNG SMARCART NATIVE]( 6756): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 6756): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/TZ_CCM_C_GetFunctionList: ( 6756): TZ_CCM_C_GetFunctionList was called
,D/[SAMSUNG SMARCART NATIVE]( 6756): FINISHED: initialize rv:0
,D/dalvikvm( 6756): GC_CONCURRENT freed 1867K, 24% free 10775K/14036K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 6756): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/UMC:SecurityUtils( 6756): Loaded server certificates: 0
,D/UMC:SecurityUtils( 6756): Loaded server certificates: 0
,D/UMC:CloudMDMSecurity( 6756): New Flow
I/        ( 2402): CCM JNI: In ccm_register_for_default_cert
I/        ( 2402): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: ( 2402): &ctx = 0x77ace618
I/TLC_TZ_CCM: ( 2402): creating new ccm context...
I/TLC_TZ_CCM: ( 2402): initializing ccm context...
I/TLC_TZ_CCM: ( 2402): root = 0, root_strlen = 1
I/TLC_TZ_CCM: ( 2402): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2402): input max_sendmsg_size = 19420
I/TZ: client_server_communication( 2402): input max_recvmsg_size = 19420
I/TZ: client_server_communication( 2402): root = 0, root_len = 1
I/TZ: client_server_communication( 2402): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2402): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication( 2402): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication( 2402): Client_Server_Open was called
D/TimaService( 2402): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService( 2402): TIMA: in getTimaVersion
I/TZ: client_server_communication( 2402): IClientServer::IClientServer()
I/TZ: client_server_communication( 2402): BpClientServer::BpClientServer()
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 2510): creating new ccm context...
I/TZ_CCM_SERVER( 2510): initializing ccm context...
I/TZ_CCM_SERVER( 2510): root = 0, root_strlen = 1
I/TZ_CCM_SERVER( 2510): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2510): input max_sendmsg_size = 19420
I/TZ: mc_tlc_communication( 2510): input max_recvmsg_size = 19420
I/TZ: mc_tlc_communication( 2510): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2510): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2510): aligned max_sendmsg_size = 19456
I/TZ: mc_tlc_communication( 2510): aligned max_recvmsg_size = 19456
I/TZ: mc_tlc_communication( 2510): device_id = 0x0
I/TZ: mc_tlc_communication( 2510): tlc_open() was called
I/TZ: mc_tlc_communication( 2510): Opening MobiCore device
I/TZ: mc_tlc_communication( 2510): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2510): Opening the session
,I/TZ: mc_tlc_communication( 2510): tlc_open() succeeded
I/TZ: client_server_communication( 2402): Client_Server_Open succeeded
I/TZ_CCM_C_Initialize: ( 2402): ctx = 0x7872af68, comm = 0x7c8065e0, sendmsg = 0x7be2f008, recvmsg = 0x7be33c08
,I/TZ_init: ( 2402): TZ_init: sending initialization request...
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
E/Parcel  ( 2402): nm 19456
E/TZ_init: ( 2402): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 2402): trustlet initialization failed
,I/TZ_init: ( 2402): TZ_init_START...
,I/TZ_init: ( 2402): TZ_init_with_data: sending initialization request...
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
,E/Parcel  ( 2402): nm 19456
I/TZ_init: ( 2402): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: ( 2402): Exercising TZ_DB_INIT in TLC
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
,E/Parcel  ( 2402): nm 19456
I/TZ_COMMON: tlc_key_db_util: ( 2402): DB Operation suceeded
,I/TLC_TZ_CCM: register for default cert: ( 2402): Exercising TZ_CCM_register_default_TLC
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
E/Parcel  ( 2402): nm 19456
I/TLC_TZ_CCM: register for default cert: ( 2402): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: ( 2402): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: ( 2402): Exercising TZ_CCM_C_Finalize_TLC
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
E/Parcel  ( 2402): nm 19456
I/TZ: client_server_communication( 2402): Client_Server_Close was called
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(1) 16
I/TZ: mc_tlc_communication( 2510): tlc_close() was called
,I/TZ: mc_tlc_communication( 2510): Closing the session
I/TZ: mc_tlc_communication( 2510): Free WSM
,I/TZ: mc_tlc_communication( 2510): Closing MobiCore device
,I/TZ: mc_tlc_communication( 2510): tlc_close() succeeded
,I/TZ: client_server_communication( 2402): Client_Server_Close succeeded
,D/UMC:CloudMDMSecurity( 6756): TIMA service call for password change success!!,
,D/UMC:AdminManager( 6756): init - start,
,D/UMC:AdminManager( 6756): loadAdmins,
,D/UMC:AdminManager( 6756): removeOutOfSyncProxyAdmins,
D/UMC:AdminManager( 6756): startPolicyHandlers
,I/UMC:TestPolicyHandler( 6756): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 6756): init - end,
,V/UMC:AlarmHandler( 6756): Enter loadList,
,D/EnterpriseDeviceManagerService( 2402): Creating context as user 0,
,D/SPPApp  ( 6756): [SppMessageReceiver] onReceive,
,D/SPPApp  ( 6756): [SppMessageReceiver] onReceive. ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest,
,I/SELinux ( 6772): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6772):  
I/ActivityManager( 2402): Killing 5379:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 6772): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6772):  
I/SELinux ( 6772):  
,I/SELinux ( 6772): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6772): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6772): >>>>> Normal User
,E/dalvikvm( 6772): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ]
,E/SELinux ( 6772): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6772): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6772): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6772): Added TimaKesytore provider
,D/dalvikvm( 6772): GC_CONCURRENT freed 3008K, 32% free 9555K/13964K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 6772): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/ApplicationPromenada( 6772): Application OnCreate start
,D/ApplicationPromenada( 6772): Application OnCreate po on Create
D/CrashReporter( 6772): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@422f3128
D/CrashReporter( 6772): Swaping uncaught exception handler
,D/ApplicationPromenada( 6772): Application OnCreate App Loader start
,D/ApplicationPromenada( 6772): Application OnCreate App Loader finish
,D/dalvikvm( 6609): GC_FOR_ALLOC freed 5358K, 31% free 16202K/23168K, paused 46ms, total 46ms
,D/p2.ApplicationLoader( 6772): ############################## cached apps: 
,V/WebViewChromium( 6772): Binding Chromium to the background looper Looper (main, tid 1) {422ac280}
,I/chromium( 6772): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6772): Initializing chromium process, renderers=0
,D/libEGL  ( 6772): loaded /system/lib/egl/libEGL_mali.so
,W/chromium( 6772): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6772): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6772): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6772): Mali API Version : 401
,I/Mali    ( 6772): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/ApplicationPromenada( 6772): Application OnCreate Finish
,I/SELinux ( 6803): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6803):  
,I/ActivityManager( 2402): Killing 5525:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,I/SELinux ( 6803): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6803):  
I/SELinux ( 6803):  
,I/SELinux ( 6803): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
E/SELinux ( 6803): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,E/dalvikvm( 6803): >>>>> Normal User
E/dalvikvm( 6803): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10041 ]
E/SELinux ( 6803): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 6803): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6803): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6803): Added TimaKesytore provider,
,D/dalvikvm( 6803): GC_CONCURRENT freed 2995K, 32% free 9575K/13968K, paused 4ms+1ms, total 31ms,
,D/dalvikvm( 6803): WAIT_FOR_CONCURRENT_GC blocked 26ms,
,D/dalvikvm( 6772): GC_CONCURRENT freed 1746K, 23% free 10812K/13964K, paused 2ms+2ms, total 35ms,
,I/ActivityManager( 2402): Killing 5617:com.sec.android.app.sns3/u0a37 (adj 15): empty #43,
,D/PackageBroadcastService( 3310): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest,
D/ChimeraCfgMgr( 3310): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3310): Module APK com.google.android.play.games already loaded,
,D/ChimeraCfgMgr( 3310): Loading module com.google.android.gms.games from APK com.google.android.play.games,
,D/ChimeraModuleLdr( 3310): Module APK com.google.android.play.games already loaded,
,D/ChimeraCfgMgr( 3310): Loading module com.google.android.gms.gass from APK com.google.android.gms,
,D/AsyncTaskServiceImpl( 3310): Submit a task: k,
,D/ChimeraCfgMgr( 3310): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 3310): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 3310): Processing package: com.test.thalitest
,D/GassUtils( 3310): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
,D/k       ( 3310): Found info for package com.test.thalitest in db.
,D/Finsky  ( 3885): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/dalvikvm( 6609): GC_CONCURRENT freed 6701K, 32% free 17668K/25788K, paused 3ms+10ms, total 72ms
D/dalvikvm( 6609): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 6609): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/dalvikvm( 6609): GC_FOR_ALLOC freed 1470K, 33% free 17359K/25788K, paused 43ms, total 44ms
,I/dalvikvm-heap( 6609): Grow heap (frag case) to 21.852MB for 3713210-byte allocation
,D/dalvikvm( 6609): GC_FOR_ALLOC freed 30K, 29% free 20954K/29416K, paused 42ms, total 42ms
,D/dalvikvm( 6772): GC_CONCURRENT freed 2362K, 27% free 10463K/14180K, paused 3ms+2ms, total 59ms
,W/ResourceType( 6772): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75)
,W/PackageManager( 6772): Failure retrieving text 0x7f060000 in package com.android.keyguard
W/PackageManager( 6772): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 6772): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 6772): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 6772): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 6772): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 6772): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 6772): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 6772): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125)
W/PackageManager( 6772): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 6772): 	at java.lang.Thread.run(Thread.java:841)
,W/jxcore-log( 6609): Initializing JXcore engine
,W/jxcore-log( 6609): JXcore engine is ready
,W/jxcore-log( 6609): Starting JXcore engine
,W/jxcore-log( 6609): Platform android
W/jxcore-log( 6609): 
,W/jxcore-log( 6609): Process ARCH arm
W/jxcore-log( 6609): 
,I/Icing   ( 3310): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,D/dalvikvm( 6772): GC_CONCURRENT freed 2051K, 27% free 10395K/14180K, paused 2ms+6ms, total 77ms
,D/dalvikvm( 3310): GC_CONCURRENT freed 1514K, 19% free 12720K/15628K, paused 5ms+16ms, total 88ms
,I/Icing   ( 3310): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/p2.ApplicationLoader( 6772): Process time: 2430
,D/p2.ApplicationLoader( 6772): ##############################  apps after loading: 
,D/dalvikvm( 6772): GC_CONCURRENT freed 2232K, 29% free 10103K/14180K, paused 3ms+2ms, total 32ms
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2402): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2402): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/jxcore-log( 6609): JXcore Cordova bridge is ready!
I/jxcore-log( 6609): 
W/jxcore-log( 6609): JXcore engine is started
I/chromium( 6609): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/Watchdog( 2402): !@Sync 5
,I/jxcore-log( 6609): Toggling radios to true
I/jxcore-log( 6609): 
,W/ActivityManager( 2402): Permission Denial: getCurrentUser() from pid=6609, uid=10552 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 2402): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 2402): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6609, uid=10552 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 2402): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/BluetoothManagerService( 2402): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService( 2402): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 2402): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService( 2402): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService( 2402): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService( 2402): foregroundUser: 0
,E/BluetoothManagerService( 2402): Package is exist.
,I/WifiManager( 6609): packageName : com.test.thalitest
,D/BluetoothAdapterState( 5102): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 5102): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5102): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5102): updateAdapterState state is 11
,D/BluetoothAdapterService( 5102): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService( 5102): Autoconnection is available 
D/BluetoothAdapterService( 5102): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 5102): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5102): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/InputMethodManagerService( 2402): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2402): [BT Setting State] State =11
I/WifiManager( 6609): setWifiEnabled : true
,I/WifiService( 2402): setWifiEnabled: true pid=6609, uid=10552
,W/BluetoothAdapterService( 5102): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,W/ActivityManager( 2402): Permission Denial: getCurrentUser() from pid=6609, uid=10552 requires android.permission.INTERACT_ACROSS_USERS
D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/PhoneApp( 2752): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
W/WifiService( 2402): Failed getting userId using ActivityManagerNative
W/WifiService( 2402): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6609, uid=10552 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2402): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2402): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2402): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2402): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2402): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2402): 	at dalvik.system.NativeStart.run(Native Method)
I/SamsungIME( 2973): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService( 5102): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/QuickConnect[1.1][2] ( 5076): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/BluetoothAdapterService( 5102): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5102): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,I/WifiService( 2402): disconnect: pid=6609, uid=10552
,W/BluetoothAdapterService( 5102): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,I/jxcore-log( 6609): Radios toggled
I/jxcore-log( 6609): 
W/BluetoothAdapterService( 5102): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5102): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5102): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 5102): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5102): Not skipping com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5102): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5102): Not skipping com.android.bluetooth.a2dp.A2dpService
,I/jxcore-log( 6609): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 6609): 
,D/BluetoothNotiBroadcastReceiver( 5577): onReceive
,I/jxcore-log( 6609): Perf Test app loaded loaded
I/jxcore-log( 6609): 
,I/jxcore-log( 6609): check test folder
I/jxcore-log( 6609): 
,I/SELinux ( 6828): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6828):  
,I/jxcore-log( 6609): found test : ./testFindPeers.js
I/jxcore-log( 6609): 
,D/HeadsetService( 5102): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 5102): classInitNative: succeeds
D/HeadsetStateMachine( 5102): Version 1.5
,D/HeadsetStateMachine( 5102): make
W/BluetoothAdapterService( 5102): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5102): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5102): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5102): Not skipping com.android.bluetooth.hdp.HealthService
I/SELinux ( 6828): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6828):  
I/SELinux ( 6828):  
,I/SELinux ( 6828): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6828): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6828): >>>>> Normal User
,E/dalvikvm( 6828): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ]
,E/SELinux ( 6828): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/QuickConnect[1.1][2] ( 5076): HeadsetProfile.onServiceConnected - Bluetooth service connected
W/BluetoothAdapterService( 5102): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5102): Not skipping com.android.bluetooth.pan.PanService
,I/dalvikvm( 6828): Enabling JNI app bug workarounds for target SDK version 7...
W/BluetoothAdapterService( 5102): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5102): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/TimaKeyStoreProvider( 6828): in addTimaSignatureService
W/BluetoothAdapterService( 5102): check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5102): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService,
,W/BluetoothAdapterService( 5102): Not skipping com.broadcom.bt.service.sap.SapService,
,D/TimaKeyStoreProvider( 6828): Cannot add TimaSignature Service, License check Failed,
D/ActivityThread( 6828): Added TimaKesytore provider
E/HeadsetStateMachine( 5102): # of Max HF connection is 2
,I/BluetoothAdapterState( 5102): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false,
,I/bluedroid( 5102): get_profile_interface handsfree,
,D/BluetoothAtMessage( 5102): createCMTIContentObservers,
,D/HeadsetStateMachine( 5102): Enter Disconnected: -2,
,E/HeadsetStateMachine( 5102): set to mRemoteBrsf = 0,
,D/HeadsetStateMachine( 5102): map size, before remove : 0
D/HeadsetStateMachine( 5102): map size, after remove: 0,
,D/HeadsetStateMachine( 5102): mNextConnectingDevice : null,
D/BluetoothA2dp( 2402): Proxy object connected
,I/jxcore-log( 6609): found test : ./testSendData.js
I/jxcore-log( 6609): 
,D/A2dpService( 5102): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 5102): classInitNative: succeeds
,D/A2dpStateMachine( 5102): make
,D/BluetoothA2dp( 5076): Proxy object connected
,D/QuickConnect[1.1][2] ( 5076): A2dpProfile.onServiceConnected - Bluetooth service connected
,I/bluedroid( 5102): get_profile_interface a2dp
,I/GKI_LINUX( 5102): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 5102): Enter Disconnected: -2
,I/BluetoothAvrcpServiceJni( 5102): classInitNative: succeeds
,I/bluedroid( 5102): get_profile_interface avrcp
,D/MediaFocusControl( 2402): >>> registerRemoteControlDisplay
,I/BluetoothHidServiceJni( 5102): classInitNative: succeeds
,D/BluetoothInputDevice( 5076): Proxy object connected
,D/QuickConnect[1.1][2] ( 5076): HidProfile.onServiceConnected - Bluetooth service connected
,D/BluetoothA2dp( 4125): Proxy object connected
D/HidService( 5102): Received start request. Starting profile...
I/bluedroid( 5102): get_profile_interface hidhost
,D/HidService( 5102): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 5102): classInitNative: succeeds
,D/HealthService( 5102): Received start request. Starting profile...
,I/bluedroid( 5102): get_profile_interface health
,I/BluetoothPanServiceJni( 5102): classInitNative(L105): succeeds
,D/BluetoothPan( 2402): BluetoothPAN Proxy object connected
,D/PanService( 5102): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5102): initializeNative(L110): pan
,I/bluedroid( 5102): get_profile_interface pan
,D/BluetoothTethering( 2402): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 5102): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 5102): mAccount : null
,I/BluetoothSAPServiceJni( 5102): classInitNative(L204): succeeds
,D/SapService( 5102): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 5102): initializeNative(L209): sap
,I/bluedroid( 5102): get_profile_interface sap
,D/HeadsetStateMachine( 5102): Try to query the phonestate on bind
,D/BluetoothPhoneService( 2752): handleMessage: 4
D/HeadsetStateMachine( 5102): Proxy object connected
,V/BluetoothPhoneService( 2752): Call state Converted2: IDLE/IDLE -> 6
,D/HeadsetPhoneState( 5102): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,W/BluetoothHeadset( 2752): Proxy not attached to service
D/HeadsetPhoneState( 5102): sendDeviceDataStateChanged
D/HeadsetPhoneState( 5102): Signal level : previous=0 curr=0
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5102): Disconnected process message: 11
D/HeadsetStateMachine( 5102): Disconnected process message: 20
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
D/HeadsetPhoneState( 5102): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 5102): Disconnected process message: 11
D/BluetoothAdapterService( 5102): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5102): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5102): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5102): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5102): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5102): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 5102): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5102): enable
,D/GKI_LINUX( 5102): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,D/dalvikvm( 6828): GC_CONCURRENT freed 2998K, 32% free 9566K/13964K, paused 13ms+3ms, total 70ms
,D/dalvikvm( 6828): WAIT_FOR_CONCURRENT_GC blocked 31ms
,E/bt-btif ( 5102): Calling BTA_HhEnable
,E/bt-btif ( 5102): btif_storage_get_adapter_property service_mask:0x160040
E/BluetoothServiceJni( 5102): populateRssiValuesNative
I/bluedroid( 5102): getModelRssiValues
,E/BluetoothServiceJni( 5102): model_rssi_values_callback: low = -75, mid = -65, high = 127
,D/dalvikvm( 2402): GC_EXPLICIT freed 2890K, 56% free 24613K/55380K, paused 14ms+21ms, total 431ms
,E/WifiHW  ( 2402): ##################### set firmware type 0 #####################
,I/WifiHW  ( 1916): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
E/WifiHW  ( 1916): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 1916): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 1916): TEMP_FAILURE_RETRY complete
,D/SoftapController( 1916): Softap fwReload - Ok
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 5102): isSecureModeOn:false
D/CommandListener( 1916): Setting iface cfg
,D/CommandListener( 1916): Trying to bring down wlan0
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,D/BtConfig.SecureMode( 5102): isSecureModeOn:false
E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
,D/WifiHW  ( 2402): Skip the update_ctrl_interface
,D/WifiHW  ( 2402): Skip the update_ctrl_interface
,E/WifiHW  ( 2402): supplicant_name : p2p_supplicant
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,D/BtConfig.SecureMode( 5102): isSecureModeOn:false
,D/WifiMonitor( 2402): startMonitoring(wlan0) with mConnected = false
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
,D/BtConfig.SecureMode( 5102): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 241
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BtConfig.SecureMode( 5102): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 241
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BtConfig.SecureMode( 5102): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
,D/GKI_LINUX( 5102): release_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 5102): isSecureModeOn:false
,W/System.err( 6828): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BtConfig.SecureMode( 5102): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5102): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 5102): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 5102): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
I/wpa_supplicant( 6848): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
,E/bt-btif ( 5102): btif_sock_init: !radio_req && !rfc_init
D/IOP_DB_BT( 5102): db_open: file /etc/bluetooth/iop_bt.db
I/wpa_supplicant( 6848): [wpa_supplicant_init]: use SECRIL
,I/wpa_supplicant( 6848): Successfully initialized wpa_supplicant
I/wpa_supplicant( 6848): >>>>> Not GET KEY, IV <<<<<
D/IOP_DB_BT( 5102): db_open: db_open : handle 2010137644l, read 9734 bytes onto local cache
D/IOP_DB_BT( 5102): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5102): db_query: result 1
I/        ( 5102): iop_db_open: iop_db_open status 0
I/bte_conf( 5102): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/GKI_LINUX( 5102): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
E/wpa_supplicant( 6848): getIMSI cannot open file
I/bte_conf( 5102): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 5102): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/wpa_supplicant( 6848): Interworking config: - SIM READ ERROR
,I/bte_conf( 5102): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 5102): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5102): ScanMode =  20
,D/BluetoothAdapterProperties( 5102): State =  11
D/BtConfig.SecureMode( 5102): isSecureModeOn:false
D/BtConfig.SecureMode( 5102): isSecureModeOn:false
D/BtConfig.SecureMode( 5102): isSecureModeOn:false
D/BtConfig.SecureMode( 5102): isSecureModeOn:false
D/BtConfig.SecureMode( 5102): isSecureModeOn:false
D/BtConfig.SecureMode( 5102): isSecureModeOn:false
D/BtConfig.SecureMode( 5102): isSecureModeOn:false
D/BtConfig.SecureMode( 5102): isSecureModeOn:false
,I/BluetoothAdapterState( 5102): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 5102): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5102): updateAdapterState state is 12
,D/BluetoothAdapterService( 5102): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService(1110198712)( 5102): Register RemoteMessageListener
W/System.err( 6828): 	at libcore.io.IoBridge.open(IoBridge.java:409)
,W/System.err( 6828): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 6828): 	at java.util.Scanner.<init>(Scanner.java:158)
W/System.err( 6828): 	at java.util.Scanner.<init>(Scanner.java:138)
W/System.err( 6828): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
W/System.err( 6828): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
W/System.err( 6828): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
,W/System.err( 6828): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
W/System.err( 6828): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
W/System.err( 6828): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 6828): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
D/BluetoothA2dp( 2402): onBluetoothStateChange: up=true
,W/System.err( 6828): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6828): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 6828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6828): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 6828): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6828): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6828): 	at java.lang.reflect.Method.invoke(Method.java:515)
D/BluetoothA2dp( 5076): onBluetoothStateChange: up=true
W/System.err( 6828): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
,D/BluetoothInputDevice( 5076): onBluetoothStateChange: up=true
W/System.err( 6828): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6828): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 6828): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 6828): 	at libcore.io.Posix.open(Native Method)
,W/System.err( 6828): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6828): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 6828): 	... 20 more
,D/BluetoothA2dp( 4125): onBluetoothStateChange: up=true
,D/HeadsetService( 5102): registerMessageListener
D/BluetoothAdapterService( 5102): Autoconnection is available 
D/HeadsetStateMachine( 5102): Disconnected process message: 70
,D/BluetoothAdapterService( 5102): updateAdapterState prevState = 11newState = 12
D/HeadsetStateMachine( 5102): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@42322328
,D/BluetoothAdapterService( 5102): starting service from this receiver
,W/ContextImpl( 5102): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,D/BluetoothAdapterService( 5102): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
,D/bluedroid( 5102): init_wake_lock lock_fd:85, unlock_fd:86
,I/BluetoothAdapterState( 5102): Entering On State from state = 11
,W/System.err( 6828): file res dir: /data/data/pl.k2.droidoaudioteka/files
,W/System.err( 6828): Excternal dir: /mnt/sdcard
W/InputMethodManagerService( 2402): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/BluetoothPbapService( 5102): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
I/InputMethodManagerService( 2402): [BT Setting State] State =12
,I/InputMethodManagerService( 2402): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/BluetoothAdapterService(1110198712)( 5102): Get Bonded Devices being called
D/PhoneApp( 2752): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
D/BluetoothHeadset( 2752): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@4238d4f0, true
I/SamsungIME( 2973): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothHeadset( 2752): registerMessageListener
I/QuickConnect[1.1][2] ( 5076): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
,D/HeadsetService( 5102): registerMessageListener
,D/HeadsetService( 5102): registerMessageListener
D/PhoneApp( 2752): registerMessageListener
D/HeadsetStateMachine( 5102): Disconnected process message: 70
,D/HeadsetStateMachine( 5102): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@42393d38,
,I/chromium( 6609): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BluetoothPanServiceJni( 5102): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan,
,I/BluetoothPbapService( 5102): Handler(): got msg=1,
,V/BluetoothPbapService( 5102): PBAP Service initSocket try: 0,
,I/wpa_supplicant( 6848): >>>>> Not GET KEY, IV <<<<<
W/BluetoothAdapter( 5102): getBluetoothService() called with no BluetoothManagerCallback
E/wpa_supplicant( 6848): getIMSI cannot open file
,E/wpa_supplicant( 6848): Interworking config: - SIM READ ERROR
I/wpa_supplicant( 6848): >>>>> Not GET KEY, IV <<<<<
,E/BluetoothServiceJni( 5102): SOCK FLAG = 1 ***********************
I/wpa_supplicant( 6848): rfkill: Cannot open RFKILL control device
,D/BluetoothMapMasInstance( 5102): set MAP SDP message type : 1
,D/BluetoothPbapService( 5102): PBAP Socket is BluetoothServerSocket,
,W/BluetoothAdapter( 5102): getBluetoothService() called with no BluetoothManagerCallback,
,E/BluetoothServiceJni( 5102): SOCK FLAG = 3 ***********************,
D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:2
,V/MaBo    ( 6828): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6828): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled,
,I/System.out( 6828): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6828): moge zapisać w resDir?true,
,V/MaBo    ( 6828): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled,
,D/GKI_LINUX( 5102): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,I/System.out( 6828): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled,
,I/System.out( 6828): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled,
,W/GAV2    ( 6828): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
I/GAV2    ( 6828): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 6828): init tracking...,
,I/AUDIOTEKA_GA( 6828): app started!,
,I/BugSenseHandler( 6828): Registering default exceptions handler,
,D/AuthorizationBluetoothService( 2851): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/DownloadService( 6828): Tworzenie serwisu - onCreate()
,I/DownloadService( 6828): Start serwisu - onStart()
,I/BugSenseHandler( 6828): Registering default exceptions handler
,I/knox    ( 5016): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 5016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 5016): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 5016): KNOXAgentService : onCreate()
D/knox    ( 5016): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 5016): KNOXAgentService. startJobThread() start
D/knox    ( 5016): KNOXAgentService. JobThread()
D/knox    ( 5016): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 5016): KNOXAgentService. startJobThread() wait
I/SELinux ( 6870): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6870):  
,D/knox    ( 5016): KNOXAgentService : onDestroy().,
,D/knox    ( 5016): ModuleBase.cancelAllAlarmManageModule(),
,I/BugSenseHandler( 6828): Flushing...,
,I/BugSenseHandler( 6828): Registering default exceptions handler,
,I/SELinux ( 6870): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6870):  
I/SELinux ( 6870):  
I/SELinux ( 6870): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 6870): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6870): >>>>> Normal User
,E/dalvikvm( 6870): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,I/PlayerService( 6828): Tworzenie serwisu - onCreate()
,E/SELinux ( 6870): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/MediaFocusControl( 2402):   Remote Control   registerMediaButtonIntent() for PendingIntent{42f6f5d0: PendingIntentRecord{430e9df8 pl.k2.droidoaudioteka broadcastIntent}}
,D/TimaKeyStoreProvider( 6870): in addTimaSignatureService
,V/KeyguardUpdateMonitor( 2581): handleSetGenerationId(g=2, clear=true)
,I/BugSenseHandler( 6828): Flushing...
I/BugSenseHandler( 6828): Registering default exceptions handler
,D/TimaKeyStoreProvider( 6870): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6870): Added TimaKesytore provider
,V/AUDIOTEKA_MB( 6828): new AudioManagerFocusWrapper in playerservice oncreate
,I/PlayerService( 6828): Start serwisu - onStart()
,D/dalvikvm( 6870): GC_CONCURRENT freed 3009K, 32% free 9565K/13968K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 6870): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/ContextImpl( 5577): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 360, Delta = 10
,D/LocalBluetoothProfileManager( 5577): Adding local A2DP profile
,I/System.out( 6828): Thread-602(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6828): Thread-602(ApacheHTTPLog):isShipBuild true
,I/System.out( 6828): Thread-602(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6828): Thread-599(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,W/ContextImpl( 5577): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,D/LocalBluetoothProfileManager( 5577): Adding local HEADSET profile
,I/System.out( 6828): pool-1-thread-1 calls detatch()
,W/BugSenseHandler( 6828): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,I/System.out( 6828): pool-1-thread-2 calls detatch()
W/BugSenseHandler( 6828): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,E/BluetoothHeadset( 5577): BTStateChangeCB is registed
,W/ContextImpl( 5577): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
E/BluetoothHeadset( 5577): BluetoothHeadset service is binded
,D/Bluetoothsap( 5577): bindService called to Bluetooth SAP Service
W/ContextImpl( 5577): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ContextImpl( 5577): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,W/ContextImpl( 5577): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
D/LocalBluetoothProfileManager( 5577): PANU : true
D/LocalBluetoothProfileManager( 5577): Adding local MAP profile
,D/BluetoothMap( 5577): Create BluetoothMap proxy object
W/ContextImpl( 5577): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 5577): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 5577): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 5577): LocalBluetoothProfileManager construction complete
,W/ContextImpl( 5577): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/DockEventReceiver( 5577): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 5577): onReceive
,D/BtConfig.SecureMode( 5102): isSecureModeOn:false
,D/BluetoothA2dp( 5577): Proxy object connected
,D/A2dpProfile( 5577): Bluetooth service connected
,D/HeadsetProfile( 5577): Bluetooth service connected
,D/Bluetoothsap( 5577): BluetoothSAP Proxy object connected
D/SapProfile( 5577): Bluetooth service connected
,D/Bluetoothsap( 5577): getConnectedDevices()
,D/BluetoothInputDevice( 5577): Proxy object connected
,D/HidProfile( 5577): Bluetooth service connected
,D/BluetoothPan( 5577): BluetoothPAN Proxy object connected
,D/PanProfile( 5577): Bluetooth service connected
,D/BluetoothMap( 5577): Proxy object connected
,D/MapProfile( 5577): Bluetooth service connected
,D/BluetoothPbap( 5577): Proxy object connected
,D/PbapServerProfile( 5577): Bluetooth service connected
D/Bluetoothsap( 5577): BluetoothSAP Proxy object connected
D/SapProfile( 5577): Bluetooth service connected
,D/Bluetoothsap( 5577): getConnectedDevices()
,I/ActivityManager( 2402): Killing 5712:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
D/AuthorizationBluetoothService( 2851): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 2851): Proximity feature is not enabled.
,W/BluetoothAdapter( 5102): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5102): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 5102): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BtOppRfcommListener( 5102): Accept thread started.
,D/GKI_LINUX( 5102): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/Tethering( 2402): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2402): interfaceStatusChanged wlan0, true
,E/Tethering( 2402): No numeric data
,D/Tethering( 2402): sendTetherStateChangedBroadcast 1, 0, 0
,I/ConnectivityService( 2402): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering( 2402): interfaceLinkStateChanged wlan0, true
D/Tethering( 2402): interfaceStatusChanged wlan0, true
D/NtpTrustedTime( 2402): forceRefresh() from cache miss
D/NtpTrustedTime( 2402): forceRefresh Fail.
,I/wpa_supplicant( 6848): wlan0: Setting scan request: 0 sec 100000 usec
V/NetworkStats( 2402): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2402): forceRefresh() from cache miss
,D/NtpTrustedTime( 2402): forceRefresh Fail.
V/NetworkStats( 2402): performPollLocked() took 19ms
,I/wpa_supplicant( 6848): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 6848): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 6848): rfkill: Cannot open RFKILL control device
,D/Tethering( 2402): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2402): interfaceStatusChanged p2p0, true
D/Tethering( 2402): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2402): interfaceStatusChanged p2p0, true
,I/wpa_supplicant( 6848): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6848): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
I/wpa_supplicant( 6848): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6848): Skip scan - bUseNetwork false
,D/WifiStateMachine( 2402): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative( 2402): callSECApiString - ID [21]
I/wpa_supplicant( 6848): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 6848): wlan0: HS20_DISABLED_COMPLETE normal
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/WifiNative( 2402): callSECApiInt - ID [65]
,I/knox    ( 5016): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 5016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,D/knox    ( 5016): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,I/knox    ( 5016): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,E/WifiConfigStore( 2402): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/knox    ( 5016): KNOXAgentService : onCreate()
,D/knox    ( 5016): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 5016): KNOXAgentService. startJobThread() start
,D/knox    ( 5016): KNOXAgentService. JobThread()
D/knox    ( 5016): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5016): KNOXAgentService. startJobThread() wait
,D/knox    ( 5016): KNOXAgentService : onDestroy().
,D/knox    ( 5016): ModuleBase.cancelAllAlarmManageModule()
,D/WifiNative( 2402): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 6848): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6848): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6848): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 6848): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6848): First Scan Start
,I/wpa_supplicant( 6848): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 5354): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine( 2402): Set the Nv default ccode
,D/WifiStateMachine( 2402): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine( 2402): HS20_DISABLED_COMPLETEnormal
D/WifiP2pService( 2402): P2pDisabledState{ what=131203 }
,D/CommandListener( 1916): Setting iface cfg
,D/CommandListener( 1916): Trying to bring up p2p0
,I/wpa_supplicant( 6848): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,D/WifiMonitor( 2402): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 2402): P2pEnablingState
D/WifiP2pService( 2402): P2pEnablingState{ what=147457 }
D/WifiP2pService( 2402): P2p socket connection successful
D/WifiP2pService( 2402): P2pEnabledState
,E/WifiStateMachine( 2402): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/QuickConnect[1.1][2] ( 5076): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
D/WifiP2pService( 2402): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController( 2402): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 2402): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2402): disconnect
D/WifiDisplayController( 2402): updateConnection
D/WifiDisplayController( 2402): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 2402): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 5076): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiDisplayAdapter( 2402): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/WifiP2pStateTracker( 2402): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/QuickConnect[1.1][2] ( 5076): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/WifiDisplayController( 2402): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/QuickConnect[1.1][2] ( 5076): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/NearbySettings( 5577): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 5577): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 5577): MountReceiver.onReceive - Create mPrefHandler
,D/AmoledAdjustTimer( 2402): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/NearbySettings( 5577): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 5577): DMSUtil.isNetworkConnected - flag-null, state-null
D/WifiP2pService( 2402): DeviceAddress: 02:e0:6d
,D/WifiDisplayController( 2402): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
D/WifiDisplayController( 2402):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiDisplayController( 2402):  primary type: 10-0050F204-5
D/WifiDisplayController( 2402):  secondary type: null
D/WifiDisplayController( 2402):  wps: 0
D/WifiDisplayController( 2402):  grpcapab: 0
D/WifiDisplayController( 2402):  devcapab: 0
D/WifiDisplayController( 2402):  status: 3
D/WifiDisplayController( 2402):  wfdInfo: null
D/WifiDisplayController( 2402):  groupownerAddress: null
D/WifiDisplayController( 2402):  GOdeviceName: null
D/WifiDisplayController( 2402):  interfaceAddress: 
D/WifiDisplayController( 2402):  SConnectInfo : null
I/NearbySettings( 5577): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 5577): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5577): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5577): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5577): MountReceiver.mPrefHandler - 7002
D/PackageManager( 2402): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/WifiP2pService( 2402): sending p2p persistent groups changed broadcast
,D/FileShare-Server( 5957): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/QuickConnect[1.1][2] ( 5076): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService( 2402): InactiveState
D/WifiP2pService( 2402): InactiveState{ what=139287 }
D/WifiP2pService( 2402): P2pEnabledState{ what=139287 }
,D/WifiP2pService( 2402): DefaultState{ what=139287 }
D/FileShare-Server( 5957): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/wpa_supplicant( 6848): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 6848): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 6848): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6848): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 6848): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2402): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 6848): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,D/Tethering( 2402): interfaceStatusChanged wlan0, true
,E/WifiStateMachine( 2402): Error! unhandled message{ when=-4ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 6848): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,D/Tethering( 2402): interfaceLinkStateChanged wlan0, true
D/Tethering( 2402): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6848): Associated with C0.AA.48
D/Tethering( 2402): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2402): interfaceStatusChanged wlan0, true
,D/Tethering( 2402): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2402): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6848): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 6848): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 6848): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 6848): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6848): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2402): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2402): interfaceStatusChanged wlan0, true
,D/WifiNative( 2402): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6908): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6908):  
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6908): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6908):  
I/SELinux ( 6908):  
,I/SELinux ( 6908): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6908): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6908): >>>>> Normal User
,E/dalvikvm( 6908): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 6908): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6908): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6908): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6908): Added TimaKesytore provider
,D/WifiP2pService( 2402): InactiveState{ what=143375 }
,D/WifiP2pService( 2402): P2pEnabledState{ what=143375 }
,D/dalvikvm( 6908): GC_CONCURRENT freed 2995K, 32% free 9576K/13968K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 6908): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/System.out( 6908): Inside WakeupProvider
,I/System.out( 6908): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 6908): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 6908): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 6908): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 6922): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6922): bssid match
,D/NearbySettings( 5577): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5577): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5577): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 5577): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5577): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5577): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5577): MountReceiver.mPrefHandler - 7002
,I/ActivityManager( 2402): Killing 5785:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
D/DialogFlow( 6908): initQueue()
,I/HarmonyEASService( 2402): Updating for all 1
,D/btif_config_util( 5102): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiP2pService( 2402): InactiveState{ what=143375 }
,D/WifiP2pService( 2402): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2402): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/PackageManager( 2402): [MSG] SEND_PENDING_BROADCAST
D/PackageManager( 2402): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.sec.enterprise.knox.cloudmdm.smdms.core.CoreReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10171, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@43069218, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2402): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2402): CaptivePortalCheckState enter
,I/InputReader( 2402): Reconfiguring input devices.  changes=0x00000010
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/PackageManager( 2402):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2402):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2402):   Scheme: "sms"
I/PackageManager( 2402): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2402):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2402):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2402):   Scheme: "smsto"
I/PackageManager( 2402): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RegisteredServicesCache( 2756): empty dynamic service
I/PackageManager( 2402):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2402):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2402):   Scheme: "mms"
I/PackageManager( 2402): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2402):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2402):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2402):   Scheme: "mmsto"
,I/PackageManager( 2402): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/NearbySettings( 5577): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 5577): MountReceiver.onReceive - Keep current state
,I/PackageManager( 2402):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2402):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2402):   Scheme: "sms"
I/PackageManager( 2402): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/jxcore-log( 6609): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6609): 
,I/PackageManager( 2402):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2402):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2402):   Scheme: "smsto"
I/PackageManager( 2402): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2402):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2402):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2402):   Scheme: "mms"
I/PackageManager( 2402): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2402):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2402):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2402):   Scheme: "mmsto"
I/PackageManager( 2402): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Icing.InternalIcingCorporaProvider( 5943): Updating corpora: A: com.sec.enterprise.knox.cloudmdm.smdms, C: MAYBE
,D/FileShare-Server( 5957): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BezelQuickConnect( 5088): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 5088): BezelBroadcastReceiver - packageName : com.sec.enterprise.knox.cloudmdm.smdms
,D/PackageBroadcastService( 3310): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NearbySettings( 5577): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5577): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5577): DMSUtil.isNetworkConnected - WIFI: VERIFYING_POOR_LINK
I/NearbySettings( 5577): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5577): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5577): MountReceiver.onReceive - Keep current state
,I/WifiTrafficPoller( 2402): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2402): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2402): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2402): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/WifiTrafficPoller( 2402): evaluateTrafficStatsPolling
D/ConnectivityService( 2402): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2402): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2402): net.tcp.delack.wifi not found in system properties. Using defaults
,I/Icing.InternalIcingCorporaProvider( 5943): UpdateCorporaTask done [took 292 ms] updated apps [took 292 ms] 
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService( 2402): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2402): updateIfacesLocked()
,D/NtpTrustedTime( 2402): forceRefresh() from cache miss
V/NetworkStats( 2402): performPollLocked(flags=0x1)
,V/NetworkStats( 2402): performPollLocked() took 17ms
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NearbySettings( 5577): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5577): MountReceiver.onReceive - Keep current state
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PowerManagerService( 2402): [PWL] Off : 105s ago
I/PowerManagerService( 2402): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2402): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2402): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=3310, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=148)
I/GAV2    ( 6828): Thread[GAThread,5,main]: connecting to Analytics service
W/ContextImpl( 6828): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:529 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/GAV2    ( 6828): Thread[GAThread,5,main]: connect: bindService returned true for Intent { act=com.google.android.gms.analytics.service.START (has extras) }
D/GAV2    ( 6828): Thread[main,5,main]: service connected, binder: android.os.BinderProxy@42473118
D/GAV2    ( 6828): Thread[main,5,main]: bound to service
I/GAV2    ( 6828): Thread[main,5,main]: Connected to service
W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NtpTrustedTime( 2402): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1450226480583 mCachedNtpElapsedRealtime : 174193 mCachedNtpCertainty : 9
,D/NtpTrustedTime( 2402): currentTimeMillis() cache hit
,I/GAV2    ( 6828): Thread[GAThread,5,main]: No campaign data found.
,D/PowerManagerService( 2402): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2402
D/NtpTrustedTime( 2402): currentTimeMillis() cache hit
D/NtpTrustedTime( 2402): currentTimeMillis() cache hit
D/NtpTrustedTime( 2402): currentTimeMillis() cache hit
D/NtpTrustedTime( 2402): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2402): currentTimeMillis() cache hit
,W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/NetworkStats( 2402): advisePersistThreshold() given 9223372036854775, clamped to 2097152
W/Resources( 2402): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/GAV2    ( 6828): Thread[GAThread,5,main]: putHit called
,I/GAV2    ( 6828): Thread[GAThread,5,main]: Sending hit to service
,W/ApplicationsProvider( 2948): Could not fetch usage stats
W/ApplicationsProvider( 2948): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2948): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2948): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2948): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2948): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2948): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2948): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2948): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2948): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2948): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2948): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2948): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Tethering( 2402): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2402): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2402): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/NtpTrustedTime( 2402): currentTimeMillis() cache hit
D/        ( 2402): Setting time of day to sec=1450226481
,D/        ( 2402): Trying to open a file
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
D/        ( 2402): File Open Success
D/        ( 2402): File Close Success
,I/        ( 2402): DRM_TIME_PATH CHMOD 660 for resetState done 
V/AlarmManager( 2402): waitForAlarm result :65536
,I/DBG_DM  ( 4655): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/PCWCLIENTTRACE_PushUtil( 6437): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6437): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6437): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6437): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,I/DBG_DM  ( 4655): [3.19.140541][Line:609][onReceive] ----------- XEVENT_DM_INIT WIFI ok
D/StatusBar-DoNotDistrub( 2581): Received intent with android.intent.action.TIME_SET action
D/StatusBar-DoNotDistrub( 2581): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/NotificationMgr( 2752): updateNotificationsAtStartup()...
,D/NotificationMgr( 2752): - start call log query...
,I/DBG_DM  ( 4655): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
,W/Settings( 2402): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DBG_DM  ( 4655): [3.19.140541][Line:432][xdmInitAdpWaitSystemRootingCheck] Check completed.
,I/DBG_DM  ( 4655): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/AudioService( 2402): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 2581): sendBroadcast android.intent.action.DORMANT_MODE_OFF
D/StatusBar-DoNotDistrub( 2581): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService( 2402): manageDisableList what=0x0 pkg=com.android.systemui
,E/Parcel  ( 2402): nm 23
I/PrGenericPlugin( 1924): [A] ENTER onAcquireDrmInfo : 0x4f5
,I/PrGenericPlugin( 1924): [A] LEAVE onAcquireDrmInfo : 0x4f5
,I/DrmEventService( 2402):  no response from SecureClock 
,I/SELinux ( 7010): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7010):  
,I/SensorManagerA( 2402): getReportingMode :: sensor.mType = 5
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
D/STATUSBAR-NotificationService( 2402): received android.intent.action.DORMANT_MODE_OFF
D/LightsService( 2402): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2402) 
D/LightsService( 2402): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,I/DBG_DM  ( 4655): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,D/Sensors ( 2402): LightSensor setDelay = 200000000
,D/Sensors ( 2402): LightSensor setSensorDelay = 200000000
D/Sensors ( 2402): Light sensor flush: not enabled 0
D/Sensors ( 2402): LightSensor enable = 1
,D/Sensors ( 2402): LightSensor enableSensor = 1
I/DBG_DM  ( 4655): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
,D/SensorManager( 2402): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/NotificationMgr( 2752): call log query complete.
D/NotificationMgr( 2752): call log cursor count : 0
,D/NotificationMgr( 2752): call log cursor count2 : null
,I/SQLiteSecureOpenHelper( 4125): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4125): getDatabaseLocked(b,b,pwd)...
,I/SELinux ( 7010): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7010):  
I/SELinux ( 7010):  
,I/SELinux ( 7010): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7010): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7010): >>>>> Normal User
,E/dalvikvm( 7010): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7010): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7010): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7010): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7010): Added TimaKesytore provider
,I/dalvikvm( 4655): Total arena pages for JIT: 11
,I/dalvikvm( 4655): Total arena pages for JIT: 12
I/dalvikvm( 4655): Total arena pages for JIT: 13
I/dalvikvm( 4655): Total arena pages for JIT: 14
I/dalvikvm( 4655): Total arena pages for JIT: 15
I/dalvikvm( 4655): Total arena pages for JIT: 16
,I/dalvikvm( 4655): Total arena pages for JIT: 17
,I/DBG_DM  ( 4655): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4655): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4655): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/DBG_DM  ( 4655): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,I/DBG_DM  ( 4655): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,E/DBG_DM  ( 4655): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
,D/LightsService( 2402): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2402): LightSensor enable = 0
D/Sensors ( 2402): LightSensor enableSensor = 0
,D/SensorManager( 2402): unregisterListener ::   
D/LightsService( 2402): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/SQLiteSecureOpenHelper( 4125): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4125): getDatabaseLocked(b,b,pwd)...
I/dalvikvm( 2734): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2734): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2734): Using platform SSLCertificateSocketFactory
,I/DBG_DM  ( 4655): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 4655): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4655): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
I/DBG_DM  ( 4655): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,I/DBG_DM  ( 4655): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4655): [3.19.140541][Line:369][handleMessage] event ->214
D/dalvikvm( 7010): GC_CONCURRENT freed 2999K, 32% free 9570K/13968K, paused 3ms+8ms, total 68ms
,D/dalvikvm( 7010): WAIT_FOR_CONCURRENT_GC blocked 62ms
,I/DBG_DM  ( 4655): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,I/DBG_DM  ( 4655): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4655): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/DBG_DM  ( 4655): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
W/ContextImpl( 4655): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,I/DBG_DM  ( 4655): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,I/DBG_DM  ( 4655): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4655): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,E/DBG_DM  ( 4655): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@423c2ae0
,I/Icing   ( 3310): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/dalvikvm( 4655): Total arena pages for JIT: 18
,I/DBG_DM  ( 4655): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/Icing   ( 3310): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,I/DBG_DM  ( 4655): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/SELinux ( 7037): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7037):  
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2402): sendNotification(1) - 4
,I/SELinux ( 7037): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7037):  
I/SELinux ( 7037):  
,I/SELinux ( 7037): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7037): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 7037): >>>>> Normal User
,E/dalvikvm( 7037): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 7037): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 7037): in addTimaSignatureService
,D/dalvikvm( 2402): GC_CONCURRENT freed 3566K, 56% free 24850K/55380K, paused 8ms+15ms, total 213ms
,D/dalvikvm( 2402): WAIT_FOR_CONCURRENT_GC blocked 89ms
D/dalvikvm( 2402): WAIT_FOR_CONCURRENT_GC blocked 48ms
D/dalvikvm( 2402): WAIT_FOR_CONCURRENT_GC blocked 48ms
D/dalvikvm( 2402): WAIT_FOR_CONCURRENT_GC blocked 89ms
D/dalvikvm( 2402): WAIT_FOR_CONCURRENT_GC blocked 88ms
,D/dalvikvm( 2402): WAIT_FOR_CONCURRENT_GC blocked 205ms
,D/TimaKeyStoreProvider( 7037): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7037): Added TimaKesytore provider
,I/SELinux ( 7050): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7050):  
,I/SELinux ( 7050): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7050):  
I/SELinux ( 7050):  
,I/SELinux ( 7050): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7050): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7050): >>>>> Normal User
,E/dalvikvm( 7050): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7050): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/libgps  ( 2402): agps_ril_update_network_state: Waiting for IPC connection...
,D/TimaKeyStoreProvider( 7050): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7050): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7050): Added TimaKesytore provider
,D/dalvikvm( 7037): GC_CONCURRENT freed 2996K, 32% free 9572K/13964K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 7037): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 7050): GC_CONCURRENT freed 3000K, 32% free 9565K/13960K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7050): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 2402): GC_EXPLICIT freed 306K, 56% free 24614K/55380K, paused 14ms+21ms, total 326ms
,D/dalvikvm( 2402): WAIT_FOR_CONCURRENT_GC blocked 400ms
,W/ResourceType( 2581): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
,W/ResourceType( 2581): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2581): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422c4268
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/SELinux ( 7065): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7065):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 14% free 9502K/10944K, paused 4ms+5ms, total 51ms
,I/dalvikvm( 2734): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 2734): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x003d
,I/SELinux ( 7065): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7065):  
I/SELinux ( 7065):  
,I/SELinux ( 7065): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7065): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7065): >>>>> Normal User
,E/dalvikvm( 7065): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7065): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9502K/10944K, paused 4ms+5ms, total 41ms
,D/TimaKeyStoreProvider( 7065): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7065): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7065): Added TimaKesytore provider
,I/System.out( 2734): Thread-119(HTTPLog):isShipBuild true
,I/System.out( 2734): Thread-119(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9502K/10944K, paused 3ms+4ms, total 38ms
,D/dalvikvm( 7065): GC_CONCURRENT freed 3004K, 32% free 9565K/13968K, paused 3ms+1ms, total 42ms
,D/dalvikvm( 7065): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/KLMS-2.3.201 : ( 7065): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7065): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450226482640
,I/KLMS-2.3.201 : ( 7065): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/ActivityManager( 2402): Killing 5802:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7081): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7081):  
,I/System.out( 7050): Thread-604(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/LocationTagReadyService( 3466): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,I/System.out( 7050): Thread-604(ApacheHTTPLog):isShipBuild true
,I/System.out( 7050): Thread-604(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux ( 7085): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7085):  
I/SELinux ( 7081): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7081):  
I/SELinux ( 7081):  
,I/SELinux ( 7081): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7081): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7081): >>>>> Normal User
E/dalvikvm( 7081): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
I/GallerySearchProvider( 3593): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
E/SELinux ( 7081): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7081): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7081): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7081): Added TimaKesytore provider
I/SELinux ( 7085): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7085):  
I/SELinux ( 7085):  
,I/SELinux ( 7085): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7085): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7085): >>>>> Normal User
,E/dalvikvm( 7085): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7085): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4352, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2402): stay LED for fully charged
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
D/TimaKeyStoreProvider( 7085): in addTimaSignatureService
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/TimaKeyStoreProvider( 7085): Cannot add TimaSignature Service, License check Failed
V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5102): Disconnected process message: 10
D/ActivityThread( 7085): Added TimaKesytore provider
,I/SELinux ( 7107): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7107):  
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 7081): GC_CONCURRENT freed 3007K, 32% free 9565K/13968K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 7081): WAIT_FOR_CONCURRENT_GC blocked 14ms
I/SELinux ( 7107): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7107):  
I/SELinux ( 7107):  
,I/SELinux ( 7107): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7107): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7107): >>>>> Normal User
,E/dalvikvm( 7107): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7107): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/System.out( 7050): AsyncTask #1 calls detatch()
,D/SO_AGENT( 7081): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7081): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/TimaKeyStoreProvider( 7107): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7107): Cannot add TimaSignature Service, License check Failed
,W/System.err( 7050): com.sec.android.fota.osp.http.RestClientException
,D/ActivityThread( 7107): Added TimaKesytore provider
W/System.err( 7050): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,W/System.err( 7050): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7050): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7050): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7050): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7050): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7050): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7050): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7050): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7050): Caused by: java.lang.NullPointerException
,W/System.err( 7050): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7050): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7050): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7050): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7050): 	... 8 more
,D/dalvikvm( 7085): GC_CONCURRENT freed 2994K, 32% free 9573K/13964K, paused 4ms+2ms, total 40ms
,D/dalvikvm( 7085): WAIT_FOR_CONCURRENT_GC blocked 36ms
,I/SA      ( 6642): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,D/libgps  ( 2402): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2402): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2402): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2402): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 6545): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x422ad2f8, skipping init
,D/dalvikvm( 7107): GC_CONCURRENT freed 2996K, 32% free 9573K/13968K, paused 10ms+2ms, total 35ms
,D/dalvikvm( 7107): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/SA      ( 6642): [BDLM] already registered in spp
,I/SecureStorage( 6545): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Credentials: uid 1000, gid 1000, pid 6545
,I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
,V/KVNProvider( 7107): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7107): getFindoCursor query string : 
,I/SA      ( 6642): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6642): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,V/KVNProvider( 7107): getTagSearchCursor() tagSearchCursor count : 0
I/ActivityManager( 2402): Killing 5836:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/ActivityManager( 2402): Killing 5886:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/dalvikvm( 7050): GC_CONCURRENT freed 2673K, 30% free 9954K/14028K, paused 38ms+6ms, total 128ms
,D/dalvikvm( 7050): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/SA      ( 6642): [SLFUCHKMGR] constructor called
,I/SA      ( 6642): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6642): [OR] == isSIMCardReady false ==
,I/SA      ( 6642): [SCU] == networkStateCheck == true
I/SA      ( 6642): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6642): isChinaCountryCode : false
,I/SA      ( 6642): [OR] == networkStateCheck true ==
,I/SA      ( 6642): [OR] GetMyCountryZoneTask
,I/SA      ( 6642): [OR] onReceive END
,I/SA      ( 6642): [SRS] prepareGetMyCountryZone
I/ActivityManager( 2402): Killing 5538:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SA      ( 6642): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6642): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SA      ( 6642): [TPMU] GetMccFromDB : null
,I/SA      ( 6642): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6642): [TPM] isNoProxy(default) : true
,I/SA      ( 6642): [RC New] Execute method=[GET] start
,I/SELinux ( 7128): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7128):  
,I/SELinux ( 7128): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7128):  
I/SELinux ( 7128):  
,I/SELinux ( 7128): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7128): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7128): >>>>> Normal User
,E/dalvikvm( 7128): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7128): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7128): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7128): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7128): Added TimaKesytore provider
,D/dalvikvm( 7128): GC_CONCURRENT freed 2995K, 32% free 9570K/13964K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 7128): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/System.out( 7050): AsyncTask #2 calls detatch()
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/sCloudBackupApp( 7128): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7128): Other Intent
I/ActivityManager( 2402): Killing 5771:com.sec.phone/1001 (adj 15): empty #43
W/BackupManagerService( 2402): dataChanged but no participant pkg='com.android.providers.settings' uid=10011
,I/SELinux ( 7142): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7142):  
,I/System.out( 6642): Thread-563(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/SELinux ( 7142): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7142):  
I/SELinux ( 7142):  
,I/SELinux ( 7142): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7142): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7142): >>>>> Normal User
,E/dalvikvm( 7142): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,I/ActivityManager( 2402): Killing 5643:com.google.android.music:main/u0a125 (adj 15): empty #43
E/SELinux ( 7142): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 2734): GC_CONCURRENT freed 1659K, 21% free 11766K/14892K, paused 4ms+6ms, total 72ms
,W/WifiP2pStateTracker( 2402): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/TimaKeyStoreProvider( 7142): in addTimaSignatureService
,D/ConnectivityService( 2402): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2402):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2402): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2402): updateSourceRoutes : no source routing conditions
D/TimaKeyStoreProvider( 7142): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7142): Added TimaKesytore provider
I/System.out( 6642): Thread-563(ApacheHTTPLog):isShipBuild true
I/System.out( 6642): Thread-563(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7142): GC_CONCURRENT freed 3006K, 32% free 9563K/13964K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 7142): WAIT_FOR_CONCURRENT_GC blocked 20ms
,E/WifiStateMachine( 2402): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/PhenotypeConfigurator( 2734): Server returned 404
,D/com.samsung.app( 7142): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7142): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7142): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7142): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7142): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7142): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5299): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7142): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5299): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7142): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5299): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7142): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7142): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2402): Killing 5806:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7155): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7155):  
,I/SELinux ( 7155): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7155):  
I/SELinux ( 7155):  
,I/SELinux ( 7155): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7155): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7155): >>>>> Normal User
,E/dalvikvm( 7155): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10110 ]
,E/SELinux ( 7155): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7155): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7155): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7155): Added TimaKesytore provider
,D/dalvikvm( 7155): GC_CONCURRENT freed 3010K, 32% free 9559K/13968K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7155): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/HeadlinesChannelApplication( 7155): [onCreate]
,D/Headlines( 7155): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7155): getCountryCode(): countryCode = PL
,D/Headlines( 7155): Breath.onCreate
,D/HeadlinesCardManager( 7155): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 7155): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 7155): CardProvider Library : 13
,I/SELinux ( 7167): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7167):  
,D/MagazineService::CardProviderContentProvider( 6706): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 6706): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 7155): registerCardProvider: provider already exists.
I/SELinux ( 7167): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7167):  
I/SELinux ( 7167):  
,I/SELinux ( 7167): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7167): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7167): >>>>> Normal User
,E/dalvikvm( 7167): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
I/Headlines( 7155): HeadlinesDataCenter ctor
I/Headlines( 7155): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 7155): getCountryCode(): countryCode = PL
,E/SELinux ( 7167): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/HeadlinesCardManager( 7155): HeadlinesCardManager : constructor welcome :YES
,D/TimaKeyStoreProvider( 7167): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7167): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7167): Added TimaKesytore provider
,D/Headlines( 7155): Breath timer started. interval : 30000
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
,D/Headlines( 7155): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 7155): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 7155): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 7155): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 7155): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7155): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7155): requestUpdateNewsWelcomeCard !!! no welcome card
D/PowerManagerService( 2402): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2402) eventTime = 177646
D/PowerManagerService( 2402): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2402 (0x0)
D/PowerManagerService( 2402): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2402, ws=WorkSource{1000}) (elapsedTime=3452)
,I/ActivityManager( 2402): Killing 5840:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=4, Uoast
,D/libgps  ( 2402): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2402): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2402): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/PowerManagerService( 2402): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2402
,D/dalvikvm( 7167): GC_CONCURRENT freed 2996K, 32% free 9575K/13968K, paused 3ms+4ms, total 29ms
,D/dalvikvm( 7167): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/dalvikvm( 3310): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 3310): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3310): VFY: replacing opcode 0x6e at 0x003d
,I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1965): [INFO]: SPID(0x00000004)PID: 6545, TID: 6582
,E/ActivityThread( 3310): Failed to find provider info for com.android.contacts.metadata
,D/DelayedSyncController( 7037): Delaying sync.
,D/NtpTrustedTime( 2402): getCachedNtpTime() cache hit
,V/WebViewChromium( 7167): Binding Chromium to the background looper Looper (main, tid 1) {422b0148}
,I/chromium( 7167): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7167): Initializing chromium process, renderers=0
,D/dalvikvm( 2851): GC_EXPLICIT freed 1706K, 23% free 10821K/13992K, paused 10ms+17ms, total 113ms
,W/chromium( 7167): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/SecureStorage( 6545): [INFO]: SPID(0x00000000)Processing data has been completed
,D/libEGL  ( 7167): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7167): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7167): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7167): Mali API Version : 401
,I/Mali    ( 7167): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,E/Auth.Api.Credentials( 3310): [CredentialSyncAdapter] Unknown sync event.
,D/SyncManager( 2402): failed sync operation 
,D/SyncManager( 2402): not retrying sync operation because the error is a hard error: 
,W/GAV2    ( 7167): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,I/ActivityManager( 2402): Killing 5354:com.google.android.talk/u0a109 (adj 15): empty #43
,W/ContextImpl( 7167): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7167): Starting up...
,I/ImageResourceManager( 5726): ImageResourceManager: uninitalized
,D/dalvikvm( 5726): GC_FOR_ALLOC freed 1066K, 30% free 9904K/13968K, paused 41ms, total 41ms
,I/dalvikvm-heap( 5726): Grow heap (frag case) to 13.063MB for 2129936-byte allocation
,D/dalvikvm( 5726): GC_FOR_ALLOC freed 6K, 26% free 11978K/16052K, paused 21ms, total 21ms
,I/iu.Environment( 5726): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/dalvikvm( 6545): Total arena pages for JIT: 11
I/dalvikvm( 6545): Total arena pages for JIT: 12
,I/dalvikvm( 6545): Total arena pages for JIT: 13
I/dalvikvm( 6545): Total arena pages for JIT: 14
,I/dalvikvm( 6545): Total arena pages for JIT: 15
I/dalvikvm( 6545): Total arena pages for JIT: 16
,I/dalvikvm( 6545): Total arena pages for JIT: 17
,D/dalvikvm( 5726): GC_CONCURRENT freed 28K, 26% free 11958K/16052K, paused 4ms+9ms, total 36ms
,V/AlarmManager( 2402): waitForAlarm result :4
,I/ActivityManager( 2402): Killing 5860:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
D/QuickConnect[1.1][2] ( 5076): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5076): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 5076): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b9ed8
,I/SELinux ( 7223): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7223):  
,D/dalvikvm( 5726): GC_FOR_ALLOC freed 13K, 26% free 11947K/16052K, paused 44ms, total 44ms
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/iu.SyncManager( 5726): SYNC; picasa accounts
,I/iu.UploadsManager( 5726): num queued entries: 0
I/SELinux ( 7223): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7223):  
I/SELinux ( 7223):  
,I/SELinux ( 7223): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/iu.UploadsManager( 5726): num updated entries: 0
,E/SELinux ( 7223): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7223): >>>>> Normal User
,E/dalvikvm( 7223): >>>>> com.android.email [ userId:0 | appId:10157 ]
E/SELinux ( 7223): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/iu.SyncManager( 5726): NEXT; no task
,D/DelayedSyncController( 7037): Delaying sync.
,D/PicasaService( 3593): start picasa sync
,D/TimaKeyStoreProvider( 7223): in addTimaSignatureService
,D/PicasaService( 3593): end picasa sync
,D/TimaKeyStoreProvider( 7223): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7223): Added TimaKesytore provider
,D/dalvikvm( 3885): GC_CONCURRENT freed 1545K, 23% free 10756K/13940K, paused 10ms+5ms, total 59ms
,D/dalvikvm( 3885): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/dalvikvm( 7223): GC_CONCURRENT freed 2986K, 32% free 9588K/13968K, paused 5ms+1ms, total 30ms
,D/dalvikvm( 7223): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 5726): GC_FOR_ALLOC freed 66K, 21% free 16094K/20220K, paused 17ms, total 17ms
,D/RCPManagerService( 2402): exchangeData() failure , invalid userId
,D/RCPManagerService( 2402): exchangeData() failure , invalid userId
,D/RCPManagerService( 2402): exchangeData() failure , invalid userId
,D/RCPManagerService( 2402): exchangeData() failure , invalid userId
,D/RCPManagerService( 2402): exchangeData() failure , invalid userId
,D/RCPManagerService( 2402): exchangeData() failure , invalid userId
,I/SELinux ( 7248): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7248):  
,I/SELinux ( 7252): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7252):  
I/ActivityManager( 2402): Killing 6384:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/SELinux ( 7248): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7248):  
I/SELinux ( 7248):  
,I/SELinux ( 7248): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7248): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7248): >>>>> Normal User
,E/dalvikvm( 7248): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7248): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7252): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7252):  
I/SELinux ( 7252):  
,I/SELinux ( 7252): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7252): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7252): >>>>> Normal User
,E/dalvikvm( 7252): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7252): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7248): in addTimaSignatureService
,W/ActivityManager( 2402): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/TimaKeyStoreProvider( 7248): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7248): Added TimaKesytore provider
,D/dalvikvm( 2402): GC_EXPLICIT freed 2321K, 56% free 24802K/55380K, paused 9ms+44ms, total 342ms
,I/ActivityManager( 2402): Killing 5963:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7252): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7252): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7252): Added TimaKesytore provider
,D/dalvikvm( 7248): GC_CONCURRENT freed 3007K, 32% free 9554K/13960K, paused 4ms+2ms, total 32ms
,D/dalvikvm( 7248): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/BadgeProvider( 7248): onCreate
,D/BadgeProvider( 7248): DatabaseHelper
,D/dalvikvm( 7252): GC_CONCURRENT freed 3011K, 32% free 9555K/13960K, paused 2ms+5ms, total 34ms
,D/dalvikvm( 7252): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/BadgeProvider( 7248): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2769): reloadBadges entered.
D/BadgeProvider( 7248): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7248): sendNotify, [notify] : null
D/BadgeProvider( 7248): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7248): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7248): update, [UpdateCount] : 1
,I/SELinux ( 7273): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7273):  
I/ActivityManager( 2402): Killing 6410:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 14% free 9502K/10944K, paused 2ms+4ms, total 37ms
I/SELinux ( 7273): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7273):  
I/SELinux ( 7273):  
I/SELinux ( 7273): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7273): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7273): >>>>> Normal User
E/dalvikvm( 7273): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7273): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
I/SA      ( 6642): [RC New] [v2liruge] api execute + 2471,
,I/SA      ( 6642): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK,
,I/System.out( 6642): AsyncTask #1 calls detatch(),
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9502K/10944K, paused 2ms+3ms, total 27ms,
,D/TimaKeyStoreProvider( 7273): in addTimaSignatureService,
,I/SA      ( 6642): [TPMU] getNetworkMcc : ,
,D/TimaKeyStoreProvider( 7273): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7273): Added TimaKesytore provider,
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9502K/10944K, paused 2ms+3ms, total 26ms,
,I/SA      ( 6642): [SCU] saveMccToPreferece Start,
I/SA      ( 6642): [SCU] RegionMCC : 260
,I/SA      ( 6642): [SSP] query invoked,
,I/SA      ( 6642): [TPMU] GetMccFromDB : null,
,I/SA      ( 6642): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6642): [SCU] saveMccToPreferece End,
,I/SA      ( 6642): [RC New] executeRequest [v2liruge] end. 2537
,I/SA      ( 6642): [RC New] Execute end
I/SA      ( 6642): [OR] GetMyCountryZoneTask mcc = 260,
,I/SA      ( 6642): [OR] GetMyCountryZoneTask Success
,D/dalvikvm( 7273): GC_CONCURRENT freed 2980K, 32% free 9586K/13964K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 7273): WAIT_FOR_CONCURRENT_GC blocked 19ms,
,I/dalvikvm( 7273): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N,
W/dalvikvm( 7273): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x0008,
D/SSRMv2:SIOP( 2402): SIOP:: AP = 360, Delta = 0
,E/dalvikvm( 7273): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a,
W/dalvikvm( 7273): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7273): VFY: replacing opcode 0x22 at 0x0000,
,E/dalvikvm( 7273): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a,
W/dalvikvm( 7273): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7273): VFY: replacing opcode 0x22 at 0x0037
,I/System.out( 3310): Thread-187(HTTPLog):isShipBuild true
,I/System.out( 3310): Thread-187(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/dalvikvm( 7273): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7273): Link of class 'Ldqp;' failed
,W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7273): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7273): Link of class 'Ldqp;' failed
I/dalvikvm( 7273): Could not find method dqp.q, referenced from method g.a
,W/dalvikvm( 7273): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x0000
,D/Finsky  ( 3885): [220] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3885): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/dalvikvm( 7273): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7273): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7273): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7273): Link of class 'Ldqp;' failed
,W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7273): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7273): Link of class 'Ldqp;' failed
I/dalvikvm( 7273): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7273): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7273): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7273): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7273): Link of class 'Ldqp;' failed
W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7273): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7273): Link of class 'Ldqp;' failed
I/dalvikvm( 7273): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 7273): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7273): Link of class 'Lax;' failed
E/dalvikvm( 7273): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7273): VFY: replacing opcode 0x22 at 0x0006
,W/dalvikvm( 7273): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7273): Link of class 'Laz;' failed
E/dalvikvm( 7273): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7273): VFY: replacing opcode 0x22 at 0x002c
,I/dalvikvm( 7273): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x0008
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6437): mConnectivityHandler : connected
I/dalvikvm( 7273): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
,W/dalvikvm( 7273): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x000c
,I/dalvikvm( 7273): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x0006
,W/PCWCLIENTTRACE_AccountUtil( 6437): [hasSamungAccount] - No Samsung Account
,I/dalvikvm( 7273): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7273): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
,D/dalvikvm( 7273): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7273): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
,D/dalvikvm( 7273): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7273): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7273): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7273): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm( 7273): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7273): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7273): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 7273): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7273): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x0009
,V/AlarmManager( 2402): waitForAlarm result :4
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,W/dalvikvm( 7273): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 7273): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7273): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7273): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7273): VFY: replacing opcode 0x1c at 0x0002
,E/dalvikvm( 7273): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7273): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7273): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 7273): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7273): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7273): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7273): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7273): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7273): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7273): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
D/dalvikvm( 7273): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 7273): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7273): Link of class 'Lax;' failed
,D/dalvikvm( 7273): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7273): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7273): Link of class 'Laz;' failed
,D/dalvikvm( 7273): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7273): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7273): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6437): failed to loading secure library
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6437): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6437): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6437): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6437): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6437): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6437): [ensureRegistration] - No Samsung account
,D/dalvikvm( 7273): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x422ada30
,D/dalvikvm( 7273): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x422ada30
,I/dalvikvm( 7273): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7273): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7273): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7273): MmsConfig.loadMmsSettings
I/Babel_SMS( 7273): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7273): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7273): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7273): MmsConfig.loadFromResources
,E/Babel_SMS( 7273): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7273): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/dalvikvm( 7273): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7273): Link of class 'Lfzc;' failed
E/dalvikvm( 7273): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7273): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7273): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,I/dalvikvm( 7273): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7273): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7273): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 7273): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7273): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x0033
,I/dalvikvm( 7273): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7273): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7273): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7273): Link of class 'Lfzc;' failed
,D/dalvikvm( 7273): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,E/SensorService( 2402): Permission Denial : SEC Private Sensor 
,E/SensorService( 2402): Permission Denial : SEC Private Sensor ,
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras),
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo),
,D/dalvikvm( 7273): GC_CONCURRENT freed 1808K, 23% free 10850K/14052K, paused 5ms+4ms, total 41ms,
,D/dalvikvm( 7273): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 7273): WAIT_FOR_CONCURRENT_GC blocked 16ms,
,W/Settings( 7273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/Babel_Crash( 7273): startup - clean
,I/Babel   ( 7273): deleted: false for 0
,I/dalvikvm( 7273): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 7273): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 7273): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7273): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7273): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7273): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7273): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7273): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7273): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7273): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7273): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7273): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/dalvikvm( 7273): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7273): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
D/dalvikvm( 7273): VFY: replacing opcode 0x6e at 0x0074
,D/WaitQueueForNetworkActivate( 6803): notifyNetworkActivated
,I/vclib   ( 7273): onServiceConnected
,W/Babel   ( 7273): Attempted to change video mute state without an active call.
,W/ContextImpl( 6803): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2402): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/AmoledAdjustTimer( 2402): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
,D/dalvikvm( 7273): GC_CONCURRENT freed 817K, 16% free 12079K/14292K, paused 10ms+5ms, total 62ms
,D/dalvikvm( 7273): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 7273): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/System.out( 7273): Thread-650(HTTPLog):isShipBuild true
,I/System.out( 7273): Thread-650(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/hcjo    ( 6803): AutoUpdateManager:IDLE:execute
,D/dalvikvm( 7273): GC_FOR_ALLOC freed 900K, 18% free 12629K/15284K, paused 43ms, total 43ms
,I/dalvikvm( 6803): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 6803): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6803): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6803): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6803): exit::IDLE
,D/InitializeManagerStateMachine( 6803): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6803): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6803): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6803): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6803): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6803): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6803): entry::SUCCESS
,D/hcjo    ( 6803): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6803): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 6803): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6803): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6803): exit::SUCCESS
,D/InitializeManagerStateMachine( 6803): entry::IDLE
,D/dalvikvm( 7273): GC_FOR_ALLOC freed 1854K, 24% free 12988K/16940K, paused 45ms, total 45ms
,I/Babel   ( 7273): connection state changed from UNKNOWN to CONNECTED
,D/dalvikvm( 3310): GC_CONCURRENT freed 2194K, 23% free 12502K/16140K, paused 5ms+9ms, total 66ms
I/ActivityManager( 2402): Killing 6423:com.android.musicfx/u0a24 (adj 15): empty #43
,I/iu.SyncManager( 3310): SYNC; picasa accounts
,D/NetworkLogImpl( 3310): Loaded NetworkSpeedPredictor
,I/iu.Environment( 3310): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3310): num queued entries: 0
,I/iu.UploadsManager( 3310): num updated entries: 0
,I/iu.SyncManager( 3310): NEXT; no task
,E/SPPClientService( 5493): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5493): [SystemStateMoniter] Current Time : 180970
,E/SPPClientService( 5493): [SystemStateMoniter] No Connect : false
,I/SELinux ( 7313): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7313):  
,I/SELinux ( 7313): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7313):  
I/SELinux ( 7313):  
,I/SELinux ( 7313): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7313): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7313): >>>>> Normal User
,E/dalvikvm( 7313): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 7313): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7313): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7313): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7313): Added TimaKesytore provider
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (-2/11)
D/PowerManagerService( 2402): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2402) eventTime = 181155
D/PowerManagerService( 2402): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2402 (0x0)
D/PowerManagerService( 2402): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2402, ws=WorkSource{1000}) (elapsedTime=3455)
,D/dalvikvm( 7313): GC_CONCURRENT freed 2990K, 32% free 9571K/13960K, paused 3ms+2ms, total 32ms
,D/dalvikvm( 7313): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/ActivityManager( 2402): Killing 6449:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/BootCompletedReceiver( 2402): onReceive
,I/KLMS-2.3.201 : ( 7065): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7065): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1450226487844
,I/KLMS-2.3.201 : ( 7065): StateImplV2() : dateTimeChanged() : Wed Dec 16 01:41:27 CET 2015
,I/GCM     ( 2851): GCM config loaded
,D/SO_AGENT( 7081): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 7081): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 6642): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/VacuumService( 2734): Vacuum at: now=1450226488005 tag=VacuumService
,D/Mms/MessagingNotification( 5592): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 5592): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 5592): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 5592): isDefault true
,D/TP/MmsSmsProvider( 2752): match 8:Elapsed time : 23.327 ms
,I/SELinux ( 7337): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7337):  
,D/TP/MmsSmsProvider( 2752): match 200:Elapsed time : 3.437 ms
,I/SELinux ( 7337): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7337):  
I/SELinux ( 7337):  
,I/SELinux ( 7337): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7337): >>>>> Normal User
,E/dalvikvm( 7337): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10064 ]
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7337): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7337): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7337): Added TimaKesytore provider
,D/BadgeProvider( 7248): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/BadgeProvider( 7248): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7248): sendNotify, [notify] : null
D/BadgeProvider( 7248): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7248): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7248): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 5592): setBadgeCount(), count=0
,D/Launcher.Model( 2769): reloadBadges entered.
,D/MessagingNotification( 5592): remove alarm
,D/Mms/MessagingNotification( 5592): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 5592): [end]    nonBlockingUpdateMessageIndicator()
,D/dalvikvm( 7337): GC_CONCURRENT freed 3004K, 32% free 9559K/13964K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 7337): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/com.samsung.app( 7142): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 7142): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 7337): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 7354): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7354):  
I/ActivityManager( 2402): Killing 6483:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/ConnectivityService( 2402): handleInetConditionHoldEnd: net=1, condition=100, published condition=0,
I/SELinux ( 7354): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7354):  
I/SELinux ( 7354):  
I/SELinux ( 7354): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7354): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7354): >>>>> Normal User
,E/dalvikvm( 7354): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ],
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
E/SELinux ( 7354): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7354): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7354): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7354): Added TimaKesytore provider
,D/dalvikvm( 7354): GC_CONCURRENT freed 2998K, 32% free 9567K/13964K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7354): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/SELinux ( 7366): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7366):  
I/ActivityManager( 2402): Killing 6594:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,I/SELinux ( 7366): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7366):  
I/SELinux ( 7366):  
,I/SELinux ( 7366): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7366): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7366): >>>>> Normal User
,E/dalvikvm( 7366): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7366): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7366): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7366): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7366): Added TimaKesytore provider
,D/dalvikvm( 7366): GC_CONCURRENT freed 3001K, 32% free 9565K/13960K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7366): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/elm:14132( 7366): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 7366): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7366): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7366): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14132( 7366): ElmAgentService : onCreate()
,D/elm:14132( 7366): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,I/knox    ( 5016): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 7366): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14132( 7366): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,W/ContextImpl( 5016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/elm:14132( 7366): ModuleBase.resetCalllogAPIAlarm()
D/knox    ( 5016): MainReceiver.listeningToTimeDateChanges( context, intent ).
I/knox    ( 5016): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/knox    ( 5016): KNOXAgentService : onCreate()
D/knox    ( 5016): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 5016): KNOXAgentService. startJobThread() start
D/knox    ( 5016): KNOXAgentService. JobThread()
D/knox    ( 5016): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 5016): KNOXAgentService. startJobThread() wait
,I/SELinux ( 7381): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7381):  
,D/knox    ( 5016): KNOXAgentService : onDestroy().
,D/knox    ( 5016): ModuleBase.cancelAllAlarmManageModule()
,D/elm:14132( 7366): ModuleBase.ModifySetAlarm()
D/elm:14132( 7366): MDMBridge.getInstance()
,D/elm:14132( 7366): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7366): ElmAgentService : onDestroy().
I/ActivityManager( 2402): Killing 4825:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,I/SELinux ( 7381): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7381):  
I/SELinux ( 7381):  
,I/SELinux ( 7381): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7381): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7381): >>>>> Normal User
,E/dalvikvm( 7381): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
,E/SELinux ( 7381): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7381): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7381): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7381): Added TimaKesytore provider
,D/dalvikvm( 7381): GC_CONCURRENT freed 2999K, 32% free 9573K/13968K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7381): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/SELinux ( 7393): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7393):  
I/ActivityManager( 2402): Killing 6676:com.sec.android.service.cm/u0a82 (adj 15): empty #43
,I/GAV2    ( 7167): Thread[GAThread,5,main]: No campaign data found.
,I/SELinux ( 7393): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7393):  
I/SELinux ( 7393):  
,I/SELinux ( 7393): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7393): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7393): >>>>> Normal User
,E/dalvikvm( 7393): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 7393): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7393): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7393): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7393): Added TimaKesytore provider
,D/dalvikvm( 7393): GC_CONCURRENT freed 3019K, 32% free 9548K/13968K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 7393): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/ActivityManager( 2402): Killing 6692:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,D/daemonapp( 5299): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5299): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5299): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5299): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5299): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 5299): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5299): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5299): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5299): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5299): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5299): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5299): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5299): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5299): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5299): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5299): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 5299): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 5299): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 3310): Checkin interval check for package: unspecified last checkin: 1450135146850 min interval config: 0 actual interval: 91342892
,D/dalvikvm( 2402): GC_EXPLICIT freed 1287K, 56% free 24626K/55328K, paused 19ms+22ms, total 285ms
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/DBG_DM  ( 4655): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 4655): [3.19.140541][Line:1835][xtpAdpGetUserCancel] flag is : false
,I/DBG_DM  ( 4655): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4655): [3.19.140541][Line:174][onReceive] sec.fota.polling.intent.RECEIVE
,I/DBG_DM  ( 4655): [3.19.140541][Line:536][xdmBroadCastCheckReceivedNfcMode] nMode : 0
,I/DBG_DM  ( 4655): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4655): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4655): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4655): [3.19.140541][Line:258][xuiAdpUserInitiate] 
,I/DBG_DM  ( 4655): [3.19.140541][Line:3767][xdbGetWifiOnlyFlag] Wifi_Only_flag : true
,I/DBG_DM  ( 4655): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/DBG_DM  ( 4655): [3.19.140541][Line:283][xuiAdpUserInitiate] bWifiOnly flag : true
,I/DBG_DM  ( 4655): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4655): [3.19.140541][Line:1835][xtpAdpGetUserCancel] flag is : false
,I/DBG_DM  ( 4655): [3.19.140541][Line:1733][xfotaDlAgentHdlrGetUpdateProcessingState] bUpdateProcessing : false
,I/DBG_DM  ( 4655): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4655): [3.19.140541][Line:369][handleMessage] event ->214
,D/Headlines( 7155): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,I/DBG_DM  ( 4655): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4655): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,D/Headlines( 7155): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7155): Breath 6321 latestRequest time : 1450226484030 current time : 1450226490352
,I/SELinux ( 7411): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7411):  
,I/DBG_DM  ( 4655): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
,W/ContextImpl( 4655): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
I/DBG_DM  ( 4655): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
E/DBG_DM  ( 4655): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
E/DBG_DM  ( 4655): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@423c2ae0
,I/DBG_DM  ( 4655): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,I/DBG_DM  ( 4655): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/SELinux ( 7411): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7411):  
I/SELinux ( 7411):  
,I/SELinux ( 7411): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7411): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7411): >>>>> Normal User
,E/dalvikvm( 7411): >>>>> com.android.providers.calendar [ userId:0 | appId:10045 ]
,E/SELinux ( 7411): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7411): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7411): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7411): Added TimaKesytore provider
,I/DBG_DM  ( 4655): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,E/SPPClientService( 5493): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2402): sendNotification(2) - 4
,I/SurfaceFlinger( 1921): id=22 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2402): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2402
,V/AlarmManager( 2402):  next == MAX_VALUE
,I/ActivityManager( 2402): Waited long enough for: ServiceRecord{44d49900 u0 pl.k2.droidoaudioteka/.services.DownloadService}
,I/ActivityManager( 2402): Waited long enough for: ServiceRecord{44d413b8 u0 pl.k2.droidoaudioteka/.services.PlayerService}
,D/dalvikvm( 7411): GC_CONCURRENT freed 2995K, 32% free 9571K/13964K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7411): WAIT_FOR_CONCURRENT_GC blocked 25ms
,E/SPPClientService( 5493): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5493): [a] [ConnectionManager] Connection is already disconnected.
V/AlarmManager( 2402): waitForAlarm result :4
V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/CaptivePortalTracker( 2402): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 2402): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2402): Checking http://216.58.209.46/generate_204
W/ActivityThread( 2402): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/Mms/MessagesLockscreen( 5592): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,W/Binder  ( 2581): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 2581): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
W/Binder  ( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2581): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2581): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2581): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2581): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2581): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2581): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2581): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2581): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 2581): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2581): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2581): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2581): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2581): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2581): 	... 16 more
W/Binder  ( 2581): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2581): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2581): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2581): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2581): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2581): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2581): 	... 19 more
,E/JavaBinder( 2581): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 2581): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2581): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 2581): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2581): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2581): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2581): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2581): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2581): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2581): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2581): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2581): 	... 16 more
E/JavaBinder( 2581): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2581): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2581): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 2581): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2581): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2581): 	... 19 more
,I/System.out( 2402): Thread-161(HTTPLog):isShipBuild true
,I/System.out( 2402): Thread-161(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker( 2402): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2402): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2402): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2402): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2402): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,E/SPPClientService( 5493): [g] getNetMCC return empty string
,E/SPPClientService( 5493): [g] getNetMNC return empty string
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2402): stay LED for fully charged
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/SurfaceFlinger( 1921): id=22 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=22 Removed Uoast (-2/11)
,D/PowerManagerService( 2402): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2402) eventTime = 187614
,D/PowerManagerService( 2402): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2402 (0x0)
,D/PowerManagerService( 2402): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2402, ws=WorkSource{1000}) (elapsedTime=3475)
,E/SPPClientService( 5493): [b] __ProvisionReply__
,E/SPPClientService( 5493): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5493): [d] null
,V/AlarmManager( 2402):  next == MAX_VALUE
,E/SPPClientService( 5493): [g] getPLMN return empty string
,E/SPPClientService( 5493): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5493): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5493): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5493): [g] getNetMCC return empty string
,D/dalvikvm( 5493): GC_CONCURRENT freed 2119K, 26% free 10417K/13960K, paused 3ms+5ms, total 50ms
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 340, Delta = -20
,D/AmoledAdjustTimer( 2402): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4,
,D/PreloadUpdateManagerStateMachine( 6803): execute::IDLE:EXECUTE,
,D/PreloadUpdateManagerStateMachine( 6803): exit::IDLE,
,D/PreloadUpdateManagerStateMachine( 6803): entry::CHECK_TIMEOUT_FOR_UPDATE,
,D/hcjo    ( 6803): AutoUpdateTriggerManager:REQUEST2:requestInterval,
,I/Volley  ( 6803): RestApi Request Add : 2307,
,D/dalvikvm( 6803): GC_CONCURRENT freed 2521K, 29% free 10049K/13964K, paused 4ms+6ms, total 50ms,
,E/SPPClientService( 5493): [b] __InitReply__,
,D/dalvikvm( 6803): GC_CONCURRENT freed 1975K, 29% free 10008K/13964K, paused 4ms+3ms, total 31ms
,D/dalvikvm( 6803): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 6803): GC_CONCURRENT freed 1820K, 28% free 10172K/13964K, paused 2ms+4ms, total 31ms
,I/System.out( 6803): Thread-589(HTTPLog):isShipBuild true,
,I/System.out( 6803): Thread-589(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,I/ActivityManager( 2402): Waited long enough for: ServiceRecord{43110858 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/hcjo    ( 6803): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 6803): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 6803): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6803): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6803): entry::REQ_UPDATE_CHECK
,I/Volley  ( 6803): RestApi Request Add : 2315
,I/qtaguid ( 6803): Failed write_ctrl(u -1) res=-1 errno=9,
,I/qtaguid ( 6803): Untagging socket -1 failed errno=-9,
,W/NetworkManagementSocketTagger( 6803): untagSocket(-1) failed with errno -9,
,D/PreloadUpdateManagerStateMachine( 6803): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS,
,D/PreloadUpdateManagerStateMachine( 6803): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 6803): entry::NOTIFY_NOTIFICATION,
D/PreloadUpdateManagerStateMachine( 6803): exit::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine( 6803): entry::FINISH,
D/PreloadUpdateManagerStateMachine( 6803): exit::FINISH,
,D/PreloadUpdateManagerStateMachine( 6803): entry::IDLE,
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true,
,D/BatteryService( 2402): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2402): !@Sync 6,
,I/ActivityManager( 2402): Waited long enough for: ServiceRecord{44c70078 u0 com.sec.spp.push/.PushClientService},
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 330, Delta = -10,
,D/AmoledAdjustTimer( 2402): prevTemp = 298, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2402): waitForAlarm result :4,
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2402): stay LED for fully charged
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2402): waitForAlarm result :8,
,D/Headlines( 7155): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 7155): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 7155): Breath 30035 latestRequest time : 1450226484030 current time : 1450226514065,
,I/PowerManagerService( 2402): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2402): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/BatteryService( 2402): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2402): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2402): !@Sync 7,
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2402): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,V/AlarmManager( 2402): waitForAlarm result :4,
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,E/ActivityThread( 3310): Failed to find provider info for com.android.contacts.metadata,
,D/SyncManager( 2402): failed sync operation 
,D/SyncManager( 2402): not retrying sync operation because the error is a hard error: 
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/BatteryService( 2402): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5102): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2402): waitForAlarm result :8,
,D/Headlines( 7155): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 7155): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 7155): Breath 60031 latestRequest time : 1450226484030 current time : 1450226544061,
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2402): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2402): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/PowerManagerService( 2402): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2402): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2402): stay LED for fully charged,
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5102): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2402): !@Sync 8,
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2402): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2402): waitForAlarm result :4,
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,V/AlarmManager( 2402): waitForAlarm result :8,
,D/Headlines( 7155): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7155): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7155): Breath 90038 latestRequest time : 1450226484030 current time : 1450226574068,
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2402): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,V/AlarmManager( 2402): waitForAlarm result :8,
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true,
,D/BatteryService( 2402): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5102): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2402): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2402): !@Sync 9,
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2402): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2402): [PWL] Off : 225s ago,
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2402): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2402): stay LED for fully charged
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5102): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2402): waitForAlarm result :4,
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 7155): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 7155): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 7155): Breath 130483 latestRequest time : 1450226484030 current time : 1450226614513
,D/Headlines( 7155): stop 
,I/SELinux ( 8118): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8118):  
,D/Headlines( 7155): Breath.onDestroy : 
I/ActivityManager( 2402): Killing 6719:com.samsung.helphub/1000 (adj 15): empty #43
,I/SELinux ( 8118): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8118):  
I/SELinux ( 8118):  
,I/SELinux ( 8118): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8118): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8118): >>>>> Normal User
,E/dalvikvm( 8118): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 8118): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8118): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8118): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8118): Added TimaKesytore provider
,D/dalvikvm( 8118): GC_CONCURRENT freed 2999K, 32% free 9569K/13964K, paused 3ms+2ms, total 33ms
,D/dalvikvm( 8118): WAIT_FOR_CONCURRENT_GC blocked 30ms
,E/SPPClientService( 8118): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8118): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8118): PushLog.txt file is not deleted.
D/SPPClientService( 8118): PushLog.txt file is not deleted.
,D/SPPClientService( 8118): ============PushLog. stop!
,I/ActivityManager( 2402): Killing 6732:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,E/SPPClientService( 5493): [b] __PingReply__
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2402): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,D/TimaService( 2402): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2402): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2402): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2402): initializing...,
I/TLC_TIMA_PKM_initialize( 2402): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2402): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2402): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2402): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2402): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2402): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2402): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2402): aligned max_recvmsg_size = 262208,
I/TZ: mc_tlc_communication( 2402): device_id = 0x0,
I/TZ: mc_tlc_communication( 2402): tlc_open() was called
,I/TZ: mc_tlc_communication( 2402): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2402): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2402): Opening the session
,I/TZ: mc_tlc_communication( 2402): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2402): Trustlet response is completed,
,E/Watchdog( 2402): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2402): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2402): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2402): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2402): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2402): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2402): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,V/AlarmManager( 2402): waitForAlarm result :8,
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2402): [PWL] Off : 275s ago
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/BatteryService( 2402): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2402): !@Sync 11
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :4
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 8453): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8453):  
,I/SELinux ( 8453): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8453):  
I/SELinux ( 8453):  
,I/SELinux ( 8453): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8453): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8453): >>>>> Normal User
,E/dalvikvm( 8453): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 8453): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 8453): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8453): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8453): Added TimaKesytore provider
,D/dalvikvm( 8453): GC_CONCURRENT freed 3013K, 32% free 9558K/13968K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 8453): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2402): Killing 6744:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 12
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/jxcore-log( 6609): Connected to the server!
I/jxcore-log( 6609): 
,I/chromium( 6609): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2402): stay LED for fully charged
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2402): Skipping unknown process pid 8698
,W/ProcessCpuTracker( 2402): Skipping unknown process pid 8700
,W/ProcessCpuTracker( 2402): Skipping unknown process pid 8701
,W/ProcessCpuTracker( 2402): Skipping unknown process pid 8703
,W/ProcessCpuTracker( 2402): Skipping unknown process pid 8705
,W/ProcessCpuTracker( 2402): Skipping unknown process pid 8706
,W/ProcessCpuTracker( 2402): Skipping unknown process pid 8708
,W/ProcessCpuTracker( 2402): Skipping unknown process pid 8710
,W/ProcessCpuTracker( 2402): Skipping unknown process pid 8711
,W/ProcessCpuTracker( 2402): Skipping unknown process pid 8712
,D/dalvikvm( 2402): GC_CONCURRENT freed 3504K, 56% free 24818K/55328K, paused 20ms+19ms, total 254ms
,I/PowerManagerService( 2402): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2402): !@Sync 13
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 14
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2402): stay LED for fully charged
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2402): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2402): !@Sync 15
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/GAV2    ( 6828): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 6828): Thread[disconnect check,5,main]: Disconnected from service
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/BatteryService( 2402): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 16
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2402): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2402): [PWL] Off : 455s ago
,E/Watchdog( 2402): !@Sync 17
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2402): stay LED for fully charged
D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 18
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2402): !@Sync 19
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/TimaService( 2402): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2402): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2402): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2402): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2402): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2402): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2402): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2402): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2402): !@Sync 21
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/BatteryService( 2402): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 22
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2402): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2402): <AppSync3 Whitelist>
,V/AlarmManager( 2402): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 23
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 24
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 25
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2402): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/dalvikvm( 2402): GC_CONCURRENT freed 3815K, 56% free 24762K/55328K, paused 27ms+16ms, total 256ms
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 26
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 27
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 28
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 29
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :4
,I/SensorManagerA( 2402): getReportingMode :: sensor.mType = 5
,D/LightsService( 2402): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2402): LightSensor setDelay = 200000000
D/Sensors ( 2402): LightSensor setSensorDelay = 200000000
D/Sensors ( 2402): Light sensor flush: not enabled 0
D/Sensors ( 2402): LightSensor enable = 1
D/Sensors ( 2402): LightSensor enableSensor = 1
D/SensorManager( 2402): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/Finsky  ( 3885): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SPPClientService( 5493): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3310): Aggregate from 1450225263615 (log), 1450225263615 (data)
D/Sensors ( 2402): LightSensor enable = 0
,D/Sensors ( 2402): LightSensor enableSensor = 0
D/LightsService( 2402): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2402): unregisterListener ::   
D/LightsService( 2402): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out( 3885): Thread-207 calls detatch()
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 3885): Failed write_ctrl(u 71) res=-1 errno=22
,I/qtaguid ( 3885): Untagging socket 71 failed errno=-22
W/NetworkManagementSocketTagger( 3885): untagSocket(71) failed with errno -22
,I/System.out( 3885): Thread-208 calls detatch()
,D/Finsky  ( 3885): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/dalvikvm( 3885): GC_CONCURRENT freed 2194K, 26% free 10502K/14092K, paused 10ms+6ms, total 70ms
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 3885): Failed write_ctrl(u 71) res=-1 errno=22
I/qtaguid ( 3885): Untagging socket 71 failed errno=-22
W/NetworkManagementSocketTagger( 3885): untagSocket(71) failed with errno -22
,I/System.out( 3885): Thread-207 calls detatch()
,D/dalvikvm( 3885): GC_CONCURRENT freed 829K, 17% free 11721K/14092K, paused 4ms+4ms, total 47ms
,D/dalvikvm( 3885): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 3885): GC_CONCURRENT freed 1001K, 17% free 12701K/15160K, paused 6ms+4ms, total 55ms
,D/dalvikvm( 3885): WAIT_FOR_CONCURRENT_GC blocked 48ms
,D/dalvikvm( 3885): GC_FOR_ALLOC freed 1008K, 19% free 13006K/15928K, paused 40ms, total 41ms
,D/dalvikvm( 3885): GC_CONCURRENT freed 2087K, 20% free 14431K/17912K, paused 5ms+5ms, total 63ms
,D/dalvikvm( 3885): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 3885): Failed write_ctrl(u 71) res=-1 errno=22
,I/qtaguid ( 3885): Untagging socket 71 failed errno=-22
W/NetworkManagementSocketTagger( 3885): untagSocket(71) failed with errno -22
,I/System.out( 3885): Thread-208 calls detatch()
,D/Finsky  ( 3885): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.magazines to true
,D/Finsky  ( 3885): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.apps.magazines from  to d_AAAAAAADF8w=
,D/TimaService( 2402): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2402): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2402): TimaServiceHandler.handleMessage what =1
,D/Finsky  ( 3885): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 3885): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2402): waitForAlarm result :4
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/DeviceConnectionService( 2734): client connected with version: 8296000
,D/Finsky  ( 3885): [235] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Watchdog( 2402): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2402): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2402): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2402): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2402): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 855s ago
,V/AlarmManager( 2402): waitForAlarm result :4
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Finsky  ( 3885): [220] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3885): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 31
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 32
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/BatteryService( 2402): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 33
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 34
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2402): GC_CONCURRENT freed 3611K, 56% free 24865K/55328K, paused 26ms+17ms, total 253ms
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 35
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :4
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PhenotypeConfigurator( 2734): Scheduling Phenotype for one-off execution 7121 seconds from now (1450227388301)
,D/GetConfigurationSnapshotOperation( 2734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2734): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 2402): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2851): GC_EXPLICIT freed 1638K, 23% free 10849K/13992K, paused 8ms+8ms, total 63ms
D/ConnectivityService( 2402): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/LocationManagerService( 2402): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2734): GC_CONCURRENT freed 1738K, 22% free 11995K/15200K, paused 4ms+8ms, total 56ms
,D/LocationManagerService( 2402): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2402): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2402): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2402): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2402): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2402): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 36
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/BatteryService( 2402): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2402): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 37
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 38
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2402): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 39
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/ClearcutLoggerApiImpl( 2851): disconnect managed GoogleApiClient
,V/AlarmManager( 2402): waitForAlarm result :4
,V/AlarmManager( 2402): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5493): [b] __PingReply__
,D/TimaService( 2402): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2402): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2402): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2402): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2402): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2402): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2402): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4064): GC_CONCURRENT freed 3826K, 35% free 9731K/14952K, paused 10ms+4ms, total 59ms
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 41
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 42
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2402): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2402): <AppSync3 Whitelist>
,V/AlarmManager( 2402): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 43
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 1265s ago
,E/Watchdog( 2402): !@Sync 44
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 45
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 46
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2402): GC_CONCURRENT freed 3784K, 56% free 24862K/55328K, paused 23ms+15ms, total 258ms
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 47
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 48
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2402): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2402): !@Sync 49
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,I/SensorManagerA( 2402): getReportingMode :: sensor.mType = 5
,D/LightsService( 2402): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2402): LightSensor setDelay = 200000000
D/Sensors ( 2402): LightSensor setSensorDelay = 200000000
D/Sensors ( 2402): Light sensor flush: not enabled 0
D/Sensors ( 2402): LightSensor enable = 1
D/Sensors ( 2402): LightSensor enableSensor = 1
D/SensorManager( 2402): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2402): LightSensor enable = 0
,D/Sensors ( 2402): LightSensor enableSensor = 0
D/LightsService( 2402): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2402): unregisterListener ::   
D/LightsService( 2402): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/TimaService( 2402): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2402): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2402): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2402): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2402): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2402): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2402): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/BatteryService( 2402): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2402): !@Sync 51
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2402): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2402): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2402): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2402): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5102): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5102): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 52
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 53
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 54
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 55
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 1625s ago
,E/Watchdog( 2402): !@Sync 56
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 5493): GC_CONCURRENT freed 1919K, 26% free 10417K/13944K, paused 9ms+4ms, total 61ms
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 57
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 58
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 59
,D/dalvikvm( 2402): GC_CONCURRENT freed 3783K, 56% free 24816K/55328K, paused 17ms+17ms, total 253ms
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,E/SPPClientService( 5493): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/TimaService( 2402): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2402): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2402): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2402): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2402): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2402): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2402): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 1755s ago
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2402): Prepared write state in 59ms
,I/ProcessStatsService( 2402): Prepared write state in 26ms
,I/ProcessStatsService( 2402): Pruning old procstats: /data/system/procstats/state-2015-12-15-09-20-00.bin
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 61
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 62
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2402): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2402): <AppSync3 Whitelist>
,V/AlarmManager( 2402): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 63
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 64
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2402): waitForAlarm result :8
,V/AlarmManager( 2402): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4064): GC_CONCURRENT freed 2056K, 35% free 9723K/14952K, paused 4ms+3ms, total 45ms
,D/dalvikvm( 4064): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2402): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2402): !@Sync 65
,D/SSRMv2:SIOP( 2402): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2402): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
