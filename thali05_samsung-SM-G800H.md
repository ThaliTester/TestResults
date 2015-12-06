#### Test 502422853393492_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e7e8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e7e8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e7e8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x23, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2389): decode(66, 37547940, 5555)
V/MediaPlayerService(  250): decode(30, 37547940, 5555)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(30, 37547940, 5555)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03468, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f03468, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03468, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03468, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03468, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03468, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03468, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03468, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x24, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2389): decode(67, 30367732, 5085)
V/MediaPlayerService(  250): decode(33, 30367732, 5085)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x25, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2389): decode(68, 30372876, 21552)
V/MediaPlayerService(  250): decode(33, 30372876, 21552)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 30372876, 21552)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efeef0, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8efeef0, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efeef0, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efeef0, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efeef0, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/AudioPlayer(  250): First fillBuffer call!!
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efeef0, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efeef0, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efeef0, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x26, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2389): decode(69, 37543652, 4230)
V/MediaPlayerService(  250): decode(33, 37543652, 4230)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0acd0, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f0acd0, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0acd0, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0acd0, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  250): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0acd0, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0acd0, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0acd0, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0acd0, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x27, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2389): decode(70, 30337076, 9400)
V/MediaPlayerService(  250): decode(33, 30337076, 9400)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 30337076, 9400)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e7e8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
I/Process ( 2389): Sending signal. PID: 2389 SIG: 9
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e7e8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e7e8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e7e8, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  250): open(44100, 1, 0x0, 1, 4)
E/IMemory (  250): binder=0xb8f0a8b0 transaction failed fd=-2147483647, size=0, err=-32 (Broken pipe)
E/IMemory (  250): cannot dup fd=-2147483647, size=0, err=-32 (Bad file number)
E/IMemory (  250): cannot map BpMemoryHeap (binder=0xb8f0a8b0), size=0, fd=-1 (Bad file number)
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e7e8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() stop AudioSource since AudioPlayer not exist
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x28, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
--------- beginning of /dev/log/system
I/ActivityManager(  732): Process com.sec.android.app.shealth (pid 2389) (adj 0) has died.
I/SELinux ( 2463): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2463):  
I/SELinux ( 2463): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2463):  
I/SELinux ( 2463):  
I/SELinux ( 2463): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2463): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2463): >>>>> Normal User
E/dalvikvm( 2463): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 2463): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/ServiceManager(  285): Waiting for service AtCmdFwd...
D/TimaKeyStoreProvider( 2463): in addTimaSignatureService
D/TimaKeyStoreProvider( 2463): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2463): Added TimaKesytore provider
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=2463, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 2463): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences( 2463): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 2463): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 2463): ContentProvider is not null
V/MediaPlayer( 2463): decode(61, 33979084, 48105)
V/MediaPlayerService(  250): decode(33, 33979084, 48105)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 33979084, 48105)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0cdf8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f0cdf8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0cdf8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0cdf8, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0cdf8, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/AudioPlayer(  250): First fillBuffer call!!
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0cdf8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0cdf8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0cdf8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x29, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(63, 33914984, 10421)
V/MediaPlayerService(  250): decode(33, 33914984, 10421)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 33914984, 10421)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff168, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8eff168, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff168, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff168, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff168, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff168, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff168, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff168, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x2a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(64, 37457308, 34198)
V/MediaPlayerService(  250): decode(33, 37457308, 34198)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 37457308, 34198)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e308, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e308, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e308, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e308, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e308, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e308, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e308, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0e308, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x2b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(65, 33862452, 7405)
V/MediaPlayerService(  250): decode(33, 33862452, 7405)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 33862452, 7405)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03e10, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f03e10, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03e10, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03e10, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03e10, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03e10, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03e10, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f03e10, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x2c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(66, 37547940, 5555)
V/MediaPlayerService(  250): decode(33, 37547940, 5555)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d360, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  25,0): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d360, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d360, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d360, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d360, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/AudioPlayer(  250): First fillBuffer call!!
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d360, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d360, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d360, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x2d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(67, 30367732, 5085)
V/MediaPlayerService(  250): decode(33, 30367732, 5085)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f04dd0, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f04dd0, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f04dd0, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f04dd0, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f04dd0, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f04dd0, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f04dd0, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f04dd0, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x2e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(68, 30372876, 21552)
V/MediaPlayerService(  250): decode(33, 30372876, 21552)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 30372876, 21552)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d380, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d380, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d380, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d380, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d380, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d380, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d380, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d380, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x2f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(69, 37543652, 4230)
V/MediaPlayerService(  250): decode(33, 37543652, 4230)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efac68, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8efac68, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efac68, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efac68, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  250): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efac68, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
I/AudioPlayer(  250): First fillBuffer call!!
V/MediaPlayerService(  250): wait for playback complete
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efac68, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efac68, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8efac68, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x30, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(70, 30337076, 9400)
V/MediaPlayerService(  250): decode(33, 30337076, 9400)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 30337076, 9400)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d2c8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d2c8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d2c8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d2c8, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  250): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d2c8, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/SELinux ( 2531): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2531):  
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d2c8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d2c8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0d2c8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x31, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(71, 33925464, 44276)
V/MediaPlayerService(  250): decode(33, 33925464, 44276)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 33925464, 44276)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ffe0, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ffe0, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ffe0, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ffe0, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ffe0, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/AudioPlayer(  250): First fillBuffer call!!
I/SELinux ( 2531): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2531):  
I/SELinux ( 2531):  
I/SELinux ( 2531): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2531): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2531): >>>>> Normal User
E/dalvikvm( 2531): >>>>> com.sec.android.app.sns3 [ userId:0 | appId:10036 ]
E/SELinux ( 2531): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
D/TimaKeyStoreProvider( 2531): in addTimaSignatureService
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ffe0, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ffe0, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ffe0, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x32, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(72, 33885672, 29256)
V/MediaPlayerService(  250): decode(33, 33885672, 29256)
D/TimaKeyStoreProvider( 2531): Cannot add TimaSignature Service, License check Failed
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 33885672, 29256)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0f8f8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
D/ActivityThread( 2531): Added TimaKesytore provider
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f0f8f8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0f8f8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0f8f8, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0f8f8, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0f8f8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0f8f8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0f8f8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x33, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(73, 37491572, 52024)
V/MediaPlayerService(  250): decode(33, 37491572, 52024)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 37491572, 52024)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f10fe8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
D/SensorService(  732):   -0.1 -0.1 9.6
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f10fe8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f10fe8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f10fe8, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f10fe8, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f10fe8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f10fe8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f10fe8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x34, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(74, 33969800, 9226)
V/MediaPlayerService(  250): decode(33, 33969800, 9226)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 33969800, 9226)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer(  250): First fillBuffer call!!
V/AudioCache(  250): notify(0xb8f0ab28, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8f0ab28, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x35, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 2463): decode(75, 30402580, 4509)
V/MediaPlayerService(  250): decode(33, 30402580, 4509)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 30402580, 4509)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff128, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8eff128, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff128, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff128, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff128, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff128, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff128, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8eff128, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x36, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=2531, uid=10036 requires android.permission.INTERACT_ACROSS_USERS
I/Process ( 2531): Sending signal. PID: 2531 SIG: 9
I/ActivityManager(  732): Process com.sec.android.app.sns3 (pid 2531) (adj 0) has died.
I/SELinux ( 2574): F,unction: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2574):  
I/SELinux ( 2574): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2574):  
I/SELinux ( 2574):  
I/SELinux ( 2574): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2574): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2574): >>>>> Normal User
E/dalvikvm( 2574): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 2574): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 2574): in addTimaSignatureService
D/TimaKeyStoreProvider( 2574): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2574): Added TimaKesytore provider
I/ServiceManager(  285): Waiting for service AtCmdFwd...
I/SELinux ( 2594): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2594):  
I/SELinux ( 2594): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2594):  
I/SELinux ( 2594):  
I/SELinux ( 2594): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2594): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2594): >>>>> Normal User
E/dalvikvm( 2594): >>>>> com.sec.spp.push [ userId:0 | appId:10038 ]
E/SELinux ( 2594): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 2594): in addTimaSignatureService
D/TimaKeyStoreProvider( 2594): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2594): Added TimaKesytore provider
E/SPPClientService( 2594): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 2594): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 2594): PushLog.txt file is not deleted.
D/SPPClientService( 2594): PushLog.txt file is not deleted.
D/SPPClientService( 2594): ============PushLog. stop!
E/SPPClientService( 2594): [SystemStateMoniter] ACTION_BOOT_COMPLETED
I/SELinux ( 2612): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2612):  
I/SELinux ( 2612): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2612):  
I/SELinux ( 2612):  
I/SELinux ( 2612): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2612): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2612): >>>>> Normal User
E/dalvikvm( 2612): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 2612): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 2612): in addTimaSignatureService
D/TimaKeyStoreProvider( 2612): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2612): Added TimaKesytore provider
I/SA      ( 2612): [SSP] onCreated
I/SA      ( 2612): [TPM] There is no property file
I/SA      ( 2612): [SCU] isHaveSA() - false
I/SA      ( 2612): [TPM] getModelProperty : null
I/SA      ( 2612): [TPM] getCSCProperty : null
I/SA      ( 2612): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED
I/SA      ( 2612): [DM] init START
I/SA      ( 2612): [DM] This device is not a Vodafone
I/SA      ( 2612): [DM] getCountryCodeFromCSC : PL
I/SA      ( 2612): support phone number id : false
I/SA      ( 2612): [DM] init END
I/SA      ( 2612): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 2612): [BDLM] already registered in spp
I/SA      ( 2612): [OR] onReceive Intent=[ action_BOOT_COMPLETED ]
I/SA      ( 2612): [OR] onReceive END
I/SA      ( 2612): [BDC] create
I/SA      ( 2612): [DBMV2] getEmailID
I/SA      ( 2612): [DBMV2] getDataV02ForItems
I/SA      ( 2612): [SSP] query invoked
I/SA      ( 2612): [SCU] get signed id from samsung account2.0 DB.
I/SELinux ( 2633): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2633):  
I/SA      ( 2612): [SCU] get signed id from samsung account1.0 DB.
I/SA      ( 2612): [BDC] destroy
I/SELinux ( 2633): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2633):  
I/SELinux ( 2633):  
I/SELinux ( 2633): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2633): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2633): >>>>> Normal User
E/dalvikvm( 2633): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
E/SELinux ( 2633): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 2633): in addTimaSignatureService
D/TimaKeyStoreProvider( 2633): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2633): Added TimaKesytore provider
D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  732): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
D/AndroidRuntime( 2624): 
D/AndroidRuntime( 2624): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2624): CheckJNI is OFF
D/AndroidRuntime( 2624): setted country_code = Poland
D/AndroidRuntime( 2624): setted countryiso_code = PL
D/AndroidRuntime( 2624): setted sales_code = XEO
D/AndroidRuntime( 2624): readGMSProperty: start
D/AndroidRuntime( 2624): readGMSProperty: already setted!!
D/AndroidRuntime( 2624): readGMSProperty: end
D/AndroidRuntime( 2624): addProductProperty: start
D/dalvikvm( 2624): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2624): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2624): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2624): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2624): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=2633, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
D/MediaScannerReceiver( 1206): action: android.intent.action.BOOT_COMPLETED
E/memtrack( 2624): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 2624): failed to load memtrack module: -2
D/dalvikvm( 2624): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 2624): Calling main entry com.android.commands.am.Am
I/ServiceManager(  285): Waiting for service AtCmdFwd...
D/MediaScannerService( 1206): !@start scanning volume internal: [/system/media]
D/TP/MmsProvider( 1250): Update uri=content://mms, match=0
D/TP/MmsProvider( 1250): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1250): need read changed broadcast:false
I/Mms:transaction( 1726): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 1726): [start]    nonBlockingUpdateMessageIndicator()
I/Mms/ReservationManager( 1726): resetAfterConnected()
D/Mms/MessagingNotification( 1726): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1726): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1726): isDefault true
D/TP/MmsSmsProvider( 1250): match 7:Elapsed time : 4.190 ms
I/Mms/ReservationManager( 1726): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1250): match 200:Elapsed time : 1.372 ms
I/SELinux ( 2670): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2670):  
V/ApplicationPolicy(  732): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  732): mDVFSHelper.acquire()
I/SurfaceFlinger(  247): id=15 createSurf (1x1),1 flag=404, iello
D/MediaScanner( 1206): Prescan. DB items number : 156 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
E/SMD     (  241): DCD ON
I/SELinux ( 2670): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2670):  
I/SELinux ( 2670):  
I/SELinux ( 2670): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2670): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2670): >>>>> Normal User
E/dalvikvm( 2670): >>>>> com.sec.android.app.safetyassurance [ userId:0 | appId:10050 ]
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
E/SELinux ( 2670): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 2670): in addTimaSignatureService
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 2670): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2670): Added TimaKesytore provider
V/MediaScanner( 1206): processDirectory :  /system/media
V/MediaScanner( 1206):  prescan time: 141ms (DB items: 156)
V/MediaScanner( 1206):     scan time: 52ms (Caching mode: true), (makeEntry time: 24ms ~46%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1206): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1206):    total time: 193ms
V/MediaScanner( 1206): checked files: 149  directories : 5  (I: 0, U: 0)
D/MediaScanner( 1206): checkDefaultSounds
D/MediaScanner( 1206): system alarm_alert  : Vwiurug_etwofi5wgg
I/HarmonyEASService(  732): Updating for all 1
I/WindowManager(  732): Screenshot max retries 4 of Token{42d897c8 ActivityRecord{42524ee8 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42dcad70 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
W/WindowManager(  732): Screenshot failure taking screenshot for (720x1280) to layer 21005
D/LockPatternUtils( 1068): isPcwEnable = null
D/Mms/TelephonyPermission( 1726): isDefault true
D/Mms/SmsReceiverService( 1726): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 1726): [start]    handleBootCompleted()
D/AndroidRuntime( 2624): Shutting down VM
D/dalvikvm( 2624): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 2683): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2683):  
D/Launcher.HomeView( 1254): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1453): [237392/5] Surface widget pause on instance = 1
D/accuweather( 1453): [KK AccuPhone]>>> SWW:224 [0:0] [SWW] onPause : instance = 1
D/accuweather( 1453): [KK AccuPhone]>>> SWW:239 [0:0] onPause : size = 0
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1453): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 1453): [KK AccuPhone]>>> SWW:517 [0:0]  unRegisterTTReceiver !! 
D/MediaScanner( 1206): OK. alarm_alert is already exist in setting DB.
E/ActivityThread( 1844): Performing stop of activity that is not resumed: {com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover}
E/ActivityThread( 1844): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover}
E/ActivityThread( 1844): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3536)
E/ActivityThread( 1844): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3623)
E/ActivityThread( 1844): 	at android.app.ActivityThread.access$1200(ActivityThread.java:172)
E/ActivityThread( 1844): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1335)
E/ActivityThread( 1844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1844): 	at android.os.Looper.loop(Looper.java:146)
E/ActivityThread( 1844): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/ActivityThread( 1844): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread( 1844): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread( 1844): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/ActivityThread( 1844): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/ActivityThread( 1844): 	at dalvik.system.NativeStart.main(Native Method)
D/MediaScanner( 1206): system notification_sound  : K_Oprkltf5wgg
D/Launcher( 1254): onTrimMemory. Level: 20
D/accuweather( 1453): [KK AccuPhone]>>> WR:149 [0:0] onPause
D/accuweather( 1453): [KK AccuPhone]>>> SM:526 [0:0] onPause
,D/SurfaceWidgetView( 1254): destroyHardwareResources():1126113696
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/MediaScanner( 1206): OK. notification_sound is already exist in setting DB.
D/MediaScanner( 1206): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/TP/MmsSmsProvider( 1250): deleteConversation threadId: 9223372036854775806
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/TP/MmsSmsProvider( 1250): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
I/SELinux ( 2683): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2683):  
I/SELinux ( 2683):  
I/SELinux ( 2683): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2683): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2683): >>>>> Normal User
E/dalvikvm( 2683): >>>>> com.example.hello [ userId:0 | appId:10180 ]
E/SELinux ( 2683): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/BadgeProvider( 1342): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/TP/MmsSmsProvider( 1250): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1250): need read changed broadcast:false
D/Mms/Conversation( 1726): deleteTempConversation(),deleted=0
D/TimaKeyStoreProvider( 2683): in addTimaSignatureService
W/dalvikvm( 2670): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
D/TimaKeyStoreProvider( 2683): Cannot add TimaSignature Service, License check Failed
D/SmsProvider( 1250): Update uri=content://sms/outbox, match=8
D/ActivityThread( 2683): Added TimaKesytore provider
D/Launcher.Model( 1254): reloadBadges entered.
D/BadgeProvider( 1342): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1342): sendNotify, [notify] : null
D/BadgeProvider( 1342): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1342): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1342): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 1726): setBadgeCount(), count=0
D/TP/MmsSmsProvider( 1250): need read changed broadcast:false
D/MessagingNotification( 1726): remove alarm
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/LockPatternUtils( 1068): isPcwEnable = null
D/Mms/SmsReceiverService( 1726): sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 1726): [SIM-1]sendFirstQueuedMessage()
D/Mms/MessagingNotification( 1726): updateAllHistoryAsRead()
D/Mms/MessagingNotification( 1726): [end]    nonBlockingUpdateMessageIndicator()
D/SafetyAssuranceAppFeatures( 2670): init start
I/SafetyAssuranceAppFeatures( 2670): mLoadBaiduMap:false
I/SafetyAssuranceAppFeatures( 2670): mFeatureEnableMultiSim true
D/SafetyAssuranceAppFeatures( 2670): init end
D/Mms/MessagingNotification( 1726): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1726): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1726): isDefault true
D/SafetyAssuranceReceiver( 2670): onReceive
I/SafetyAssuranceApp( 2670): Acquire WL
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=2683, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
D/SafetyAssuranceConfig( 2670): getAppState : 1
D/SafetyAssuranceReceiver( 2670): onReceive - action:android.intent.action.BOOT_COMPLETED, currentAppState:1
D/SafetyAssuranceReceiver( 2670): Init App state
D/TP/MmsSmsProvider( 1250): match 200:Elapsed time : 3.821 ms
D/dalvikvm(  732): GC_EXPLICIT freed 2867K, 19% free 22583K/27564K, paused 7ms+11ms, total 150ms
D/MediaScanner( 1206): OK. ringtone is already exist in setting DB.
W/BackupManagerService(  732): dataChanged but no participant pkg='com.android.providers.settings' uid=10050
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=2683, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
D/SafetyAssuranceConfig( 2670): setAppState : 1
D/SafetyAssuranceApp( 2670): topActivity's name is=.MainActivity
D/MediaScanner( 1206): system ringtone_2  : Wmfi_lpf_pwirywu5wgg
I/SafetyAssuranceApp( 2670): Release WL
,D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
,V/WebViewChromium( 2683): Binding Chromium to the background looper Looper (main, tid 1) {422c8430}
,I/chromium( 2683): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 2683): Initializing chromium process, renderers=0
D/MediaScanner( 1206): OK. ringtone_2 is already exist in setting DB.
D/MediaScanner( 1206): system notification_sound_2  : K_Oprkltf5wgg
D/MediaScanner( 1206): OK. notification_sound_2 is already exist in setting DB.
,D/MediaScannerService( 1206): !@done scanning volume internal
,D/MediaScannerService( 1206): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,I/Adreno-EGL( 2683): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2683): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2683): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2683): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2683): Remote Branch: 
I/Adreno-EGL( 2683): Local Patches: 
I/Adreno-EGL( 2683): Reconstruct Branch: 
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter started
,W/chromium( 2683): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/NetworkStatusReceiver( 1250): action: android.intent.action.BOOT_COMPLETED
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/BadgeProvider( 1342): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/NearbySettings( 1321): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 1321): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 1321): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,V/NearbySettings( 1321): MountReceiver.mPrefHandler - 7002
I/NearbySettings( 1321): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,I/NearbySettings( 1321): MountReceiver.onReceive - Internal Path
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 1206): Prescan. DB items number : 20 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/Launcher.Model( 1254): reloadBadges entered.
D/BadgeProvider( 1342): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1342): sendNotify, [notify] : null
,D/BadgeProvider( 1342): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1342): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1342): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 1726): setBadgeCount(), count=0
I/dalvikvm( 2683): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2683): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/MessagingNotification( 1726): remove alarm
,D/dalvikvm( 2683): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2683): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2683): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 2683): VFY: replacing opcode 0x6e at 0x0008
,I/AccessibilityManagerService(  732): setmDNIeNegative (false)
W/dalvikvm( 2683): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2683): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2683): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2683): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2683): VFY: replacing opcode 0x6f at 0x001a
D/Mms/MessagingNotification( 1726): updateAllHistoryAsRead()
W/dalvikvm( 2683): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2683): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2683): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2683): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2683): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2683): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2683): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2683): CordovaWebView is running on device made by: samsung
D/Mms/SmsReceiverService( 1726): [end]    handleBootCompleted()
V/MediaScanner( 1206): processDirectory :  /storage/emulated/0
D/MediaScanner( 1206): Skipping:
D/MediaScanner( 1206): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1206): Skipping:
,D/MediaScanner( 1206): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1206): processDirectory :  /storage/extSdCard
W/MediaScanner( 1206): Error opening directory, reason : Permission denied.
,W/MediaScanner( 1206): 7klwibgf7fxlKdCbid7
,I/iu.UploadsManager( 1644): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,E/File    ( 1206): fail readDirectory() errno=2
,V/MediaScanner( 1206): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@426bf620
,V/MediaScanner( 1206): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@426bf620
V/MediaScanner( 1206):  prescan time: 54ms (DB items: 20)
V/MediaScanner( 1206):     scan time: 31ms (Caching mode: true), (makeEntry time: 19ms ~61%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1206): postscan time: 8ms (bulkDeleter : 0), (delete DeadThumbnail time : 5ms)
V/MediaScanner( 1206):    total time: 93ms
V/MediaScanner( 1206): checked files: 3  directories : 17  (I: 0, U: 0)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=16 createSurf (720x1280),1 flag=404, NainActivit
D/MediaScannerService( 1206): !@done scanning volume external
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/MediaScannerService( 1206): send command to ssrm : REQ_DROP_CACHE
,I/HWUI    ( 2683): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 2683): Enabling debug mode 0
,W/AwContents( 2683): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetView( 1254): destroyHardwareResources():1126113696
D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  732): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=15 Removed iello (10/13)
,I/SurfaceFlinger(  247): id=15 Removed iello (-2/13)
,D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  247): id=9 Removed Mauncher (8/12)
I/SurfaceFlinger(  247): id=9 Removed Mauncher (-2/12)
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (8/11)
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (-2/11)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/iu.UploadsManager( 1644): End new media; added: 0, uploading: 0, time: 133 ms
,W/Settings( 1321): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/SettingSearch/SearchIntentReceiver( 1321): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1321): search setting db init!!
,I/SettingSearch/SearchIntentReceiver( 1321): BOOT_COMPLETED call InitSerachDBThread thread start!
,W/Atfwd_Sendcmd(  285): AtCmdFwd service not published, waiting... retryCnt : 3
W/ContextImpl( 1321): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:40 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:60 
,I/SELinux ( 2740): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2740):  
,D/PhoneNumberLocatorBootCompletedReceiver( 1250): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1250): Phone number locator feature is dsiabled
,W/BackupManagerService(  732): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
,I/BootupListener( 1250): mPendingNetworkManualSelection : false
,D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
,I/ManualSelectionReceiver( 1250): onReceive : Intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.phone/.ManualSelectionReceiver (has extras) }
,I/SELinux ( 2744): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2744):  
,I/SELinux ( 2740): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2740):  
I/SELinux ( 2740):  
,I/SELinux ( 2740): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2740): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2740): >>>>> Normal User
,E/dalvikvm( 2740): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10160 ]
,E/SELinux ( 2740): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 2740): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2740): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2740): Added TimaKesytore provider
,I/SELinux ( 2744): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2744):  
I/SELinux ( 2744):  
,I/SELinux ( 2744): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2744): >>>>> Normal User
,E/dalvikvm( 2744): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
,E/SELinux ( 2744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2744): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2744): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2744): Added TimaKesytore provider
,I/chromium( 2683): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=2740, uid=10160 requires android.permission.INTERACT_ACROSS_USERS
,I/chromium( 2683): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/DBG_DM  ( 2744): [][Line:95][onCreate] 
E/DBG_DM  ( 2744): BootingfileStream is null
,E/DBG_DM  ( 2744): xdmCreateBootingFilestream
,E/libGLESv2( 2683): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,E/libGLESv2( 2683): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,I/DBG_DM  ( 2744): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DM  ( 2744): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
I/DBG_DM  ( 2744): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
,I/DBG_DM  ( 2744): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
,I/chromium( 2683): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,I/DBG_DM  ( 2744): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
,E/AndroidProtocolHandler( 2683): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/DBG_DM  ( 2744): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
,I/DBG_DM  ( 2744): [3.19.140541][Line:36][onCreate] myUserId : 0
,I/DBG_DM  ( 2744): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 0
,I/DBG_DM  ( 2744): [3.19.140541][Line:2702][xdmdbsqlGetDownloadPostponeStatus] xdbsqlGetDownloadPostponeStatus : 0
,I/DBG_DM  ( 2744): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
,D/JsMessageQueue( 2683): Set native->JS mode to OnlineEventsBridgeMode
,I/DBG_DM  ( 2744): [3.19.140541][Line:99][onCreate] DMApplication NOT Start !
,I/DBG_DM  ( 2744): [3.19.140541][Line:139][onReceive] android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1068): onReceive() getAction : android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1068): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1068): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1068): isSafeMode = false
,D/LocationManagerService(  732): getProviders()=[passive]
,E/libGLESv2( 2683): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,E/libGLESv2( 2683): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,E/Tethering(  732): No numeric data
I/ConnectivityService(  732): defaultVal : 1, tetherEnabledInSettings : true
,E/Tethering(  732): No numeric data
D/dalvikvm( 2683): Trying to load lib /data/app-lib/com.example.hello-3/libjxcore.so 0x425ef098
E/Tethering(  732): No numeric data
E/Tethering(  732): No numeric data
E/Tethering(  732): No numeric data
,E/Tethering(  732): No numeric data
I/ConnectivityService(  732): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  732): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  732): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  732): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  732): defaultVal : 1, tetherEnabledInSettings : true
,I/ContactAccountLoggerTas( 2140): canRun() : Opted Out
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PowerManagerService(  732): [s] UserActivityState : 1 -> 0
,I/PowerManagerService(  732): [PWL] On : 0 (39582 ms ago)
I/PowerManagerService(  732): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  732): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1068, ws=null) (elapsedTime=18547)
,D/DisplayPowerController(  732): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  (  732): lcd : 6 +
D/PowerManagerService(  732): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/dalvikvm( 2683): Added shared lib /data/app-lib/com.example.hello-3/libjxcore.so 0x425ef098
D/jxcore_app_log( 2683): JniHelper::setJavaVM(0x4171a528), pthread_self() = 2028402160
,D/JX-Cordova( 2683): jxcore cordova android initializing
,W/GAV2    ( 2140): Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/lights  (  732): lcd : 6 -
,D/lights  (  732): lcd : 2 +
D/RampAnimator(  732): Light Animator Finished currentValue=2
,W/GAV2    ( 2140): Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.ssrm.u.i:-1 com.android.server.ssrm.ai.run:-1 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 
,D/lights  (  732): lcd : 2 -
,E/Tethering(  732): No numeric data
,E/Tethering(  732): No numeric data
I/ConnectivityService(  732): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  732): defaultVal : 1, tetherEnabledInSettings : true
,E/Tethering(  732): No numeric data
,I/ContactAccountLoggerTas( 2140): canRun() : Opted Out
,W/dalvikvm( 2140): method Lcom/google/android/search/core/state/QueryState;.a incorrectly overrides package-private method with same name in Lcfl;
,E/Tethering(  732): No numeric data
,V/NFC     ( 1321): this device does not have NFC support
,V/NFC     ( 1321): this device does not have NFC support
I/ConnectivityService(  732): defaultVal : 1, tetherEnabledInSettings : true
,I/ConnectivityService(  732): defaultVal : 1, tetherEnabledInSettings : true
V/NFC     ( 1321): this device does not have NFC support
V/NFC     ( 1321): this device does not have NFC support
,V/VibratorService(  732): hasVibrator - useVibetonz: false
,D/WifiDisplayAdapter(  732): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService(  732): getStreamVolume 3 index 0
,I/MediaRouter( 2140): Found default route: MediaRouter.RouteInfo{ uniqueId=android/kb:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  732): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/jxcore-log( 2683): Initializing JXcore engine
,W/jxcore-log( 2683): JXcore engine is ready
,D/SSRMv2:SIOP(  732): SIOP:: AP = 330, Delta = 10
D/LockPatternUtils( 1068): isPcwEnable = null
,W/jxcore-log( 2683): Starting JXcore engine
,D/SensorService(  732):   -0.0 -0.1 9.6
,D/WifiDisplayAdapter(  732): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 2790): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2790):  
,D/dalvikvm(  248): GC_EXPLICIT freed 44K, 51% free 9506K/19044K, paused 3ms+3ms, total 30ms
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9506K/19044K, paused 2ms+3ms, total 21ms
,I/SELinux ( 2790): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2790):  
I/SELinux ( 2790):  
,I/SELinux ( 2790): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2790): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2790): >>>>> Normal User
,E/dalvikvm( 2790): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 2790): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9506K/19044K, paused 1ms+3ms, total 22ms
,D/TimaKeyStoreProvider( 2790): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2790): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2790): Added TimaKesytore provider
,I/LockPatternUtils( 1321): isSmartCardAuthenticationAvailable: false
,D/UserAnalysis.PlaceProvider( 2790): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 2790): Create SecureDbHelper
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=2790, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
,I/SQLiteSecureOpenHelper( 2790): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2790): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2790): Open Place.db in secure mode
,W/jxcore-log( 2683): Platform android
W/jxcore-log( 2683): 
,W/jxcore-log( 2683): Process ARCH arm
W/jxcore-log( 2683): 
,I/jxcore-log( 2683): JXcore Cordova bridge is ready!
I/jxcore-log( 2683): 
,W/jxcore-log( 2683): JXcore engine is started
I/ActivityManager(  732): Waited long enough for: ServiceRecord{4305d030 u0 com.google.android.gms/.gcm.GcmService}
,V/VibratorService(  732): hasVibrator - useVibetonz: false
,I/SQLiteSecureOpenHelper( 2790): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2790): ...getDatabaseLocked(b,b,pwd)
,I/SQLiteSecureOpenHelper( 2790): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2790): getDatabaseLocked(b,b,pwd)...
,D/UserAnalysis.CarAnalyzer( 2790): Create SecureDbHelper
,I/SQLiteSecureOpenHelper( 2790): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2790): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2790): Open Place.db in secure mode
,E/jxcore-log( 2683): >> samsung-SM-G800H
E/jxcore-log( 2683): 
,I/jxcore-log( 2683): Total memory 1454641152
I/jxcore-log( 2683): 
I/jxcore-log( 2683): Free memory 435769344
I/jxcore-log( 2683): 
I/jxcore-log( 2683): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2683): 
,I/jxcore-log( 2683): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2683): 
,I/jxcore-log( 2683): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2683): 
,I/jxcore-log( 2683): Size 720 1280
I/jxcore-log( 2683): 
,I/jxcore-log( 2683): Screen Brightness 134
I/jxcore-log( 2683): 
,E/jxcore-log( 2683): Dummy Error Log.
E/jxcore-log( 2683): 
,I/LockPatternUtils( 1321): isSmartCardAuthenticationAvailable: false
,I/SQLiteSecureOpenHelper( 2790): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2790): ...getDatabaseLocked(b,b,pwd)
,I/SELinux ( 2803): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2803):  
,I/SELinux ( 2803): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2803):  
I/SELinux ( 2803):  
,I/SELinux ( 2803): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2803): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2803): >>>>> Normal User
,E/dalvikvm( 2803): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 2803): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2803): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2803): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2803): Added TimaKesytore provider
,I/SettingSearch/SearchIntentReceiver( 1321): InitSerachDBThread thread end!
W/ContextImpl( 1321): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:129 <bottom of call stack> 
,I/sCloudBackupApp( 2803): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SELinux ( 2816): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2816):  
,I/SELinux ( 2816): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2816):  
I/SELinux ( 2816):  
,I/SELinux ( 2816): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2816): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2816): >>>>> Normal User
,E/dalvikvm( 2816): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 2816): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2816): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2816): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2816): Added TimaKesytore provider
,I/jxcore-log( 2683): getBuffer is called!!!!
I/jxcore-log( 2683): 
,W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=2816, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 2832): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2832):  
,W/BackupManagerService(  732): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/BackupManagerService(  732): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
,D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
,I/SELinux ( 2832): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2832):  
I/SELinux ( 2832):  
,I/SELinux ( 2832): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2832): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2832): >>>>> Normal User
,E/dalvikvm( 2832): >>>>> com.wssnps [ userId:0 | appId:1000 ]
,E/SELinux ( 2832): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2832): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2832): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2832): Added TimaKesytore provider
,D/NPS_WSSNPS( 2832): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2832): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.wssnps.smlNpsReceiver.onReceive:380 android.app.ActivityThread.handleReceiver:2698 
D/NPS_WSSNPS( 2832): [] Service onCreate!!
,I/SELinux ( 2844): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2844):  
,D/NPS_WSSNPS( 2832): [] NpsServiceTask Start
,I/NPS_WSSNPS( 2832): [44.140541] loadCryptionkeyLibrary
,I/NPS_WSSNPS( 2832): [44.140541] FirstLoad Or Not Exist
,D/dalvikvm( 2832): Trying to load lib /data/data/com.wssnps/files/libCryptionkey.so 0x425eb7c0
,D/dalvikvm( 2832): Added shared lib /data/data/com.wssnps/files/libCryptionkey.so 0x425eb7c0
,D/NPS_WSSNPS( 2832): [44.140541] smlDBHelper
,I/NPS_WSSNPS( 2832): [44.140541] AsyncBulkFlagCheck
E/SMD     (  241): DCD ON
,I/NPS_WSSNPS( 2832): [44.140541] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 2832): [44.140541] IsRemain_Asyncing nothing
I/SELinux ( 2844): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2844):  
I/SELinux ( 2844):  
,I/SELinux ( 2844): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2844): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2844): >>>>> Normal User
,E/dalvikvm( 2844): >>>>> com.samsung.android.app.accesscontrol [ userId:0 | appId:10064 ]
,D/NPS_WSSNPS( 2832): [44.140541] Service onDestroy
,E/SELinux ( 2844): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/NPS_WSSNPS( 2832): [44.140541] smlBRConfigurationDelete
,I/NPS_WSSNPS( 2832): [44.140541] smlBRMessageDelete
,I/NPS_WSSNPS( 2832): [44.140541] smlBREmailDelete
,I/NPS_WSSNPS( 2832): [44.140541] smlBRNetworkDelete
,I/NPS_WSSNPS( 2832): [44.140541] smlBRCallLogDelete
,W/ContextImpl( 2832): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 com.wssnps.smlNpsService$1.run:108 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/NPS_WSSNPS( 2832): [44.140541] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 2832): [44.140541] smlBRPenMemoMDelete
,D/PowerManagerService(  732): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=1068 (0x0)
I/PowerManagerService(  732): Nap time...
,D/PowerManagerService(  732): [s] WAKEFULNESS_NAPPING
I/PowerManagerService(  732): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService(  732): Going to sleep due to screen timeout...
D/PowerManagerService(  732): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController(  732): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController(  732): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/Sensors (  732): LightSensor enable = 0
,D/Sensors (  732): LightSensor enableSensor = 0
,D/DisplayPowerController(  732): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/SensorManager(  732): unregisterListener ::   
D/TimaKeyStoreProvider( 2844): in addTimaSignatureService
I/Sensors (  732): HAL:resetDataRates mEnabled=4
I/NPS_WSSNPS( 2832): [44.140541] smlBRSMemoDelete
D/TimaKeyStoreProvider( 2844): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2844): Added TimaKesytore provider
D/SensorManager(  732): unregisterListener ::   
I/NPS_WSSNPS( 2832): [44.140541] cpuBooster release : false
D/NPS_WSSNPS( 2832): [44.140541] dsServerSocket close
,I/SELinux ( 2864): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2864):  
,I/SurfaceFlinger(  247): id=17 createSurf (720x1280),-1 flag=20004, FlectronBea
D/PackageManager(  732): [MSG] MCS_UNBIND
I/PackageManager(  732): calling disconnectService()
D/PackageManager(  732): Trying to unbind to DefaultContainerService
,D/DisplayPowerController(  732): !@ElectronBeam entry
I/SELinux ( 2864): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2864):  
I/SELinux ( 2864):  
I/SELinux ( 2864): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2864): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2864): >>>>> Normal User
E/dalvikvm( 2864): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
E/SELinux ( 2864): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2864): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2864): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2864): Added TimaKesytore provider
,D/FileShare-Server( 2864): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,D/AmoledAdjustTimer(  732): prevTemp = 286, currTemp = 289, prevStep = 4, currStep = 4
,I/SELinux ( 2882): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2882):  
I/ActivityManager(  732): Killing 1287:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #43
,D/lights  (  732): lcd : 0 +
,I/SELinux ( 2882): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2882):  
I/SELinux ( 2882):  
,I/SELinux ( 2882): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/lights  (  732): lcd : 0 -
E/SELinux ( 2882): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 2882): >>>>> Normal User
D/MISC PowerHAL(  732): miscpower_set_interactive: /sys/class/input/input1/enabled
E/dalvikvm( 2882): >>>>> com.sec.android.nearby.mediaserver [ userId:0 | appId:10070 ]
D/MISC PowerHAL(  732): sysfs_write +: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL(  732): sysfs_write -: /sys/class/input/input1/enabled: 0
,D/MISC PowerHAL(  732): miscpower_set_interactive: /sys/class/input/input6/enabled
,D/MISC PowerHAL(  732): sysfs_write +: /sys/class/input/input6/enabled: 0
D/MISC PowerHAL(  732): sysfs_write -: /sys/class/input/input6/enabled: 0
,D/MISC PowerHAL(  732): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,V/WindowOrientationListener(  732): WindowOrientationListener disabled
E/SELinux ( 2882): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/SensorService(  732): AutoRotationSensor::activate (ident=0x783af8f0, enabled=0)
,I/Sensors (  732): HAL: batch Dry Run is complete
D/MISC PowerHAL(  732): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  732): Got set_interactive hint
,D/KeyguardViewMediator( 1068): onScreenTurnedOff(3)
D/PowerManagerService(  732): blankAllDisplays() is called.
D/PowerManagerService(  732): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService(  732): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  732): [PWL] sb release: PowerManagerService.Display
,D/PowerManagerService(  732): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceFlinger(  247): Screen released, type=0 flinger=0xb8a5a980
D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
I/Sensors (  732): HAL:resetDataRates mEnabled=4
D/KeyguardViewMediator( 1068): notifyScreenOffLocked
E/KeyguardViewMediator( 1068): resetStateLocked
D/KeyguardViewMediator( 1068): handleNotifyScreenOff
D/KeyguardViewManager( 1068): onScreenTurnedOff()
D/KeyguardHostView( 1068): screen off, instance 4258c520 at 41413
D/LockPatternUtils( 1068): isPcwEnable = null
V/KeyguardHostView( 1068): showPrimarySecurityScreen(turningOff=true)
I/MDPP    ( 1068): Property: Empty
D/KeyguardHostView( 1068): showSecurityScreen(None)
D/SecCameraShortcut( 1068): onScreenTurnedOff
D/SensorManager( 1068): unregisterListener ::   
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
D/SensorManager(  732): unregisterListener ::   
D/InputDispatcher(  732): setInputDispatchMode: enabled=0, frozen=0
D/VisualEffectParticleEffect( 1068): KeyguardEffectViewParticleSpace : screenTurnedOff
D/VisualEffectParticleEffect( 1068): clearEffect
D/PersonaManager( 1068): isKioskContainerExistOnDevice
D/KeyguardViewMediator( 1068): Kiosk container not exists on device or sim lock exists.
D/KeyguardViewMediator( 1068): handleReset
D/KeyguardViewManager( 1068): reset()
D/KeyguardHostView( 1068): onSaveInstanceState, tstate=1
D/KeyguardGuestSelectorView( 1068): onDetachedFromWindow()
V/KeyguardUpdateMonitor( 1068): *** unregister callback for com.android.keyguard.CarrierText$1@42864860
V/KeyguardUpdateMonitor( 1068): *** unregister callback for com.android.keyguard.MSimCarrierText$1@42864c38
V/KeyguardUpdateMonitor( 1068): *** unregister callback for com.android.keyguard.CarrierText$1@428514c0
V/KeyguardUpdateMonitor( 1068): *** unregister callback for com.android.keyguard.EmergencyButton$1@42861668
D/TimaKeyStoreProvider( 2882): in addTimaSignatureService
D/TimaKeyStoreProvider( 2882): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2882): Added TimaKesytore provider
,D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  732): Excessive delay in blankDisplay() while turning screen off: 251ms
,I/libsuspend(  732): !@[s] autosuspend_autosleep_enable
,I/libsuspend(  732): !@[s] autosuspend_autosleep_enable done
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/PowerManagerService(  732): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 252ms
D/PowerManagerService(  732): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService(  732): [PWL] Off : 0s ago
I/PowerManagerService(  732): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  732): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  732): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=732, ws=null) (elapsedTime=240)
I/PowerManagerService(  732): [PWL]   PowerManagerService.Broadcasts: ref count=1
,I/WindowManager(  732): Screenshot max retries 4 of Token{431072f8 ActivityRecord{43107178 u0 com.example.hello/.MainActivity t3}} appWin=Window{42576fa8 u0 com.example.hello/com.example.hello.MainActivity} drawState=4
,V/KeyguardUpdateMonitor( 1068): *** unregister callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@42637708
W/WindowManager(  732): Screenshot failure taking screenshot for (720x1280) to layer 21010
,D/LightsService(  732): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 732) 
,I/SQLiteSecureOpenHelper( 2066): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2066): getDatabaseLocked(b,b,pwd)...
,I/SensorManagerA(  732): getReportingMode :: sensor.mType = 5
,D/LightsService(  732): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors (  732): LightSensor setDelay = 200000000
D/Sensors (  732): LightSensor setSensorDelay = 200000000
D/Sensors (  732): Light sensor flush: not enabled 0
D/Sensors (  732): LightSensor enable = 1
D/Sensors (  732): LightSensor enableSensor = 1
,D/SensorManager(  732): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/KeyguardUpdateMonitor( 1068): *** unregister callback for com.android.keyguard.KeyguardHostView$2@4258d970
,E/KeyguardHostView( 1068): KeyguardHostView()
,D/ContextualEventManager( 1068): setOnClickHandler()
D/BatteryService(  732): turn on LED for fully charged
,D/VibratorService(  732): JNI vibratorOff()
,V/KeyguardHostView( 1068): mIsMultipleLockOn is false
D/KeyguardHostView( 1068): mIsVoiceUnlockOn=false
,V/KeyguardHostView( 1068): Initial transport state: 1, pbstate=0
,I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
,D/LockPatternUtils( 1068): isPcwEnable = null
W/InputMethodManagerService(  732): Ignoring setImeWindowStatus of uid 1000 token: null
,D/ContextualEventContainer( 1068): ContextualEventContainer()
V/KeyguardUpdateMonitor( 1068): *** register callback for com.android.keyguard.KeyguardMessageArea$2@4257a918
,V/KeyguardUpdateMonitor( 1068): *** unregister callback for null
D/ContextualEventContainer( 1068): onFinishInflate()
,D/ContextualEventContainer( 1068): update()
D/STATUSBAR-NotificationService(  732): ACTION_SCREEN_OFF
D/LightsService(  732): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 732) 
,D/LightsService(  732): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LockPatternUtils( 1068): isPcwEnable = null
D/LockPatternUtils( 1068): isPcwEnable = null
D/audio_hw_primary(  250): adev_set_parameters: enter: screen_state=off
V/voice   (  250): voice_set_parameters: enter: screen_state=off
V/voice   (  250): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  250): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  250): platform_set_parameters: exit with code(-2)
V/audio_hw_primary(  250): adev_set_parameters: exit
D/LockPatternUtils( 1068): isPcwEnable = null
I/SecExternalDisplayIntents_Java(  732): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/KeyguardHostView( 1068): mIsFMMEnabled = false, mIsCarrierLockEnabled = false, mIsCarrierLockPlusEnabled = false
D/LockPatternUtils( 1068): isPcwEnable = null
V/KeyguardHostView( 1068): showPrimarySecurityScreen(turningOff=false)
D/IpRemoteDisplayController(  732): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  732): Bridge Server is not available
I/MDPP    ( 1068): Property: Empty
D/KeyguardHostView( 1068): showSecurityScreen(None)
V/KeyguardHostView( 1068): inflating id = 2130903095
D/SecuritySelectorView( 1068): explore by touch mode off
D/PersonaManagerService(  732): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler(  732): MSG_ACTION_SCREEN_OFF called
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
D/SecCameraShortcut( 1068): shortcutSetting:1
D/SecCameraShortcut( 1068): isKidsMode:false
D/SecCameraShortcut( 1068): isEmergencyMode:false
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/EmergencyButton( 1068): enabled = false, :0
,D/LockPatternUtils( 1068): isPcwEnable = null
,I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
,D/SecCameraShortcut( 1068): setCallback(): null
,D/KeyguardVoiceEngineThread( 1068): condition = 0
D/SecuritySelectorView( 1068): mIsAirViewEnabled =false
D/SecCameraShortcut( 1068): setCallback(): not null
D/SecuritySelectorView( 1068): hideBouncer mBouncerHelpText != null
D/SecCameraShortcut( 1068): setCallback(): not null
D/SecCameraShortcut( 1068): setCallback(): not null
D/SecuritySelectorView( 1068): hideBouncer mBouncerHelpText != null
D/KeyguardHostView( 1068): mKeyguardHelpOverlay : null
D/KeyguardHostView( 1068): AUTO_WIPE = false , IT Policy = false
D/ContextualEventManager( 1068): setOnClickHandler()
E/LSO     ( 1068): LSO Service is not yet ready!!!
V/KeyguardUpdateMonitor( 1068): *** register callback for com.android.keyguard.KeyguardHostView$2@42632d70
V/KeyguardUpdateMonitor( 1068): *** unregister callback for null
V/KeyguardHostView( 1068): music state changed: 0
D/KeyguardProperties( 1068): isIgnoreNationalRoaming() = false
D/VisualEffectCircleUnlockEffect( 1068): KeyguardEffectViewNone : Constructor
D/VisualEffectCircleUnlockEffect( 1068): screenWidth : 720
D/VisualEffectCircleUnlockEffect( 1068): screenHeight : 1280
D/VisualEffectCircleUnlockEffect( 1068): ratio : 0.6666667
D/VisualEffectCircleUnlockEffect( 1068): Constructor
D/VisualEffectCircleUnlockEffect( 1068): arrowImageId = 2130837796
D/VisualEffectCircleUnlockEffect( 1068): circleUnlockMaxWidth = 576
D/VisualEffectCircleUnlockEffect( 1068): circleUnlockMinWidth = 172
D/VisualEffectCircleUnlockEffect( 1068): outerStrokeWidth = 2
D/VisualEffectCircleUnlockEffect( 1068): innerStrokeWidth = 4
D/VisualEffectCircleUnlockEffect( 1068): lockSequenceTotal = 30
V/KeyguardUpdateMonitor( 1068): *** register callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@428614d8
V/KeyguardUpdateMonitor( 1068): *** unregister callback for null
I/AllShare(ASF-DMSLIB)( 2882): DMSReceiver.onReceive - android.intent.action.BOOT_COMPLETED
V/KeyguardUpdateMonitor( 1068): *** register callback for com.android.keyguard.MSimCarrierText$1@42aaf650
V/KeyguardUpdateMonitor( 1068): *** unregister callback for null
D/MSimCarrierText( 1068):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 0
D/CarrierText( 1068): getCarrierTextForSimState: status = Normal
D/CarrierText( 1068): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1068): updateCarrierText: text = 
D/CarrierText( 1068): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1068): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1068): updateCarrierText: text = 
D/MSimCarrierText( 1068):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 1
D/CarrierText( 1068): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1068): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1068): updateCarrierText: text = 
D/CarrierText( 1068): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1068): getCarrierTextForSimState: status = SimNotReady
D/MSimCarrierText( 1068): updateCarrierText: text = null
V/KeyguardUpdateMonitor( 1068): *** register callback for com.android.keyguard.EmergencyButton$1@42a770e8
V/KeyguardUpdateMonitor( 1068): *** unregister callback for null
D/LockPatternUtils( 1068): isPcwEnable = null
D/EmergencyButton( 1068): enabled = false, :0
D/SecCameraShortcut( 1068): setCallback(): not null
D/SecuritySelectorView( 1068): hideBouncer mBouncerHelpText != null
D/KeyguardViewManager( 1068): mWindowLayoutParams not null
D/KeyguardHostView( 1068): onRestoreInstanceState, transport=1
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 1068): KeyguardEffectViewParticleSpace : reset
W/BackupManagerService(  732): dataChanged but no participant pkg='com.android.providers.settings' uid=10070
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,I/SELinux ( 2904): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2904):  
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/ContextualEventContainer( 1068): handleUpdate()
,D/ContextualEventManager( 1068): getTopEventView()
,D/ContextualEventManager( 1068): getTopContextualEvent()
,D/ContextualEventManager( 1068): top view = flightmode
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1068): getTopEventClass()
D/ContextualEventManager( 1068): getTopContextualEvent()
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
D/ContextualEventManager( 1068): getTopContextualEvent()
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
I/ActivityManager(  732): Killing 1342:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
D/UsbManager( 1068):  :::: isUsb30Available :: return = false from pid = 1068
,I/SELinux ( 2904): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2904):  
I/SELinux ( 2904):  
,I/SELinux ( 2904): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2904): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2904): >>>>> Normal User
,E/dalvikvm( 2904): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 2904): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/Sensors (  732): LightSensor enable = 0
,D/Sensors (  732): LightSensor enableSensor = 0
D/SensorManager(  732): unregisterListener ::   
,D/lights  (  732): led_pattern : 5 +
,D/dalvikvm( 1068): GC_EXPLICIT freed 13154K, 32% free 31346K/46032K, paused 4ms+6ms, total 41ms
D/LightsService(  732): [SvcLED]  onSensorChanged::light value = 0
,D/lights  (  732): led_pattern : 5 -
,D/TimaKeyStoreProvider( 2904): in addTimaSignatureService
,D/LightsService(  732): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/TimaKeyStoreProvider( 2904): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2904): Added TimaKesytore provider
,D/dalvikvm(  732): GC_EXPLICIT freed 1479K, 18% free 22613K/27564K, paused 5ms+12ms, total 118ms
D/STATUSBAR-PhoneStatusBar( 1068): makeExpandedInvisible
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
D/PhoneStatusBarView( 1068): marqueeStatusBar:121, mClearCover:0
,D/SecContextualClockFlightMode( 1068): handleUpdateClock()
,D/KeyguardProperties( 1068): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SecKeyguardFlightModeView( 1068): received broadcast android.intent.action.SCREEN_OFF
,D/accuweather( 1453): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1453): [KK AccuPhone]>>> SWW:440 [0:0] stopRefreshIcon : 1
,D/accuweather( 1453): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/PowerManagerService(  732): [PWL] sb release: PowerManagerService.Broadcasts
,W/ContextImpl( 2904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:61 android.app.ActivityThread.handleReceiver:2698 
,D/SSRMv2:SIOP(  732): SIOP:: AP = 330, Delta = 0
,I/SELinux ( 2918): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2918):  
,I/SELinux ( 2918): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2918):  
I/SELinux ( 2918):  
,I/SELinux ( 2918): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2918): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2918): >>>>> Normal User
,E/dalvikvm( 2918): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
,E/SELinux ( 2918): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2918): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2918): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2918): Added TimaKesytore provider
,D/BluetoothBDAdrressReceiver( 2918): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2918): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
W/ContextImpl( 2918): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2930): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2930):  
,I/ActivityManager(  732): Killing 1276:com.android.printspooler/u0a144 (adj 15): empty #43
,D/BluetoothBDTestService( 1250): onCreate()
E/BluetoothBDTestService( 1250): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
,E/BluetoothBDTestService( 1250): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1250): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,I/SELinux ( 2930): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2930):  
I/SELinux ( 2930):  
,I/SELinux ( 2930): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2930): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2930): >>>>> Normal User
,E/dalvikvm( 2930): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 2930): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 2930): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2930): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2930): Added TimaKesytore provider
,W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=2930, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 2942): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2942):  
I/ActivityManager(  732): Killing 1774:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #43
,I/SELinux ( 2942): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2942):  
I/SELinux ( 2942):  
,I/SELinux ( 2942): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2942): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2942): >>>>> Normal User
,E/dalvikvm( 2942): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 2942): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2942): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2942): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2942): Added TimaKesytore provider
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2904): Resource data:2131165197
,I/AMMetaDataParserService( 2904): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2904): Resource data:2131165194
I/AMMetaDataParserService( 2904): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/AMMetaDataParserService( 2904): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,E/PersonaManagerService(  732): returning null in  getPersonasForUser
,I/SELinux ( 2955): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2955):  
I/ActivityManager(  732): Killing 1787:com.sec.modem.settings/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2904): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
V/AlarmManager(  732): waitForAlarm result :4
V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm(  248): GC_EXPLICIT freed 46K, 51% free 9506K/19044K, paused 3ms+3ms, total 31ms
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9506K/19044K, paused 2ms+3ms, total 21ms
,I/SELinux ( 2955): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2955):  
I/SELinux ( 2955):  
,I/SELinux ( 2955): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2955): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2955): >>>>> Normal User
,E/dalvikvm( 2955): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 2955): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9506K/19044K, paused 2ms+3ms, total 25ms
,I/AMMetaDataParserService( 2904): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,D/TimaKeyStoreProvider( 2955): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2955): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2955): Added TimaKesytore provider
,I/AMMetaDataParserService( 2904): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2904): Resource data:2131165194
I/AMMetaDataParserService( 2904): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/AMMetaDataParserService( 2904): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,I/AMMetaDataParserService( 2904): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,I/AMMetaDataParserService( 2904): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,W/BackupManagerService(  732): dataChanged but no participant pkg='com.android.providers.settings' uid=10084
,I/AMMetaDataParserService( 2904): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,I/AMMetaDataParserService( 2904): Resource data:2131165195
I/AMMetaDataParserService( 2904): getResourceName:com.sec.android.gallery3d:xml/device_filter
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2904): Resource data:2131165204
I/AMMetaDataParserService( 2904): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2904): Resource data:2131165204
I/AMMetaDataParserService( 2904): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2904): Resource data:2131165204
I/AMMetaDataParserService( 2904): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 2904): getResourceTypeNamexml
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 2904): Resource data:2131099676
,I/AMMetaDataParserService( 2904): getResourceName:com.android.mms:xml/spellscroll
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/AMMetaDataParserService( 2904): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2904): Resource data:2131099648
,I/AMMetaDataParserService( 2904): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/AMMetaDataParserService( 2904): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 2975): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2975):  
I/ActivityManager(  732): Killing 1799:com.sec.tcpdumpservice/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2904): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2904): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/SELinux ( 2975): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2975):  
I/SELinux ( 2975):  
,I/SELinux ( 2975): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2975): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2975): >>>>> Normal User
,E/dalvikvm( 2975): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
,E/SELinux ( 2975): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2904): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/TimaKeyStoreProvider( 2975): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2975): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2975): Added TimaKesytore provider
,I/AMMetaDataParserService( 2904): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2904): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2904): Resource data:2131099648
,I/AMMetaDataParserService( 2904): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/SELinux ( 2987): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2987):  
,I/AMMetaDataParserService( 2904): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
I/ActivityManager(  732): Killing 1831:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,I/ActivityManager(  732): Waited long enough for: ServiceRecord{43061320 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/AMMetaDataParserService( 2904): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 2987): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2987):  
I/SELinux ( 2987):  
,I/SELinux ( 2987): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2987): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2987): >>>>> Normal User
,E/dalvikvm( 2987): >>>>> com.dropbox.android [ userId:0 | appId:10091 ]
,I/AMMetaDataParserService( 2904): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,E/SELinux ( 2987): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 2987): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2987): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2987): Added TimaKesytore provider
,I/AMMetaDataParserService( 2904): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2904): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2904): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2904): Resource data:2131099648
I/AMMetaDataParserService( 2904): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/AMMetaDataParserService( 2904): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2904): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/com.dropbox.android.service.DropboxNetworkReceiver( 2987): Setting receiver enabled: false
,I/AMMetaDataParserService( 2904): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/AMMetaDataParserService( 2904): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/com.dropbox.sync.android.a( 2987): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/AMMetaDataParserService( 2904): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/com.dropbox.sync.android.aa( 2987): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800H armeabi-v7a; en_US))
,W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=2987, uid=10091 requires android.permission.INTERACT_ACROSS_USERS
,I/AMMetaDataParserService( 2904): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2904): Resource data:2131099648
,I/AMMetaDataParserService( 2904): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/SELinux ( 3008): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3008):  
I/ActivityManager(  732): Killing 1746:com.sec.android.app.mt/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2904): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2904): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 3008): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3008):  
I/SELinux ( 3008):  
,I/SELinux ( 3008): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3008): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3008): >>>>> Normal User
,E/dalvikvm( 3008): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 3008): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2904): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/TimaKeyStoreProvider( 3008): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3008): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3008): Added TimaKesytore provider
,I/AMMetaDataParserService( 2904): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2904): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=3008, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 3008): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 3008): ELMEngine.ELMEngine( context ).
,D/elm:14132( 3008): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 3008): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 3008): ElmAgentService : onCreate()
,D/elm:14132( 3008): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14132( 3008): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:14132( 3008): BootCompletedState : startBootCompleted() call
,D/elm:14132( 3008): ModuleBase.resetCalllogAPIAlarm()
,I/SELinux ( 3023): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3023):  
,D/elm:14132( 3008): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:14132( 3008): Get License : 0
,D/elm:14132( 3008): ElmAgentService : onDestroy().
I/ActivityManager(  732): Killing 1919:com.sec.phone/1001 (adj 15): empty #43
,I/AMMetaDataParserService( 2904): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2904): Resource data:2131099648
,I/AMMetaDataParserService( 2904): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/SELinux ( 3023): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3023):  
I/SELinux ( 3023):  
,I/SELinux ( 3023): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3023): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3023): >>>>> Normal User
,E/dalvikvm( 3023): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,I/AMMetaDataParserService( 2904): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,E/SELinux ( 3023): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3023): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3023): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3023): Added TimaKesytore provider
,I/AMMetaDataParserService( 2904): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,E/SMD     (  241): DCD ON
,I/AMMetaDataParserService( 2904): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/System.out( 2987): Thread-257(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 2987): Thread-257(ApacheHTTPLog):isShipBuild true
,I/System.out( 2987): Thread-257(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/AMMetaDataParserService( 2904): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 3040): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3040):  
,I/System.out( 2987): pool-4-thread-1 calls detatch()
I/ActivityManager(  732): Killing 2018:com.google.android.configupdater/u0a3 (adj 15): empty #43
,I/AMMetaDataParserService( 2904): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2904): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
I/SELinux ( 3040): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3040):  
I/SELinux ( 3040):  
,I/SELinux ( 3040): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3040): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3040): >>>>> Normal User
,E/dalvikvm( 3040): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,E/SELinux ( 3040): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2904): Resource data:2131099648
,I/AMMetaDataParserService( 2904): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 3040): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3040): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3040): Added TimaKesytore provider
,I/AMMetaDataParserService( 2904): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2904): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/CameraApp( 3040): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3040): Feature.Feature(context)
I/testFeature( 3040): Feature.readInternalDefaultXml()
,I/testFeature( 3040): ResetFeatureValue
,I/AMMetaDataParserService( 2904): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/CameraFirmware_broadcast( 3040): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 3040): CameraApp.getAppFeature()...
,I/SELinux ( 3054): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3054):  
,I/AMMetaDataParserService( 2904): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
I/ActivityManager(  732): Killing 2112:com.sec.dsm.system/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2904): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/SELinux ( 3054): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3054):  
I/SELinux ( 3054):  
,I/SELinux ( 3054): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3054): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3054): >>>>> Normal User
,E/dalvikvm( 3054): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 3054): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2904): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,D/TimaKeyStoreProvider( 3054): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3054): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3054): Added TimaKesytore provider
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2904): Resource data:2131099671
,I/AMMetaDataParserService( 2904): getResourceName:com.android.mms:xml/searchable
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
,D/PackageIntentReceiver( 3054): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3054): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager(  732): Killing 2148:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
,I/SELinux ( 3072): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3072):  
,D/dalvikvm( 2904): GC_CONCURRENT freed 4985K, 34% free 12702K/19044K, paused 3ms+3ms, total 45ms
,D/dalvikvm( 2904): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.GridSettings
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2904): Resource data:2131165216
,I/SELinux ( 3072): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3072):  
I/SELinux ( 3072):  
,I/SELinux ( 3072): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,E/SELinux ( 3072): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3072): >>>>> Normal User
,E/dalvikvm( 3072): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
,E/SELinux ( 3072): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/AMMetaDataParserService( 2904): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,D/TimaKeyStoreProvider( 3072): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3072): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3072): Added TimaKesytore provider
,I/AMMetaDataParserService( 2904): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.TimDataConnectionDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429159
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2904): Resource data:2131296695
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429159
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429144
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429144
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429144
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131297114
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ApnSettings
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ApnSettingsTabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429146
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429146
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429168
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/mirror_link_settings
,I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429159
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2904): Resource data:2131296695
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429159
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2904): Resource data:2131296695
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429144
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131297114
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/wifi_settings
,I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429159
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2904): Resource data:2131296695
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429159
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131296695
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429159
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2904): Resource data:2131296695
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429159
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2904): Resource data:2131296695
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429159
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2904): Resource data:2131296695
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429219
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429191
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429191
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429191
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429191
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429191
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429191
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2904): Resource data:2131298419
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429191
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2904): Resource data:2131298419
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/language_keyboard_settings_title
,I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429191
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131298419
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429176
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429176
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429173
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429173
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429172
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429172
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429182
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429173
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429186
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/AMMetaDataParserService( 2904): Resource data:2131429186
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429173
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131297804
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429173
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429228
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.users.UserOptions
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429128
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2904): Resource data:2131429128
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/application_settings
,W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=3072, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429128
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429127
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429127
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429128
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429128
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Laun,chApplication
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429127
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429127
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429128
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429153
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/location_settings
,I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429224
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.CarrierMatchSetting
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429224
I/GAV2    ( 2140): Thread[GAThread,5,main]: No campaign data found.
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131296750
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429224
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429123
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/privacy_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.CredentialStorage
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429224
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131296750
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring,
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429224
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131296750
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429187,
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429187
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131298587
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity,
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429187
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131298587
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429191
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429180
,I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/driving_mode
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern,
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock,
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity,
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429223
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429225
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429159
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
I/GAv4-SVC( 1644): Google Analytics 8.3.01 is starting up.
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131296695
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429165
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429225
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429223
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131297938
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429223
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131297938
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429161
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429163
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429167
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131296695
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429221
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429221
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429119
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429217
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429224
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429224
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429159
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429173
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429208
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429286
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429224
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429201
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429185
I/Babel   ( 3072): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3072): MmsConfig.loadMmsSettings
I/Babel   ( 3072): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
I/Babel   ( 3072): MmsConfig.loadFromDatabase
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429185
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131299843
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/power_saving_mode_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429185
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429185
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429222
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/power_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429186
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
,I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 2904): Resource data:1
W/ResourceType( 2904): No package identifier when getting name for resource number 0x00000001
W/System.err( 2904): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 2904): 	at android.content.res.Resources.getResourceName(Resources.java:3017)
W/System.err( 2904): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 2904): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 2904): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 2904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2904): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 2904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429199
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131301070
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429173
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131297804
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429203
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429193
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429194
E/Babel   ( 3072): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3072): MmsConfig.loadFromResources
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429206
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 2904): getResourceTypeNameid
E/Babel   ( 3072): canonicalizeMccMnc: invalid mccmnc nullnull
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131300118
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/Babel   ( 3072): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429196
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429260
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429197
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429291
W/Settings( 3072): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429228
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429199
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429199
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429199
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429199
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.NetworkManagement
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.MultiSimCardManagerPreference
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.NetworkManagementSetting
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.DualHelpActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.DualSoundRingtoneSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.RingtoneSettingTabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.IccLockTabSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429173
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429285
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429172
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131301505
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429203
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429203
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131302910
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429179
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2130838248
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2904): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429216
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429209
D/dalvikvm( 3072): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3072): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3072): VFY: replacing opcode 0x62 at 0x000a
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429209
D/dalvikvm( 3072): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3072): VFY: unable to resolve instance field 46
D/dalvikvm( 3072): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3072): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3072): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3072): VFY: replacing opcode 0x62 at 0x0047
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
D/dalvikvm( 3072): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 3072): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAlertDialogActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429177
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429212
D/dalvikvm( 3072): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42720010
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429213
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429153
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131302078
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429153
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131302078
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429153
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131302107
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429159
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429159
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429117
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429122
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429195
D/dalvikvm( 3072): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42720010
D/dalvikvm( 3072): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42720010, skipping init
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131297804
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429151
D/dalvikvm( 3072): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42720010
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/dalvikvm( 3072): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42720010
V/JNIHelp ( 3072): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/AMMetaDataParserService( 2904): Resource data:2131429204
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429204
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429195
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2130838300
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2904): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2130838300
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2904): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429202
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429202
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2904): Resource data:2131165381
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:xml/searchable
I/AMMetaDataParserService( 2904): getResourceTypeNamexml
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429124
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429187
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2904): Resource data:2131298587
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2904): getResourceTypeNamestring
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
V/Babel   ( 3072): babel boot account: thalitester@gmail.com
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
V/Babel   ( 3072): babel boot account: SMS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429198
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429258
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429220
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429220
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429276
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429276
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429148
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429242
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.KnoxSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429211
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2130838248
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2904): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2904): Resource data:2131429192
I/AMMetaDataParserService( 2904): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 2904): getResourceTypeNameid
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintOnehandGrip
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
I/SELinux ( 3107): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3107):  
I/ActivityManager(  732): Killing 2180:com.sec.kidsplat.installer/u0a158 (adj 15): empty #43
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2904): Resource data:2131034120
I/AMMetaDataParserService( 2904): getResourceName:com.android.contacts:xml/searchable
I/AMMetaDataParserService( 2904): getResourceTypeNamexml
I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
I/AMMetaDataParserService( 2904): Resource data:2131034113
I/AMMetaDataParserService( 2904): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 2904): getResourceTypeNamexml
I/SELinux ( 3107): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3107):  
I/SELinux ( 3107):  
I/SELinux ( 3107): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3107): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3107): >>>>> Normal User
E/dalvikvm( 3107): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 3107): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2904): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
D/TimaKeyStoreProvider( 3107): in addTimaSignatureService
D/dalvikvm( 3072): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42720010
D/dalvikvm( 3072): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42720010
D/dalvikvm( 3072): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42720010
D/dalvikvm( 3072): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42720010
D/TimaKeyStoreProvider( 3107): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3107): Added TimaKesytore provider
I/AMMetaDataParserService( 2904): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
I/AMMetaDataParserService( 2904): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
I/AMMetaDataParserService( 2904): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
I/AMMetaDataParserService( 2904): Resource data:2131034113
I/AMMetaDataParserService( 2904): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 2904): getResourceTypeNamexml
I/AMMetaDataParserService( 2904): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/SELinux ( 3121): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3121):  
I/ActivityManager(  732): Killing 2185:com.sec.factory/1000 (adj 15): empty #43
,I/ProviderInstaller( 3072): Installed default security provider GmsCore_OpenSSL
,I/AMMetaDataParserService( 2904): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
V/AlarmManager(  732): waitForAlarm result :4
V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager(  732): waitForAlarm result :4
V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/AMMetaDataParserService( 2904): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/SELinux ( 3121): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3121):  
I/SELinux ( 3121):  
,I/SELinux ( 3121): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3121): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3121): >>>>> Normal User
,E/dalvikvm( 3121): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
,E/SELinux ( 3121): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2904): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,D/TimaKeyStoreProvider( 3121): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3121): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3121): Added TimaKesytore provider
,I/AMMetaDataParserService( 2904): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 2904): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2904): Resource data:2131034112
I/AMMetaDataParserService( 2904): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/AMMetaDataParserService( 2904): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
,W/ContextImpl( 3121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
I/AMMetaDataParserService( 2904): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
,I/knox    ( 3121): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
,I/knox    ( 3121): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3121): KNOXAgentService : onCreate()
D/knox    ( 3121): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3121): KNOXAgentService. startJobThread() start
D/knox    ( 3121): KNOXAgentService. JobThread()
D/knox    ( 3121): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3121): KNOXAgentService. startJobThread() wait
,I/AMMetaDataParserService( 2904): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
,I/SELinux ( 3138): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3138):  
,D/knox    ( 3121): mKnoxAgentEngine.ELMEngine( context , reStart:true).
D/knox    ( 3121): KNOXAgentService : onDestroy().
,D/knox    ( 3121): ModuleBase.cancelAllAlarmManageModule()
,I/AMMetaDataParserService( 2904): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sams,ung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
I/AMMetaDataParserService( 2904): Resource data:2131034113
I/AMMetaDataParserService( 2904): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/AMMetaDataParserService( 2904): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/SELinux ( 3138): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3138):  
I/SELinux ( 3138):  
,I/SELinux ( 3138): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3138): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3138): >>>>> Normal User
,E/dalvikvm( 3138): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
E/SELinux ( 3138): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3138): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3138): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3138): Added TimaKesytore provider
,I/AMMetaDataParserService( 2904): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/dalvikvm( 2904): GC_CONCURRENT freed 2271K, 36% free 12371K/19044K, paused 1ms+2ms, total 28ms
,I/AMMetaDataParserService( 2904): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,E/KnoxSetupWizardClient( 3138): isShipMode : 1
,I/KnoxSetupWizardClient( 3138): onReceive : android.intent.action.BOOT_COMPLETED
,E/BluetoothManagerService(  732): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 2683): packageName : com.example.hello
I/WifiManager( 2683): setWifiEnabled : false
,I/WifiService(  732): setWifiEnabled: false pid=2683, uid=10180
,I/jxcore-log( 2683): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 2683): 
,I/jxcore-log( 2683): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2683): 
,W/System.err( 3138): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3138): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 3138): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 3138): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3138): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 3138): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
W/System.err( 3138): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/ActivityManager(  732): Waited long enough for: ServiceRecord{431184a8 u0 com.samsung.android.providers.context/.ContextService}
W/System.err( 3138): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
W/System.err( 3138): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 3138): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 3138): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3138): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 3138): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
W/System.err( 3138): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
W/System.err( 3138): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
D/ShortcutReceiver( 3138):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
I/AMMetaDataParserService( 2904): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
I/yash    ( 3138): setDisableWidget>size:0
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2904): Resource data:2131034116
I/AMMetaDataParserService( 2904): getResourceName:com.android.contacts:xml/findo_searchable
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2904): Resource data:2131099668
,I/SELinux ( 3152): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3152):  
I/ActivityManager(  732): Killing 2211:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2904): getResourceName:com.sec.android.app.sbrowser:xml/searchable
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
I/AMMetaDataParserService( 2904): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 2904): Resource data:2131099650
I/AMMetaDataParserService( 2904): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,D/dalvikvm(  248): GC_EXPLICIT freed 47K, 51% free 9506K/19044K, paused 2ms+3ms, total 26ms
,I/AMMetaDataParserService( 2904): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9506K/19044K, paused 1ms+3ms, total 18ms
I/SELinux ( 3152): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3152):  
I/SELinux ( 3152):  
I/SELinux ( 3152): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3152): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3152): >>>>> Normal User
E/dalvikvm( 3152): >>>>> com.LocalFota [ userId:0 | appId:10110 ]
,E/SELinux ( 3152): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2904): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9506K/19044K, paused 1ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 3152): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3152): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3152): Added TimaKesytore provider
,I/AMMetaDataParserService( 2904): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 2904): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAutoDiscover
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2904): Resource data:2131099667
,I/AMMetaDataParserService( 2904): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/DBG_WSS_LF( 3152): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
,I/DBG_WSS_LF( 3152): [20.0040.140326][Line:27][<init>] First call
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=3152, uid=10110 requires android.permission.INTERACT_ACROSS_USERS
,I/AMMetaDataParserService( 2904): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559
,I/AMMetaDataParserService( 2904): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558
,I/DBG_WSS_LF( 3152): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_WSS_LF( 3152): [20.0040.140326][Line:31][onReceive] *** boot complete ***
,I/DBG_WSS_LF( 3152): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
,I/DBG_WSS_LF( 3152): [20.0040.140326][Line:41][onReceive] nStatus : -1
,I/SELinux ( 3169): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3169):  
,I/AMMetaDataParserService( 2904): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
I/ActivityManager(  732): Killing 1698:com.fmm.dm/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2904): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
,I/SELinux ( 3169): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3169):  
I/SELinux ( 3169):  
,I/SELinux ( 3169): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3169): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3169): >>>>> Normal User
,E/dalvikvm( 3169): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
,E/SELinux ( 3169): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2904): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
,D/TimaKeyStoreProvider( 3169): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3169): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3169): Added TimaKesytore provider
,I/AMMetaDataParserService( 2904): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2904): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2904): Resource data:2131099689
,I/AMMetaDataParserService( 2904): getResourceName:com.android.email:xml/spellscroll
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
D/StatusChecker( 3169): onReceive : android.intent.action.BOOT_COMPLETED
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2904): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2904): Resource data:2131099685
I/AMMetaDataParserService( 2904): getResourceName:com.android.email:xml/searchable
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/AMMetaDataParserService( 2904): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 2904): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2904): getResourcePackageName:com.android.keyguard.layout
,I/AMMetaDataParserService( 2904): Resource data:2130903052
I/AMMetaDataParserService( 2904): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
I/AMMetaDataParserService( 2904): getResourceTypeNamelayout
I/AMMetaDataParserService( 2904): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2904): Resource data:2131034112
I/AMMetaDataParserService( 2904): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 2904): getResourceTypeNamexml
,I/AMMetaDataParserService( 2904): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,I/SELinux ( 3183): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3183):  
I/ActivityManager(  732): Killing 2229:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
,I/AMMetaDataParserService( 2904): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 2904): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
I/ActivityManager(  732): Killing 2241:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #43
,I/SELinux ( 3183): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3183):  
I/SELinux ( 3183):  
,I/SELinux ( 3183): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3183): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3183): >>>>> Normal User
,E/dalvikvm( 3183): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10133 ]
,E/SELinux ( 3183): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3183): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3183): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3183): Added TimaKesytore provider
,D/AndroidRuntime( 3156): 
D/AndroidRuntime( 3156): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3156): CheckJNI is OFF
,D/AndroidRuntime( 3156): setted country_code = Poland
,D/AndroidRuntime( 3156): setted countryiso_code = PL
D/AndroidRuntime( 3156): setted sales_code = XEO
D/AndroidRuntime( 3156): readGMSProperty: start
,D/AndroidRuntime( 3156): readGMSProperty: already setted!!
D/AndroidRuntime( 3156): readGMSProperty: end
,D/AndroidRuntime( 3156): addProductProperty: start
,D/dalvikvm( 3156): Trying to load lib libjavacore.so 0x0
,D/QuickConnect( 3183): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 3156): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3156): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3156): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3156): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,W/BackupManagerService(  732): dataChanged but no participant pkg='com.android.providers.settings' uid=10133
D/QuickConnect( 3183): Utils.setQCRunningSetting - set : 0
I/QuickConnect( 3183): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
V/QuickConnect( 3183): SconnectManager.getInstance - () return existing instance null
W/ContextImpl( 3183): Implicit intents with startService are not safe: Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } android.content.ContextWrapper.startServiceAsUser:517 android.content.ContextWrapper.startServiceAsUser:517 com.samsung.android.sconnect.periph.PeriphStartReceiver.onReceive:30 
I/QuickConnect( 3183): PeriphService.onCreate - [START]
,I/SELinux ( 3202): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3202):  
,I/QuickConnect( 3183): PeriphService.onCreate - [START] USER_OWNER
,D/QuickConnect( 3183): PeriphService.setProcessForeground - Build.VERSION.SDK_INT = 19
,I/QuickConnect( 3183): PeriphService.setProcessForeground - true of JB_MR2 complete 
I/QuickConnect( 3183): PeriphService.setState - 0 >> 1
,V/QuickConnect( 3183): PeriphService.runService - 
,I/QuickConnect[1.1][2] ( 3183): SconnectManager.SconnectManager - initiate from com.samsung.android.sconnect.periph.PeriphService@425f3518
,I/QuickConnect[1.1][2] ( 3183): SconnectManager.SconnectManager - set getApplicationContext android.app.Application@425eb4a0
,D/QuickConnect[1.1][2] ( 3183): SconnectManager.registerBroadcast - --
,D/QuickConnect[1.1][2] ( 3183): SconnectManager.SconnectManager - REQUEST_ID :  1
,D/QuickConnect[1.1][2] ( 3183): ScanThread.ScanThread - created!
,V/QuickConnect[1.1][2] ( 3183): BluetoothHelper.BluetoothHelper - 
,D/QuickConnect[1.1][2] ( 3183): BluetoothHelper.registerBluetoothAdapterReceiver - mIsBluetoothAdapterReceiver = false
,V/QuickConnect[1.1][2] ( 3183): BleHelper.BleHelper - Constructor
,I/SELinux ( 3202): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3202):  
I/SELinux ( 3202):  
,I/SELinux ( 3202): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3202): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3202): >>>>> Normal User
,E/dalvikvm( 3202): >>>>> com.sec.android.service.bezel [ userId:0 | appId:1000 ]
,E/SELinux ( 3202): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3202): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3202): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3202): Added TimaKesytore provider
,E/QuickConnect[1.1][2] ( 3183): BleHelper.startScan - not isGattServiceReady. Try to BLE On calling addLeRadioReference()
D/BluetoothRadioManager( 3183): addLeRadioReference: Add CB  com.samsung.android.sconnect.common.net.BleHelper$GattServiceStateChangeCallback@426068c8
D/BluetoothRadioManager( 3183):  addRadioReference enabled = false
,D/BluetoothRadioManager( 3183):  BLE Radio count is : 1
D/BluetoothRadioManager( 3183): addLeRadioReference: isRadioEnabled() =  false
,V/QuickConnect[1.1][2] ( 3183): BleHelper.mSearchWearable - true
,D/BluetoothManagerService(  732): foregroundUser: 0
,V/QuickConnect[1.1][2] ( 3183): UpnpHelper.UpnpHelper - 
,V/QuickConnect[1.1][2] ( 3183): JmdnsHelper.JmdnsHelper - Constructor
,V/QuickConnect[1.1][2] ( 3183): P2pHelper.P2pHelper - EXEC
,D/QuickConnect[1.1][2] ( 3183): p2pHelperWorkThread.p2pHelperWorkThread - created!
,E/BluetoothManagerService(  732): Package is exist.
,E/memtrack( 3156): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3156): failed to load memtrack module: -2
,I/SELinux ( 3216): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3216):  
,D/QuickConnect[1.1][2] ( 3183): WifiHelper.WifiHelper -  -- 
,D/BezelQuickConnect( 3202): BezelBroadcastReceiver - onReceive : android.intent.action.BOOT_COMPLETED
,D/BezelQuickConnect( 3202): BezelBroadcastReceiver - StartBezelInteractionService
,D/BezelQuickConnect( 3202): BezelManagerService - setProcessForeground, Build.VERSION.SDK_INT = 19
,I/BezelQuickConnect( 3202): BezelManagerService - setProcessForeground, true of JB_MR2 complete 
,D/BezelQuickConnect( 3202): BezelBroadcastReceiver - onReceive : Send to quickpanel - service.ENABLED
,V/PhoneStatusBar( 1068): onReceive: Intent { act=com.sec.android.sconnect.service.ENABLED flg=0x10 }mQconnectEnable = true
,I/QuickConnect[1.1][2] ( 3183): CentralActionManager.CentralActionManager - EXEC
,V/QuickConnect[1.1][2] ( 3183): BluetoothOppActionHelper.BluetoothOppActionHelper - 
D/WifiDisplayAdapter(  732): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ContextImpl( 3202): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.android.service.bezel.BezelBroadcastReceiver.onReceive:40 android.app.ActivityThread.handleReceiver:2698 
V/QuickConnect[1.1][2] ( 3183): GroupVoiceTalkActionHelper.GroupVoiceTalkActionHelper -  --
V/QuickConnect[1.1][2] ( 3183): SmartHomeActionHelper.SmartHomeActionHelper - --
V/QuickConnect[1.1][2] ( 3183): ScreenMirrorActionHelper.ScreenMirrorActionHelper - 
V/QuickConnect[1.1][2] ( 3183): BluetoothActionHelper.BluetoothActionHelper - 
,D/BluetoothAdapter( 3183): 1113598808: getState() :  mService = null. Returning STATE_OFF
,E/NetworkSettingsReceiver( 1761): onReceive: android.intent.action.BOOT_COMPLETED
D/STATUSBAR-PhoneStatusBar( 1068): showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
,E/BluetoothHeadset( 3183): BTStateChangeCB is registed
,E/BluetoothHeadset( 3183): BluetoothHeadset service is binded
,D/dalvikvm( 3156): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 3216): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3216):  
I/SELinux ( 3216):  
,I/SELinux ( 3216): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,W/BroadcastQueue(  732): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.android.calendar/.magazine.CalendarUpdateRelatedDataReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
E/SELinux ( 3216): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3216): >>>>> Normal User
E/dalvikvm( 3216): >>>>> com.android.bluetooth [ userId:0 | appId:1002 ]
I/QuickConnect[1.1][2] ( 3183): SconnectManager.getInstance - make new instance com.samsung.android.sconnect.SconnectManager@425f5110
V/QuickConnect[1.1][2] ( 3183): SconnectManager.getInstance - return existing instance com.samsung.android.sconnect.SconnectManager@425f5110
E/SELinux ( 3216): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/QuickConnect[1.1][2] ( 3183): PreDiscoveryHelper.PreDiscoveryHelper -  -- 
D/QuickConnect[1.1][2] ( 3183): PreDiscoveryHelper.setVisibilityFromSystemDb - --
D/QuickConnect[1.1][2] ( 3183): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 3183): Utils.getFromDb -  Key[quick_connect_contact_only], isEnabled [1] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 3183): PreDiscoveryHelper.setVisibilityFromSystemDb - isAllowToConnect : false, isContactOnly : true, visibilitySetting : 2
D/QuickConnect[1.1][2] ( 3183): PreDiscoveryHelper.changeResponseSetting - changed: 2
V/QuickConnect[1.1][2] ( 3183): PreDiscoveryHelper.updateAdvData - 
V/QuickConnect[1.1][2] ( 3183): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425f5110
V/QuickConnect[1.1][2] ( 3183): PreDiscoveryHelper.updateRespTarget - 
,D/TimaKeyStoreProvider( 3216): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3216): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3216): Added TimaKesytore provider
,I/SELinux ( 3231): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3231):  
,D/QuickConnect[1.1][2] ( 3183): PreDiscoveryHelper.initializeAdvData - 
,V/QuickConnect[1.1][2] ( 3183): PreDiscoveryHelper.initializeAdvData - name: Galaxy S5-2(11)
,D/QuickConnect[1.1][2] ( 3183): PreDiscoveryHelper.initializeAdvData - name selected: Galaxy S5-2(11)
,V/QuickConnect[1.1][2] ( 3183): CONTACT_Info.getMyMobileNumber - 
,D/AndroidRuntime( 3156): Calling main entry com.android.commands.pm.Pm
,I/SELinux ( 3231): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3231):  
I/SELinux ( 3231):  
,I/SELinux ( 3231): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3231): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3231): >>>>> Normal User
,E/dalvikvm( 3231): >>>>> com.sec.android.app.camera [ userId:0 | appId:10147 ]
,E/SELinux ( 3231): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3231): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3231): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3231): Added TimaKesytore provider
,D/dalvikvm(  732): GC_EXPLICIT freed 1397K, 18% free 22702K/27564K, paused 5ms+10ms, total 116ms
,D/PackageManagerService(  732): deletePackageAsUser- pkg:com.example.hello, userId:0
,D/PersonaManagerService(  732): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  732): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  732): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  732): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  732): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService(  732): deletePackage- pkg:com.example.hello, edmuserId:0
,D/PackageManagerService(  732): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  732): getApplicationUninstallationEnabled
D/ApplicationPolicy(  732): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService(  732): deletePackageX- pkg:com.example.hello, userId:0
D/PackageManager(  732): START PACKAGE DELETE: observer{1126987336}
D/PackageManager(  732): pkg{<packageName>}
D/PackageManager(  732): user{0}
D/PackageManager(  732): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  732): [MSG] DELETE_PACKAGE_AS_USER
,D/QuickConnect[1.1][2] ( 3183): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3183): CONTACT_Info.getMyMobileNumber - null 
,D/QuickConnect[1.1][2] ( 3183): NetUtil.getP2pMacFromWifiMac - ($)
,V/QuickConnect[1.1][2] ( 3183): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425f5110
,W/QuickConnect[1.1][2] ( 3183): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.emeeting.b2c.hancom
,D/QuickConnect[1.1][2] ( 3183): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.emeeting
D/QuickConnect[1.1][2] ( 3183): AppPackageUtil.isStubApk - but Stub version[2.7.025] of com.samsung.groupcast
W/QuickConnect[1.1][2] ( 3183): AppPackageUtil.isAppInstalled - this is Stub - com.samsung.groupcast
,D/QuickConnect[1.1][2] ( 3183): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.samsung.groupcast
W/QuickConnect[1.1][2] ( 3183): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3183): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3183): PeriphService.registerUserReceiver - mIsUserReceiver == false
I/QuickConnect[1.1][2] ( 3183): PeriphService.onStartCommand - USER_OWNER
I/QuickConnect[1.1][2] ( 3183): PeriphService.onStartCommand - Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } flags[0] startId[1]
,I/QuickConnect[1.1][2] ( 3183): PeriphService.onStartCommand - Action: com.samsung.android.sconnect.periph.START_SERVICE
,W/dalvikvm( 3231): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
D/PackageManager(  732): !@killApplicatoin: 10180, uninstall pkg
I/ActivityManager(  732): Killing 2683:com.example.hello/u0a180 (adj 0): stop com.example.hello
,D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  732): mDVFSHelper.acquire()
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=16 Removed NainActivit (7/11)
,I/SurfaceFlinger(  247): id=16 Removed NainActivit (-2/11)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=16 Removed NainActivit (-2/11)
,I/WindowState(  732): WIN DEATH: Window{42576fa8 u0 com.example.hello/com.example.hello.MainActivity}
D/SurfaceWidgetView( 1254): destroyHardwareResources():1126113696
,W/PackageSettings(  732): Skipping PackageSetting{42488518 com.test.thalitest/10179} due to missing metadata
,D/PackageManager(  732): queryIntentReceivers - Execution time: 115 ms
,D/LockPatternUtils( 1068): isPcwEnable = null
D/PackageManager(  732): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10180, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1254): onRestart, Launcher: 1114179632
D/Launcher( 1254): onStart, Launcher: 1114179632
,D/Launcher.HomeView( 1254): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1453): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1453): [237392/5] SurfaceWidget drawing first frame
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/BtSettings.ProfileConfig( 3216): Adding GattService
D/BtSettings.ProfileConfig( 3216): Adding HeadsetService
,D/BtSettings.ProfileConfig( 3216): Adding A2dpService
D/BtSettings.ProfileConfig( 3216): Adding HidService
D/BtSettings.ProfileConfig( 3216): Adding HealthService
D/BtSettings.ProfileConfig( 3216): Adding PanService
,D/BtSettings.ProfileConfig( 3216): Adding BluetoothMapService
D/PackageManager(  732): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10180, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/FPMS_FingerprintManagerService( 1087): onReceive: android.intent.action.PACKAGE_REMOVED
,D/AdaptiveEventManager( 1068): action=android.intent.action.PACKAGE_REMOVED
,W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
,D/dalvikvm( 1411): GC_EXPLICIT freed 4147K, 48% free 9987K/19044K, paused 2ms+6ms, total 44ms
D/QuickConnect[1.1][2] ( 3183): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.example.hello
,I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  732):   Scheme: "sms"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/InputReader(  732): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "smsto"
,I/SurfaceFlinger(  247): id=18 createSurf (720x1280),1 flag=4, Mauncher
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=19 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  732):   Scheme: "mms"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  732):   Scheme: "mmsto"
,D/BluetoothAdapterService( 3216): REFCOUNT: CREATED. INSTANCE_COUNT1
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3251): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3251):  
I/ActivityManager(  732): Killing 2269:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/BluetoothAdapterState( 3216): make
,I/bluedroid( 3216): init
,I/BluetoothAdapterState( 3216): Entering OffState
,D/RCPManagerService(  732): PackageReceiver onReceive()
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  732):   Scheme: "sms"
,D/Launcher.HomeView( 1254): onStop
,I/bte_conf( 3216): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3216): get_profile_interface socket
I/GKI_LINUX( 3216): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterService( 3216):  checkAddrForIOP: Loading from conf
,I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/BluetoothServiceJni( 3216): populateRssiValuesNative
I/bluedroid( 3216): getModelRssiValues
E/BluetoothServiceJni( 3216): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SELinux ( 3251): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3251):  
I/SELinux ( 3251):  
I/SELinux ( 3251): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3251): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3251): >>>>> Normal User
E/dalvikvm( 3251): >>>>> com.sec.android.inputmethod [ userId:0 | appId:1000 ]
E/SELinux ( 3251): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@5
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  732):   Scheme: "smsto"
,I/HarmonyEASService(  732): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  732): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 3251): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3251): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3251): Added TimaKesytore provider
,I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  732):   Scheme: "mms"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  732):   Scheme: "mmsto"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PowerManagerService(  732): [PWL] Off : 5s ago
I/PowerManagerService(  732): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  732): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  732): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=732, ws=WorkSource{10044}) (elapsedTime=3887)
,D/dalvikvm(  732): GC_EXPLICIT freed 1600K, 18% free 22809K/27564K, paused 5ms+13ms, total 229ms
D/PackageManager(  732): delete sourFile : 
,D/EnterpriseDeviceManagerService(  732): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  732): Admin package name: com.google.android.gms
,D/AndroidRuntime( 3156): Shutting down VM
,D/dalvikvm( 3156): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+0ms, total 3ms
D/PackageManager(  732): delete native library directory: 
D/PackageManager(  732): return delete result to caller: 1126987336
D/PackageManager(  732): returnCode: 1
,I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  732):   Scheme: "sms"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  732):   Scheme: "smsto"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  732):   Scheme: "mms"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  732):   Scheme: "mmsto"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3267): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3267):  
I/ActivityManager(  732): Killing 2285:com.sec.android.app.mss/u0a21 (adj 15): empty #43
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService(  732): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService(  732): removePackageParticipantsLocked: uid=10180 #1
,I/SELinux ( 3267): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3267):  
I/SELinux ( 3267):  
,I/SELinux ( 3267): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3267): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3267): >>>>> Normal User
,E/dalvikvm( 3267): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 3267): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/bluedroid( 3216): config_hci_snoop_log
,D/BluetoothManagerService(  732): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/TimaKeyStoreProvider( 3267): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3267): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3267): Added TimaKesytore provider
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BluetoothRadioManager( 3183): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4265e890
,D/BluetoothRadioManager( 3183): onBluetoothServiceUp()  registerRadioClient mUUID = e9331bab-a4cd-4080-8802-81e4ff44e6eb
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/bluedroid( 3216): update_radio_count
D/BluetoothAdapterState( 3216): CURRENT_STATE=OFF, MSG = USER_TURN_ON_RADIO
I/BluetoothAdapterState( 3216): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=false
D/BluetoothAdapterState( 3216): CURRENT_STATE=PENDING, MSG = BEGIN_ENABLE_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
,I/bluedroid( 3216): enable
,I/bt_hci_bdroid( 3216): init
,I/bt_vendor( 3216): bt-vendor : init
I/bt_vendor( 3216): bt-vendor : get_bt_soc_type
E/bt_vendor( 3216): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 3216): init: Local BD Address : dc:06:b5:96:94:38
D/bt_userial_mct( 3216): userial_init
I/bt_vendor( 3216): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_hci_bdroid( 3216): bt_hc_worker_thread started
,I/bt_vendor( 3216): Starting hciattach daemon
,I/bt_vendor( 3216): try to set false
,I/bt_vendor( 3216): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 3216): Starting hciattach daemon
,I/bt_vendor( 3216): try to set true
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/qcom-bluetooth( 3283): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,E/SMD     (  241): DCD ON
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/qcom-bluetooth( 3290): /system/etc/init.qcom.bt.sh: Transport : smd 
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector(  732): onPackageRemoved : com.example.hello
,D/InputReader(  732): Processing first event
,D/UsbSettingsManager(  732): clearDefaults: com.example.hello
I/qcom-bluetooth( 3291): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 

```
