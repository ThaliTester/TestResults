#### Test 50242285e132180_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
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
V/AudioCache(  253): notify(0xb7ff4340, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff4340, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff4340, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff4340, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff4340, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff4340, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff4340, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x22, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2426): decode(64, 33862452, 7405)
V/MediaPlayerService(  253): decode(33, 33862452, 7405)
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
V/StagefrightPlayer(  253): setDataSource(33, 33862452, 7405)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7feb070, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7feb070, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7feb070, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7feb070, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7feb070, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7feb070, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7feb070, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7feb070, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x23, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2426): decode(65, 37547940, 5555)
V/MediaPlayerService(  253): decode(33, 37547940, 5555)
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
V/StagefrightPlayer(  253): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff3070, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff3070, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff3070, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff3070, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff3070, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff3070, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff3070, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff3070, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x24, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2426): decode(66, 30367732, 5085)
V/MediaPlayerService(  253): decode(33, 30367732, 5085)
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
V/StagefrightPlayer(  253): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdbcf8, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7fdbcf8, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdbcf8, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdbcf8, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7fdbcf8, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7fdbcf8, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdbcf8, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdbcf8, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x25, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2426): decode(68, 30372876, 21552)
V/MediaPlayerService(  253): decode(34, 30372876, 21552)
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
V/StagefrightPlayer(  253): setDataSource(34, 30372876, 21552)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe7910, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe7910, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe7910, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe7910, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe7910, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe7910, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe7910, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe7910, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x26, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2426): decode(69, 37543652, 4230)
V/MediaPlayerService(  253): decode(33, 37543652, 4230)
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
V/StagefrightPlayer(  253): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fde0f0, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7fde0f0, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fde0f0, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fde0f0, 1, 0, 0)
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
I/OMXCodec(  253): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  253): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  253): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fde0f0, 6, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
V/MediaPlayerService(  253): wait for playback complete
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/AwesomePlayer(  253): onCheckAudioStatus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fde0f0, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fde0f0, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fde0f0, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x27, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2426): decode(70, 30337076, 9400)
V/MediaPlayerService(  253): decode(33, 30337076, 9400)
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
V/StagefrightPlayer(  253): setDataSource(33, 30337076, 9400)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdff78, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
I/Process ( 2426): Sending signal. PID: 2426 SIG: 9
D/SensorService(  772):   -0.1 -0.1 9.6
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
V/AudioCache(  253): notify(0xb7fdff78, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdff78, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdff78, 1, 0, 0)
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
E/IMemory (  253): binder=0xb7fa67e8 transaction failed fd=-2147483647, size=0, err=-32 (Broken pipe)
E/IMemory (  253): cannot dup fd=-2147483647, size=0, err=-32 (Bad file number)
E/IMemory (  253): cannot map BpMemoryHeap (binder=0xb7fa67e8), size=0, fd=-1 (Bad file number)
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdff78, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() stop AudioSource since AudioPlayer not exist
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x28, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  253): instance freeNode
--------- beginning of /dev/log/system
I/ActivityManager(  772): Process com.sec.android.app.shealth (pid 2426) (adj 0) has died.
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
I/SELinux ( 2505): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2505):  
I/SELinux ( 2505): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2505):  
I/SELinux ( 2505):  
I/SELinux ( 2505): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2505): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2505): >>>>> Normal User
E/dalvikvm( 2505): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 2505): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 2505): in addTimaSignatureService
D/TimaKeyStoreProvider( 2505): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2505): Added TimaKesytore provider
W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=2505, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 2505): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences( 2505): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 2505): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 2505): ContentProvider is not null
V/MediaPlayer( 2505): decode(61, 33979084, 48105)
V/MediaPlayerService(  253): decode(33, 33979084, 48105)
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
V/StagefrightPlayer(  253): setDataSource(33, 33979084, 48105)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe21f8, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe21f8, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe21f8, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe21f8, 1, 0, 0)
V/AudioCache(  253): prepared
V/AudioCache(  253): wait - success
V/MediaPlayerService(  253): start
V/StagefrightPlayer(  253): start
V/AwesomePlayer(  253): play
V/AwesomePlayer(  253): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  253): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  253): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/ServiceManager(  294): Waiting for service AtCmdFwd...
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  253): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  253): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe21f8, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe21f8, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe21f8, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): addBatteryData
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe21f8, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x29, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2505): decode(63, 33914984, 10421)
V/MediaPlayerService(  253): decode(33, 33914984, 10421)
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
V/StagefrightPlayer(  253): setDataSource(33, 33914984, 10421)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdeb58, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7fdeb58, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdeb58, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdeb58, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7fdeb58, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7fdeb58, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdeb58, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): addBatteryData
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdeb58, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x2a, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2505): decode(64, 37457308, 34198)
V/MediaPlayerService(  253): decode(33, 37457308, 34198)
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
V/StagefrightPlayer(  253): setDataSource(33, 37457308, 34198)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff3220, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff3220, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff3220, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff3220, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff3220, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff3220, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff3220, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): addBatteryData
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff3220, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x2b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  253): instance freeNode
I/AudioPlayer(  253): reset out
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  253): SecMediaClock destructor
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): ~StagefrightPlayer
V/,StagefrightPlayer(  253): reset
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
V/MediaPlayer( 2505): decode(65, 33862452, 7405)
V/MediaPlayerService(  253): decode(30, 33862452, 7405)
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
V/StagefrightPlayer(  253): setDataSource(30, 33862452, 7405)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe1df0, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe1df0, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe1df0, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe1df0, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe1df0, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe1df0, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe1df0, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): addBatteryData
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe1df0, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x2c, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2505): decode(66, 37547940, 5555)
V/MediaPlayerService(  253): decode(33, 37547940, 5555)
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
V/StagefrightPlayer(  253): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe7910, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe7910, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe7910, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe7910, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe7910, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe7910, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe7910, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe7910, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x2d, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2505): decode(67, 30367732, 5085)
V/MediaPlayerService(  253): decode(34, 30367732, 5085)
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
V/StagefrightPlayer(  253): setDataSource(34, 30367732, 5085)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe9138, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe9138, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe9138, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe9138, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe9138, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe9138, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe9138, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): addBatteryData
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe9138, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x2e, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2505): decode(68, 30372876, 21552)
V/MediaPlayerService(  253): decode(33, 30372876, 21552)
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
V/StagefrightPlayer(  253): setDataSource(33, 30372876, 21552)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdab18, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7fdab18, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdab18, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdab18, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7fdab18, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7fdab18, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdab18, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdab18, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x2f, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2505): decode(69, 37543652, 4230)
V/MediaPlayerService(  253): decode(33, 37543652, 4230)
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
V/StagefrightPlayer(  253): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff6808, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff6808, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff6808, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff6808, 1, 0, 0)
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
I/OMXCodec(  253): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  253): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  253): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff6808, 6, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
V/MediaPlayerService(  253): wait for playback complete
I/AudioPlayer(  253): First fillBuffer call!!
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/AwesomePlayer(  253): onCheckAudioStatus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff6808, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff6808, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff6808, 8, 0, 0)
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
V/MediaPlayer( 2505): decode(70, 30337076, 9400)
V/MediaPlayerService(  253): decode(33, 30337076, 9400)
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
V/StagefrightPlayer(  253): setDataSource(33, 30337076, 9400)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe31b8, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe31b8, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe31b8, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe31b8, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe31b8, 6, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
V/MediaPlayerService(  253): wait for playback complete
I/SELinux ( 2572): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2572):  
I/OMXCodec(  253): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/AwesomePlayer(  253): onCheckAudioStatus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe31b8, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe31b8, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe31b8, 8, 0, 0)
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
V/MediaPlayer( 2505): decode(71, 33925464, 44276)
V/MediaPlayerService(  253): decode(33, 33925464, 44276)
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
V/StagefrightPlayer(  253): setDataSource(33, 33925464, 44276)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe78b0, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe78b0, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe78b0, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe78b0, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7fe78b0, 6, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
V/MediaPlayerService(  253): wait for playback complete
I/SELinux ( 2572): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2572):  
I/SELinux ( 2572):  
I/SELinux ( 2572): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2572): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2572): >>>>> Normal User
E/dalvikvm( 2572): >>>>> com.sec.android.app.sns3 [ userId:0 | appId:10036 ]
E/SELinux ( 2572): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/OMXCodec(  253): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/AwesomePlayer(  253): onCheckAudioStatus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe78b0, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe78b0, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fe78b0, 8, 0, 0)
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
V/MediaPlayer( 2505): decode(72, 33885672, 29256)
V/MediaPlayerService(  253): decode(33, 33885672, 29256)
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
V/StagefrightPlayer(  253): setDataSource(33, 33885672, 29256)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fde888, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
D/TimaKeyStoreProvider( 2572): in addTimaSignatureService
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
D/TimaKeyStoreProvider( 2572): Cannot add TimaSignature Service, License check Failed
I/OMX     (  253): mDispatchers.add
I/OMXCodec(  253): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  253): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  253): finishAsyncPrepare_l
V/AwesomePlayer(  253): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  253): notify(0xb7fde888, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fde888, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fde888, 1, 0, 0)
V/AudioCache(  253): prepared
V/AudioCache(  253): wait - success
V/MediaPlayerService(  253): start
V/StagefrightPlayer(  253): start
D/ActivityThread( 2572): Added TimaKesytore provider
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
V/AudioCache(  253): notify(0xb7fde888, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7fde888, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fde888, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fde888, 8, 0, 0)
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
V/MediaPlayer( 2505): decode(73, 37491572, 52024)
V/MediaPlayerService(  253): decode(33, 37491572, 52024)
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
V/StagefrightPlayer(  253): setDataSource(33, 37491572, 52024)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff2228, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff2228, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff2228, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff2228, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff2228, 6, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff2228, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff2228, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): addBatteryData
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff2228, 8, 0, 0)
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
V/MediaPlayer( 2505): decode(74, 33969800, 9226)
V/MediaPlayerService(  253): decode(33, 33969800, 9226)
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
V/StagefrightPlayer(  253): setDataSource(33, 33969800, 9226)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff22f8, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff22f8, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff22f8, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff22f8, 1, 0, 0)
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
V/AudioCache(  253): notify(0xb7ff22f8, 6, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
V/MediaPlayerService(  253): wait for playback complete
I/OMXCodec(  253): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/AwesomePlayer(  253): onCheckAudioSt,atus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff22f8, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff22f8, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7ff22f8, 8, 0, 0)
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
V/MediaPlayer( 2505): decode(75, 30402580, 4509)
V/MediaPlayerService(  253): decode(33, 30402580, 4509)
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
V/StagefrightPlayer(  253): setDataSource(33, 30402580, 4509)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdbb40, 8, 0, 0)
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
V/AudioCache(  253): notify(0xb7fdbb40, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdbb40, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdbb40, 1, 0, 0)
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
,I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  253): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  253): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdbb40, 6, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/MediaPlayerService(  253): wait for playback complete
V/AwesomePlayer(  253): onCheckAudioStatus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdbb40, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdbb40, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb7fdbb40, 8, 0, 0)
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
W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=2572, uid=10036 requires android.permission.INTERACT_ACROSS_USERS
D/AndroidRuntime( 2588): 
D/AndroidRuntime( 2588): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2588): CheckJNI is OFF
D/AndroidRuntime( 2588): setted country_code = Poland
D/AndroidRuntime( 2588): setted countryiso_code = PL
D/AndroidRuntime( 2588): setted sales_code = XEO
D/AndroidRuntime( 2588): readGMSProperty: start
D/AndroidRuntime( 2588): readGMSProperty: already setted!!
D/AndroidRuntime( 2588): readGMSProperty: end
I/Process ( 2572): Sending signal. PID: 2572 SIG: 9
D/AndroidRuntime( 2588): addProductProperty: start
D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  772): mCoverManager.getCoverState() : true
D/dalvikvm( 2588): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2588): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2588): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2588): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2588): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/ActivityManager(  772): Process com.sec.android.app.sns3 (pid 2572) (adj 0) has died.
I/SELinux ( 2625): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2625):  
D/PowerManagerService(  772): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=1065
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/KeyguardViewMediator( 1065): handleKeyguardDoneDrawing
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/ProgressBar( 1065): setProgressDrawable drawableHeight = 12
D/PhoneStatusBar( 1065): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@421caf20
D/NotificationService(  772): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200dd contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/RCPManagerService(  772): NotificationReceiver onReceive()
D/RCPManagerService(  772):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService(  772): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967296772
D/RCPManagerService(  772): getPolicy: policy value returned = false
D/RCPManagerService(  772): going to get the app label for pkg == com.android.systemui
D/RCPManagerService(  772): app label == com.android.systemui
D/RCPManagerService(  772): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967296772
W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService(  772): sendNotification(1) - 5
W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/UserManagerService(  772): User -1does not exists!!
D/RCPManagerService(  772): getPolicy: policy value returned = true
D/RCPManagerService(  772): Calling User is -1
D/RCPManagerService(  772): userid of SBN ==-1
I/SELinux ( 2625): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2625):  
I/SELinux ( 2625):  
I/SELinux ( 2625): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2625): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2625): >>>>> Normal User
E/dalvikvm( 2625): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/PersonaManagerService(  772): returning null in  getPersonasForUser
E/SELinux ( 2625): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 2625): in addTimaSignatureService
D/BatteryMeterView( 1065): onDraw batteryColor : -1
D/TimaKeyStoreProvider( 2625): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2625): Added TimaKesytore provider
E/memtrack( 2588): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 2588): failed to load memtrack module: -2
D/dalvikvm( 2588): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
E/SMD     (  241): DCD ON
D/AndroidRuntime( 2588): Calling main entry com.android.commands.am.Am
I/SELinux ( 2645): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2645):  
V/ApplicationPolicy(  772): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ServiceManager(  294): Waiting for service AtCmdFwd...
D/CustomFrequencyManagerService(  772): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 772  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  772): mDVFSHelper.acquire()
I/SurfaceFlinger(  247): id=15 createSurf (1x1),1 flag=404, iello
I/SELinux ( 2645): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2645):  
I/SELinux ( 2645):  
I/SELinux ( 2645): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2645): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2645): >>>>> Normal User
E/dalvikvm( 2645): >>>>> com.sec.spp.push [ userId:0 | appId:10038 ]
E/SELinux ( 2645): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 2645): in addTimaSignatureService
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/TimaKeyStoreProvider( 2645): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2645): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/WindowManager(  772): Screenshot max retries 4 of Token{42983458 ActivityRecord{42b07260 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42b06748 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
W/WindowManager(  772): Screenshot failure taking screenshot for (720x1280) to layer 21005
D/LockPatternUtils( 1065): isPcwEnable = null
D/AndroidRuntime( 2588): Shutting down VM
D/dalvikvm( 2588): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+0ms, total 3ms
I/SELinux ( 2657): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2657):  
D/Launcher.HomeView( 1251): onStop
D/Launcher( 1251): onTrimMemory. Level: 20
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1448): [237392/5] Surface widget pause on instance = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1448): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 1448): [KK AccuPhone]>>> SWW:224 [0:0] [SWW] onPause : instance = 1
D/accuweather( 1448): [KK AccuPhone]>>> SWW:239 [0:0] onPause : size = 0
D/accuweather( 1448): [KK AccuPhone]>>> SWW:517 [0:0]  unRegisterTTReceiver !! 
D/accuweather( 1448): [KK AccuPhone]>>> WR:149 [0:0] onPause
D/accuweather( 1448): [KK AccuPhone]>>> SM:526 [0:0] onPause
D/SurfaceWidgetView( 1251): destroyHardwareResources():1124944272
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SELinux ( 2657): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2657):  
I/SELinux ( 2657):  
I/SELinux ( 2657): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2657): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2657): >>>>> Normal User
E/dalvikvm( 2657): >>>>> com.example.hello [ userId:0 | appId:10180 ]
E/SELinux ( 2657): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 2657): in addTimaSignatureService
D/TimaKeyStoreProvider( 2657): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2657): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/LockPatternUtils( 1065): isPcwEnable = null
E/SPPClientService( 2645): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 2645): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 2645): PushLog.txt file is not deleted.
D/SPPClientService( 2645): PushLog.txt file is not deleted.
D/SPPClientService( 2645): ============PushLog. stop!
W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=2657, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
E/SPPClientService( 2645): [SystemStateMoniter] ACTION_BOOT_COMPLETED
W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=2657, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 2657): Binding Chromium to the background looper Looper (main, tid 1) {421a7548}
I/chromium( 2657): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 2657): Initializing chromium process, renderers=0
I/Adreno-EGL( 2657): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2657): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2657): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2657): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2657): Remote Branch: 
I/Adreno-EGL( 2657): Local Patches: 
I/Adreno-EGL( 2657): Reconstruct Branch: 
I/SELinux ( 2682): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2682):  
W/chromium( 2657): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/SELinux ( 2682): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2682):  
I/SELinux ( 2682):  
I/SELinux ( 2682): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2682): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2682): >>>>> Normal User
E/dalvikvm( 2682): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 2682): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/dalvikvm( 2657): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2657): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2657): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2657): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2657): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2657): VFY: replacing opcode 0x6e at 0x0008
D/TimaKeyStoreProvider( 2682): in addTimaSignatureService
D/TimaKeyStoreProvider( 2682): Cannot add TimaSignature Service, License check Failed
W/dalvikvm( 2657): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
D/ActivityThread( 2682): Added TimaKesytore provider
W/dalvikvm( 2657): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2657): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2657): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2657): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2657): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2657): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2657): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2657): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2657): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2657): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2657): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2657): CordovaWebView is running on device made by: samsung
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  247): id=16 createSurf (720x1280),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SA      ( 2682): [SSP] onCreated
I/HWUI    ( 2657): EGLImpl-HWUI Protected EGL context created
I/SA      ( 2682): [TPM] There is no property file
I/SA      ( 2682): [SCU] isHaveSA() - false
D/OpenGLRenderer( 2657): Enabling debug mode 0
I/SA      ( 2682): [TPM] getModelProperty : null
I/SA      ( 2682): [TPM] getCSCProperty : null
I/SA      ( 2682): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED
I/SA      ( 2682): [DM] init START
W/AwContents( 2657): nativeOnDraw failed; clearing to background color.
I/SA      ( 2682): [DM] This device is not a Vodafone
I/SA      ( 2682): [DM] getCountryCodeFromCSC : PL
I/SA      ( 2682): support phone number id : false
I/SA      ( 2682): [DM] init END
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SA      ( 2682): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SA      ( 2682): [BDLM] already registered in spp
I/SA      ( 2682): [OR] onReceive Intent=[ action_BOOT_COMPLETED ]
D/SurfaceWidgetView( 1251): destroyHardwareResources():1124944272
I/SA      ( 2682): [OR] onReceive END
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SA      ( 2682): [BDC] create
I/SurfaceFlinger(  247): id=7 Removed Mauncher (8/13)
I/SurfaceFlinger(  247): id=7 Removed Mauncher (-2/13)
D/CustomFrequencyManagerService(  772): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 772  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  772): mDVFSHelper.release()
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  247): id=15 Removed iello (8/11)
I/SurfaceFlinger(  247): id=15 Removed iello (-2/11)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  772): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 772  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SA      ( 2682): [DBMV2] getEmailID
I/SA      ( 2682): [DBMV2] getDataV02ForItems
I/SA      ( 2682): [SSP] query invoked
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SA      ( 2682): [SCU] get signed id from samsung account2.0 DB.
E/ActivityThread( 1840): Performing stop of activity that is not resumed: {com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover}
E/ActivityThread( 1840): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover}
E/ActivityThread( 1840): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3536)
E/ActivityThread( 1840): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3623)
E/ActivityThread( 1840): 	at android.app.ActivityThread.access$1200(ActivityThread.java:172)
E/ActivityThread( 1840): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1335)
E/ActivityThread( 1840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1840): 	at android.os.Looper.loop(Looper.java:146)
E/ActivityThread( 1840): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/ActivityThread( 1840): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread( 1840): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread( 1840): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/ActivityThread( 1840): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/ActivityThread( 1840): 	at dalvik.system.NativeStart.main(Native Method)
I/SA      ( 2682): [SCU] get signed id from samsung account1.0 DB.
I/SELinux ( 2713): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2713):  
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SA      ( 2682): [BDC] destroy
I/SELinux ( 2713): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2713):  
I/SELinux ( 2713):  
I/SELinux ( 2713): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2713): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2713): >>>>> Normal User
E/dalvikvm( 2713): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
E/SELinux ( 2713): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 2713): in addTimaSignatureService
D/TimaKeyStoreProvider( 2713): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2713): Added TimaKesytore provider
I/chromium( 2657): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 2657): Unable to open asset URL: file:///android_asset/www/jxcore.js
W/Atfwd_Sendcmd(  294): AtCmdFwd service not published, waiting... retryCnt : 3
D/JsMessageQueue( 2657): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 2657): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/dalvikvm( 2657): Trying to load lib /data/app-lib/com.example.hello-6/libjxcore.so 0x424ce220
D/dalvikvm( 2657): Added shared lib /data/app-lib/com.example.hello-6/libjxcore.so 0x424ce220
D/jxcore_app_log( 2657): JniHelper::setJavaVM(0x417ba4f8), pthread_self() = 1980349392
D/JX-Cordova( 2657): jxcore cordova android initializing
I/chromium( 2657): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
E/libGLESv2( 2657): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
E/libGLESv2( 2657): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=2713, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
I/HarmonyEASService(  772): Updating for all 1
D/MediaScannerReceiver( 1202): action: android.intent.action.BOOT_COMPLETED
D/MediaScannerService( 1202): !@start scanning volume internal: [/system/media]
D/TP/MmsProvider( 1247): Update uri=content://mms, match=0
D/TP/MmsProvider( 1247): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1247): need read changed broadcast:false
I/Mms:transaction( 1724): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 1724): [start]    nonBlockingUpdateMessageIndicator()
I/Mms/ReservationManager( 1724): resetAfterConnected()
D/Mms/MessagingNotification( 1724): sDisableVibrateForCamera = false
D/TP/MmsSmsProvider( 1247): match 7:Elapsed time : 2.591 ms
D/Mms/MessagingNotification( 1724): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1724): isDefault true
I/Mms/ReservationManager( 1724): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1247): match 200:Elapsed time : 1.417 ms
I/SELinux ( 2738): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2738):  
W/jxcore-log( 2657): Initializing JXcore engine
W/jxcore-log( 2657): JXcore engine is ready
W/jxcore-log( 2657): Starting JXcore engine
I/SELinux ( 2738): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2738):  
I/SELinux ( 2738):  
,I/SELinux ( 2738): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2738): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2738): >>>>> Normal User
,E/dalvikvm( 2738): >>>>> com.sec.android.app.safetyassurance [ userId:0 | appId:10050 ]
,E/SELinux ( 2738): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2738): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2738): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2738): Added TimaKesytore provider
,D/dalvikvm(  772): GC_EXPLICIT freed 3097K, 17% free 22590K/27080K, paused 5ms+11ms, total 124ms
D/Mms/TelephonyPermission( 1724): isDefault true
D/Mms/SmsReceiverService( 1724): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
,D/Mms/SmsReceiverService( 1724): [start]    handleBootCompleted()
,D/MediaScanner( 1202): Prescan. DB items number : 156 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/TP/MmsSmsProvider( 1247): deleteConversation threadId: 9223372036854775806
,D/BadgeProvider( 1337): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/TP/MmsSmsProvider( 1247): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,D/TP/MmsSmsProvider( 1247): delete threadId: 9223372036854775806
,D/TP/MmsSmsProvider( 1247): need read changed broadcast:false
,D/Mms/Conversation( 1724): deleteTempConversation(),deleted=0
D/BadgeProvider( 1337): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1337): sendNotify, [notify] : null
D/BadgeProvider( 1337): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1337): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1337): update, [UpdateCount] : 1
,D/Launcher.Model( 1251): reloadBadges entered.
,D/Mms/MessagingNotification( 1724): setBadgeCount(), count=0
D/MessagingNotification( 1724): remove alarm
D/SmsProvider( 1247): Update uri=content://sms/outbox, match=8
D/Mms/MessagingNotification( 1724): [end]    nonBlockingUpdateMessageIndicator()
D/TP/MmsSmsProvider( 1247): need read changed broadcast:false
D/Mms/SmsReceiverService( 1724): sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 1724): [SIM-1]sendFirstQueuedMessage()
W/dalvikvm( 2738): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
D/Mms/MessagingNotification( 1724): updateAllHistoryAsRead()
D/Mms/MessagingNotification( 1724): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1724): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1724): isDefault true
,D/SafetyAssuranceAppFeatures( 2738): init start
,I/SafetyAssuranceAppFeatures( 2738): mLoadBaiduMap:false
I/SafetyAssuranceAppFeatures( 2738): mFeatureEnableMultiSim true
,D/SafetyAssuranceAppFeatures( 2738): init end
,D/SafetyAssuranceReceiver( 2738): onReceive
,I/SafetyAssuranceApp( 2738): Acquire WL
,D/TP/MmsSmsProvider( 1247): match 200:Elapsed time : 1.784 ms
D/SafetyAssuranceConfig( 2738): getAppState : 1
D/SafetyAssuranceReceiver( 2738): onReceive - action:android.intent.action.BOOT_COMPLETED, currentAppState:1
,D/SafetyAssuranceReceiver( 2738): Init App state
,D/SafetyAssuranceConfig( 2738): setAppState : 1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=10050
D/SafetyAssuranceApp( 2738): topActivity's name is=.MainActivity
I/SafetyAssuranceApp( 2738): Release WL
,D/KeyguardViewMediator( 1065): handleKeyguardDoneDrawing
,I/NetworkStatusReceiver( 1247): action: android.intent.action.BOOT_COMPLETED
,D/BadgeProvider( 1337): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/NearbySettings( 1310): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 1310): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 1310): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,I/NearbySettings( 1310): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,I/NearbySettings( 1310): MountReceiver.onReceive - Internal Path
,V/NearbySettings( 1310): MountReceiver.mPrefHandler - 7002
,D/Launcher.Model( 1251): reloadBadges entered.
D/BadgeProvider( 1337): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1337): sendNotify, [notify] : null
D/BadgeProvider( 1337): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1337): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1337): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 1724): setBadgeCount(), count=0
,D/MessagingNotification( 1724): remove alarm
,D/Mms/MessagingNotification( 1724): updateAllHistoryAsRead()
,V/MediaScanner( 1202): processDirectory :  /system/media
,D/Mms/SmsReceiverService( 1724): [end]    handleBootCompleted()
,W/jxcore-log( 2657): Platform android
W/jxcore-log( 2657): 
,W/jxcore-log( 2657): Process ARCH arm
W/jxcore-log( 2657): 
,I/AccessibilityManagerService(  772): setmDNIeNegative (false)
,I/jxcore-log( 2657): JXcore Cordova bridge is ready!
I/jxcore-log( 2657): 
,W/jxcore-log( 2657): JXcore engine is started
,I/Choreographer( 2657): Skipped 31 frames!  The application may be doing too much work on its main thread.
V/MediaScanner( 1202):  prescan time: 380ms (DB items: 156)
V/MediaScanner( 1202):     scan time: 74ms (Caching mode: true), (makeEntry time: 33ms ~44%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1202): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
,V/MediaScanner( 1202):    total time: 454ms
V/MediaScanner( 1202): checked files: 149  directories : 5  (I: 0, U: 0)
D/MediaScanner( 1202): checkDefaultSounds
D/MediaScanner( 1202): system alarm_alert  : Vwiurug_etwofi5wgg
E/libGLESv2( 2657): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
D/MediaScanner( 1202): OK. alarm_alert is already exist in setting DB.
D/MediaScanner( 1202): system notification_sound  : K_Oprkltf5wgg
D/MediaScanner( 1202): OK. notification_sound is already exist in setting DB.
D/CustomFrequencyManagerService(  772): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 772  tag : ACTIVITY_RESUME_BOOSTER@9
,E/libGLESv2( 2657): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
D/MediaScanner( 1202): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1202): OK. ringtone is already exist in setting DB.
D/MediaScanner( 1202): system ringtone_2  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1202): OK. ringtone_2 is already exist in setting DB.
D/MediaScanner( 1202): system notification_sound_2  : K_Oprkltf5wgg
D/MediaScanner( 1202): OK. notification_sound_2 is already exist in setting DB.
D/MediaScannerService( 1202): !@done scanning volume internal
D/MediaScannerService( 1202): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter finished
,E/jxcore-log( 2657): >> samsung-SM-G800H
E/jxcore-log( 2657): 
,I/jxcore-log( 2657): Total memory 1454641152
I/jxcore-log( 2657): 
,I/jxcore-log( 2657): Free memory 107651072
I/jxcore-log( 2657): 
I/jxcore-log( 2657): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2657): 
I/jxcore-log( 2657): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2657): 
,D/MediaScanner( 1202): Prescan. DB items number : 20 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/jxcore-log( 2657): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2657): 
,I/jxcore-log( 2657): Size 720 1280
I/jxcore-log( 2657): 
,I/jxcore-log( 2657): Screen Brightness 134
I/jxcore-log( 2657): 
,E/jxcore-log( 2657): Dummy Error Log.
E/jxcore-log( 2657): 
,V/MediaScanner( 1202): processDirectory :  /storage/emulated/0
D/MediaScanner( 1202): Skipping:
,D/MediaScanner( 1202): 7klwibgf7fvntblfd7(75ebcf7
,W/Settings( 1310): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/iu.UploadsManager( 1639): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,D/MediaScanner( 1202): Skipping:
,D/MediaScanner( 1202): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1202): processDirectory :  /storage/extSdCard
W/MediaScanner( 1202): Error opening directory, reason : Permission denied.
,W/MediaScanner( 1202): 7klwibgf7fxlKdCbid7
,E/File    ( 1202): fail readDirectory() errno=2
,V/MediaScanner( 1202): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@425aab98
,V/MediaScanner( 1202): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@425aab98
V/MediaScanner( 1202):  prescan time: 58ms (DB items: 20)
V/MediaScanner( 1202):     scan time: 55ms (Caching mode: true), (makeEntry time: 43ms ~78%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1202): postscan time: 11ms (bulkDeleter : 0), (delete DeadThumbnail time : 7ms)
V/MediaScanner( 1202):    total time: 124ms
V/MediaScanner( 1202): checked files: 3  directories : 17  (I: 0, U: 0)
,D/MediaScannerService( 1202): !@done scanning volume external
,D/MediaScannerService( 1202): send command to ssrm : REQ_DROP_CACHE
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PowerManagerService(  772): [s] UserActivityState : 1 -> 0
I/PowerManagerService(  772): [PWL] On : 0 (39937 ms ago)
I/PowerManagerService(  772): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  772): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1065, ws=null) (elapsedTime=2269)
,D/DisplayPowerController(  772): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService(  772): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  (  772): lcd : 2 +
D/RampAnimator(  772): Light Animator Finished currentValue=2
,D/lights  (  772): lcd : 2 -
,I/SettingSearch/SearchIntentReceiver( 1310): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1310): search setting db init!!
,I/iu.UploadsManager( 1639): End new media; added: 0, uploading: 0, time: 107 ms
,D/SensorService(  772):   -0.0 -0.1 9.5
,I/SettingSearch/SearchIntentReceiver( 1310): BOOT_COMPLETED call InitSerachDBThread thread start!
W/ContextImpl( 1310): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:40 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:60 
,I/SELinux ( 2768): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2768):  
,D/PhoneNumberLocatorBootCompletedReceiver( 1247): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 1247): Phone number locator feature is dsiabled
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
,D/KeyguardViewMediator( 1065): handleKeyguardDoneDrawing
,I/BootupListener( 1247): mPendingNetworkManualSelection : false
,I/ManualSelectionReceiver( 1247): onReceive : Intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.phone/.ManualSelectionReceiver (has extras) }
,I/SELinux ( 2768): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2768):  
I/SELinux ( 2768):  
,I/SELinux ( 2768): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2768): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2768): >>>>> Normal User
,E/dalvikvm( 2768): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10160 ]
,E/SELinux ( 2768): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 2780): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2780):  
,D/TimaKeyStoreProvider( 2768): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2768): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2768): Added TimaKesytore provider
,I/SELinux ( 2780): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2780):  
I/SELinux ( 2780):  
,I/SELinux ( 2780): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2780): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2780): >>>>> Normal User
,E/dalvikvm( 2780): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
,E/SELinux ( 2780): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2780): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2780): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2780): Added TimaKesytore provider
,W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=2768, uid=10160 requires android.permission.INTERACT_ACROSS_USERS
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.ssrm.u.i:-1 com.android.server.ssrm.ai.run:-1 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 
,I/DBG_DM  ( 2780): [][Line:95][onCreate] 
E/DBG_DM  ( 2780): BootingfileStream is null
,E/DBG_DM  ( 2780): xdmCreateBootingFilestream
,D/SSRMv2:SIOP(  772): SIOP:: AP = 330, Delta = 20
I/DBG_DM  ( 2780): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
I/DBG_DM  ( 2780): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
I/DBG_DM  ( 2780): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
I/DBG_DM  ( 2780): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
,I/jxcore-log( 2657): getBuffer is called!!!!
I/jxcore-log( 2657): 
,I/DBG_DM  ( 2780): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
,I/DBG_DM  ( 2780): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
,I/DBG_DM  ( 2780): [3.19.140541][Line:36][onCreate] myUserId : 0
,I/DBG_DM  ( 2780): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 0
,I/DBG_DM  ( 2780): [3.19.140541][Line:2702][xdmdbsqlGetDownloadPostponeStatus] xdbsqlGetDownloadPostponeStatus : 0
,I/DBG_DM  ( 2780): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
,I/DBG_DM  ( 2780): [3.19.140541][Line:99][onCreate] DMApplication NOT Start !
,I/DBG_DM  ( 2780): [3.19.140541][Line:139][onReceive] android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1065): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1065): into the SAFE_MODE_ACTION
,D/OverheatReceiver( 1065): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1065): isSafeMode = false
,I/ActivityManager(  772): Waited long enough for: ServiceRecord{42e46d00 u0 com.google.android.gms/.gcm.GcmService}
,E/Tethering(  772): No numeric data
,E/Tethering(  772): No numeric data
E/Tethering(  772): No numeric data
,E/Tethering(  772): No numeric data
,E/Tethering(  772): No numeric data
I/ConnectivityService(  772): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  772): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  772): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  772): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  772): defaultVal : 1, tetherEnabledInSettings : true
,I/ConnectivityService(  772): defaultVal : 1, tetherEnabledInSettings : true
E/Tethering(  772): No numeric data
,D/LocationManagerService(  772): getProviders()=[passive]
,I/ContactAccountLoggerTas( 2143): canRun() : Opted Out
,E/Tethering(  772): No numeric data
,E/Tethering(  772): No numeric data
,E/Tethering(  772): No numeric data
I/ConnectivityService(  772): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  772): defaultVal : 1, tetherEnabledInSettings : true
,I/ConnectivityService(  772): defaultVal : 1, tetherEnabledInSettings : true
,I/Velvet.VelvetFactory( 2143): refreshing search history.
,E/Tethering(  772): No numeric data
,V/NFC     ( 1310): this device does not have NFC support
V/NFC     ( 1310): this device does not have NFC support
,V/NFC     ( 1310): this device does not have NFC support
,V/NFC     ( 1310): this device does not have NFC support
I/ConnectivityService(  772): defaultVal : 1, tetherEnabledInSettings : true
,V/VibratorService(  772): hasVibrator - useVibetonz: false
,D/LockPatternUtils( 1065): isPcwEnable = null
,W/GAV2    ( 2143): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 2143): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ContactAccountLoggerTas( 2143): canRun() : Opted Out
,W/dalvikvm( 2143): method Lcom/google/android/search/core/state/QueryState;.a incorrectly overrides package-private method with same name in Lcfl;
,V/WebViewChromium( 2143): Binding Chromium to the main looper Looper (main, tid 1) {421aa808}
,D/WifiDisplayAdapter(  772): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService(  772): getStreamVolume 3 index 0
,D/WifiDisplayAdapter(  772): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/MediaRouter( 2143): Found default route: MediaRouter.RouteInfo{ uniqueId=android/kb:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/LockPatternUtils( 1065): isPcwEnable = null
,I/SELinux ( 2816): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2816):  
,E/SMD     (  241): DCD ON
,I/chromium( 2143): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 2143): Initializing chromium process, renderers=0
,D/dalvikvm(  248): GC_EXPLICIT freed 44K, 48% free 9507K/18252K, paused 2ms+3ms, total 30ms
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 48% free 9507K/18252K, paused 2ms+2ms, total 20ms
I/SELinux ( 2816): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2816):  
I/SELinux ( 2816):  
,I/SELinux ( 2816): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2816): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2816): >>>>> Normal User
,E/dalvikvm( 2816): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 2816): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 48% free 9507K/18252K, paused 2ms+3ms, total 23ms
,D/TimaKeyStoreProvider( 2816): in addTimaSignatureService
,W/chromium( 2143): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/TimaKeyStoreProvider( 2816): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2816): Added TimaKesytore provider
,I/Adreno-EGL( 2143): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2143): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2143): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2143): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2143): Remote Branch: 
I/Adreno-EGL( 2143): Local Patches: 
I/Adreno-EGL( 2143): Reconstruct Branch: 
,I/LockPatternUtils( 1310): isSmartCardAuthenticationAvailable: false
,D/WifiDisplayAdapter(  772): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/UserAnalysis.PlaceProvider( 2816): Create SecureDbHelper
W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=2816, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 2816): Create SecureDbHelper
,I/SQLiteSecureOpenHelper( 2816): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2816): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2816): Open Place.db in secure mode
,W/NetworkUtils( 2143): OkHttp exception
,I/ContactAccountLoggerTas( 2143): canRun() : Opted Out
,V/VibratorService(  772): hasVibrator - useVibetonz: false
,I/SQLiteSecureOpenHelper( 2816): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2816): ...getDatabaseLocked(b,b,pwd)
I/SQLiteSecureOpenHelper( 2816): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2816): getDatabaseLocked(b,b,pwd)...
,D/UserAnalysis.CarAnalyzer( 2816): Create SecureDbHelper
,I/SQLiteSecureOpenHelper( 2816): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2816): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2816): Open Place.db in secure mode
,I/LockPatternUtils( 1310): isSmartCardAuthenticationAvailable: false
,I/SQLiteSecureOpenHelper( 2816): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2816): ...getDatabaseLocked(b,b,pwd)
,I/SELinux ( 2845): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2845):  
,I/SELinux ( 2845): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2845):  
I/SELinux ( 2845):  
,I/SELinux ( 2845): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2845): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2845): >>>>> Normal User
,E/dalvikvm( 2845): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 2845): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2845): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2845): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2845): Added TimaKesytore provider
,I/SettingSearch/SearchIntentReceiver( 1310): InitSerachDBThread thread end!
W/ContextImpl( 1310): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:129 <bottom of call stack> 
,I/sCloudBackupApp( 2845): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SELinux ( 2861): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2861):  
,I/SELinux ( 2861): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2861):  
I/SELinux ( 2861):  
,I/SELinux ( 2861): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2861): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2861): >>>>> Normal User
,E/dalvikvm( 2861): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 2861): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2861): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2861): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2861): Added TimaKesytore provider
D/AmoledAdjustTimer(  772): prevTemp = 283, currTemp = 285, prevStep = 4, currStep = 4
,D/PackageManager(  772): [MSG] MCS_UNBIND
I/PackageManager(  772): calling disconnectService()
,D/PackageManager(  772): Trying to unbind to DefaultContainerService
,W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=2861, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 2877): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2877):  
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/KeyguardViewMediator( 1065): handleKeyguardDoneDrawing
,D/KeyguardViewMediator( 1065): handleKeyguardDoneDrawing
,I/SELinux ( 2877): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2877):  
I/SELinux ( 2877):  
,I/SELinux ( 2877): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2877): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2877): >>>>> Normal User
,E/dalvikvm( 2877): >>>>> com.wssnps [ userId:0 | appId:1000 ]
,E/SELinux ( 2877): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2877): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2877): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2877): Added TimaKesytore provider
,D/dalvikvm(  772): GC_EXPLICIT freed 1327K, 17% free 22566K/27080K, paused 5ms+10ms, total 121ms
,D/NPS_WSSNPS( 2877): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2877): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.wssnps.smlNpsReceiver.onReceive:380 android.app.ActivityThread.handleReceiver:2698 
D/NPS_WSSNPS( 2877): [] Service onCreate!!
,I/SELinux ( 2889): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2889):  
,D/NPS_WSSNPS( 2877): [] NpsServiceTask Start
,I/NPS_WSSNPS( 2877): [44.140541] loadCryptionkeyLibrary
,I/NPS_WSSNPS( 2877): [44.140541] FirstLoad Or Not Exist
,D/dalvikvm( 2877): Trying to load lib /data/data/com.wssnps/files/libCryptionkey.so 0x424cd7d0
,D/dalvikvm( 2877): Added shared lib /data/data/com.wssnps/files/libCryptionkey.so 0x424cd7d0
,D/NPS_WSSNPS( 2877): [44.140541] smlDBHelper
,I/NPS_WSSNPS( 2877): [44.140541] AsyncBulkFlagCheck
,I/NPS_WSSNPS( 2877): [44.140541] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 2877): [44.140541] IsRemain_Asyncing nothing
,D/NPS_WSSNPS( 2877): [44.140541] Service onDestroy
,W/ContextImpl( 2877): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 com.wssnps.smlNpsService$1.run:108 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/NPS_WSSNPS( 2877): [44.140541] smlBRConfigurationDelete
I/NPS_WSSNPS( 2877): [44.140541] smlBRMessageDelete
I/NPS_WSSNPS( 2877): [44.140541] smlBREmailDelete
I/NPS_WSSNPS( 2877): [44.140541] smlBRNetworkDelete
I/NPS_WSSNPS( 2877): [44.140541] smlBRCallLogDelete
I/SELinux ( 2889): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2889):  
I/SELinux ( 2889):  
I/SELinux ( 2889): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/NPS_WSSNPS( 2877): [44.140541] smlBRMiniDiaryDelete
E/SELinux ( 2889): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/NPS_WSSNPS( 2877): [44.140541] smlBRPenMemoMDelete
E/dalvikvm( 2889): >>>>> Normal User
E/dalvikvm( 2889): >>>>> com.samsung.android.app.accesscontrol [ userId:0 | appId:10064 ]
I/NPS_WSSNPS( 2877): [44.140541] smlBRSMemoDelete
I/NPS_WSSNPS( 2877): [44.140541] cpuBooster release : false
E/SELinux ( 2889): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/NPS_WSSNPS( 2877): [44.140541] dsServerSocket close
,D/TimaKeyStoreProvider( 2889): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2889): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2889): Added TimaKesytore provider
,I/SELinux ( 2905): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2905):  
,I/SELinux ( 2905): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2905):  
I/SELinux ( 2905):  
,I/SELinux ( 2905): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2905): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2905): >>>>> Normal User
,E/dalvikvm( 2905): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
,E/SELinux ( 2905): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2905): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2905): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2905): Added TimaKesytore provider
,D/FileShare-Server( 2905): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/ActivityManager(  772): Killing 1285:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #43
I/SELinux ( 2919): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2919):  
,I/SELinux ( 2919): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2919):  
I/SELinux ( 2919):  
,I/SELinux ( 2919): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2919): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2919): >>>>> Normal User
E/dalvikvm( 2919): >>>>> com.sec.android.nearby.mediaserver [ userId:0 | appId:10070 ]
,E/SELinux ( 2919): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2919): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2919): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2919): Added TimaKesytore provider
,I/AllShare(ASF-DMSLIB)( 2919): DMSReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=10070
,I/SELinux ( 2931): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2931):  
,D/KeyguardViewMediator( 1065): handleKeyguardDoneDrawing
I/ActivityManager(  772): Killing 1337:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/SELinux ( 2931): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2931):  
I/SELinux ( 2931):  
,I/SELinux ( 2931): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2931): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2931): >>>>> Normal User
E/dalvikvm( 2931): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 2931): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2931): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2931): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2931): Added TimaKesytore provider
,W/ContextImpl( 2931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:61 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2948): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2948):  
,I/SELinux ( 2948): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2948):  
I/SELinux ( 2948):  
,I/SELinux ( 2948): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2948): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2948): >>>>> Normal User
,E/dalvikvm( 2948): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
,E/SELinux ( 2948): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2948): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2948): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2948): Added TimaKesytore provider
,D/BluetoothBDAdrressReceiver( 2948): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2948): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
W/ContextImpl( 2948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2960): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2960):  
,I/ActivityManager(  772): Killing 1263:com.android.printspooler/u0a144 (adj 15): empty #43
D/BluetoothBDTestService( 1247): onCreate()
E/BluetoothBDTestService( 1247): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
E/BluetoothBDTestService( 1247): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1247): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,I/SELinux ( 2960): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2960):  
I/SELinux ( 2960):  
,I/SELinux ( 2960): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2960): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2960): >>>>> Normal User
,E/dalvikvm( 2960): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 2960): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 2960): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2960): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2960): Added TimaKesytore provider
,W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=2960, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 2973): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2973):  
I/ActivityManager(  772): Killing 1771:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #43
,I/SELinux ( 2973): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2973):  
I/SELinux ( 2973):  
,I/SELinux ( 2973): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2973): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2973): >>>>> Normal User
,E/dalvikvm( 2973): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 2973): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2973): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2973): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2973): Added TimaKesytore provider
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2931): Resource data:2131165197
I/AMMetaDataParserService( 2931): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131165194
I/AMMetaDataParserService( 2931): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
E/PersonaManagerService(  772): returning null in  getPersonasForUser
,I/SELinux ( 2985): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2985):  
I/ActivityManager(  772): Killing 1784:com.sec.modem.settings/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2931): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,D/dalvikvm(  248): GC_EXPLICIT freed 46K, 48% free 9507K/18252K, paused 2ms+2ms, total 28ms
,D/SensorService(  772):   -0.0 -0.1 9.6
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 48% free 9507K/18252K, paused 1ms+3ms, total 19ms
,I/SELinux ( 2985): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2985):  
I/SELinux ( 2985):  
,I/SELinux ( 2985): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2985): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2985): >>>>> Normal User
,E/dalvikvm( 2985): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 2985): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 48% free 9507K/18252K, paused 1ms+3ms, total 18ms
,I/AMMetaDataParserService( 2931): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,D/TimaKeyStoreProvider( 2985): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2985): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2985): Added TimaKesytore provider
,I/AMMetaDataParserService( 2931): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131165194
,I/AMMetaDataParserService( 2931): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,I/AMMetaDataParserService( 2931): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,I/AMMetaDataParserService( 2931): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=10084
,I/AMMetaDataParserService( 2931): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,D/KeyguardViewMediator( 1065): handleKeyguardDoneDrawing
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,I/AMMetaDataParserService( 2931): Resource data:2131165195
,I/AMMetaDataParserService( 2931): getResourceName:com.sec.android.gallery3d:xml/device_filter
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2931): Resource data:2131165204
,I/AMMetaDataParserService( 2931): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2931): Resource data:2131165204
,I/AMMetaDataParserService( 2931): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 2931): Resource data:2131165204
I/AMMetaDataParserService( 2931): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 2931): getResourceTypeNamexml
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2931): Resource data:2131099676
,I/AMMetaDataParserService( 2931): getResourceName:com.android.mms:xml/spellscroll
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131099648
I/AMMetaDataParserService( 2931): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 2999): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2999):  
I/ActivityManager(  772): Killing 1800:com.sec.tcpdumpservice/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2931): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2931): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/SELinux ( 2999): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2999):  
I/SELinux ( 2999):  
,I/SELinux ( 2999): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2999): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2999): >>>>> Normal User
,E/dalvikvm( 2999): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
,E/SELinux ( 2999): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,I/AMMetaDataParserService( 2931): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/TimaKeyStoreProvider( 2999): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2999): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2999): Added TimaKesytore provider
,I/AMMetaDataParserService( 2931): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2931): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131099648
I/AMMetaDataParserService( 2931): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/ActivityManager(  772): Killing 1827:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
I/SELinux ( 3011): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3011):  
,I/AMMetaDataParserService( 2931): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,E/SMD     (  241): DCD ON
I/ActivityManager(  772): Waited long enough for: ServiceRecord{42e49140 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/AMMetaDataParserService( 2931): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/SELinux ( 3011): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3011):  
I/SELinux ( 3011):  
,I/SELinux ( 3011): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3011): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 3011): >>>>> Normal User
,E/dalvikvm( 3011): >>>>> com.dropbox.android [ userId:0 | appId:10091 ]
,E/SELinux ( 3011): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/AMMetaDataParserService( 2931): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/TimaKeyStoreProvider( 3011): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3011): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3011): Added TimaKesytore provider
,I/AMMetaDataParserService( 2931): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2931): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131099648
,I/AMMetaDataParserService( 2931): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2931): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2931): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/AMMetaDataParserService( 2931): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3011): Setting receiver enabled: false
,I/AMMetaDataParserService( 2931): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/com.dropbox.sync.android.a( 3011): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/AMMetaDataParserService( 2931): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131099648
I/AMMetaDataParserService( 2931): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/com.dropbox.sync.android.aa( 3011): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800H armeabi-v7a; en_US))
,I/AMMetaDataParserService( 2931): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=3011, uid=10091 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 3036): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3036):  
I/ActivityManager(  772): Killing 1744:com.sec.android.app.mt/1000 (adj 15): empty #43
V/AlarmManager(  772): waitForAlarm result :4
,I/AMMetaDataParserService( 2931): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
V/AlarmManager(  772): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 3036): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3036):  
I/SELinux ( 3036):  
,I/SELinux ( 3036): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3036): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3036): >>>>> Normal User
,E/dalvikvm( 3036): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 3036): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3036): in addTimaSignatureService
,I/AMMetaDataParserService( 2931): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/TimaKeyStoreProvider( 3036): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3036): Added TimaKesytore provider
,I/AMMetaDataParserService( 2931): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2931): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/elm:14132( 3036): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 3036): ELMEngine.ELMEngine( context ).
,D/elm:14132( 3036): MDMBridge.setEnterpriseBridge()
,W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=3036, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 3036): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 3036): ElmAgentService : onCreate()
D/elm:14132( 3036): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 3036): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:14132( 3036): BootCompletedState : startBootCompleted() call
D/elm:14132( 3036): ModuleBase.resetCalllogAPIAlarm()
,I/SELinux ( 3051): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3051):  
,D/elm:14132( 3036): MDMBridge.getAllLicenseInfoFromSDK()
I/elm:14132( 3036): Get License : 0
,D/elm:14132( 3036): ElmAgentService : onDestroy().
I/ActivityManager(  772): Killing 1910:com.sec.phone/1001 (adj 15): empty #43
,I/AMMetaDataParserService( 2931): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131099648
I/AMMetaDataParserService( 2931): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 3051): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3051):  
I/SELinux ( 3051):  
,I/SELinux ( 3051): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3051): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3051): >>>>> Normal User
,E/dalvikvm( 3051): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,E/SELinux ( 3051): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2931): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/TimaKeyStoreProvider( 3051): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3051): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3051): Added TimaKesytore provider
,I/AMMetaDataParserService( 2931): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/System.out( 3011): Thread-257(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3011): Thread-257(ApacheHTTPLog):isShipBuild true
,I/System.out( 3011): Thread-257(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/AMMetaDataParserService( 2931): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/System.out( 3011): pool-4-thread-1 calls detatch()
,I/SELinux ( 3067): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3067):  
I/ActivityManager(  772): Killing 2013:com.google.android.configupdater/u0a3 (adj 15): empty #43
,I/AMMetaDataParserService( 2931): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2931): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131099648
I/AMMetaDataParserService( 2931): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
I/SELinux ( 3067): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3067):  
I/SELinux ( 3067):  
,I/SELinux ( 3067): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3067): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3067): >>>>> Normal User
,E/dalvikvm( 3067): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,E/SELinux ( 3067): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2931): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/TimaKeyStoreProvider( 3067): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3067): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3067): Added TimaKesytore provider
,I/AMMetaDataParserService( 2931): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2931): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/CameraApp( 3067): CameraApp.onCreate()... mFeature : null
I/testFeature( 3067): Feature.Feature(context)
I/testFeature( 3067): Feature.readInternalDefaultXml()
,I/testFeature( 3067): ResetFeatureValue
I/CameraFirmware_broadcast( 3067): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 3067): CameraApp.getAppFeature()...
,I/AMMetaDataParserService( 2931): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 3079): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3079):  
I/ActivityManager(  772): Killing 2104:com.sec.dsm.system/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2931): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2931): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/SELinux ( 3079): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3079):  
I/SELinux ( 3079):  
,I/SELinux ( 3079): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3079): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3079): >>>>> Normal User
,E/dalvikvm( 3079): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 3079): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 2931): Resourc,e data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2931): Resource data:2131099671
I/AMMetaDataParserService( 2931): getResourceName:com.android.mms:xml/searchable
I/AMMetaDataParserService( 2931): getResourceTypeNamexml
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity,
,D/TimaKeyStoreProvider( 3079): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3079): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3079): Added TimaKesytore provider
,D/PackageIntentReceiver( 3079): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3079): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager(  772): Killing 2171:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
,D/dalvikvm( 2931): GC_CONCURRENT freed 4984K, 31% free 12703K/18252K, paused 4ms+3ms, total 41ms
,D/dalvikvm( 2931): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.GridSettings
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131165216
,I/SELinux ( 3098): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3098):  
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,E/BluetoothManagerService(  772): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 2657): packageName : com.example.hello
,I/WifiManager( 2657): setWifiEnabled : false
,I/WifiService(  772): setWifiEnabled: false pid=2657, uid=10180
,I/jxcore-log( 2657): ****TEST TOOK:  5075  ms ****
I/jxcore-log( 2657): 
,I/jxcore-log( 2657): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2657): 
,I/SELinux ( 3098): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3098):  
I/SELinux ( 3098):  
I/SELinux ( 3098): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3098): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3098): >>>>> Normal User
E/dalvikvm( 3098): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
,E/SELinux ( 3098): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/AMMetaDataParserService( 2931): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,D/TimaKeyStoreProvider( 3098): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3098): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3098): Added TimaKesytore provider
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.TimDataConnectionDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429159
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2931): Resource data:2131296695
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429159
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429144
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429144
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429144
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2931): Resource data:2131297114
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/wifi_settings
,I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ApnSettings
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ApnSettingsTabActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429146
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429146
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/bluetooth_settings
,I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429168
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/mirror_link_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429159
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2931): Resource data:2131296695
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429159
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2931): Resource data:2131296695
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429144
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2931): Resource data:2131297114
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429159
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2931): Resource data:2131296695
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429159
W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/PowerManagerService(  772): [PWL] On : 0 (44937 ms ago)
I/PowerManagerService(  772): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService(  772): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1065, ws=null) (elapsedTime=7269)
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131296695
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429159
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131296695
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429159
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131296695
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429159
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource dat,a:2131296695
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429219
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429191
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429191
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429191
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429191
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429191
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMe,taDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429191
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131298419
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429191
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131298419
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429191
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131298419
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429176
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429176
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429173
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429173
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429172
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429172
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429182
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429173
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429186
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429186
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429173
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131297804
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429173
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429228
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.users.UserOptions
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429128
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429128
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429128
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429127
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429127
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429128
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429128
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429127
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429127
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429128
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429153
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429224
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.CarrierMatchSetting
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429224
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131296750
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429224
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429123
,W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=3098, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/privacy_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429224
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131296750
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429224
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131296750
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429187
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429187
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131298587
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429187
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131298587
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429191
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429180
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/driving_mode
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429223
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429225
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429159
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131296695
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429165
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429225
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429223
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131297938
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429223
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131297938
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429161
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429163
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429167
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131296695
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.RadioInfo
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429221
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429221
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429119
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429217
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429224
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429224
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429159
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429173
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429208
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429286
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429224
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429201
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429185
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429185
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131299843
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/power_saving_mode_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429185
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429185
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429222
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/power_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429186
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 2931): Resource data:1
W/ResourceType( 2931): No package identifier when getting name for resource number 0x00000001
W/System.err( 2931): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 2931): 	at android.content.res.Resources.getResourceName(Resources.java:3017)
W/System.err( 2931): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 2931): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 2931): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
,W/System.err( 2931): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2931): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 2931): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429199
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131301070
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429173
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/display_settings
,I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131297804
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429203
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/header_display_notification_panel
,I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429193
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429194
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429206
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131300118
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429196
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429260
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 2931): getResourceTypeNameid
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429197
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429291
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429228
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429199
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429199
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429199
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429199
,I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.InputControlHelp
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.NetworkManagement
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.MultiSimCardManagerPreference
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.NetworkManagementSetting
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.DualHelpActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.DualSoundRingtoneSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.RingtoneSettingTabActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.IccLockTabSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429173
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429285
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429172
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131301505
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429203
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429203
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131302910
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429179,
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2130838248
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2931): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429216
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429209
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429209
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAlertDialogActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429177
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429212
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429213
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429153
I/Babel   ( 3098): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3098): MmsConfig.loadMmsSettings
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131302078
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429153
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131302078
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429153
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131302107
I/Babel   ( 3098): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
I/Babel   ( 3098): MmsConfig.loadFromDatabase
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429159
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429159
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429117
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429122
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429195
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2931): Resource data:2131297804
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429151
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429204
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429204
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429195
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2130838300
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2931): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2130838300
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2931): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429202
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429202
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2931): Resource data:2131165381
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:xml/searchable
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429124
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429187
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2931): Resource data:2131298587
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2931): getResourceTypeNamestring
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429198
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429258
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429220
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429220
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429276
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429276
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429148
,E/Babel   ( 3098): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3098): MmsConfig.loadFromResources
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429242
,E/Babel   ( 3098): canonicalizeMccMnc: invalid mccmnc nullnull
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.KnoxSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2931): Resource data:2131429211
,I/Babel   ( 3098): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2130838248
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2931): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2931): Resource data:2131429192
I/AMMetaDataParserService( 2931): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 2931): getResourceTypeNameid
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintOnehandGrip
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
,W/Settings( 3098): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 3098): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3098): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3098): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3098): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3098): VFY: unable to resolve instance field 46
,D/dalvikvm( 3098): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3098): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3098): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3098): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3098): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3098): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,D/dalvikvm( 3098): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x425fc7c8
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2931): Resource data:2131034120
,I/AMMetaDataParserService( 2931): getResourceName:com.android.contacts:xml/searchable
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131034113
I/AMMetaDataParserService( 2931): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,D/dalvikvm( 3098): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x425fc7c8
,D/dalvikvm( 3098): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x425fc7c8, skipping init
,D/dalvikvm( 3098): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x425fc7c8
D/dalvikvm( 3098): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x425fc7c8
,V/JNIHelp ( 3098): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...,
,I/AMMetaDataParserService( 2931): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,V/Babel   ( 3098): babel boot account: thalitester@gmail.com
,V/Babel   ( 3098): babel boot account: SMS
,I/AMMetaDataParserService( 2931): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/SELinux ( 3132): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3132):  
I/ActivityManager(  772): Killing 2187:com.sec.kidsplat.installer/u0a158 (adj 15): empty #43
,I/AMMetaDataParserService( 2931): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,D/dalvikvm( 3098): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x425fc7c8
,D/dalvikvm( 3098): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x425fc7c8
D/dalvikvm( 3098): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x425fc7c8
,D/dalvikvm( 3098): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x425fc7c8
I/SELinux ( 3132): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3132):  
I/SELinux ( 3132):  
,I/SELinux ( 3132): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3132): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3132): >>>>> Normal User
,E/dalvikvm( 3132): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 3132): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2931): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,D/TimaKeyStoreProvider( 3132): in addTimaSignatureService
,D/AndroidRuntime( 3111): 
D/AndroidRuntime( 3111): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/TimaKeyStoreProvider( 3132): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3132): Added TimaKesytore provider
,D/AndroidRuntime( 3111): CheckJNI is OFF
,D/AndroidRuntime( 3111): setted country_code = Poland
,D/AndroidRuntime( 3111): setted countryiso_code = PL
D/AndroidRuntime( 3111): setted sales_code = XEO
D/AndroidRuntime( 3111): readGMSProperty: start
,D/AndroidRuntime( 3111): readGMSProperty: already setted!!
D/AndroidRuntime( 3111): readGMSProperty: end
,D/AndroidRuntime( 3111): addProductProperty: start
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131034113
I/AMMetaDataParserService( 2931): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,D/dalvikvm( 3111): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3111): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3111): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3111): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3111): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,I/AMMetaDataParserService( 2931): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/ProviderInstaller( 3098): Installed default security provider GmsCore_OpenSSL
,V/AlarmManager(  772): waitForAlarm result :4
,V/AlarmManager(  772): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  772): waitForAlarm result :4
,V/AlarmManager(  772): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/AMMetaDataParserService( 2931): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/SELinux ( 3155): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3155):  
,I/AMMetaDataParserService( 2931): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
I/ActivityManager(  772): Killing 2213:com.sec.factory/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2931): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 2931): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 2931): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131034112
I/AMMetaDataParserService( 2931): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
,I/SELinux ( 3155): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3155):  
I/SELinux ( 3155):  
,I/SELinux ( 3155): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3155): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3155): >>>>> Normal User
,E/dalvikvm( 3155): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
,E/SELinux ( 3155): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2931): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
,D/TimaKeyStoreProvider( 3155): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3155): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3155): Added TimaKesytore provider
,I/AMMetaDataParserService( 2931): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
I/ActivityManager(  772): Waited long enough for: ServiceRecord{430184c8 u0 com.samsung.android.providers.context/.ContextService}
,E/memtrack( 3111): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3111): failed to load memtrack module: -2
,I/AMMetaDataParserService( 2931): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
W/ContextImpl( 3155): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3155): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 29,31): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131034113
,I/knox    ( 3155): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3155): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
D/knox    ( 3155): KNOXAgentService : onCreate()
I/AMMetaDataParserService( 2931): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 2931): getResourceTypeNamexml
D/dalvikvm( 3111): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/knox    ( 3155): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3155): KNOXAgentService. startJobThread() start
D/knox    ( 3155): KNOXAgentService. JobThread()
D/knox    ( 3155): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3155): KNOXAgentService. startJobThread() wait
,I/AMMetaDataParserService( 2931): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/SELinux ( 3169): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3169):  
,D/knox    ( 3155): mKnoxAgentEngine.ELMEngine( context , reStart:true).
,D/knox    ( 3155): KNOXAgentService : onDestroy().
,D/knox    ( 3155): ModuleBase.cancelAllAlarmManageModule()
,I/GAV2    ( 2143): Thread[GAThread,5,main]: No campaign data found.
,I/AMMetaDataParserService( 2931): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/AndroidRuntime( 3111): Calling main entry com.android.commands.pm.Pm
,I/GAv4-SVC( 1639): Google Analytics 8.3.01 is starting up.
,I/SELinux ( 3169): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3169):  
I/SELinux ( 3169):  
,I/SELinux ( 3169): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3169): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3169): >>>>> Normal User
,E/dalvikvm( 3169): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
,E/SELinux ( 3169): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/PackageManagerService(  772): deletePackageAsUser- pkg:com.example.hello, userId:0
,D/PersonaManagerService(  772): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  772): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  772): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  772): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  772): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/dalvikvm( 2931): GC_CONCURRENT freed 2314K, 33% free 12374K/18252K, paused 5ms+12ms, total 50ms
D/PackageManagerService(  772): deletePackage- pkg:com.example.hello, edmuserId:0
,D/PackageManagerService(  772): deletePackage- pkg:com.example.hello, edmuserId:-1
D/TimaKeyStoreProvider( 3169): in addTimaSignatureService
D/ApplicationPolicy(  772): getApplicationUninstallationEnabled
D/ApplicationPolicy(  772): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService(  772): deletePackageX- pkg:com.example.hello, userId:0
D/PackageManager(  772): START PACKAGE DELETE: observer{1122468952}
D/PackageManager(  772): pkg{<packageName>}
D/PackageManager(  772): user{0}
D/PackageManager(  772): deletePackageAsUser : uid = 2000 userId = 0
,D/PackageManager(  772): [MSG] DELETE_PACKAGE_AS_USER
D/TimaKeyStoreProvider( 3169): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3169): Added TimaKesytore provider
I/AMMetaDataParserService( 2931): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,D/PackageManager(  772): !@killApplicatoin: 10180, uninstall pkg
,I/AMMetaDataParserService( 2931): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
I/ActivityManager(  772): Killing 2657:com.example.hello/u0a180 (adj 0): stop com.example.hello
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2931): Resource data:2131034116
,I/SurfaceFlinger(  247): id=16 Removed NainActivit (7/10)
,I/SurfaceFlinger(  247): id=16 Removed NainActivit (-2/10)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/WindowState(  772): WIN DEATH: Window{43175c28 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  772): Skipping PackageSetting{42619ad0 com.test.thalitest/10179} due to missing metadata
,D/PackageManager(  772): queryIntentReceivers - Execution time: 101 ms
I/AMMetaDataParserService( 2931): getResourceName:com.android.contacts:xml/findo_searchable
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/SQLiteSecureOpenHelper( 2058): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2058): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1065): isPcwEnable = null
W/ActivityManager(  772): Force removing ActivityRecord{431e4a90 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,D/PackageManager(  772): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10180, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2931): Resource data:2131099668
D/CustomFrequencyManagerService(  772): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 772  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  772): mDVFSHelper.acquire()
D/Launcher( 1251): onRestart, Launcher: 1113008512
,D/Launcher( 1251): onStart, Launcher: 1113008512
,D/Launcher.HomeView( 1251): onStart
I/AMMetaDataParserService( 2931): getResourceName:com.sec.android.app.sbrowser:xml/searchable
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,D/LockPatternUtils( 1065): isPcwEnable = null
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1448): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1448): [237392/5] SurfaceWidget drawing first frame
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/AMMetaDataParserService( 2931): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 2931): Resource data:2131099650
I/AMMetaDataParserService( 2931): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=17 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/AMMetaDataParserService( 2931): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=18 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/AMMetaDataParserService( 2931): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
,I/FPMS_FingerprintManagerService( 1084): onReceive: android.intent.action.PACKAGE_REMOVED
,D/AdaptiveEventManager( 1065): action=android.intent.action.PACKAGE_REMOVED
,E/KnoxSetupWizardClient( 3169): isShipMode : 1
,I/KnoxSetupWizardClient( 3169): onReceive : android.intent.action.BOOT_COMPLETED
D/PackageManager(  772): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10180, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/InputReader(  772): Reconfiguring input devices.  changes=0x00000010
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/dalvikvm( 1414): GC_EXPLICIT freed 4142K, 46% free 9983K/18252K, paused 3ms+5ms, total 55ms
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "sms"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/AMMetaDataParserService( 2931): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,W/GeofencerStateMachine( 1216): Ignoring removeGeofence because network location is disabled.
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 2931): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
D/CustomFrequencyManagerService(  772): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 772  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  772): mDVFSHelper.release()
D/CustomFrequencyManagerService(  772): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 772  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "smsto"
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/PackageManager(  772): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
D/RCPManagerService(  772): PackageReceiver onReceive()
D/ShortcutReceiver( 3169):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  772):   Scheme: "mms"
,I/yash    ( 3169): setDisableWidget>size:0
,I/HarmonyEASService(  772): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAutoDiscover
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131099667
,W/System.err( 3169): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3169): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 3169): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 3169): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
,W/System.err( 3169): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 3169): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
,W/System.err( 3169): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "mmsto"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/AMMetaDataParserService( 2931): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,W/System.err( 3169): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
W/System.err( 3169): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 3169): 	at android.os.Parcel.readException(Parcel.java:1419)
,W/System.err( 3169): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3169): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
,W/System.err( 3169): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
,W/System.err( 3169): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
,W/System.err( 3169): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "sms"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/AMMetaDataParserService( 2931): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559
,I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "smsto"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/AMMetaDataParserService( 2931): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558
,I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "mms"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3192): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3192):  
I/ActivityManager(  772): Killing 2238:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,D/dalvikvm(  248): GC_EXPLICIT freed 48K, 48% free 9507K/18252K, paused 2ms+3ms, total 30ms
,I/SELinux ( 3192): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3192):  
I/SELinux ( 3192):  
,I/SELinux ( 3192): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3192): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3192): >>>>> Normal User
,E/dalvikvm( 3192): >>>>> com.LocalFota [ userId:0 | appId:10110 ]
,I/AMMetaDataParserService( 2931): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
,E/SELinux ( 3192): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 48% free 9507K/18252K, paused 2ms+3ms, total 20ms
,D/TimaKeyStoreProvider( 3192): in addTimaSignatureService
I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "mmsto"
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 48% free 9507K/18252K, paused 2ms+2ms, total 21ms
D/EnterpriseDeviceManagerService(  772): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  772): Admin package name: com.google.android.gms
,D/TimaKeyStoreProvider( 3192): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3192): Added TimaKesytore provider
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/AMMetaDataParserService( 2931): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
,D/dalvikvm(  772): GC_EXPLICIT freed 2627K, 16% free 22972K/27080K, paused 17ms+23ms, total 295ms
D/PackageManager(  772): delete sourFile : 
,D/PackageManager(  772): delete native library directory: 
D/PackageManager(  772): return delete result to caller: 1122468952
,D/AndroidRuntime( 3111): Shutting down VM
,D/PackageManager(  772): returnCode: 1
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 3111): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 2ms
I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "sms"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_WSS_LF( 3192): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=3192, uid=10110 requires android.permission.INTERACT_ACROSS_USERS
,I/AMMetaDataParserService( 2931): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
,I/DBG_WSS_LF( 3192): [20.0040.140326][Line:27][<init>] First call
I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "smsto"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/BackupManagerService(  772): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  772): removePackageParticipantsLocked: uid=10180 #1
I/AMMetaDataParserService( 2931): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "mms"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
,I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2931): Resource data:2131099689
,I/AMMetaDataParserService( 2931): getResourceName:com.android.email:xml/spellscroll
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2931): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2931): Resource data:2131099685
I/AMMetaDataParserService( 2931): getResourceName:com.android.email:xml/searchable
I/AMMetaDataParserService( 2931): getResourceTypeNamexml
I/AMMetaDataParserService( 2931): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 2931): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2931): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 2931): Resource data:2130903052
,I/DBG_WSS_LF( 3192): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED
I/DBG_WSS_LF( 3192): [20.0040.140326][Line:31][onReceive] *** boot complete ***
I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "mmsto"
,I/PackageManager(  772): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/DBG_WSS_LF( 3192): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
I/DBG_WSS_LF( 3192): [20.0040.140326][Line:41][onReceive] nStatus : -1
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 2931): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
,I/AMMetaDataParserService( 2931): getResourceTypeNamelayout
I/AMMetaDataParserService( 2931): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2931): Resource data:2131034112
I/AMMetaDataParserService( 2931): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 2931): getResourceTypeNamexml
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 3208): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3208):  
I/ActivityManager(  772): Killing 1695:com.fmm.dm/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2931): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,I/SELinux ( 3208): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3208):  
I/SELinux ( 3208):  
,I/SELinux ( 3208): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3208): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3208): >>>>> Normal User
,E/dalvikvm( 3208): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
,E/SELinux ( 3208): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 2931): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
,D/TimaKeyStoreProvider( 3208): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3208): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3208): Added TimaKesytore provider
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 2931): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,I/ActivityManager(  772): Killing 2252:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
,D/SensorService(  772):   -0.1 -0.1 9.6
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  772): waitForAlarm result :8
V/AlarmManager(  772): ClockReceiver onReceive() ACTION_TIME_TICK
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KeyguardViewMediator( 1065): handleKeyguardDoneDrawing
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/StatusChecker( 3208): onReceive : android.intent.action.BOOT_COMPLETED
D/daemonapp( 1465): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 1465): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,I/ActivityManager(  772): Killing 2264:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #43
I/SELinux ( 3223): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3223):  
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 3223): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3223):  
I/SELinux ( 3223):  
,I/SELinux ( 3223): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3223): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3223): >>>>> Normal User
,E/dalvikvm( 3223): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10133 ]
,E/SELinux ( 3223): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector(  772): onPackageRemoved : com.example.hello
D/UsbSettingsManager(  772): clearDefaults: com.example.hello
,W/AtomicFile(  772): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,D/TimaKeyStoreProvider( 3223): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3223): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3223): Added TimaKesytore provider
W/AppWidgetServiceImpl(  772): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/SMD     (  241): DCD ON
,D/InputReader(  772): Processing first event
,W/ApplicationsProvider( 1414): Could not fetch usage stats
W/ApplicationsProvider( 1414): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1414): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1414): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1414): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1414): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1414): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1414): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1414): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1414): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1414): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1414): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1414): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/CustomFrequencyManagerService(  772): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 772  tag : ACTIVITY_RESUME_BOOSTER@9

```
