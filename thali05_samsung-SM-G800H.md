#### Test 506502789252e15_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72a00, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
D/dalvikvm( 4500): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42628cb0, skipping init
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
I/SecureStorage( 4500): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4500): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72a00, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72a00, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72a00, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/SecureStorage(  300): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4500
I/SecureStorage(  300): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/OMX     (  251): instance freeNode
I/SecureStorage( 4500): [INFO]: SPID(0x00000000)SS Daemon is running
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4482): decode(64, 37457308, 34198)
V/MediaPlayerService(  251): decode(33, 37457308, 34198)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 37457308, 34198)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d871a8, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7d871a8, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d871a8, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d871a8, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d871a8, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
I/AudioPlayer(  251): First fillBuffer call!!
V/MediaPlayerService(  251): wait for playback complete
I/SecureStorage( 4500): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  300): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4500
I/SecureStorage(  300): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d871a8, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d871a8, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d871a8, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4482): decode(65, 33862452, 7405)
V/MediaPlayerService(  251): decode(33, 33862452, 7405)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 33862452, 7405)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75660, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7d75660, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75660, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75660, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75660, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75660, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75660, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): addBatteryData
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75660, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
,I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4482): decode(66, 37547940, 5555)
V/MediaPlayerService(  251): decode(33, 37547940, 5555)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4482): decode(67, 30367732, 5085)
V/MediaPlayerService(  251): decode(33, 30367732, 5085)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d75758, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4482): decode(68, 30372876, 21552)
V/MediaPlayerService(  251): decode(33, 30372876, 21552)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 30372876, 21552)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d6f730, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7d6f730, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d6f730, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d6f730, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d6f730, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d6f730, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d6f730, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d6f730, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4482): decode(69, 37543652, 4230)
V/MediaPlayerService(  251): decode(33, 37543652, 4230)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72770, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7d72770, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72770, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72770, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  251): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72770, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72770, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72770, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72770, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4482): decode(70, 30337076, 9400)
V/MediaPlayerService(  251): decode(33, 30337076, 9400)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 30337076, 9400)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d782b8, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7d782b8, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d782b8, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d782b8, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  251): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d782b8, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/SELinux ( 4564): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4564):  
--------- beginning of /dev/log/system
I/ActivityManager(  726): Killing 3100:com.sec.android.app.mt/1000 (adj 15): empty #43
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d782b8, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d782b8, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d782b8, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4482): decode(71, 33925464, 44276)
V/MediaPlayerService(  251): decode(33, 33925464, 44276)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 33925464, 44276)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d73868, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7d73868, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d73868, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d73868, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
I/SELinux ( 4564): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4564):  
I/SELinux ( 4564):  
I/SELinux ( 4564): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4564): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
E/dalvikvm( 4564): >>>>> Normal User
E/dalvikvm( 4564): >>>>> com.policydm [ userId:0 | appId:1000 ]
V/AudioCache(  251): notify(0xb7d73868, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
E/SELinux ( 4564): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4564): in addTimaSignatureService
D/TimaKeyStoreProvider( 4564): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4564): Added TimaKesytore provider
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d73868, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d73868, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d73868, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4482): decode(72, 33885672, 29256)
V/MediaPlayerService(  251): decode(33, 33885672, 29256)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 33885672, 29256)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7ad98, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7d7ad98, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7ad98, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7ad98, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7ad98, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7ad98, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7ad98, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7ad98, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4482): decode(73, 37491572, 52024)
V/MediaPlayerService(  251): decode(33, 37491572, 52024)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 37491572, 52024)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7c2b0, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7d7c2b0, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7c2b0, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7c2b0, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7c2b0, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/AudioPlayer(  251): First fillBuffer call!!
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7c2b0, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7c2b0, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d7c2b0, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4482): decode(74, 33969800, 9226)
V/MediaPlayerService(  251): decode(33, 33969800, 9226)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 33969800, 9226)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72470, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7d72470, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72470, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72470, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
D/AndroidRuntime( 4558): 
D/AndroidRuntime( 4558): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/AndroidRuntime( 4558): CheckJNI is OFF
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72470, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
D/AndroidRuntime( 4558): setted country_code = Poland
D/AndroidRuntime( 4558): setted countryiso_code = PL
D/AndroidRuntime( 4558): setted sales_code = XEO
D/AndroidRuntime( 4558): readGMSProperty: start
D/AndroidRuntime( 4558): readGMSProperty: already setted!!
D/AndroidRuntime( 4558): readGMSProperty: end
D/AndroidRuntime( 4558): addProductProperty: start
I/AudioPlayer(  251): First fillBuffer call!!
D/dalvikvm( 4558): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4558): Added shared lib libjavacore.so 0x0
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72470, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72470, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d72470, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/dalvikvm( 4558): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4558): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4558): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4482): decode(75, 30402580, 4509)
V/MediaPlayerService(  251): decode(33, 30402580, 4509)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 30402580, 4509)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d76260, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7d76260, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d76260, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d76260, 1, 0, 0)
V/AudioCache(  251): prepared
V/Audi,oCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d76260, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
I/AudioPlayer(  251): First fillBuffer call!!
V/MediaPlayerService(  251): wait for playback complete
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d76260, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d76260, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7d76260, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
I/SELinux ( 4609): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4609):  
E/memtrack( 4558): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4558): failed to load memtrack module: -2
I/ActivityManager(  726): Killing 3166:com.sec.android.app.camera/u0a147 (adj 15): empty #43
D/dalvikvm( 4558): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/dalvikvm(  249): GC_EXPLICIT freed 45K, 50% free 9509K/19008K, paused 2ms+2ms, total 39ms
I/SELinux ( 4609): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4609):  
I/SELinux ( 4609):  
I/SELinux ( 4609): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4609): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4609): >>>>> Normal User
E/dalvikvm( 4609): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 4609): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/19008K, paused 2ms+3ms, total 18ms
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/19008K, paused 1ms+3ms, total 17ms
D/TimaKeyStoreProvider( 4609): in addTimaSignatureService
D/TimaKeyStoreProvider( 4609): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4609): Added TimaKesytore provider
D/AndroidRuntime( 4558): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy(  726): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  726): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 726  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  726): mDVFSHelper.acquire()
I/SELinux ( 4623): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4623):  
D/LockPatternUtils( 1068): isPcwEnable = null
D/AndroidRuntime( 4558): Shutting down VM
D/dalvikvm( 4558): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 4623): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4623):  
I/SELinux ( 4623):  
I/SELinux ( 4623): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/SA      ( 4609): [SSP] onCreated
E/SELinux ( 4623): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4623): >>>>> Normal User
E/dalvikvm( 4623): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 4623): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/SA      ( 4609): [TPM] There is no property file
I/SA      ( 4609): [SCU] isHaveSA() - false
D/TimaKeyStoreProvider( 4623): in addTimaSignatureService
I/SA      ( 4609): [TPM] getModelProperty : null
I/SA      ( 4609): [TPM] getCSCProperty : null
I/SA      ( 4609): [PMR] Received action : android.intent.action.PACKAGE_ADDED
D/TimaKeyStoreProvider( 4623): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4623): Added TimaKesytore provider
I/SA      ( 4609): [DM] init START
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1447): [237392/5] Surface widget visibility changed visibility = false on instance = 1
I/SA      ( 4609): [DM] This device is not a Vodafone
D/LockPatternUtils( 1068): isPcwEnable = null
D/SurfaceWidgetView( 1262): destroyHardwareResources():1126343368
I/SQLiteSecureOpenHelper( 2025): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2025): getDatabaseLocked(b,b,pwd)...
I/SA      ( 4609): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4609): support phone number id : false
I/SA      ( 4609): [DM] init END
I/SA      ( 4609): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4609): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  726): Killing 3267:com.android.email/u0a155 (adj 15): empty #43
D/Mms/PackageInstallReceiver( 3776): loadAuthorityPref(): sEnableAuthority = true
I/SurfaceFlinger(  248): id=14 Removed CatteryCove (8/13)
I/SurfaceFlinger(  248): id=14 Removed CatteryCove (-2/13)
W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=4623, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=4623, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 4623): Binding Chromium to the background looper Looper (main, tid 1) {422f9380}
I/chromium( 4623): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4623): Initializing chromium process, renderers=0
I/IcingCorporaProvider( 2131): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 2822): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,W/chromium( 4623): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/SELinux ( 4653): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4653):  
D/AmoledAdjustTimer(  726): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
D/dalvikvm( 2131): GC_CONCURRENT freed 6480K, 42% free 11209K/19008K, paused 4ms+9ms, total 45ms
D/dalvikvm( 2131): WAIT_FOR_CONCURRENT_GC blocked 6ms
I/SELinux ( 4653): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4653):  
I/SELinux ( 4653):  
I/SELinux ( 4653): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4653): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4653): >>>>> Normal User
E/dalvikvm( 4653): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 4653): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 4653): in addTimaSignatureService
D/TimaKeyStoreProvider( 4653): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4653): Added TimaKesytore provider
I/IcingCorporaProvider( 2131): UpdateCorporaTask done [took 149 ms] updated apps [took 148 ms] 
W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=4653, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CapabilityManagerService New( 4653): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 4666): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4666):  
I/ActivityManager(  726): Killing 3263:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
I/SELinux ( 4666): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4666):  
I/SELinux ( 4666):  
I/SELinux ( 4666): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4666): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4666): >>>>> Normal User
E/dalvikvm( 4666): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 4666): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 4666): in addTimaSignatureService
D/TimaKeyStoreProvider( 4666): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4666): Added TimaKesytore provider
I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4623): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4623): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4623): Remote Branch: 
I/Adreno-EGL( 4623): Local Patches: 
I/Adreno-EGL( 4623): Reconstruct Branch: 
I/SurfaceFlinger(  248): id=17 Removed TettingsRec (8/12)
I/SurfaceFlinger(  248): id=17 Removed TettingsRec (-2/12)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SecureStorage(  300): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  300): [INFO]: SPID(0x00000003)PID: 4500, TID: 4500
I/SurfaceFlinger(  248): id=8 Removed Mauncher (7/11)
I/SurfaceFlinger(  248): id=8 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/Launcher( 1262): onTrimMemory. Level: 20
D/SurfaceWidgetView( 1262): destroyHardwareResources():1126343368
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/dalvikvm( 4623): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4623): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4623): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4623): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x0008
I/SecureStorage( 4500): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4500): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4500): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4500): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 4500): Open platform.db in secure mode
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4623): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4623): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4623): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4623): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4623): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4623): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4623): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4623): CordovaWebView is running on device made by: samsung
W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=4666, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
I/SurfaceFlinger(  248): id=18 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 4623): EGLImpl-HWUI Protected EGL context created
I/SQLiteSecureOpenHelper( 4500): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 4500): ...getDatabaseLocked(b,b,pwd)
D/OpenGLRenderer( 4623): Enabling debug mode 0
D/OpenGLRenderer( 4623): GL error from OpenGLRenderer: 0x502
E/OpenGLRenderer( 4623):   GL_INVALID_OPERATION
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  726): Killing 3292:com.sec.modem.settings/1000 (adj 15): empty #43
D/CustomFrequencyManagerService(  726): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 726  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  726): mDVFSHelper.release()
D/CustomFrequencyManagerService(  726): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 726  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
E/SMD     (  242): DCD ON
W/GAV2    ( 4666): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/JsMessageQueue( 4623): Set native->JS mode to OnlineEventsBridgeMode
,I/SELinux ( 4703): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4703):  
,I/SELinux ( 4703): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4703):  
I/SELinux ( 4703):  
,I/SELinux ( 4703): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4703): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4703): >>>>> Normal User
,E/dalvikvm( 4703): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 4703): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4703): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4703): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4703): Added TimaKesytore provider
,D/dalvikvm( 4623): Trying to load lib /data/app-lib/com.test.thalitest-24/libjxcore.so 0x426200b8
,D/dalvikvm( 4623): Added shared lib /data/app-lib/com.test.thalitest-24/libjxcore.so 0x426200b8
D/jxcore_app_log( 4623): JniHelper::setJavaVM(0x4175b528), pthread_self() = 2033162936
,D/JX-Cordova( 4623): jxcore cordova android initializing
I/dalvikvm( 4623): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4623): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x0045
,D/PackageIntentReceiver( 4703): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4703): Not GearManger package! 
,I/SELinux ( 4717): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4717):  
I/ActivityManager(  726): Killing 1336:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/SELinux ( 4717): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4717):  
I/SELinux ( 4717):  
,I/SELinux ( 4717): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4717): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4717): >>>>> Normal User
,E/dalvikvm( 4717): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 4717): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4717): in addTimaSignatureService
D/TimaKeyStoreProvider( 4717): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4717): Added TimaKesytore provider
,D/MagazineService Version( 4717): Magazine-Channel: 13
,D/MagazineService Version( 4717): Magazine-Provider: 13
,D/MagazineService Version( 4717): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 4717): [onCreate]
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=4717, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/MagazineService::MagazineBroadcastReceiver( 4717): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,I/MagazineService::MagazineService( 4717): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/SELinux ( 4730): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4730):  
,D/MagazineService::MagazineService( 4717): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/ActivityManager(  726): Killing 3313:tv.peel.smartremote/u0a163 (adj 15): empty #43
,W/GAV2    ( 4666): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/SELinux ( 4730): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4730):  
I/SELinux ( 4730):  
,I/SELinux ( 4730): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4730): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4730): >>>>> Normal User
,E/dalvikvm( 4730): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,I/ActivityManager(  726): Killing 3334:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
E/SELinux ( 4730): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4730): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4730): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4730): Added TimaKesytore provider
,D/dalvikvm( 4623): GC_CONCURRENT freed 4909K, 33% free 12780K/19008K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 4623): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/SELinux ( 4744): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4744):  
I/ActivityManager(  726): Killing 3394:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 4744): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4744):  
I/SELinux ( 4744):  
,I/SELinux ( 4744): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4744): >>>>> Normal User
,E/dalvikvm( 4744): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 4744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  726): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/TimaKeyStoreProvider( 4744): in addTimaSignatureService
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 4744): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4744): Added TimaKesytore provider
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=4744, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4744): Package not found : com.sec.android.app.kidshome
D/SSRMv2:SIOP(  726): SIOP:: AP = 310, Delta = 10
,I/SELinux ( 4756): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4756):  
I/ActivityManager(  726): Killing 3413:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,D/CustomFrequencyManagerService(  726): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 726  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 4756): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4756):  
I/SELinux ( 4756):  
,I/SELinux ( 4756): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4756): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4756): >>>>> Normal User
,E/dalvikvm( 4756): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4756): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4756): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4756): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4756): Added TimaKesytore provider
,I/SELinux ( 4768): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4768):  
I/ActivityManager(  726): Killing 3428:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4768): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4768):  
I/SELinux ( 4768):  
,I/SELinux ( 4768): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4768): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4768): >>>>> Normal User
,E/dalvikvm( 4768): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4768): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4768): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4768): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4768): Added TimaKesytore provider
,D/dalvikvm( 4623): GC_FOR_ALLOC freed 4662K, 28% free 15766K/21768K, paused 38ms, total 38ms
,I/ActivityManager(  726): Killing 3624:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/Finsky  ( 3501): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 1759): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1759): Loading module APK com.google.android.play.games
I/dalvikvm( 1759): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1759): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1759): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1759): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1759): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1759): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1759): VFY: replacing opcode 0x22 at 0x001a
,I/dalvikvm( 1759): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1759): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1759): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1759): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1759): Submit a task: k
,D/dalvikvm( 1759): GC_CONCURRENT freed 1842K, 40% free 11419K/19008K, paused 5ms+5ms, total 117ms
,D/dalvikvm( 1759): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 1759): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 1759): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/dalvikvm( 1759): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 1759): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 4623): GC_FOR_ALLOC freed 5022K, 32% free 16772K/24440K, paused 38ms, total 38ms
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 22.010MB for 2459024-byte allocation
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1759): Processing package: com.test.thalitest
,D/GassUtils( 1759): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1759): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,D/dalvikvm( 1321): GC_EXPLICIT freed 1113K, 44% free 10756K/19008K, paused 6ms+5ms, total 44ms
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1759): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1759): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1759): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1759): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1759): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1759): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1759): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1759): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1759): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1759): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0006
,D/dalvikvm( 4623): GC_FOR_ALLOC freed 3766K, 35% free 17455K/26844K, paused 33ms, total 39ms
,I/PeopleDatabaseHelper( 1759): cleanUpNonGplusAccounts done.
,D/dalvikvm( 4623): GC_FOR_ALLOC freed 1200K, 36% free 17356K/26844K, paused 28ms, total 28ms
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1759): Module APK com.google.android.play.games already loaded
,W/jxcore-log( 4623): Initializing JXcore engine
,W/jxcore-log( 4623): JXcore engine is ready
,W/jxcore-log( 4623): Starting JXcore engine
,W/jxcore-log( 4623): Platform android
W/jxcore-log( 4623): 
,W/jxcore-log( 4623): Process ARCH arm
W/jxcore-log( 4623): 
,I/Icing   ( 1759): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,E/SMD     (  242): DCD ON
,I/Icing   ( 1759): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,I/jxcore-log( 4623): JXcore Cordova bridge is ready!
I/jxcore-log( 4623): 
,W/jxcore-log( 4623): JXcore engine is started
,I/chromium( 4623): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4623): Toggling radios to true
I/jxcore-log( 4623): 
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=4623, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  726): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  726): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4623, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  726): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/BluetoothManagerService(  726): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService(  726): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  726): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService(  726): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService(  726): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService(  726): foregroundUser: 0
,E/BluetoothManagerService(  726): Package is exist.
,D/BluetoothAdapterState( 3151): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 3151): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3151): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3151): updateAdapterState state is 11
,D/BluetoothAdapterService( 3151): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3151): Autoconnection is available 
I/WifiManager( 4623): packageName : com.test.thalitest
D/BluetoothAdapterService( 3151): updateAdapterState prevState = 10newState = 11
,D/BtConfig.SecureMode( 3151): isSecureModeOn:false
I/WifiManager( 4623): setWifiEnabled : true
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,I/WifiService(  726): setWifiEnabled: true pid=4623, uid=10179
,W/BluetoothAdapterService( 3151): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3151): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/WifiService(  726): Failed getting userId using ActivityManagerNative
W/WifiService(  726): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4623, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  726): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  726): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  726): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  726): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  726): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  726): 	at dalvik.system.NativeStart.run(Native Method)
W/BluetoothAdapterService( 3151): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3151): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=4623, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/InputMethodManagerService(  726): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  726): [BT Setting State] State =11
I/WifiService(  726): disconnect: pid=4623, uid=10179
E/WifiHW  (  726): ##################### set firmware type 0 #####################
I/jxcore-log( 4623): Radios toggled
I/jxcore-log( 4623): 
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/PhoneApp( 1241): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
W/BluetoothAdapterService( 3151): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,I/QuickConnect[1.1][2] ( 3114): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
,W/BluetoothAdapterService( 3151): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3151): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3151): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 3151): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3151): Not skipping com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3151): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3151): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3151): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3151): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3151): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/QuickConnect[1.1][2] ( 3114): HeadsetProfile.onServiceConnected - Bluetooth service connected
,D/HeadsetService( 3151): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3151): classInitNative: succeeds
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3151): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3151): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3151): Not skipping com.android.bluetooth.pan.PanService
D/HeadsetStateMachine( 3151): Version 1.6
,D/HeadsetStateMachine( 3151): make
,W/BluetoothAdapterService( 3151): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3151): Not skipping com.android.bluetooth.map.BluetoothMapService
,I/BluetoothAdapterState( 3151): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,E/HeadsetStateMachine( 3151): # of Max HF connection is 2
,I/bluedroid( 3151): get_profile_interface handsfree
,D/BluetoothAtMessage( 3151): createCMTIContentObservers
,D/HeadsetStateMachine( 3151): Enter Disconnected: -2
,E/HeadsetStateMachine( 3151): set to mRemoteBrsf = 0
D/HeadsetStateMachine( 3151): map size, before remove : 0
D/HeadsetStateMachine( 3151): map size, after remove: 0
,D/HeadsetStateMachine( 3151): mNextConnectingDevice : null
,D/BluetoothA2dp(  726): Proxy object connected
,D/BluetoothA2dp( 3114): Proxy object connected
,D/QuickConnect[1.1][2] ( 3114): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/A2dpService( 3151): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 3151): classInitNative: succeeds
,D/A2dpStateMachine( 3151): make
,I/bluedroid( 3151): get_profile_interface a2dp
,I/GKI_LINUX( 3151): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothAvrcpServiceJni( 3151): classInitNative: succeeds
,I/bluedroid( 3151): get_profile_interface avrcp
,D/A2dpStateMachine( 3151): Enter Disconnected: -2
,D/MediaFocusControl(  726): >>> registerRemoteControlDisplay
,E/MediaFocusControl(  726): Error updating focussed RCC to RCD 
E/MediaFocusControl(  726): java.util.EmptyStackException
E/MediaFocusControl(  726): 	at java.util.Stack.peek(Stack.java:57)
E/MediaFocusControl(  726): 	at android.media.MediaFocusControl.registerRemoteControlDisplay_int(MediaFocusControl.java:2308)
E/MediaFocusControl(  726): 	at android.media.MediaFocusControl.registerRemoteControlDisplay(MediaFocusControl.java:250)
E/MediaFocusControl(  726): 	at android.media.AudioService.registerRemoteControlDisplay(AudioService.java:6425)
E/MediaFocusControl(  726): 	at android.media.IAudioService$Stub.onTransact(IAudioService.java:593)
E/MediaFocusControl(  726): 	at android.os.Binder.execTransact(Binder.java:404)
E/MediaFocusControl(  726): 	at dalvik.system.NativeStart.run(Native Method)
,I/BluetoothHidServiceJni( 3151): classInitNative: succeeds
,D/BluetoothInputDevice( 3114): Proxy object connected
,D/QuickConnect[1.1][2] ( 3114): HidProfile.onServiceConnected - Bluetooth service connected
,D/HidService( 3151): Received start request. Starting profile...
I/bluedroid( 3151): get_profile_interface hidhost
,D/HidService( 3151): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 3151): classInitNative: succeeds
,D/HealthService( 3151): Received start request. Starting profile...
,I/bluedroid( 3151): get_profile_interface health
,I/BluetoothPanServiceJni( 3151): classInitNative(L105): succeeds
,D/BluetoothPan(  726): BluetoothPAN Proxy object connected
,D/PanService( 3151): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3151): initializeNative(L110): pan
,I/bluedroid( 3151): get_profile_interface pan
,D/BluetoothTethering(  726): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 3151): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 3151): mAccount : null
,D/HeadsetStateMachine( 3151): Try to query the phonestate on bind
,D/BluetoothPhoneService( 1241): handleMessage: 4
,V/BluetoothPhoneService( 1241): Call state Converted2: IDLE/IDLE -> 6
D/HeadsetStateMachine( 3151): Proxy object connected
,W/BluetoothHeadset( 1241): Proxy not attached to service
,D/HeadsetPhoneState( 3151): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3151): sendDeviceDataStateChanged
D/HeadsetStateMachine( 3151): Disconnected process message: 11
,D/HeadsetPhoneState( 3151): Signal level : previous=0 curr=0
D/HeadsetStateMachine( 3151): Disconnected process message: 20
D/BluetoothAdapterService( 3151): Profile still not running:com.android.bluetooth.hdp.HealthService
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3151): Disconnected process message: 10
D/HeadsetPhoneState( 3151): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3151): Disconnected process message: 11
,D/BluetoothAdapterService( 3151): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3151): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3151): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3151): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterState( 3151): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3151): enable
,D/GKI_LINUX( 3151): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 3151): Calling BTA_HhEnable
,E/bt-btif ( 3151): btif_storage_get_adapter_property service_mask:0x140040
E/BluetoothServiceJni( 3151): populateRssiValuesNative
,I/bluedroid( 3151): getModelRssiValues
,E/BluetoothServiceJni( 3151): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/BluetoothA2dp( 2025): Proxy object connected
,D/dalvikvm(  726): GC_EXPLICIT freed 2247K, 58% free 23272K/55384K, paused 14ms+23ms, total 257ms
,E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
,D/BluetoothNotiBroadcastReceiver( 1306): onReceive
,D/BtConfig.SecureMode( 3151): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 241
,E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BtConfig.SecureMode( 3151): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 241
,E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/BtConfig.SecureMode( 3151): isSecureModeOn:false
E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 241
,D/GKI_LINUX( 3151): release_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,D/AuthorizationBluetoothService( 1321): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,D/BtConfig.SecureMode( 3151): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 241
,E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 3151): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BtConfig.SecureMode( 3151): isSecureModeOn:false
E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 241
E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BtConfig.SecureMode( 3151): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 241
,E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 10
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 241
E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 10
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 241
E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
E/BluetoothRemoteDevices( 3151): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 241
E/bt-btif ( 3151): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 3151): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 3151): btif_sock_init: !radio_req && !rfc_init
D/IOP_DB_BT( 3151): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 3151): db_open: db_open : handle 2012984088l, read 9734 bytes onto local cache
D/IOP_DB_BT( 3151): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 3151): db_query: result 1
I/        ( 3151): iop_db_open: iop_db_open status 0
D/GKI_LINUX( 3151): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
I/bte_conf( 3151): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3151): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 3151): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3151): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 3151): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3151): ScanMode =  20
D/BluetoothAdapterProperties( 3151): State =  11
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
I/BluetoothAdapterState( 3151): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3151): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3151): updateAdapterState state is 12
,D/BluetoothAdapterService( 3151): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothInputDevice( 3114): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(1113808112)( 3151): Register RemoteMessageListener
D/BluetoothA2dp(  726): onBluetoothStateChange: up=true
D/HeadsetService( 3151): registerMessageListener
D/BluetoothAdapterService( 3151): Autoconnection is available 
D/BluetoothAdapterService( 3151): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 3151): starting service from this receiver
D/HeadsetStateMachine( 3151): Disconnected process message: 70
D/HeadsetStateMachine( 3151): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@42678840
D/BluetoothA2dp( 3114): onBluetoothStateChange: up=true
I/BluetoothPbapService( 3151): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
D/BluetoothA2dp( 2025): onBluetoothStateChange: up=true
I/BluetoothPbapService( 3151): Handler(): got msg=1
D/BluetoothAdapterService( 3151): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[91]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[92]}
D/bluedroid( 3151): init_wake_lock lock_fd:91, unlock_fd:92
,W/ContextImpl( 3151): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,D/BluetoothPanServiceJni( 3151): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,I/BluetoothAdapterState( 3151): Entering On State from state = 11
,V/BluetoothPbapService( 3151): PBAP Service initSocket try: 0
,W/BluetoothAdapter( 3151): getBluetoothService() called with no BluetoothManagerCallback
I/WifiTrafficPoller(  726): mBoosterFLAG : 2
,I/WifiTrafficPoller(  726): current booster mode : BTCoexMode
D/BluetoothAdapterService(1113808112)( 3151): Get Bonded Devices being called
D/PhoneApp( 1241): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
,D/BluetoothHeadset( 1241): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@42362100, true
,D/BluetoothHeadset( 1241): registerMessageListener
W/InputMethodManagerService(  726): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  726): [BT Setting State] State =12
,I/InputMethodManagerService(  726): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/QuickConnect[1.1][2] ( 3114): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
,D/HeadsetService( 3151): registerMessageListener
,E/BluetoothServiceJni( 3151): SOCK FLAG = 1 ***********************
D/HeadsetService( 3151): registerMessageListener
D/BluetoothPbapService( 3151): PBAP Socket is BluetoothServerSocket
D/HeadsetStateMachine( 3151): Disconnected process message: 70
,D/HeadsetStateMachine( 3151): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@4270a328
,D/PhoneApp( 1241): registerMessageListener
,D/BluetoothMapMasInstance( 3151): set MAP SDP message type : 1
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/BluetoothAdapter( 3151): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3151): SOCK FLAG = 3 ***********************
D/STATUSBAR-IconMerger( 1068): checkOverflow(336), More:false, Req:false Child:2
,D/LocalBluetoothProfileManager( 1306): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1306): Adding local HEADSET profile
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1306): BTStateChangeCB is registed
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
E/BluetoothHeadset( 1306): BluetoothHeadset service is binded
,D/Bluetoothsap( 1306): bindService called to Bluetooth SAP Service
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 1306): PANU : true
,D/LocalBluetoothProfileManager( 1306): Adding local MAP profile
,D/BluetoothMap( 1306): Create BluetoothMap proxy object
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1306): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1306): LocalBluetoothProfileManager construction complete
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/DockEventReceiver( 1306): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 1306): onReceive
D/BluetoothA2dp( 1306): Proxy object connected
D/A2dpProfile( 1306): Bluetooth service connected
D/GKI_LINUX( 3151): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
,D/AuthorizationBluetoothService( 1321): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1321): Proximity feature is not enabled.
,D/HeadsetProfile( 1306): Bluetooth service connected
,D/BluetoothInputDevice( 1306): Proxy object connected
,D/HidProfile( 1306): Bluetooth service connected
,D/BluetoothPan( 1306): BluetoothPAN Proxy object connected
,D/PanProfile( 1306): Bluetooth service connected
,D/BluetoothMap( 1306): Proxy object connected
,D/MapProfile( 1306): Bluetooth service connected
,D/BluetoothPbap( 1306): Proxy object connected
,D/PbapServerProfile( 1306): Bluetooth service connected
,W/BluetoothAdapter( 3151): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3151): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 3151): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 3151): Accept thread started.
,D/Tethering(  726): interfaceAdded wlan0
,E/Tethering(  726): No numeric data
,D/Tethering(  726): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  726): forceRefresh() from cache miss
,I/ConnectivityService(  726): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  726): interfaceLinkStateChanged wlan0, false
D/Tethering(  726): interfaceStatusChanged wlan0, false
,D/Tethering(  726): InitialState.processMessage what=4
,E/Tethering(  726): No numeric data
,D/Tethering(  726): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering(  726): interfaceAdded p2p0
,D/Tethering(  726): p2p0 is not a tetherable iface, ignoring
,D/NtpTrustedTime(  726): forceRefresh Fail.
I/ConnectivityService(  726): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  726): interfaceLinkStateChanged p2p0, false
,D/Tethering(  726): interfaceStatusChanged p2p0, false
V/NetworkStats(  726): performPollLocked(flags=0x1)
,I/WifiHW  (  239): wifi_change_fw_path(): fwpath = sta
,D/SoftapController(  239): Softap fwReload - Ok
,D/NtpTrustedTime(  726): forceRefresh() from cache miss
D/NtpTrustedTime(  726): forceRefresh Fail.
,D/NtpTrustedTime(  726): forceRefresh() from cache miss
,D/NtpTrustedTime(  726): forceRefresh Fail.
D/CommandListener(  239): Setting iface cfg
,D/CommandListener(  239): Trying to bring down wlan0
V/NetworkStats(  726): performPollLocked() took 21ms
V/NetworkStats(  726): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  726): forceRefresh() from cache miss
,D/NtpTrustedTime(  726): forceRefresh Fail.
,D/WifiHW  (  726): Skip the update_ctrl_interface
,D/WifiHW  (  726): Skip the update_ctrl_interface
,E/WifiHW  (  726): supplicant_name : p2p_supplicant
V/NetworkStats(  726): performPollLocked() took 18ms
,D/WifiMonitor(  726): startMonitoring(wlan0) with mConnected = false
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/knox    ( 3055): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 3055): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3055): KNOXAgentService : onCreate()
D/knox    ( 3055): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3055): KNOXAgentService. startJobThread() start
D/knox    ( 3055): KNOXAgentService. JobThread()
D/knox    ( 3055): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3055): KNOXAgentService. startJobThread() wait
D/GKI_LINUX( 3151): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/SELinux ( 4850): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4850):  
,I/wpa_supplicant( 4848): wpa_supplicant v2.1-devel-4.4.22014-11-04/18:06:52
I/wpa_supplicant( 4848): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 4848): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4848): >>>>> Not GET KEY, IV <<<<<
,D/knox    ( 3055): KNOXAgentService : onDestroy().
E/wpa_supplicant( 4848): getIMSI cannot open file
,E/wpa_supplicant( 4848): Interworking config: - SIM READ ERROR
,D/knox    ( 3055): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 4850): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4850):  
I/SELinux ( 4850):  
,I/SELinux ( 4850): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4850): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4850): >>>>> Normal User
,E/dalvikvm( 4850): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 4850): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4850): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4850): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4850): Added TimaKesytore provider
,I/wpa_supplicant( 4848): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4848): getIMSI cannot open file
,E/wpa_supplicant( 4848): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 4848): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4848): rfkill: Cannot open RFKILL control device
D/Tethering(  726): interfaceLinkStateChanged wlan0, false
D/Tethering(  726): interfaceStatusChanged wlan0, false
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=4850, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
,I/wpa_supplicant( 4848): wlan0: Setting scan request: 0 sec 100000 usec
,I/ActivityManager(  726): Killing 3672:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/wpa_supplicant( 4848): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4848): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4848): rfkill: Cannot open RFKILL control device
D/Tethering(  726): interfaceLinkStateChanged p2p0, false
,D/Tethering(  726): interfaceStatusChanged p2p0, false
D/Tethering(  726): interfaceLinkStateChanged p2p0, false
,D/Tethering(  726): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4848): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4848): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
I/wpa_supplicant( 4848): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4848): Skip scan - bUseNetwork false
,D/WifiStateMachine(  726): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative(  726): callSECApiString - ID [21]
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
,I/wpa_supplicant( 4848): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 4848): wlan0: HS20_DISABLED_COMPLETE normal
,I/knox    ( 3055): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3055): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
I/knox    ( 3055): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3055): KNOXAgentService : onCreate()
D/knox    ( 3055): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 3055): KNOXAgentService. startJobThread() start
D/knox    ( 3055): KNOXAgentService. JobThread()
D/knox    ( 3055): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3055): KNOXAgentService. startJobThread() wait
,D/knox    ( 3055): KNOXAgentService : onDestroy().
,D/knox    ( 3055): ModuleBase.cancelAllAlarmManageModule()
,D/WifiNative(  726): callSECApiInt - ID [65]
,E/WifiConfigStore(  726): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative(  726): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 4848): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 4848): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 4848): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 4848): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 4848): First Scan Start
,I/wpa_supplicant( 4848): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 3014): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine(  726): Set the Nv default ccode
,D/WifiStateMachine(  726): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine(  726): HS20_DISABLED_COMPLETEnormal
D/WifiP2pService(  726): P2pDisabledState{ what=131203 }
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.enterprise.wifi.WifiPolicy.asyncEnableNetwork:3065 com.android.server.enterprise.wifi.WifiPolicy.edmUpdateConfiguredNetworks:2530 com.android.server.enterprise.wifi.WifiPolicy$2$2.run:3022 java.lang.Thread.run:841 
,I/wpa_supplicant( 4848): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/CommandListener(  239): Setting iface cfg
,D/CommandListener(  239): Trying to bring up p2p0
,D/WifiMonitor(  726): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  726): P2pEnablingState
D/WifiP2pService(  726): P2pEnablingState{ what=147457 }
D/WifiP2pService(  726): P2p socket connection successful
D/WifiP2pService(  726): P2pEnabledState
,D/WifiP2pService(  726): sending p2p connection changed broadcast: IDLE
,E/WifiStateMachine(  726): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/QuickConnect[1.1][2] ( 3114): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
D/WifiDisplayController(  726): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  726): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  726): disconnect
D/WifiDisplayController(  726): updateConnection
D/WifiDisplayController(  726): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  726): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 3114): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,D/QuickConnect[1.1][2] ( 3114): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/WifiDisplayAdapter(  726): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/WifiP2pStateTracker(  726): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDisplayController(  726): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/QuickConnect[1.1][2] ( 3114): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 4149): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/WifiDisplayController(  726): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy S5-2
D/WifiDisplayController(  726):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiDisplayController(  726):  primary type: 10-0050F204-5
D/WifiDisplayController(  726):  secondary type: null
D/WifiDisplayController(  726):  wps: 0
D/WifiDisplayController(  726):  grpcapab: 0
D/WifiDisplayController(  726):  devcapab: 0
D/WifiDisplayController(  726):  status: 3
D/WifiDisplayController(  726):  wfdInfo: null
D/WifiDisplayController(  726):  groupownerAddress: null
D/WifiDisplayController(  726):  GOdeviceName: null
D/WifiDisplayController(  726):  interfaceAddress: 
D/WifiDisplayController(  726):  SConnectInfo : null
,D/WifiP2pService(  726): DeviceAddress: 3a:06:dd
D/FileShare-Server( 4149): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,D/WifiP2pService(  726): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  726): InactiveState
,D/WifiP2pService(  726): InactiveState{ what=139287 }
D/WifiP2pService(  726): P2pEnabledState{ what=139287 }
,D/QuickConnect[1.1][2] ( 3114): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService(  726): DefaultState{ what=139287 }
,D/Tethering(  726): interfaceLinkStateChanged p2p0, false
,D/Tethering(  726): interfaceStatusChanged p2p0, false
,I/GAV2    ( 4666): Thread[GAThread,5,main]: No campaign data found.
,I/wpa_supplicant( 4848): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4848): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4848): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 4848): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 4848): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 4848): Trying to associate with  'G700'
,I/wpa_supplicant( 4848): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 4848): Cmd 35609 not handled
D/Tethering(  726): interfaceLinkStateChanged wlan0, false
,D/Tethering(  726): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  726): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/SMD     (  242): DCD ON
,E/wpa_supplicant( 4848): Cmd 35605 not handled
I/wpa_supplicant( 4848): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 4848): Associated with C0.AA.48
,I/wpa_supplicant( 4848): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  726): interfaceLinkStateChanged wlan0, false
,D/Tethering(  726): interfaceStatusChanged wlan0, false
D/Tethering(  726): interfaceLinkStateChanged wlan0, false
,D/Tethering(  726): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 4848): Cmd 35847 not handled
E/wpa_supplicant( 4848): Cmd 35848 not handled
,E/wpa_supplicant( 4848): Cmd 35605 not handled
D/Tethering(  726): interfaceLinkStateChanged wlan0, false
,D/Tethering(  726): interfaceStatusChanged wlan0, false
D/Tethering(  726): interfaceLinkStateChanged wlan0, true
,D/Tethering(  726): interfaceStatusChanged wlan0, true
,E/Tethering(  726): No numeric data
,I/wpa_supplicant( 4848): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 4848): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4848): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 4848): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/ConnectivityService(  726): defaultVal : 1, tetherEnabledInSettings : true
D/NtpTrustedTime(  726): forceRefresh() from cache miss
,D/NtpTrustedTime(  726): forceRefresh Fail.
,D/Tethering(  726): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiNative(  726): callSECApiVoid - ID [50]
V/NetworkStats(  726): performPollLocked(flags=0x1)
,D/Tethering(  726): interfaceLinkStateChanged wlan0, true
,D/Tethering(  726): interfaceStatusChanged wlan0, true
D/Tethering(  726): interfaceLinkStateChanged wlan0, true
,D/Tethering(  726): interfaceStatusChanged wlan0, true
,D/Tethering(  726): interfaceLinkStateChanged wlan0, true
,D/Tethering(  726): interfaceStatusChanged wlan0, true
D/Tethering(  726): interfaceLinkStateChanged wlan0, true
,D/Tethering(  726): interfaceStatusChanged wlan0, true
,V/NetworkStats(  726): performPollLocked() took 28ms
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 4887): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4887):  
,D/NtpTrustedTime(  726): forceRefresh() from cache miss
,D/NtpTrustedTime(  726): forceRefresh Fail.
,D/dalvikvm(  249): GC_EXPLICIT freed 43K, 50% free 9509K/19008K, paused 2ms+3ms, total 31ms
,I/SELinux ( 4887): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4887):  
I/SELinux ( 4887):  
,I/SELinux ( 4887): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4887): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4887): >>>>> Normal User
,E/dalvikvm( 4887): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 4887): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/19008K, paused 1ms+4ms, total 26ms
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/WifiP2pService(  726): InactiveState{ what=143375 }
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/19008K, paused 1ms+4ms, total 21ms
D/WifiP2pService(  726): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider( 4887): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4887): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4887): Added TimaKesytore provider
,I/System.out( 4887): Inside WakeupProvider
,I/System.out( 4887): Inside onCreate() of WakeupTriggerProvide
,I/dhcpcd  ( 4903): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 4903): bssid match
,I/VlingoApplication( 4887): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 4887): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 4887): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 4887): initQueue()
I/ActivityManager(  726): Killing 3720:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/WifiP2pService(  726): InactiveState{ what=143375 }
,D/WifiP2pService(  726): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/WifiStateMachine(  726): VerifyingLinkState enter
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  726): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  726): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  726): evaluateTrafficStatsPolling
D/ConnectivityService(  726): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  726): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/WifiStateMachine(  726): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  726): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  726): mBoosterFLAG : 2
,I/WifiTrafficPoller(  726): current booster mode : BTCoexMode
D/ConnectivityService(  726): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
E/ConnectivityService(  726): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  726): net.tcp.delack.wifi not found in system properties. Using defaults
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  726): handleConnectivityChange: setting default proxy info 
,V/RouteController(  239): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,V/RouteController(  239): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  239): RTNETLINK answers: No such file or directory
,V/RouteController(  239): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,D/Toast   ( 1306):  checkMirrorLinkEnabled returns : false
D/Toast   ( 1306): showing allowed
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,V/RouteController(  239): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,I/SurfaceFlinger(  248): id=19 createSurf (1x1),1 flag=4, Uoast
,V/NetworkStats(  726): updateIfacesLocked()
,V/NetworkStats(  726): performPollLocked(flags=0x1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/NtpTrustedTime(  726): forceRefresh() from cache miss
,D/PowerManagerService(  726): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=726
,V/NetworkStats(  726): performPollLocked() took 16ms
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  726): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449683684353 mCachedNtpElapsedRealtime : 129823 mCachedNtpCertainty : 17
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
V/NetworkStats(  726): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/Tethering(  726): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  726): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  726): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
D/        (  726): Setting time of day to sec=1449683684
D/        (  726): Trying to open a file
D/        (  726): File Open Success
,D/        (  726): File Close Success
,I/        (  726): DRM_TIME_PATH CHMOD 660 for resetState done 
,W/        (  726): Unable to set rtc to 1449683684: Invalid argument
V/AlarmManager(  726): waitForAlarm result :65536
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
D/StatusBar-DoNotDistrub( 1068): Received intent with android.intent.action.TIME_SET action
D/StatusBar-DoNotDistrub( 1068): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar-DoNotDistrub( 1068): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,I/AudioService(  726): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 1068): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService(  726): manageDisableList what=0x0 pkg=com.android.systemui
,W/Settings(  726): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionTIME_SET
D/accuweather( 1447): [KK AccuPhone]>>> SWW:452 [0:0] doChangeDayOrNight : 1
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
,I/PCWCLIENTTRACE_PushUtil( 4453): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4453): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4453): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4453): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
V/AlarmManager(  726): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  726): waitForAlarm result :4
W/SEC_DRM_PLUGIN_Playready(  250): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1449683684 after conversion: 1449683684
,W/SEC_DRM_PLUGIN_Playready(  250): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1449683684 after conversion: 1449683684
,I/SensorManagerA(  726): getReportingMode :: sensor.mType = 5
D/Sensors (  726): LightSensor setDelay = 200000000
D/Sensors (  726): LightSensor setSensorDelay = 200000000
D/Sensors (  726): Light sensor flush: not enabled 0
D/Sensors (  726): LightSensor enable = 1
D/Sensors (  726): LightSensor enableSensor = 1
,I/NetworkMonitor( 3755): type=WIFI subType= reason=null isConnected=true
,D/SensorManager(  726): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/LocSvc_java(  726): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  726): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  726): ignore wifi update if we are not in OPENING or CLOSING
D/STATUSBAR-NotificationService(  726): received android.intent.action.DORMANT_MODE_OFF
D/LightsService(  726): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 726) 
D/LightsService(  726): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,I/SELinux ( 4989): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4989):  
,I/SELinux ( 4989): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4989):  
I/SELinux ( 4989):  
,I/SELinux ( 4989): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4989): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4989): >>>>> Normal User
,E/dalvikvm( 4989): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 4989): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4989): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4989): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4989): Added TimaKesytore provider
,D/dalvikvm( 1759): GC_CONCURRENT freed 1641K, 39% free 11748K/19008K, paused 3ms+3ms, total 49ms
,D/Sensors (  726): LightSensor enable = 0
,D/Sensors (  726): LightSensor enableSensor = 0
,D/SensorManager(  726): unregisterListener ::   
D/LightsService(  726): [SvcLED]  onSensorChanged::light value = 0
,D/LightsService(  726): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/SELinux ( 5007): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5007):  
,I/SELinux ( 5007): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5007):  
I/SELinux ( 5007):  
,I/SELinux ( 5007): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5007): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5007): >>>>> Normal User
,E/dalvikvm( 5007): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=4989, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
E/SELinux ( 5007): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5007): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5007): Cannot add TimaSignature Service, License check Failed
I/dalvikvm( 1759): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1759): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x003d
,D/ActivityThread( 5007): Added TimaKesytore provider
,E/ActivityThread( 1759): Failed to find provider info for com.android.contacts.metadata
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5007, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,D/SyncManager(  726): failed sync operation 
,D/SyncManager(  726): not retrying sync operation because the error is a hard error: 
,I/SELinux ( 5030): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5030):  
,D/DelayedSyncController( 5007): Delaying sync.
,I/SELinux ( 5030): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5030):  
I/SELinux ( 5030):  
,I/SELinux ( 5030): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5030): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5030): >>>>> Normal User
,E/dalvikvm( 5030): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5030): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5030): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5030): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5030): Added TimaKesytore provider
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5030, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  726): Killing 3738:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,E/SMD     (  242): DCD ON
,I/ActivityManager(  726): Killing 3958:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,I/SELinux ( 5044): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5044):  
,I/SELinux ( 5044): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5044):  
I/SELinux ( 5044):  
,I/SELinux ( 5044): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5044): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5044): >>>>> Normal User
,E/dalvikvm( 5044): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5044): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5044): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5044): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5044): Added TimaKesytore provider
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/DelayedSyncController( 5007): Delaying sync.
,D/PicasaService( 3834): start picasa sync
,D/PicasaService( 3834): end picasa sync
W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5044, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5044): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5044): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449683685827
,I/KLMS-2.3.201 : ( 5044): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/ActivityManager(  726): Killing 3983:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 5061): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5061):  
I/LocationTagReadyService( 2373): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 2373): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2373): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2373): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 5065): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5065):  
I/SELinux ( 5061): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5061):  
I/SELinux ( 5061):  
,I/SELinux ( 5061): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5061): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5061): >>>>> Normal User
,E/dalvikvm( 5061): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5061): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/GallerySearchProvider( 3834): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/TimaKeyStoreProvider( 5061): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5061): Cannot add TimaSignature Service, License check Failed
I/SELinux ( 5065): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5065):  
I/SELinux ( 5065):  
,I/SELinux ( 5065): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/ActivityThread( 5061): Added TimaKesytore provider
,E/SELinux ( 5065): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5065): >>>>> Normal User
,E/dalvikvm( 5065): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5065): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5065): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5065): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5065): Added TimaKesytore provider
,D/AmoledAdjustTimer(  726): prevTemp = 290, currTemp = 291, prevStep = 4, currStep = 4
,D/dalvikvm(  726): GC_EXPLICIT freed 2628K, 58% free 23370K/55384K, paused 7ms+14ms, total 154ms
,I/ActivityManager(  726): Killing 3951:com.android.calendar/u0a142 (adj 15): empty #43
,D/dalvikvm( 1208): GC_EXPLICIT freed 435K, 48% free 10049K/19008K, paused 3ms+5ms, total 43ms
W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5061, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5086): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5086):  
,D/SO_AGENT( 5061): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5061): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 5086): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5086):  
I/SELinux ( 5086):  
,I/SELinux ( 5086): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5086): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5086): >>>>> Normal User
,E/dalvikvm( 5086): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5086): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5086): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5086): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5086): Added TimaKesytore provider
,I/SA      ( 4609): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4609): [BDLM] already registered in spp
I/SA      ( 4609): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4609): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4609): [SLFUCHKMGR] constructor called
,V/KVNProvider( 5086): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5086): getFindoCursor query string : 
,I/SA      ( 4609): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4609): [OR] == isSIMCardReady false ==
I/SA      ( 4609): [SCU] == networkStateCheck == true
,I/SA      ( 4609): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4609): isChinaCountryCode : false
I/SA      ( 4609): [OR] == networkStateCheck true ==
,V/KVNProvider( 5086): getTagSearchCursor() tagSearchCursor count : 0
,I/ActivityManager(  726): Killing 4001:com.android.providers.calendar/u0a44 (adj 15): empty #43
,I/SA      ( 4609): [OR] GetMyCountryZoneTask
,I/SA      ( 4609): [OR] onReceive END
,I/SA      ( 4609): [SRS] prepareGetMyCountryZone
,I/ActivityManager(  726): Killing 4005:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,I/dalvikvm( 4564): Total arena pages for JIT: 11
,I/dalvikvm( 4564): Total arena pages for JIT: 12
D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
I/dalvikvm( 4564): Total arena pages for JIT: 13
I/dalvikvm( 4564): Total arena pages for JIT: 14
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,I/SELinux ( 5106): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5106):  
,I/SA      ( 4609): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4609): [SSP] query invoked
,I/SELinux ( 5106): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5106):  
I/SELinux ( 5106):  
,I/SELinux ( 5106): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5106): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5106): >>>>> Normal User
,E/dalvikvm( 5106): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5106): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 4609): [TPMU] GetMccFromDB : null
I/SA      ( 4609): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4609): [TPM] isNoProxy(default) : true
,I/SA      ( 4609): [RC New] Execute method=[GET] start
,D/btif_config_util( 3151): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TimaKeyStoreProvider( 5106): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5106): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5106): Added TimaKesytore provider
,I/sCloudBackupApp( 5106): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5106): Other Intent
I/ActivityManager(  726): Killing 3933:com.sec.phone/1001 (adj 15): empty #43
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:37 [0:0] oR : create UI manager : start
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:89 [0:0] getInstance
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1447): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 1447): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,W/DriveInitializer( 1759): Awaiting to be initialized
,W/DriveInitializer( 1759): Background init thread started
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 1759): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,D/accuweather( 1447): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,W/Vold    (  229): Returning OperationFailed - no handler for errno 30
D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1447): [KK AccuPhone]>>> DBH:3047 [0:0] gADWI : count = 0
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/DriveInitializer( 1759): Background init thread ended
,I/SELinux ( 5132): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5132):  
,I/SELinux ( 5132): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5132):  
I/SELinux ( 5132):  
I/SELinux ( 5132): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5132): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5132): >>>>> Normal User
E/dalvikvm( 5132): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10106 ]
,E/SELinux ( 5132): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5132): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5132): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5132): Added TimaKesytore provider
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5132, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/HeadlinesChannelApplication( 5132): [onCreate]
D/Headlines( 5132): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,I/System.out( 4609): Thread-446(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4609): Thread-446(ApacheHTTPLog):isShipBuild true
,I/System.out( 4609): Thread-446(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/HeadlinesChannelUtil( 5132): getCountryCode(): countryCode = PL
,D/Headlines( 5132): Breath.onCreate
,D/HeadlinesCardManager( 5132): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 5132): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 5132): CardProvider Library : 13
,I/SELinux ( 5148): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5148):  
,D/MagazineService::CardProviderContentProvider( 4717): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 4717): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5132): registerCardProvider: provider already exists.
,I/Headlines( 5132): HeadlinesDataCenter ctor
,I/Headlines( 5132): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 5132): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 5132): HeadlinesCardManager : constructor welcome :YES
,I/SELinux ( 5148): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5148):  
I/SELinux ( 5148):  
,I/SELinux ( 5148): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5148): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5148): >>>>> Normal User
,E/dalvikvm( 5148): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5148): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/Headlines( 5132): Breath timer started. interval : 30000
,D/Headlines( 5132): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5132): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5132): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5132): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5132): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5132): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5132): requestUpdateNewsWelcomeCard !!! no welcome card
,D/TimaKeyStoreProvider( 5148): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5148): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5148): Added TimaKesytore provider
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5148): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,W/Vold    (  229): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5148): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 5148): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 5148): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5148): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,V/WebViewChromium( 5148): Binding Chromium to the main looper Looper (main, tid 1) {423022f0}
,I/chromium( 5148): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5148): Initializing chromium process, renderers=0
,E/WifiStateMachine(  726): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/chromium( 5148): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5148): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5148): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5148): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5148): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5148): Remote Branch: 
I/Adreno-EGL( 5148): Local Patches: 
I/Adreno-EGL( 5148): Reconstruct Branch: 
,I/NSApplication( 5148): Starting up...
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5148, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3114): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  726): Killing 3878:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
I/QuickConnect[1.1][2] ( 3114): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3114): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42636b98
,I/SELinux ( 5185): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5185):  
,D/dalvikvm(  249): GC_EXPLICIT freed 44K, 50% free 9509K/19008K, paused 2ms+2ms, total 24ms
,D/SSRMv2:SIOP(  726): SIOP:: AP = 330, Delta = 20
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/19008K, paused 2ms+3ms, total 19ms
,I/SELinux ( 5185): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5185):  
I/SELinux ( 5185):  
,I/SELinux ( 5185): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5185): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5185): >>>>> Normal User
,E/dalvikvm( 5185): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5185): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/19008K, paused 1ms+2ms, total 18ms
,D/TimaKeyStoreProvider( 5185): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5185): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5185): Added TimaKesytore provider
,D/RCPManagerService(  726): exchangeData() failure , invalid userId
,D/RCPManagerService(  726): exchangeData() failure , invalid userId
,I/SurfaceFlinger(  248): id=19 Removed Uoast (11/12)
,I/SurfaceFlinger(  248): id=19 Removed Uoast (-2/12)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  726): Killing 3014:com.google.android.talk/u0a105 (adj 15): empty #43
D/PowerManagerService(  726): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=726 (0x0)
D/PowerManagerService(  726): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=726, ws=WorkSource{1000}) (elapsedTime=3440)
,D/RCPManagerService(  726): exchangeData() failure , invalid userId
,I/SA      ( 4609): [RC New] [v2liruge] api execute + 1246
,I/SA      ( 4609): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4609): AsyncTask #1 calls detatch()
,I/SA      ( 4609): [TPMU] getNetworkMcc : 
,I/SA      ( 4609): [SCU] saveMccToPreferece Start
,I/SA      ( 4609): [SCU] RegionMCC : 260
,I/SA      ( 4609): [SSP] query invoked
,I/SA      ( 4609): [TPMU] GetMccFromDB : null
I/SA      ( 4609): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4609): [SCU] saveMccToPreferece End
,I/SA      ( 4609): [RC New] executeRequest [v2liruge] end. 1273
,I/SA      ( 4609): [RC New] Execute end
I/SA      ( 4609): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4609): [OR] GetMyCountryZoneTask Success
,D/RCPManagerService(  726): exchangeData() failure , invalid userId
,D/RCPManagerService(  726): exchangeData() failure , invalid userId
,D/RCPManagerService(  726): exchangeData() failure , invalid userId
,I/SELinux ( 5204): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5204):  
I/ActivityManager(  726): Killing 4025:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,I/SELinux ( 5208): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5208):  
,I/SELinux ( 5204): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5204):  
I/SELinux ( 5204):  
,I/SELinux ( 5204): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5204): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5204): >>>>> Normal User
,E/dalvikvm( 5204): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5204): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5204): in addTimaSignatureService
I/SELinux ( 5208): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5208):  
I/SELinux ( 5208):  
,I/SELinux ( 5208): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5208): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5208): >>>>> Normal User
,E/dalvikvm( 5208): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5208): [DEBUG] seapp_context_lookup: seinfoCategory = release
,W/ActivityManager(  726): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/TimaKeyStoreProvider( 5204): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5204): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 5208): in addTimaSignatureService
D/TimaKeyStoreProvider( 5208): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5208): Added TimaKesytore provider
,I/ActivityManager(  726): Killing 2884:com.sec.knox.bridge/1000 (adj 15): empty #43
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5204, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/WaitQueueForNetworkActivate( 4768): notifyNetworkActivated
,I/HarmonyEASService(  726): Updating for all 1
,D/BadgeProvider( 5208): onCreate
,D/BadgeProvider( 5208): DatabaseHelper
W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5208, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5208): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ContextImpl( 4768): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager(  726): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/Launcher.Model( 1262): reloadBadges entered.
D/BadgeProvider( 5208): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5208): sendNotify, [notify] : null
D/BadgeProvider( 5208): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5208): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5208): update, [UpdateCount] : 1
,D/hcjo    ( 4768): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 4768): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 4768): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 4768): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 4768): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4768): exit::IDLE
,D/InitializeManagerStateMachine( 4768): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4768): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4768): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4768): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4768): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4768): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4768): entry::SUCCESS
,D/hcjo    ( 4768): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4768): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 4768): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4768): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4768): exit::SUCCESS
,D/InitializeManagerStateMachine( 4768): entry::IDLE
I/ActivityManager(  726): Killing 4214:com.wssyncmldm/1000 (adj 15): empty #43
,I/iu.SyncManager( 1759): SYNC; picasa accounts
,D/NetworkLogImpl( 1759): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1759): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1759): num queued entries: 0
,I/iu.UploadsManager( 1759): num updated entries: 0
,I/iu.SyncManager( 1759): NEXT; no task
,I/SELinux ( 5236): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5236):  
,I/SELinux ( 5236): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5236):  
I/SELinux ( 5236):  
,I/SELinux ( 5236): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5236): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5236): >>>>> Normal User
,E/dalvikvm( 5236): >>>>> com.android.calendar [ userId:0 | appId:10142 ]
,E/SELinux ( 5236): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5236): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5236): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5236): Added TimaKesytore provider
,I/GCM     ( 1321): GCM config loaded
,I/ActivityManager(  726): Killing 4360:com.android.defcontainer/u0a6 (adj 15): empty #43
D/BootCompletedReceiver(  726): onReceive
,I/KLMS-2.3.201 : ( 5044): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5044): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1449683688494
,I/KLMS-2.3.201 : ( 5044): StateImplV2() : dateTimeChanged() : Wed Dec 09 18:54:48 CET 2015
,D/SO_AGENT( 5061): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 5061): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 4609): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/Mms/MessagingNotification( 3776): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 3776): sDisableVibrateForCamera = false
,D/Mms/MessagingNotification( 3776): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 3776): isDefault true
,D/TP/MmsSmsProvider( 1241): match 8:Elapsed time : 5.467 ms
,E/SMD     (  242): DCD ON
,I/SELinux ( 5263): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5263):  
,D/TP/MmsSmsProvider( 1241): match 200:Elapsed time : 1.344 ms
,D/BadgeProvider( 5208): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/SELinux ( 5263): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5263):  
I/SELinux ( 5263):  
,I/SELinux ( 5263): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5263): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5263): >>>>> Normal User
,E/dalvikvm( 5263): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 5263): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/BadgeProvider( 5208): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5208): sendNotify, [notify] : null
D/BadgeProvider( 5208): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5208): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5208): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 3776): setBadgeCount(), count=0
,D/Launcher.Model( 1262): reloadBadges entered.
,D/MessagingNotification( 3776): remove alarm
,D/TimaKeyStoreProvider( 5263): in addTimaSignatureService
,D/dalvikvm(  726): WAIT_FOR_CONCURRENT_GC blocked 1ms
,D/TimaKeyStoreProvider( 5263): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5263): Added TimaKesytore provider
,D/Mms/MessagingNotification( 3776): updateAllHistoryAsRead()
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5263, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  726): Killing 3180:com.sec.android.inputmethod/1000 (adj 15): empty #43
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/dalvikvm(  726): GC_EXPLICIT freed 1291K, 58% free 23261K/55384K, paused 5ms+12ms, total 142ms
,I/ Time Manager ( 5263): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 5282): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5282):  
,D/Mms/MessagingNotification( 3776): [end]    nonBlockingUpdateMessageIndicator()
,I/SELinux ( 5282): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5282):  
I/SELinux ( 5282):  
,I/SELinux ( 5282): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5282): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5282): >>>>> Normal User
,E/dalvikvm( 5282): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 5282): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5282): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5282): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5282): Added TimaKesytore provider
,D/ConnectivityService(  726): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 5297): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5297):  
,I/ActivityManager(  726): Killing 4412:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 5297): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5297):  
I/SELinux ( 5297):  
,I/SELinux ( 5297): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5297): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5297): >>>>> Normal User
,E/dalvikvm( 5297): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 5297): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5297): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5297): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5297): Added TimaKesytore provider
,W/WifiP2pStateTracker(  726): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  726): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  726):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  726): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  726): updateSourceRoutes : no source routing conditions
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5297, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 5297): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 5297): ELMEngine.ELMEngine( context ).
,D/elm:14132( 5297): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 5297): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14132( 5297): ElmAgentService : onCreate()
,I/knox    ( 3055): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,W/ContextImpl( 3055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3055): MainReceiver.listeningToTimeDateChanges( context, intent ).
I/knox    ( 3055): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,I/SELinux ( 5310): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5310):  
D/knox    ( 3055): KNOXAgentService : onCreate()
D/knox    ( 3055): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3055): KNOXAgentService. startJobThread() start
D/knox    ( 3055): KNOXAgentService. JobThread()
D/knox    ( 3055): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3055): KNOXAgentService. startJobThread() wait
D/knox    ( 3055): KNOXAgentService : onDestroy().
,D/knox    ( 3055): ModuleBase.cancelAllAlarmManageModule()
,D/elm:14132( 5297): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14132( 5297): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14132( 5297): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14132( 5297): ModuleBase.resetCalllogAPIAlarm()
,D/elm:14132( 5297): ModuleBase.ModifySetAlarm()
,D/elm:14132( 5297): MDMBridge.getInstance()
,D/elm:14132( 5297): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 5297): ElmAgentService : onDestroy().
I/ActivityManager(  726): Killing 4427:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/SELinux ( 5310): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5310):  
I/SELinux ( 5310):  
,I/SELinux ( 5310): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5310): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5310): >>>>> Normal User
,E/dalvikvm( 5310): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10143 ]
,E/SELinux ( 5310): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5310): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5310): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5310): Added TimaKesytore provider
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5310, uid=10143 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5328): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5328):  
I/ActivityManager(  726): Killing 4439:com.android.musicfx/u0a24 (adj 15): empty #43
,I/SELinux ( 5328): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5328):  
I/SELinux ( 5328):  
,I/SELinux ( 5328): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5328): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5328): >>>>> Normal User
,E/dalvikvm( 5328): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
,E/SELinux ( 5328): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5328): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5328): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5328): Added TimaKesytore provider
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5328, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5340): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5340):  
I/ActivityManager(  726): Killing 4465:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty #43
,I/SELinux ( 5340): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5340):  
I/SELinux ( 5340):  
,I/SELinux ( 5340): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5340): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5340): >>>>> Normal User
,E/dalvikvm( 5340): >>>>> com.qualcomm.timeservice [ userId:0 | appId:10168 ]
,E/SELinux ( 5340): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5340): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5340): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5340): Added TimaKesytore provider
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5340, uid=10168 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm( 5340): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42627a10, skipping init
D/TimeService( 5340): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449683689706
D/        ( 5340): TimeServiceNative: User Time to be set is 1449683689706
D/QC-time-services( 5340): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5340): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 5340): Lib:time_genoff_operation: pargs->ts_val = 1449683689706
,D/QC-time-services(  289): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 5340): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  289): Daemon: genoff_handler: Process name is omm.timeservice
D/QC-time-services(  289): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449683689706
D/QC-time-services(  289): Daemon:genoff_opr: Base = 2, val = 1449683689706, operation = 0
D/QC-time-services(  289): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/13/70 9:51:57
D/QC-time-services(  289): Daemon:Value read from RTC seconds = 1072317000
D/QC-time-services(  289): Daemon:new time 1449683689706 
D/QC-time-services(  289): Daemon: delta 1448611372706 genoff 1448611372706 
D/QC-time-services(  289): Daemon:genoff_persistent_update: Writing genoff = 1448611372706 to memory
D/QC-time-services(  289): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  289): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  289): Updating the TOD offset
D/QC-time-services(  289): Daemon:genoff_persistent_update: Writing genoff = 1448611372706 to memory
D/QC-time-services(  289): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  289): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  289): Daemon:Update to modem bit set
D/QC-time-services(  289): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  289): Daemon: Base = 2, Value being sent to MODEM = 1133718889706
,E/QC-time-services( 5340): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  289): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  289): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  726): Killing 4500:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1465): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1465): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 1465): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1465): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 1759): Checkin interval check for package: unspecified last checkin: 1449576543959 min interval config: 0 actual interval: 107145848
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4453): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 4453): [hasSamungAccount] - No Samsung Account
,V/AlarmManager(  726): waitForAlarm result :4
,V/AlarmManager(  726): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/Mms/MessagesLockscreen( 3776): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
D/ContextualEventManager( 1068): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1068): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1068): updateContainer()
D/ContextualEventContainer( 1068): update()
D/ContextualEventContainer( 1068): handleUpdate()
D/ContextualEventManager( 1068): getTopEventView()
D/ContextualEventManager( 1068): getTopContextualEvent()
,I/SELinux ( 5358): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5358):  
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
,D/SecContextualClockFlightMode( 1068): handleUpdateClock()
,D/KeyguardProperties( 1068): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SELinux ( 5358): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5358):  
I/SELinux ( 5358):  
,I/SELinux ( 5358): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5358): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5358): >>>>> Normal User
,E/dalvikvm( 5358): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
,E/SELinux ( 5358): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
D/BatteryService(  726): stay LED for fully charged
D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  726): mCoverManager.getCoverState() : true
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3151): Disconnected process message: 10
,D/TimaKeyStoreProvider( 5358): in addTimaSignatureService
,W/linker  ( 4453): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/TimaKeyStoreProvider( 5358): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5358): Added TimaKesytore provider
I/CSTORAGE( 4453): ================================================
I/CSTORAGE( 4453):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 4453): ================================================
D/dalvikvm( 4453): No JNI_OnLoad found in /system/lib/libterrier.so 0x42627190, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4453): [GetString-S]
,I/terrier ( 4453): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 4453): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 4453): App is not loaded in QSEE
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/QSEECOMAPI: ( 4453): Loaded image: APP id = 5
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/QSEECOMAPI: ( 4453): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 4453): QSEECom_shutdown_app, app_id = 5
,E/terrier ( 4453): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 4453): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 4453): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4453): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4453): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 4453): [ensureRegistration] - No Samsung account
,I/VacuumService( 1220): Vacuum at: now=1449683690152 tag=VacuumService
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5358, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,D/Headlines( 5132): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5132): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5132): Breath 3268 latestRequest time : 1449683687098 current time : 1449683690366
,I/ActivityManager(  726): Killing 3847:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty #43
,E/SMD     (  242): DCD ON
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
I/PowerManagerService(  726): [PWL] Off : 75s ago
I/PowerManagerService(  726): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  726): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  726): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10084, pid=5282, ws=null) (elapsedTime=2999)
I/jxcore-log( 4623): Test app app.js loaded
I/jxcore-log( 4623): 
I/chromium( 4623): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/GAV2    ( 5148): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  726): waitForAlarm result :4
,V/AlarmManager(  726): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Finsky  ( 3501): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3501): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/Watchdog(  726): !@Sync 4
,E/SMD     (  242): DCD ON
,D/CaptivePortalTracker(  726): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  726): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  726): Checking http://216.58.209.46/generate_204
W/ActivityThread(  726): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out(  726): Thread-165(HTTPLog):isShipBuild true
,I/System.out(  726): Thread-165(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker(  726): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  726): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  726): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  726): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  726): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AmoledAdjustTimer(  726): prevTemp = 291, currTemp = 295, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 310, Delta = -20
,D/PreloadUpdateManagerStateMachine( 4768): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4768): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4768): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4768): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 4768): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4768): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4768): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4768): entry::IDLE
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3151): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,I/ActivityManager(  726): Waited long enough for: ServiceRecord{446e1828 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = -10
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager(  726): waitForAlarm result :4
,V/AlarmManager(  726): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3151): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,D/SyncManager(  726): failed sync operation 
,D/SyncManager(  726): not retrying sync operation because the error is a hard error: 
,E/ActivityThread( 1759): Failed to find provider info for com.android.contacts.metadata
E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 105s ago
,E/Watchdog(  726): !@Sync 5
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 296, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  726): waitForAlarm result :4
,V/AlarmManager(  726): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5132): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3151): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/Headlines( 5132): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5132): Breath 43547 latestRequest time : 1449683687098 current time : 1449683730647
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype for one-off execution 1432 seconds from now (1449683731270)
,D/GetConfigurationSnapshotOperation( 1220): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1220): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1220): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x00bb
,D/dalvikvm( 1321): GC_EXPLICIT freed 1402K, 44% free 10773K/19008K, paused 4ms+7ms, total 47ms
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  726): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1220): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1220): Thread-109(HTTPLog):isShipBuild true
,I/System.out( 1220): Thread-109(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1220): GC_CONCURRENT freed 1480K, 38% free 11903K/19008K, paused 6ms+7ms, total 72ms
,D/LocationManagerService(  726): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  726): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  726): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager(  726): waitForAlarm result :4
,V/AlarmManager(  726): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  726): waitForAlarm result :8
,D/Headlines( 5132): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): stay LED for fully charged
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3151): Disconnected process message: 10
,D/Headlines( 5132): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5132): Breath 60149 latestRequest time : 1449683687098 current time : 1449683747247
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 6
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 292, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService(  726): [PWL] Off : 140s ago
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3151): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager(  726): waitForAlarm result :8
,D/Headlines( 5132): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5132): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5132): Breath 90038 latestRequest time : 1449683687098 current time : 1449683777136
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3151): Disconnected process message: 10
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 7
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3151): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 180s ago
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3151): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager(  726): waitForAlarm result :8
,D/Headlines( 5132): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5132): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5132): Breath 120023 latestRequest time : 1449683687098 current time : 1449683807121
,D/Headlines( 5132): stop 
,D/Headlines( 5132): Breath.onDestroy : 
,I/ActivityManager(  726): Killing 2822:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3151): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 8
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm(  726): GC_CONCURRENT freed 3063K, 58% free 23558K/55384K, paused 25ms+58ms, total 568ms
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3151): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3151): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 225s ago
,E/Watchdog(  726): !@Sync 9
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3151): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService(  726): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  726): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  726): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  726): initializing...
,I/TLC_TIMA_PKM_initialize(  726): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  726): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  726): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  726): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  726): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  726): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  726): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  726): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  726): App is not loaded in QSEE
,D/QSEECOMAPI: (  726): Loaded image: APP id = 5
,I/TZ: qc_tlc_communication(  726): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  726): Trustlet response is completed
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  726): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  726): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  726): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  726): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  726): !@Sync 10
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3151): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3151): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 275s ago
,I/jxcore-log( 4623): Toggling radios to false
I/jxcore-log( 4623): 
,D/BluetoothAdapterService(1113808112)( 3151): unRegister RemoteMessageListener
,D/HeadsetService( 3151): registerMessageListener
,D/HeadsetStateMachine( 3151): Disconnected process message: 80
,D/HeadsetStateMachine( 3151): processUnRegisterMessageListener : 2
,D/BluetoothAdapterState( 3151): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,I/BluetoothAdapterState( 3151): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 3151): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3151): updateAdapterState state is 13
,I/BluetoothPbapService( 3151): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,E/bt-btif ( 3151): bta_jv_rfcomm_stop_server
,I/WifiManager( 4623): packageName : com.test.thalitest
,I/WifiManager( 4623): setWifiEnabled : false
,I/WifiService(  726): setWifiEnabled: false pid=4623, uid=10179
,D/BluetoothAdapterService( 3151): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService( 3151): Autoconnection is available 
,D/BluetoothAdapterService( 3151): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 3151): terminating service from this receiver
,W/ContextImpl( 3151): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,D/GKI_LINUX( 3151): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BluetoothAdapterState( 3151): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/PhoneApp( 1241): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,D/STATUSBAR-IconMerger( 1068): checkOverflow(336), More:false, Req:false Child:2
,I/QuickConnect[1.1][2] ( 3114): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
W/InputMethodManagerService(  726): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  726): [BT Setting State] State =13
,I/jxcore-log( 4623): Radios toggled
I/jxcore-log( 4623): 
,D/GKI_LINUX( 3151): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/BluetoothAdapterState( 3151): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 3151): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 3151): bta_jv_rfcomm_stop_server
,E/bt-btif ( 3151): cmd socket is not created
,E/BtOppRfcommListener( 3151): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3151): bta_jv_rfcomm_stop_server
,D/GKI_LINUX( 3151): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 3151): stopping Accept Thread
,E/SMD     (  242): DCD ON
,D/btif_config_util( 3151): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/BtOppRfcommListener( 3151): BluetoothSocket listen thread finished
,I/wpa_supplicant( 4848): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 4848): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 4848): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings(  726): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  726): ignore requestNetworkTransitionWakelock airplane:true
,D/WifiP2pService(  726): InactiveState{ what=143375 }
,D/WifiP2pService(  726): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/IOP_DB_BT( 3151): db_close: nbr users 0
,D/IOP_DB_BT( 3151): db_close: free database
,D/CommandListener(  239): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  726): evaluateTrafficStatsPolling
,D/BluetoothAdapterState( 3151): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 3151): isSecureModeOn:false
,W/BluetoothAdapterService( 3151): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3151): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 3151): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3151): Not skipping com.android.bluetooth.hfp.HeadsetService
D/ConnectivityService(  726): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  726): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  726): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  726): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  726): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  726): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/ConnectivityService(  726): Attempting to switch to mobile
,D/ConnectivityService(  726): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/HeadsetService( 3151): Received stop request...Stopping profile...
,D/QuickConnect[1.1][2] ( 3114): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
,W/BluetoothAdapterService( 3151): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3151): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3151): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3151): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3151): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3151): Not skipping com.android.bluetooth.hdp.HealthService
D/WifiP2pService(  726): InactiveState{ what=131204 }
D/WifiP2pService(  726): P2pEnabledState{ what=131204 }
,E/WifiStateMachine(  726): Error! unhandled message{ when=-55ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  726): Error! unhandled message{ when=-57ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
W/BluetoothAdapterService( 3151): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/WifiP2pService(  726): sending p2p connection changed broadcast: FAILED
W/BluetoothAdapterService( 3151): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothPbap( 1306): Proxy object disconnected
D/PbapServerProfile( 1306): Bluetooth service disconnected
,V/BluetoothEventManager( 1306): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/QuickConnect[1.1][2] ( 3114): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
W/BluetoothAdapterService( 3151): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3151): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterState( 3151): Stopping profile services that were post enabled
,D/QuickConnect[1.1][2] ( 3114): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
W/WifiP2pStateTracker(  726): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController(  726): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter(  726): onP2pDisconnected
D/IpRemoteDisplayController(  726): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  726): WfdBridgeServer is already null
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/GKI_LINUX( 3151): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
D/HeadsetProfile( 1306): Bluetooth service disconnected
,D/DockEventReceiver( 1306): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1306): onReceive
,V/RouteController(  239): /system/bin/ip -6 route del default table 2 2>&1
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,E/WifiStateMachine(  726): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/BluetoothAdapterService( 3151): Profile still running: com.android.bluetooth.hdp.HealthService
D/QuickConnect[1.1][2] ( 3114): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
D/QuickConnect[1.1][2] ( 3114): P2pHelper.cancelConnectPeer -  mTargetList clear all 
,D/QuickConnect[1.1][2] ( 3114): P2pHelper.removeP2pConfirm - skip: false
D/WifiDisplayController(  726): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  726): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  726): disconnect
D/WifiDisplayController(  726): updateConnection
D/WifiDisplayController(  726): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  726): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService(  726): sending p2p connection changed broadcast: DISCONNECTED
D/QuickConnect[1.1][2] ( 3114): CentralActionManager.removeHoldingIntentAll - all request done.
,D/QuickConnect[1.1][2] ( 3114): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,D/QuickConnect[1.1][2] ( 3114): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiDisplayAdapter(  726): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService(  726): P2pDisablingState
D/WifiP2pService(  726): P2pDisablingState{ what=139287 }
D/WifiP2pService(  726): DefaultState{ what=139287 }
D/WifiP2pService(  726): P2pDisablingState{ what=147458 }
D/WifiP2pService(  726): p2p socket connection lost
W/WifiP2pStateTracker(  726): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/QuickConnect[1.1][2] ( 3114): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 3114): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,W/BluetoothHeadsetServiceJni( 3151): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3151): Cleaning up Bluetooth Handsfree callback object
,D/A2dpService( 3151): Received stop request...Stopping profile...
D/Avrcp   ( 3151): Unregistering previous receiver
D/QuickConnect[1.1][2] ( 3114): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
V/RouteController(  239): RTNETLINK answers: No such process
,D/A2dpStateMachine( 3151): Exit Disconnected: -1
D/WifiP2pService(  726): P2pDisabledState
D/WifiDisplayController(  726): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiP2pService(  726): P2pDisabledState{ what=139376 }
D/WifiDisplayAdapter(  726): onP2pDisconnected
D/IpRemoteDisplayController(  726): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  726): WfdBridgeServer is already null
D/WifiP2pService(  726): DefaultState{ what=139376 }
E/WifiP2pService(  726): Unhandled message { what=139376 }
D/WifiP2pService(  726): P2pDisabledState{ what=139287 }
,D/WifiP2pService(  726): DefaultState{ what=139287 }
D/MediaFocusControl(  726): <<< unregisterRemoteControlDisplay
V/RouteController(  239): /system/bin/ip -6 rule del table 2 2>&1
D/BluetoothA2dp( 2025): Proxy object disconnected
D/BluetoothA2dp(  726): Proxy object disconnected
D/BluetoothA2dp( 3114): Proxy object disconnected
D/QuickConnect[1.1][2] ( 3114): A2dpProfile.onServiceConnected - Bluetooth service disconnected
D/BluetoothA2dp( 1306): Proxy object disconnected
D/A2dpProfile( 1306): Bluetooth service disconnected
D/HidService( 3151): Received stop request...Stopping profile...
D/HidService( 3151): Stopping Bluetooth HidService
D/BluetoothInputDevice( 1306): Proxy object disconnected
D/HidProfile( 1306): Bluetooth service disconnected
D/BluetoothInputDevice( 3114): Proxy object disconnected
D/QuickConnect[1.1][2] ( 3114): HidProfile.onServiceDisconnected - Bluetooth service disconnected
D/HealthService( 3151): Received stop request...Stopping profile...
D/PanService( 3151): Received stop request...Stopping profile...
D/BluetoothPan(  726): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 1306): BluetoothPAN Proxy object disconnected
D/PanProfile( 1306): Bluetooth service disconnected
D/BluetoothMapService( 3151): Received stop request...Stopping profile...
D/BluetoothMap( 1306): Proxy object disconnected
D/MapProfile( 1306): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3151): Profile still running: com.android.bluetooth.hdp.HealthService
I/GKI_LINUX( 3151): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3151): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 3151): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3151): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 3151): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3151): Cleaning up Bluetooth GID callback object
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3151): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3151): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3151): Cleaning up Bluetooth Health object
D/BtSettings.ProfileConfig( 3151): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3151): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3151): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3151): Cleaning up Bluetooth PAN callback object
V/RouteController(  239): RTNETLINK answers: No such file or directory
D/AuthorizationBluetoothService( 1321): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/CommandListener(  239): Clearing all IP addresses on wlan0
D/BluetoothAdapterService( 3151): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
D/BluetoothAdapterState( 3151): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 3151): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3151): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3151): updateAdapterState state is 10
D/BluetoothAdapterService( 3151): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3151): Autoconnection is available 
D/BluetoothAdapterService( 3151): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 3151): Entering OffState
D/BluetoothInputDevice( 3114): onBluetoothStateChange: up=fal,se
W/NetworkManagementService(  726): route cmd failed: 
W/NetworkManagementService(  726): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '36 route del src v6 2' failed with '400 36 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  726): '
W/NetworkManagementService(  726): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  726): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  726): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  726): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  726): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  726): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  726): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  726): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  726): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  726): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  726): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  726): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  726): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/RouteController(  239): /system/bin/ip -4 route del default table 2 2>&1
D/WifiNative(  726): callSECApiBoolean - ID [13]
I/WifiTrafficPoller(  726): evaluateTrafficStatsPolling
,I/wpa_supplicant( 4848): USE_NETWORK : USE_NETWORK OFF
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip -4 rule del table 2 2>&1
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: GONE sig=0 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=0 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=0 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=0 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/Bluetoothsap( 1306): onBluetoothStateChange: up=false
D/Bluetoothsap( 1306): Unbinding service...
D/BluetoothPbap( 1306): onBluetoothStateChange: up=false
D/BluetoothMap( 1306): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 1306): onBluetoothStateChange: up=false
D/Bluetoothsap( 1306): onBluetoothStateChange: up=false
D/Bluetoothsap( 1306): Unbinding service...
D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
D/BluetoothA2dp( 1306): onBluetoothStateChange: up=false
V/RouteController(  239): /system/bin/ip route flush cached 2>&1
D/BluetoothA2dp(  726): onBluetoothStateChange: up=false
D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
D/BluetoothA2dp( 3114): onBluetoothStateChange: up=false
D/FileShare-Server( 4149): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/BluetoothA2dp( 2025): onBluetoothStateChange: up=false
,D/FileShare-Server( 4149): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() DISCONNECTED
,I/wpa_supplicant( 4848): p2p0: CTRL-EVENT-TERMINATING 
D/Tethering(  726): interfaceLinkStateChanged p2p0, false
,D/Tethering(  726): interfaceStatusChanged p2p0, false
D/Tethering(  726): interfaceLinkStateChanged wlan0, true
,D/Tethering(  726): interfaceStatusChanged wlan0, true
I/WifiTrafficPoller(  726): mBoosterFLAG : 0
,I/WifiTrafficPoller(  726): current booster mode : FullMode
,D/PhoneApp( 1241): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
,I/QuickConnect[1.1][2] ( 3114): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
W/InputMethodManagerService(  726): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  726): [BT Setting State] State =10
,I/InputMethodManagerService(  726): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
V/BluetoothEventManager( 1306): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
I/wpa_supplicant( 4848): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 4848): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 4848): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  726): interfaceLinkStateChanged wlan0, false
,D/Tethering(  726): interfaceStatusChanged wlan0, false
,D/Tethering(  726): InitialState.processMessage what=4
E/Tethering(  726): No numeric data
D/Tethering(  726): interfaceLinkStateChanged wlan0, false
,D/Tethering(  726): interfaceStatusChanged wlan0, false
,D/Tethering(  726): interfaceLinkStateChanged wlan0, false
,D/Tethering(  726): interfaceStatusChanged wlan0, false
,D/NetUtils(  726): android_net_utils_resetConnections in env=0x794ff970 clazz=0x6cf00001 iface=wlan0 mask=0x3
,I/knox    ( 3055): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/ConnectivityService(  726): defaultVal : 1, tetherEnabledInSettings : true
,D/ConnectivityService(  726): resetConnections(wlan0, 3)
D/Tethering(  726): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  726): Error! unhandled message{ when=-105ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  726): Error! unhandled message{ when=-106ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
V/NetworkStats(  726): performPollLocked(flags=0x1)
W/ContextImpl( 3055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,E/WifiStateMachine(  726): Error! unhandled message{ when=-98ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  726): Error! unhandled message{ when=-99ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,I/knox    ( 3055): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3055): KNOXAgentService : onCreate()
,D/knox    ( 3055): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 3055): KNOXAgentService. startJobThread() start
,D/knox    ( 3055): KNOXAgentService. JobThread()
,D/knox    ( 3055): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3055): KNOXAgentService. startJobThread() wait
D/knox    ( 3055): KNOXAgentService : onDestroy().
,D/knox    ( 3055): ModuleBase.cancelAllAlarmManageModule()
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,V/NetworkStats(  726): performPollLocked() took 36ms
D/NtpTrustedTime(  726): currentTimeMillis() cache hit
D/NtpTrustedTime(  726): currentTimeMillis() cache hit
D/DockEventReceiver( 1306): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 1306): onReceive
,D/AuthorizationBluetoothService( 1321): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/NativeCrypto( 1321): Read error: ssl=0x79fc8238: I/O error during system call, Connection timed out
,V/NativeCrypto( 1321): SSL shutdown failed: ssl=0x79fc8238: I/O error during system call, Broken pipe
D/Tethering(  726): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 4848): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  726): interfaceStatusChanged wlan0, false
,D/BluetoothTethering(  726): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  726): attempted to stop reverse tether with nothing tethered
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
V/NetworkStats(  726): updateIfacesLocked()
D/ConnectivityService(  726): handleInetConditionChange: no active default network - ignore
V/NetworkStats(  726): performPollLocked(flags=0x1)
V/NetworkStats(  726): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,D/WifiStateMachine(  726): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
V/NetworkStats(  726): performPollLocked() took 26ms
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,W/Settings( 1220): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/knox    ( 3055): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,I/knox    ( 3055): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3055): KNOXAgentService : onCreate()
,D/knox    ( 3055): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3055): KNOXAgentService. startJobThread() start
,D/knox    ( 3055): KNOXAgentService. JobThread()
,W/ContextImpl( 3055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3055): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3055): KNOXAgentService. startJobThread() wait
D/knox    ( 3055): KNOXAgentService : onDestroy().
D/knox    ( 3055): ModuleBase.cancelAllAlarmManageModule()
,W/Netd    (  239): No subsystem found in netlink event
D/NetlinkEvent(  239): Unexpected netlink message. type=0x11
,D/Vpn     (  726): Interface removed : wlan0
,D/Tethering(  726): interfaceRemoved wlan0
,E/Tethering(  726): attempting to remove unknown iface (wlan0), ignoring
,W/Netd    (  239): No subsystem found in netlink event
D/NetlinkEvent(  239): Unexpected netlink message. type=0x11
,D/Vpn     (  726): Interface removed : p2p0
,D/Tethering(  726): interfaceRemoved p2p0
,E/Tethering(  726): attempting to remove unknown iface (p2p0), ignoring
,I/ApplicationPolicy(  726): updateDataUsageMap
,D/Tethering(  726): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  726): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  726): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  726): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/LocSvc_java(  726): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  726): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  726): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 4453): SPPPushClient is installed : true
,I/NetworkMonitor( 3755): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 4453): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 4453): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4453): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4453): noConnectivity : true
,D/WifiStateMachine(  726): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,I/KLMS-2.3.201 : ( 5044): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5044): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449683894638
,I/KLMS-2.3.201 : ( 5044): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5061): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5061): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4609): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4609): [BDLM] already registered in spp
,I/SA      ( 4609): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4609): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4609): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4609): [OR] == isSIMCardReady false ==
I/SA      ( 4609): [SCU] == networkStateCheck == false
,I/SA      ( 4609): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5106): Other Intent
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 5132): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5132): getCountryCode(): countryCode = PL
,D/Headlines( 5132): Breath.onCreate
,D/Headlines( 5132): Breath timer started. interval : 30000
,D/Headlines( 5132): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5132): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5132): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5132): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5132): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5132): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5132): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 4163): GC_FOR_ALLOC freed 4074K, 38% free 11961K/19008K, paused 46ms, total 46ms
,I/dalvikvm-heap( 4163): Grow heap (frag case) to 16.999MB for 2129936-byte allocation
,D/QuickConnect[1.1][2] ( 3114): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3114): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3114): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42636b98
,D/dalvikvm( 4163): GC_CONCURRENT freed 42K, 27% free 14017K/19008K, paused 6ms+10ms, total 40ms
,D/dalvikvm( 4163): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/RCPManagerService(  726): exchangeData() failure , invalid userId
,I/dalvikvm-heap( 4163): Grow heap (frag case) to 19.005MB for 2129936-byte allocation
,D/RCPManagerService(  726): exchangeData() failure , invalid userId
,D/dalvikvm( 4163): GC_CONCURRENT freed 4K, 24% free 16093K/21092K, paused 3ms+2ms, total 27ms
,V/AlarmManager(  726): waitForAlarm result :4
,I/iu.Environment( 1759): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1759): num queued entries: 0
V/AlarmManager(  726): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/iu.UploadsManager( 1759): num updated entries: 0
,I/iu.SyncManager( 1759): NEXT; no task
,I/SELinux ( 5553): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5553):  
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
D/BatteryService(  726): stay LED for fully charged
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/dalvikvm(  249): GC_EXPLICIT freed 42K, 50% free 9509K/19008K, paused 4ms+4ms, total 41ms
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/19008K, paused 2ms+4ms, total 24ms
,I/SELinux ( 5553): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5553):  
I/SELinux ( 5553):  
,I/SELinux ( 5553): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5553): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5553): >>>>> Normal User
,E/dalvikvm( 5553): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5553): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/19008K, paused 2ms+3ms, total 24ms
,D/TimaKeyStoreProvider( 5553): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5553): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5553): Added TimaKesytore provider
,W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=5553, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,D/Headlines( 5132): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5132): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5132): Breath 350 latestRequest time : 1449683894814 current time : 1449683895165
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  239): write error (Broken pipe)
,E/Watchdog(  726): !@Sync 11
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  726): Waited long enough for: ServiceRecord{431756d8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,D/Headlines( 5132): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5132): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5132): Breath 30039 latestRequest time : 1449683894814 current time : 1449683924854
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 12
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  726): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,D/Headlines( 5132): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5132): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5132): Breath 60036 latestRequest time : 1449683894814 current time : 1449683954850
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 13
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,D/Headlines( 5132): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5132): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5132): Breath 90036 latestRequest time : 1449683894814 current time : 1449683984850
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 14
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 390s ago
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,D/Headlines( 5132): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5132): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5132): Breath 120020 latestRequest time : 1449683894814 current time : 1449684014835
,D/Headlines( 5132): stop 
,D/Headlines( 5132): Breath.onDestroy : 
,I/ActivityManager(  726): Killing 4653:com.sec.android.service.cm/u0a78 (adj 15): empty #43
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 15
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 16
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 455s ago
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 17
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 18
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  726): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  726): stay LED for fully charged
,D/AmoledAdjustTimer(  726): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/AmoledAdjustTimer(  726): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm(  726): GC_CONCURRENT freed 3447K, 57% free 23555K/54620K, paused 52ms+51ms, total 590ms
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 525s ago
,E/Watchdog(  726): !@Sync 19
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  726): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/AmoledAdjustTimer(  726): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/AmoledAdjustTimer(  726): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  726): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  726): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  726): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  726): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  726): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  726): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  726): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  726): !@Sync 20
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/AmoledAdjustTimer(  726): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,W/ContextImpl(  726): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 3501): GC_CONCURRENT freed 2758K, 46% free 10453K/19008K, paused 13ms+18ms, total 177ms
,W/SocketClient(  239): write error (Broken pipe)
,E/Watchdog(  726): !@Sync 21
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 600s ago
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 22
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  726): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  726): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  726): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
V/AlarmManager(  726): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 23
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,I/SensorManagerA(  726): getReportingMode :: sensor.mType = 5
,D/Sensors (  726): LightSensor setDelay = 200000000
,D/Sensors (  726): LightSensor setSensorDelay = 200000000
,D/LightsService(  726): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  726): Light sensor flush: not enabled 0
D/Sensors (  726): LightSensor enable = 1
D/Sensors (  726): LightSensor enableSensor = 1
,D/SensorManager(  726): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  726): LightSensor enable = 0
,D/Sensors (  726): LightSensor enableSensor = 0
,D/SensorManager(  726): unregisterListener ::   
D/LightsService(  726): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  726): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 24
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService(  726): [PWL] Off : 680s ago
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 25
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 26
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 765s ago
,E/Watchdog(  726): !@Sync 27
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 28
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 29
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService(  726): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  726): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  726): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  726): [PWL] Off : 855s ago
,I/PowerManagerService(  726): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  726): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  726): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=726, ws=null) (elapsedTime=4075)
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  726): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  726): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  726): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  726): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  726): !@Sync 30
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Watchdog(  726): !@Sync 31
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 32
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 33
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService(  726): [PWL] Off : 950s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 34
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/dalvikvm(  726): GC_CONCURRENT freed 3436K, 57% free 23534K/54620K, paused 25ms+41ms, total 514ms
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 35
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 36
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService(  726): [PWL] Off : 1050s ago
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 37
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 38
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 39
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService(  726): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  726): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  726): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  726): [PWL] Off : 1155s ago
,I/PowerManagerService(  726): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  726): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  726): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=726, ws=null) (elapsedTime=4085)
,I/TLC_TIMA_PKM_measure_kernel(  726): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  726): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  726): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  726): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 40
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Watchdog(  726): !@Sync 41
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 42
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  726): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  726): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
V/AlarmManager(  726): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  726): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 43
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  726): [PWL] Off : 1265s ago
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,D/LightsService(  726): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  726): getReportingMode :: sensor.mType = 5
D/Sensors (  726): LightSensor setDelay = 200000000
D/Sensors (  726): LightSensor setSensorDelay = 200000000
D/Sensors (  726): Light sensor flush: not enabled 0
D/Sensors (  726): LightSensor enable = 1
D/Sensors (  726): LightSensor enableSensor = 1
,D/SensorManager(  726): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  726): LightSensor enable = 0
,D/Sensors (  726): LightSensor enableSensor = 0
,D/SensorManager(  726): unregisterListener ::   
D/LightsService(  726): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  726): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 44
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 45
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 46
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 47
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 1380s ago
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 48
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  726): !@Sync 49
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/TimaService(  726): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  726): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  726): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  726): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  726): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  726): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  726): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  726): !@Sync 50
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/dalvikvm(  726): GC_CONCURRENT freed 3424K, 57% free 23515K/54620K, paused 24ms+48ms, total 566ms
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Watchdog(  726): !@Sync 51
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 1500s ago
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  726): !@Sync 52
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  726): !@Sync 53
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  726): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  726): !@Sync 54
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-13, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  726): !@Sync 55
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  726): [PWL] Off : 1625s ago
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  726): !@Sync 56
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  726): !@Sync 57
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 58
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 59
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  726): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  726): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  726): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  726): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  726): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  726): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  726): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService(  726): [PWL] Off : 1755s ago
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 60
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,I/ProcessStatsService(  726): Prepared write state in 132ms
,I/ProcessStatsService(  726): Prepared write state in 123ms
,I/ProcessStatsService(  726): Pruning old procstats: /data/system/procstats/state-2015-12-09-06-38-36.bin
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 61
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 62
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  726): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  726): <AppSync3 Whitelist>
,V/AlarmManager(  726): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 63
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  726): stay LED for fully charged
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  726): mCoverManager.getCoverState() : true
,D/BatteryService(  726): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  726): waitForAlarm result :4
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
V/NetworkStats(  726): performPollLocked(flags=0x3)
,V/AlarmManager(  726): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
V/NetworkStats(  726): performPollLocked() took 127ms
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,D/NtpTrustedTime(  726): currentTimeMillis() cache hit
,I/ActivityManager(  726): Killing 4756:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1808s
,I/ActivityManager(  726): Killing 4744:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1808s
,I/ActivityManager(  726): Killing 4730:com.samsung.helphub/1000 (adj 15): empty for 1808s
,I/ActivityManager(  726): Killing 4703:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1808s
,I/ActivityManager(  726): Killing 4666:com.google.android.apps.docs/u0a90 (adj 15): empty for 1808s
,I/SensorManagerA(  726): getReportingMode :: sensor.mType = 5
,D/Sensors (  726): LightSensor setDelay = 200000000
,D/LightsService(  726): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  726): LightSensor setSensorDelay = 200000000
D/Sensors (  726): Light sensor flush: not enabled 0
D/Sensors (  726): LightSensor enable = 1
D/Sensors (  726): LightSensor enableSensor = 1
D/SensorManager(  726): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/ActivityManager(  726): Killing 5065:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1800s
,I/EventLogService( 1759): Aggregate from 1449682971797 (log), 1449682971797 (data)
,D/Sensors (  726): LightSensor enable = 0
,D/Sensors (  726): LightSensor enableSensor = 0
,D/SensorManager(  726): unregisterListener ::   
D/LightsService(  726): [SvcLED]  onSensorChanged::light value = 0
,D/LightsService(  726): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  726): Killing 5086:com.sec.android.app.voicenote/1000 (adj 15): empty for 1800s
,D/dalvikvm( 1759): GC_CONCURRENT freed 1431K, 36% free 12283K/19008K, paused 7ms+13ms, total 74ms
,D/dalvikvm(  726): GC_CONCURRENT freed 3406K, 57% free 23549K/54620K, paused 8ms+16ms, total 178ms
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,I/ActivityManager(  726): Killing 5358:com.android.providers.calendar/u0a44 (adj 15): empty for 1800s
,I/ActivityManager(  726): Killing 3776:com.android.mms/u0a48 (adj 15): empty for 1801s
,I/ActivityManager(  726): Killing 5340:com.qualcomm.timeservice/u0a168 (adj 15): empty for 1801s
,I/ActivityManager(  726): Killing 5328:com.sec.android.app.taskmanager/u0a166 (adj 15): empty for 1801s
,I/ActivityManager(  726): Killing 5297:com.sec.esdk.elm/u0a94 (adj 15): empty for 1801s
,I/ActivityManager(  726): Killing 5282:com.sec.android.app.clockpackage/u0a84 (adj 15): empty for 1802s
,I/ActivityManager(  726): Killing 5263:com.samsung.android.scloud.sync/u0a62 (adj 15): empty for 1802s
,I/ActivityManager(  726): Killing 4482:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1802s
,I/ActivityManager(  726): Killing 5208:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1803s
,I/ActivityManager(  726): Killing 4717:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1804s
,I/ActivityManager(  726): Killing 5310:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty for 1800s
,I/ActivityManager(  726): Killing 5236:com.android.calendar/u0a142 (adj 15): empty for 1800s
,D/CountryDetector(  726): No listener is left
,E/SMD     (  242): DCD ON
,E/Watchdog(  726): !@Sync 64
,D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  726): waitForAlarm result :8
,V/AlarmManager(  726): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  242): DCD ON
D/SSRMv2:SIOP(  726): SIOP:: AP = 300, Delta = 0
D/BatteryService(  726): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
D/BatteryService(  726): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  726): mCoverManager.getCoverState() : true
D/BatteryService(  726): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
I/PowerManagerService(  726): [PWL] Off : 1890s ago
E/SMD     (  242): DCD ON
D/AmoledAdjustTimer(  726): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
D/AndroidRuntime( 5983): 
D/AndroidRuntime( 5983): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5983): CheckJNI is OFF
D/AndroidRuntime( 5983): setted country_code = Poland
D/AndroidRuntime( 5983): setted countryiso_code = PL
D/AndroidRuntime( 5983): setted sales_code = XEO
D/AndroidRuntime( 5983): readGMSProperty: start
D/AndroidRuntime( 5983): readGMSProperty: already setted!!
D/AndroidRuntime( 5983): readGMSProperty: end
D/AndroidRuntime( 5983): addProductProperty: start
D/dalvikvm( 5983): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5983): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5983): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5983): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5983): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5983): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5983): failed to load memtrack module: -2
D/dalvikvm( 5983): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5983): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  726): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  726): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  726): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  726): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  726): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  726): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  726): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  726): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  726): getApplicationUninstallationEnabled
D/ApplicationPolicy(  726): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  726): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  726): START PACKAGE DELETE: observer{1124286136}
D/PackageManager(  726): pkg{<packageName>}
D/PackageManager(  726): user{0}
D/PackageManager(  726): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  726): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  726): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  726): Killing 4623:com.test.thalitest/u0a179 (adj 0): stop com.test.thalitest
D/CustomFrequencyManagerService(  726): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 726  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  726): mDVFSHelper.acquire()
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1262): destroyHardwareResources():1126343368
I/SurfaceFlinger(  248): id=18 Removed NainActivit (7/11)
I/SurfaceFlinger(  248): id=18 Removed NainActivit (-2/11)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  248): id=18 Removed NainActivit (-2/11)
I/WindowState(  726): WIN DEATH: Window{424b2300 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  726): Skipping PackageSetting{4277d190 com.example.hello/10180} due to missing metadata
D/PackageManager(  726): queryIntentReceivers - Execution time: 110 ms
D/LockPatternUtils( 1068): isPcwEnable = null
D/PackageManager(  726): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  248): id=20 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/Launcher( 1262): onRestart, Launcher: 1114408616
D/Launcher( 1262): onStart, Launcher: 1114408616
D/Launcher.HomeView( 1262): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1447): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1447): [237392/5] SurfaceWidget drawing first frame
I/SurfaceFlinger(  248): id=21 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/AdaptiveEventManager( 1068): action=android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3114): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager(  726):   Action: "android.intent.action.SENDTO"
I/PackageManager(  726):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  726):   Scheme: "sms"
I/PackageManager(  726): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6011): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6011):  
I/SurfaceFlinger(  248): id=22 createSurf (707x984),1 flag=4, TettingsRec
I/PackageManager(  726):   Action: "android.intent.action.SENDTO"
I/PackageManager(  726):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  726):   Scheme: "smsto"
I/PackageManager(  726): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SELinux ( 6011): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6011):  
I/SELinux ( 6011):  
I/SELinux ( 6011): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/PackageManager(  726):   Action: "android.intent.action.SENDTO"
I/PackageManager(  726):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  726):   Scheme: "mms"
E/SELinux ( 6011): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6011): >>>>> Normal User
E/dalvikvm( 6011): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6011): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 2131): GC_EXPLICIT freed 537K, 43% free 10956K/19008K, paused 3ms+3ms, total 147ms
I/FPMS_FingerprintManagerService( 1087): onReceive: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  726): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PackageManager(  726): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/InputReader(  726): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  726):   Action: "android.intent.action.SENDTO"
I/PackageManager(  726):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  726):   Scheme: "mmsto"
D/TimaKeyStoreProvider( 6011): in addTimaSignatureService
I/PackageManager(  726): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6011): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6011): Added TimaKesytore provider
D/dalvikvm( 1759): GC_EXPLICIT freed 268K, 36% free 12252K/19008K, paused 13ms+9ms, total 206ms
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
D/dalvikvm(  726): GC_EXPLICIT freed 1464K, 57% free 23563K/54620K, paused 6ms+16ms, total 193ms
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/dalvikvm( 1411): GC_EXPLICIT freed 4295K, 48% free 10019K/19008K, paused 9ms+12ms, total 215ms
D/CustomFrequencyManagerService(  726): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 726  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  726): mDVFSHelper.release()
D/CustomFrequencyManagerService(  726): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 726  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/PackageManager(  726):   Action: "android.intent.action.SENDTO"
I/PackageManager(  726):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  726):   Scheme: "sms"
I/PackageManager(  726): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/PackageManager(  726):   Action: "android.intent.action.SENDTO"
I/PackageManager(  726):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  726):   Scheme: "smsto"
I/PackageManager(  726): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  726): PackageReceiver onReceive()
I/PackageManager(  726):   Action: "android.intent.action.SENDTO"
I/PackageManager(  726):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  726):   Scheme: "mms"
I/PackageManager(  726): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService(  726): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  726):   Action: "android.intent.action.SENDTO"
I/PackageManager(  726):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  726):   Scheme: "mmsto"
I/PackageManager(  726): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=6011, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 6011): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6011): ELMEngine.ELMEngine( context ).
D/elm:14132( 6011): MDMBridge.setEnterpriseBridge()
D/elm:14132( 6011): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6011): ElmAgentService : onCreate()
D/elm:14132( 6011): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6011): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6011): MDMBridge.getInstance()
D/elm:14132( 6011): MDMBridge.getAllLicenseInfoFromSDK()
D/EnterpriseDeviceManagerService(  726): Package has changed for user 0
D/elm:14132( 6011): MDMBridge.getAllLicenseInfoFromSDK()
D/EnterpriseDeviceManagerService(  726): Admin package name: com.google.android.gms
I/SELinux ( 6027): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6027):  
D/elm:14132( 6011): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 6011): ElmAgentService : onDestroy().
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6027): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6027):  
I/SELinux ( 6027):  
I/SELinux ( 6027): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6027): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6027): >>>>> Normal User
E/dalvikvm( 6027): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6027): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6027): in addTimaSignatureService
D/TimaKeyStoreProvider( 6027): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6027): Added TimaKesytore provider
D/BackupManagerService(  726): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  726): removePackageParticipantsLocked: uid=10179 #1
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(  726): GC_EXPLICIT freed 1025K, 57% free 23605K/54620K, paused 8ms+22ms, total 262ms
D/PackageManager(  726): delete sourFile : 
D/PackageManager(  726): delete native library directory: 
D/PackageManager(  726): return delete result to caller: 1124286136
D/AndroidRuntime( 5983): Shutting down VM
D/PackageManager(  726): returnCode: 1
D/dalvikvm( 5983): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 2ms
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Launcher.HomeView( 1262): onStop
I/PackageManager(  726):   Action: "android.intent.action.SENDTO"
I/PackageManager(  726):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  726):   Scheme: "sms"
I/PackageManager(  726): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  726): Permission Denial: getCurrentUser() from pid=6027, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  726):   Action: "android.intent.action.SENDTO"
I/PackageManager(  726):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  726):   Scheme: "smsto"
I/PackageManager(  726): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  726):   Action: "android.intent.action.SENDTO"
I/PackageManager(  726):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  726):   Scheme: "mms"
I/PackageManager(  726): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  726):   Action: "android.intent.action.SENDTO"
I/PackageManager(  726):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  726):   Scheme: "mmsto"
I/PackageManager(  726): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 6027): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42621bf8, skipping init
I/SecureStorage( 6027): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6027): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6027
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6027): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 6027): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6027
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  726): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  726): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  726): clearDefaults: com.test.thalitest
D/InputReader(  726): Processing first event

```
