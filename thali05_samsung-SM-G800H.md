#### Test 50650278c0f6ec2_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
V/MediaPlayer( 4514): decode(61, 33979084, 48105)
V/MediaPlayerService(  250): decode(35, 33979084, 48105)
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
V/StagefrightPlayer(  250): setDataSource(35, 33979084, 48105)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8539578, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8539578, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8539578, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8539578, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8539578, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
,--------- beginning of /dev/log/system
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=4532, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8539578, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8539578, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8539578, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4514): decode(63, 33914984, 10421)
V/MediaPlayerService(  250): decode(35, 33914984, 10421)
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
V/StagefrightPlayer(  250): setDataSource(35, 33914984, 10421)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8532e10, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
D/dalvikvm( 4532): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425b7ba8, skipping init
I/SecureStorage( 4532): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4532): [INFO]: SPID(0x00000000)This device supports Secure Storage
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
V/AudioCache(  250): notify(0xb8532e10, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8532e10, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8532e10, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/SecureStorage(  300): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4532
I/SecureStorage(  300): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4532): [INFO]: SPID(0x00000000)SS Daemon is running
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8532e10, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
I/AudioPlayer(  250): First fillBuffer call!!
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
I/SecureStorage( 4532): [INFO]: SPID(0x00000000)Processing data
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8532e10, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8532e10, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
I/SecureStorage(  300): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4532
I/SecureStorage(  300): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8532e10, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4514): decode(64, 37457308, 34198)
V/MediaPlayerService(  250): decode(35, 37457308, 34198)
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
V/StagefrightPlayer(  250): setDataSource(35, 37457308, 34198)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542c48, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8542c48, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542c48, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542c48, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8542c48, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8542c48, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542c48, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542c48, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4514): decode(65, 33862452, 7405)
V/MediaPlayerService(  250): decode(35, 33862452, 7405)
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
V/StagefrightPlayer(  250): setDataSource(35, 33862452, 7405)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8545eb8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8545eb8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8545eb8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8545eb8, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8545eb8, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8545eb8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8545eb8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8545eb8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4514): decode(66, 37547940, 5555)
V/MediaPlayerService(  250): decode(35, 37547940, 5555)
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
V/StagefrightPlayer(  250): setDataSource(35, 37547940, 5555)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8530eb8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8530eb8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8530eb8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8530eb8, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8530eb8, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8530eb8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8530eb8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8530eb8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4514): decode(67, 30367732, 5085)
V/MediaPlayerService(  250): decode(35, 30367732, 5085)
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
V/StagefrightPlayer(  250): setDataSource(35, 30367732, 5085)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85393f8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb85393f8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85393f8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85393f8, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb85393f8, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
I/AudioPlayer(  250): First fillBuffer call!!
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85393f8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85393f8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85393f8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4514): decode(68, 30372876, 21552)
V/MediaPlayerService(  250): decode(35, 30372876, 21552)
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
V/StagefrightPlayer(  250): setDataSource(35, 30372876, 21552)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85381d8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb85381d8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85381d8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85381d8, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb85381d8, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb85381d8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85381d8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85381d8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4514): decode(69, 37543652, 4230)
V/MediaPlayerService(  250): decode(35, 37543652, 4230)
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
V/StagefrightPlayer(  250): setDataSource(35, 37543652, 4230)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85395e8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb85395e8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85395e8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85395e8, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb85395e8, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85395e8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85395e8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb85395e8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4514): decode(70, 30337076, 9400)
V/MediaPlayerService(  250): decode(35, 30337076, 9400)
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
V/StagefrightPlayer(  250): setDataSource(35, 30337076, 9400)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853eda8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb853eda8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853eda8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853eda8, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb853eda8, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/ActivityManager(  756): Killing 3082:com.sec.android.app.mt/1000 (adj 15): empty #43
I/SELinux ( 4596): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4596):  
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853eda8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853eda8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853eda8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4514): decode(71, 33925464, 44276)
V/MediaPlayerService(  250): decode(35, 33925464, 44276)
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
,V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(35, 33925464, 44276)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853b218, 8, 0, 0)
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
I/SELinux ( 4596): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4596):  
I/SELinux ( 4596):  
I/SELinux ( 4596): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
E/SELinux ( 4596): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
E/dalvikvm( 4596): >>>>> Normal User
E/dalvikvm( 4596): >>>>> com.policydm [ userId:0 | appId:1000 ]
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb853b218, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853b218, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853b218, 1, 0, 0)
V/AudioCache(  250): prepared
E/SELinux ( 4596): [DEBUG] seapp_context_lookup: seinfoCategory = platform
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
V/AudioCache(  250): notify(0xb853b218, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
D/TimaKeyStoreProvider( 4596): in addTimaSignatureService
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853b218, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853b218, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853b218, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4514): decode(72, 33885672, 29256)
V/MediaPlayerService(  250): decode(35, 33885672, 29256)
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
V/StagefrightPlayer(  250): setDataSource(35, 33885672, 29256)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542bf0, 8, 0, 0)
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
D/AndroidRuntime( 4577): 
D/AndroidRuntime( 4577): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/AndroidRuntime( 4577): CheckJNI is OFF
D/AndroidRuntime( 4577): setted country_code = Poland
D/AndroidRuntime( 4577): setted countryiso_code = PL
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/AndroidRuntime( 4577): setted sales_code = XEO
D/AndroidRuntime( 4577): readGMSProperty: start
D/AndroidRuntime( 4577): readGMSProperty: already setted!!
D/AndroidRuntime( 4577): readGMSProperty: end
D/AndroidRuntime( 4577): addProductProperty: start
D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
D/BatteryService(  756): stay LED for fully charged
D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  756): mCoverManager.getCoverState() : true
D/TimaKeyStoreProvider( 4596): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4596): Added TimaKesytore provider
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8542bf0, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542bf0, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542bf0, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
D/dalvikvm( 4577): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4577): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4577): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4577): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4577): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542bf0, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542bf0, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542bf0, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542bf0, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4514): decode(73, 37491572, 52024)
V/MediaPlayerService(  250): decode(35, 37491572, 52024)
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
V/StagefrightPlayer(  250): setDataSource(35, 37491572, 52024)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542ca0, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8542ca0, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542ca0, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542ca0, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8542ca0, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/AudioPlayer(  250): First fillBuffer call!!
D/SSRMv2:SIOP(  756): SIOP:: AP = 310, Delta = 0
E/memtrack( 4577): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4577): failed to load memtrack module: -2
D/dalvikvm( 4577): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542ca0, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542ca0, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8542ca0, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4514): decode(74, 33969800, 9226)
V/MediaPlayerService(  250): decode(35, 33969800, 9226)
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
V/StagefrightPlayer(  250): setDataSource(35, 33969800, 9226)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853a2d8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb853a2d8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853a2d8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853a2d8, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb853a2d8, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb853a2d8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853a2d8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853a2d8, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
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
D/AndroidRuntime( 4577): Calling main entry com.android.commands.am.Am
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 4514): decode(75, 30402580, 4509)
V/MediaPlayerService(  250): decode(35, 30402580, 4509)
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
V/StagefrightPlayer(  250): setDataSource(35, 30402580, 4509)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853a960, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb853a960, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853a960, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853a960, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb853a960, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853a960, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853a960, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb853a960, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
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
V/ApplicationPolicy(  756): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  756): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  756): mDVFSHelper.acquire()
I/SELinux ( 4642): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4642):  
I/SELinux ( 4642): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4642):  
I/SELinux ( 4642):  
I/SELinux ( 4642): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4642): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4642): >>>>> Normal User
E/dalvikvm( 4642): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
D/dalvikvm(  248): GC_EXPLICIT freed 45K, 50% free 9509K/18716K, paused 2ms+4ms, total 40ms
E/SELinux ( 4642): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18716K, paused 1ms+3ms, total 18ms
D/TimaKeyStoreProvider( 4642): in addTimaSignatureService
D/TimaKeyStoreProvider( 4642): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4642): Added TimaKesytore provider
D/LockPatternUtils( 1067): isPcwEnable = null
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18716K, paused 1ms+3ms, total 19ms
D/AndroidRuntime( 4577): Shutting down VM
D/dalvikvm( 4577): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
I/SQLiteSecureOpenHelper( 2024): getWritableDatabase(pwd)
D/LockPatternUtils( 1067): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2024): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  247): id=13 Removed CatteryCove (8/13)
D/SurfaceWidgetView( 1261): destroyHardwareResources():1125881808
I/SurfaceFlinger(  247): id=13 Removed CatteryCove (-2/13)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=4642, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 4655): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4655):  
I/ActivityManager(  756): Killing 3140:com.sec.android.app.camera/u0a147 (adj 15): empty #43
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=4642, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 4642): Binding Chromium to the background looper Looper (main, tid 1) {422927a8}
I/chromium( 4642): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4642): Initializing chromium process, renderers=0
W/chromium( 4642): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/SELinux ( 4655): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4655):  
I/SELinux ( 4655):  
I/SELinux ( 4655): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4655): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4655): >>>>> Normal User
E/dalvikvm( 4655): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 4655): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 4655): in addTimaSignatureService
D/TimaKeyStoreProvider( 4655): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4655): Added TimaKesytore provider
I/SA      ( 4655): [SSP] onCreated
I/SA      ( 4655): [TPM] There is no property file
I/SA      ( 4655): [SCU] isHaveSA() - false
I/SA      ( 4655): [TPM] getModelProperty : null
I/SA      ( 4655): [TPM] getCSCProperty : null
I/SA      ( 4655): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4655): [DM] init START
I/SA      ( 4655): [DM] This device is not a Vodafone
I/SA      ( 4655): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4655): support phone number id : false
I/SA      ( 4655): [DM] init END
I/SA      ( 4655): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4655): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  756): Killing 3243:com.android.email/u0a155 (adj 15): empty #43
D/Mms/PackageInstallReceiver( 3744): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2120): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Adreno-EGL( 4642): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4642): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4642): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4642): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4642): Remote Branch: 
I/Adreno-EGL( 4642): Local Patches: 
I/Adreno-EGL( 4642): Reconstruct Branch: 
W/ContextImpl( 2797): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SecureStorage(  300): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  300): [INFO]: SPID(0x00000003)PID: 4532, TID: 4532
I/SELinux ( 4687): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4687):  
I/SurfaceFlinger(  247): id=7 Removed Mauncher (7/12)
I/SurfaceFlinger(  247): id=7 Removed Mauncher (-2/12)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  247): id=16 Removed TettingsRec (7/11)
I/SurfaceFlinger(  247): id=16 Removed TettingsRec (-2/11)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1443): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1261): onTrimMemory. Level: 20
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/SELinux ( 4687): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4687):  
I/SELinux ( 4687):  
I/SELinux ( 4687): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4687): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4687): >>>>> Normal User
E/dalvikvm( 4687): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 4687): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm( 2120): GC_CONCURRENT freed 6480K, 41% free 11210K/18716K, paused 6ms+2ms, total 88ms
D/dalvikvm( 2120): WAIT_FOR_CONCURRENT_GC blocked 29ms
D/TimaKeyStoreProvider( 4687): in addTimaSignatureService
D/TimaKeyStoreProvider( 4687): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4687): Added TimaKesytore provider
I/dalvikvm( 4642): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4642): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4642): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4642): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4642): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4642): VFY: replacing opcode 0x6e at 0x0008
I/SecureStorage( 4532): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4532): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4532): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4532): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 4532): Open platform.db in secure mode
W/dalvikvm( 4642): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4642): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4642): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4642): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4642): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4642): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4642): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4642): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4642): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4642): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4642): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4642): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4642): CordovaWebView is running on device made by: samsung
I/IcingCorporaProvider( 2120): UpdateCorporaTask done [took 212 ms] updated apps [took 212 ms] 
D/CapabilityManagerService New( 4687): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=4687, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 4705): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4705):  
I/ActivityManager(  756): Killing 3239:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
I/SurfaceFlinger(  247): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 4642): EGLImpl-HWUI Protected EGL context created
I/SELinux ( 4705): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4705):  
I/SELinux ( 4705):  
I/SELinux ( 4705): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4705): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4705): >>>>> Normal User
E/dalvikvm( 4705): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 4705): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/OpenGLRenderer( 4642): Enabling debug mode 0
D/OpenGLRenderer( 4642): GL error from OpenGLRenderer: 0x502
E/OpenGLRenderer( 4642):   GL_INVALID_OPERATION
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/TimaKeyStoreProvider( 4705): in addTimaSignatureService
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 4705): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4705): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4532): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 4532): ...getDatabaseLocked(b,b,pwd)
D/CustomFrequencyManagerService(  756): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  756): mDVFSHelper.release()
D/CustomFrequencyManagerService(  756): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  756): Killing 3265:com.sec.modem.settings/1000 (adj 15): empty #43
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=4705, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
D/JsMessageQueue( 4642): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4642): Trying to load lib /data/app-lib/com.test.thalitest-27/libjxcore.so 0x425b94e0
,D/dalvikvm( 4642): Added shared lib /data/app-lib/com.test.thalitest-27/libjxcore.so 0x425b94e0
D/jxcore_app_log( 4642): JniHelper::setJavaVM(0x4175e4f8), pthread_self() = 2025657016
,D/JX-Cordova( 4642): jxcore cordova android initializing
I/dalvikvm( 4642): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4642): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4642): VFY: replacing opcode 0x6e at 0x0045
,W/GAV2    ( 4705): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 4733): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4733):  
,I/SELinux ( 4733): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4733):  
I/SELinux ( 4733):  
,I/SELinux ( 4733): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4733): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 4733): >>>>> Normal User
,E/dalvikvm( 4733): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 4733): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4733): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4733): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4733): Added TimaKesytore provider
,D/PackageIntentReceiver( 4733): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4733): Not GearManger package! 
,I/SELinux ( 4748): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4748):  
,I/ActivityManager(  756): Killing 1335:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,D/dalvikvm( 4642): GC_CONCURRENT freed 4938K, 32% free 12751K/18716K, paused 2ms+2ms, total 37ms
,D/dalvikvm( 4642): WAIT_FOR_CONCURRENT_GC blocked 30ms
I/SELinux ( 4748): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4748):  
I/SELinux ( 4748):  
,I/SELinux ( 4748): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4748): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4748): >>>>> Normal User
E/dalvikvm( 4748): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 4748): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4748): in addTimaSignatureService
D/TimaKeyStoreProvider( 4748): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4748): Added TimaKesytore provider
,D/MagazineService Version( 4748): Magazine-Channel: 13
,D/MagazineService Version( 4748): Magazine-Provider: 13
,D/MagazineService Version( 4748): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 4748): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 4748): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=4748, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 4760): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4760):  
,E/SMD     (  241): DCD ON
,I/SELinux ( 4760): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4760):  
I/SELinux ( 4760):  
,I/SELinux ( 4760): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4760): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4760): >>>>> Normal User
,E/dalvikvm( 4760): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 4760): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/GAV2    ( 4705): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  756): Killing 3283:tv.peel.smartremote/u0a163 (adj 15): empty #43
,D/TimaKeyStoreProvider( 4760): in addTimaSignatureService
,I/MagazineService::MagazineService( 4748): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,D/MagazineService::MagazineService( 4748): [onHandleIntent] Send broadcast to (com.test.thalitest).
,D/TimaKeyStoreProvider( 4760): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4760): Added TimaKesytore provider
I/ActivityManager(  756): Killing 3308:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,D/CustomFrequencyManagerService(  756): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 4775): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4775):  
I/ActivityManager(  756): Killing 3362:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 4775): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4775):  
I/SELinux ( 4775):  
,I/SELinux ( 4775): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4775): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4775): >>>>> Normal User
,E/dalvikvm( 4775): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 4775): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4775): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4775): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4775): Added TimaKesytore provider
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=4775, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4775): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4787): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4787):  
I/ActivityManager(  756): Killing 3386:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,D/dalvikvm( 4642): GC_FOR_ALLOC freed 4674K, 27% free 15765K/21488K, paused 35ms, total 41ms
,I/SELinux ( 4787): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4787):  
I/SELinux ( 4787):  
,I/SELinux ( 4787): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4787): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4787): >>>>> Normal User
,E/dalvikvm( 4787): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4787): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4787): in addTimaSignatureService
D/TimaKeyStoreProvider( 4787): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4787): Added TimaKesytore provider
,I/SELinux ( 4799): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4799):  
I/ActivityManager(  756): Killing 3398:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4799): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4799):  
I/SELinux ( 4799):  
,I/SELinux ( 4799): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4799): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4799): >>>>> Normal User
,E/dalvikvm( 4799): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4799): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4799): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4799): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4799): Added TimaKesytore provider
V/AlarmManager(  756): waitForAlarm result :8
V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager(  756): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager(  756): <AppSync3 Whitelist>
,V/AlarmManager(  756): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,I/ActivityManager(  756): Killing 3592:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/Finsky  ( 3474): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 1794): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1794): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1794): Loading module APK com.google.android.play.games
,I/dalvikvm( 1794): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1794): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1794): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1794): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1794): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1794): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1794): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1794): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1794): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1794): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1794): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/dalvikvm( 4642): GC_FOR_ALLOC freed 5022K, 31% free 16771K/24160K, paused 35ms, total 35ms
,I/dalvikvm-heap( 4642): Grow heap (frag case) to 21.724MB for 2459024-byte allocation
,D/ChimeraCfgMgr( 1794): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1794): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1794): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1794): Submit a task: k
,D/ChimeraCfgMgr( 1794): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 1794): Processing package: com.test.thalitest
,D/ChimeraCfgMgr( 1794): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/BaseAppContext( 1794): Using Auth Proxy for data requests.
,W/BaseAppContext( 1794): Using Auth Proxy for data requests.
,D/GassUtils( 1794): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1794): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1794): Using Auth Proxy for data requests.
,W/BaseAppContext( 1794): Using Auth Proxy for data requests.
,W/BaseAppContext( 1794): Using Auth Proxy for data requests.
,W/BaseAppContext( 1794): Using Auth Proxy for data requests.
,W/dalvikvm( 1794): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1794): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1794): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1794): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1794): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1794): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1794): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1794): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1794): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1794): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1794): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 1794): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1794): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1794): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1794): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1794): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1794): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1794): cleanUpNonGplusAccounts done.
,D/dalvikvm( 4642): GC_FOR_ALLOC freed 3766K, 35% free 17454K/26564K, paused 36ms, total 39ms
,D/dalvikvm( 1304): GC_EXPLICIT freed 849K, 43% free 10744K/18716K, paused 3ms+5ms, total 36ms
,D/dalvikvm( 4642): GC_FOR_ALLOC freed 1201K, 35% free 17355K/26564K, paused 31ms, total 31ms
,D/ChimeraCfgMgr( 1794): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1794): Module APK com.google.android.play.games already loaded
,W/jxcore-log( 4642): Initializing JXcore engine
,W/jxcore-log( 4642): JXcore engine is ready
,W/jxcore-log( 4642): Starting JXcore engine
,D/dalvikvm(  756): GC_EXPLICIT freed 1930K, 58% free 23149K/55032K, paused 6ms+13ms, total 139ms
,W/jxcore-log( 4642): Platform android
W/jxcore-log( 4642): 
,W/jxcore-log( 4642): Process ARCH arm
W/jxcore-log( 4642): 
,I/Icing   ( 1794): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1794): GC_CONCURRENT freed 1261K, 36% free 12094K/18716K, paused 5ms+5ms, total 49ms
,I/Icing   ( 1794): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,I/jxcore-log( 4642): JXcore Cordova bridge is ready!
I/jxcore-log( 4642): 
,W/jxcore-log( 4642): JXcore engine is started
,I/chromium( 4642): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4642): Toggling radios to true
I/jxcore-log( 4642): 
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=4642, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  756): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  756): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4642, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  756): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/BluetoothManagerService(  756): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService(  756): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  756): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService(  756): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService(  756): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService(  756): foregroundUser: 0
,E/BluetoothManagerService(  756): Package is exist.
D/BluetoothAdapterState( 3125): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 3125): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3125): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3125): updateAdapterState state is 11
,D/BluetoothAdapterService( 3125): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3125): Autoconnection is available 
D/BluetoothAdapterService( 3125): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 3125): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3125): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,I/WifiManager( 4642): packageName : com.test.thalitest
,W/BluetoothAdapterService( 3125): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,I/WifiManager( 4642): setWifiEnabled : true
,I/WifiService(  756): setWifiEnabled: true pid=4642, uid=10179
,W/BluetoothAdapterService( 3125): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3125): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/WifiService(  756): Failed getting userId using ActivityManagerNative
W/WifiService(  756): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4642, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  756): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  756): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  756): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  756): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  756): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  756): 	at dalvik.system.NativeStart.run(Native Method)
,W/BluetoothAdapterService( 3125): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=4642, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/InputMethodManagerService(  756): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,D/PhoneApp( 1240): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
I/InputMethodManagerService(  756): [BT Setting State] State =11
,E/WifiHW  (  756): ##################### set firmware type 0 #####################
,I/QuickConnect[1.1][2] ( 3096): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
,W/BluetoothAdapterService( 3125): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,I/WifiService(  756): disconnect: pid=4642, uid=10179
,W/BluetoothAdapterService( 3125): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
,W/BluetoothAdapterService( 3125): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3125): Not skipping com.android.bluetooth.hfp.HeadsetService
,I/jxcore-log( 4642): Radios toggled
I/jxcore-log( 4642): 
,W/BluetoothAdapterService( 3125): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3125): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/HeadsetService( 3125): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3125): classInitNative: succeeds
D/HeadsetStateMachine( 3125): Version 1.6
,D/HeadsetStateMachine( 3125): make
,W/BluetoothAdapterService( 3125): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3125): Not skipping com.android.bluetooth.hid.HidService
,E/HeadsetStateMachine( 3125): # of Max HF connection is 2
,D/QuickConnect[1.1][2] ( 3096): HeadsetProfile.onServiceConnected - Bluetooth service connected
,W/BluetoothAdapterService( 3125): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3125): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3125): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3125): Not skipping com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 3125): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3125): Not skipping com.android.bluetooth.map.BluetoothMapService
,I/BluetoothAdapterState( 3125): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3125): get_profile_interface handsfree
,D/BluetoothAtMessage( 3125): createCMTIContentObservers
,D/HeadsetStateMachine( 3125): Enter Disconnected: -2
,E/HeadsetStateMachine( 3125): set to mRemoteBrsf = 0
D/HeadsetStateMachine( 3125): map size, before remove : 0
D/HeadsetStateMachine( 3125): map size, after remove: 0
,D/HeadsetStateMachine( 3125): mNextConnectingDevice : null
,D/BluetoothA2dp(  756): Proxy object connected
,D/BluetoothA2dp( 3096): Proxy object connected
,D/QuickConnect[1.1][2] ( 3096): A2dpProfile.onServiceConnected - Bluetooth service connected
D/BluetoothA2dp( 2024): Proxy object connected
,D/A2dpService( 3125): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 3125): classInitNative: succeeds
,D/A2dpStateMachine( 3125): make
I/bluedroid( 3125): get_profile_interface a2dp
,I/GKI_LINUX( 3125): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3125): Enter Disconnected: -2
,I/BluetoothAvrcpServiceJni( 3125): classInitNative: succeeds
,I/bluedroid( 3125): get_profile_interface avrcp
,D/MediaFocusControl(  756): >>> registerRemoteControlDisplay
,E/MediaFocusControl(  756): Error updating focussed RCC to RCD 
E/MediaFocusControl(  756): java.util.EmptyStackException
E/MediaFocusControl(  756): 	at java.util.Stack.peek(Stack.java:57)
E/MediaFocusControl(  756): 	at android.media.MediaFocusControl.registerRemoteControlDisplay_int(MediaFocusControl.java:2308)
E/MediaFocusControl(  756): 	at android.media.MediaFocusControl.registerRemoteControlDisplay(MediaFocusControl.java:250)
E/MediaFocusControl(  756): 	at android.media.AudioService.registerRemoteControlDisplay(AudioService.java:6425)
E/MediaFocusControl(  756): 	at android.media.IAudioService$Stub.onTransact(IAudioService.java:593)
E/MediaFocusControl(  756): 	at android.os.Binder.execTransact(Binder.java:404)
E/MediaFocusControl(  756): 	at dalvik.system.NativeStart.run(Native Method)
,I/BluetoothHidServiceJni( 3125): classInitNative: succeeds
,D/BluetoothInputDevice( 3096): Proxy object connected
,D/QuickConnect[1.1][2] ( 3096): HidProfile.onServiceConnected - Bluetooth service connected
,D/HidService( 3125): Received start request. Starting profile...
I/bluedroid( 3125): get_profile_interface hidhost
D/HidService( 3125): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 3125): classInitNative: succeeds
,D/HealthService( 3125): Received start request. Starting profile...
,I/bluedroid( 3125): get_profile_interface health
,I/BluetoothPanServiceJni( 3125): classInitNative(L105): succeeds
,D/BluetoothPan(  756): BluetoothPAN Proxy object connected
,D/PanService( 3125): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3125): initializeNative(L110): pan
,I/bluedroid( 3125): get_profile_interface pan
,D/BluetoothTethering(  756): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 3125): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 3125): mAccount : null
,D/HeadsetStateMachine( 3125): Try to query the phonestate on bind
,D/BluetoothPhoneService( 1240): handleMessage: 4
V/BluetoothPhoneService( 1240): Call state Converted2: IDLE/IDLE -> 6
,W/BluetoothHeadset( 1240): Proxy not attached to service
,D/HeadsetStateMachine( 3125): Proxy object connected
,D/HeadsetPhoneState( 3125): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 3125): Disconnected process message: 11
,D/HeadsetPhoneState( 3125): sendDeviceDataStateChanged
,D/HeadsetStateMachine( 3125): Disconnected process message: 20
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
D/HeadsetPhoneState( 3125): Signal level : previous=0 curr=0
D/BluetoothAdapterService( 3125): Profile still not running:com.android.bluetooth.hdp.HealthService
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3125): Disconnected process message: 10
D/HeadsetPhoneState( 3125): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3125): Disconnected process message: 11
,D/BluetoothAdapterService( 3125): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3125): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3125): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3125): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterState( 3125): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3125): enable
,D/AuthorizationBluetoothService( 1304): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/GKI_LINUX( 3125): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 3125): Calling BTA_HhEnable
,E/bt-btif ( 3125): btif_storage_get_adapter_property service_mask:0x140040
,E/BluetoothServiceJni( 3125): populateRssiValuesNative
I/bluedroid( 3125): getModelRssiValues
,E/BluetoothServiceJni( 3125): model_rssi_values_callback: low = -70, mid = -60, high = 127
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
,D/BtConfig.SecureMode( 3125): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 241
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BtConfig.SecureMode( 3125): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 241
,E/SMD     (  241): DCD ON
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/BtConfig.SecureMode( 3125): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 241
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,D/BtConfig.SecureMode( 3125): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 241
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 3125): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BtConfig.SecureMode( 3125): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 241
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BtConfig.SecureMode( 3125): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 241
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 10
,D/BtConfig.SecureMode( 3125): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 241
E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 10
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 241
E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
E/BluetoothRemoteDevices( 3125): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 241
E/bt-btif ( 3125): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 3125): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 3125): btif_sock_init: !radio_req && !rfc_init
D/IOP_DB_BT( 3125): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 3125): db_open: db_open : handle 2012082968l, read 9734 bytes onto local cache
D/IOP_DB_BT( 3125): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 3125): db_query: result 1
I/        ( 3125): iop_db_open: iop_db_open status 0
I/bte_conf( 3125): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3125): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 3125): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3125): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 3125): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3125): ScanMode =  20
D/BluetoothAdapterProperties( 3125): State =  11
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
I/BluetoothAdapterState( 3125): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3125): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3125): updateAdapterState state is 12
,D/BluetoothAdapterService( 3125): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService(1113345416)( 3125): Register RemoteMessageListener
D/HeadsetService( 3125): registerMessageListener
D/BluetoothAdapterService( 3125): Autoconnection is available 
D/BluetoothAdapterService( 3125): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 3125): starting service from this receiver
D/HeadsetStateMachine( 3125): Disconnected process message: 70
,D/HeadsetStateMachine( 3125): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@426078e8
W/ContextImpl( 3125): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
D/BluetoothA2dp(  756): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3125): Entering On State from state = 11
D/BluetoothInputDevice( 3096): onBluetoothStateChange: up=true
D/BluetoothA2dp( 3096): onBluetoothStateChange: up=true
,I/BluetoothPbapService( 3125): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothA2dp( 2024): onBluetoothStateChange: up=true
,D/BluetoothAdapterService( 3125): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[91]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[92]}
,D/bluedroid( 3125): init_wake_lock lock_fd:91, unlock_fd:92
,I/WifiTrafficPoller(  756): mBoosterFLAG : 2
,I/WifiTrafficPoller(  756): current booster mode : BTCoexMode
,D/BluetoothAdapterService(1113345416)( 3125): Get Bonded Devices being called
W/InputMethodManagerService(  756): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  756): [BT Setting State] State =12
,I/InputMethodManagerService(  756): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/PhoneApp( 1240): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
I/QuickConnect[1.1][2] ( 3096): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
D/BluetoothHeadset( 1240): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@422f3bb0, true
D/BluetoothHeadset( 1240): registerMessageListener
D/HeadsetService( 3125): registerMessageListener
D/HeadsetService( 3125): registerMessageListener
D/HeadsetStateMachine( 3125): Disconnected process message: 70
D/HeadsetStateMachine( 3125): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@42691208
D/PhoneApp( 1240): registerMessageListener
,D/BluetoothPanServiceJni( 3125): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,I/BluetoothPbapService( 3125): Handler(): got msg=1
,V/BluetoothPbapService( 3125): PBAP Service initSocket try: 0
,D/BluetoothMapMasInstance( 3125): set MAP SDP message type : 1
,W/BluetoothAdapter( 3125): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3125): SOCK FLAG = 1 ***********************
,W/BluetoothAdapter( 3125): getBluetoothService() called with no BluetoothManagerCallback
,D/STATUSBAR-IconMerger( 1067): checkOverflow(336), More:false, Req:false Child:2
D/BluetoothPbapService( 3125): PBAP Socket is BluetoothServerSocket
E/BluetoothServiceJni( 3125): SOCK FLAG = 3 ***********************
,W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/LocalBluetoothProfileManager( 1308): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1308): Adding local HEADSET profile
W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1308): BTStateChangeCB is registed
,W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
E/BluetoothHeadset( 1308): BluetoothHeadset service is binded
,D/Bluetoothsap( 1308): bindService called to Bluetooth SAP Service
W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/GKI_LINUX( 3125): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
,D/LocalBluetoothProfileManager( 1308): PANU : true
,D/LocalBluetoothProfileManager( 1308): Adding local MAP profile
,D/BluetoothMap( 1308): Create BluetoothMap proxy object
W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1308): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1308): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1308): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
D/BluetoothA2dp( 1308): Proxy object connected
D/A2dpProfile( 1308): Bluetooth service connected
,D/AuthorizationBluetoothService( 1304): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/HeadsetProfile( 1308): Bluetooth service connected
,E/AuthorizationBluetoothService( 1304): Proximity feature is not enabled.
,D/BluetoothInputDevice( 1308): Proxy object connected
,D/HidProfile( 1308): Bluetooth service connected
,D/BluetoothPan( 1308): BluetoothPAN Proxy object connected
,D/PanProfile( 1308): Bluetooth service connected
,D/BluetoothMap( 1308): Proxy object connected
D/MapProfile( 1308): Bluetooth service connected
,D/BluetoothPbap( 1308): Proxy object connected
,D/PbapServerProfile( 1308): Bluetooth service connected
,W/BluetoothAdapter( 3125): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3125): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 3125): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 3125): Accept thread started.
,D/Tethering(  756): interfaceAdded wlan0
,E/Tethering(  756): No numeric data
,D/Tethering(  756): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  756): forceRefresh() from cache miss
D/Tethering(  756): interfaceLinkStateChanged wlan0, false
,D/Tethering(  756): interfaceStatusChanged wlan0, false
,I/ConnectivityService(  756): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  756): InitialState.processMessage what=4
E/Tethering(  756): No numeric data
,D/Tethering(  756): interfaceAdded p2p0
D/Tethering(  756): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  756): forceRefresh Fail.
,D/Tethering(  756): p2p0 is not a tetherable iface, ignoring
I/ConnectivityService(  756): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  756): performPollLocked(flags=0x1)
,D/Tethering(  756): interfaceLinkStateChanged p2p0, false
,D/Tethering(  756): interfaceStatusChanged p2p0, false
,D/GKI_LINUX( 3125): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/WifiHW  (  238): wifi_change_fw_path(): fwpath = sta
,D/SoftapController(  238): Softap fwReload - Ok
D/NtpTrustedTime(  756): forceRefresh() from cache miss
D/NtpTrustedTime(  756): forceRefresh() from cache miss
,D/NtpTrustedTime(  756): forceRefresh Fail.
,D/NtpTrustedTime(  756): forceRefresh Fail.
V/NetworkStats(  756): performPollLocked() took 21ms
V/NetworkStats(  756): performPollLocked(flags=0x1)
,D/CommandListener(  238): Setting iface cfg
,D/CommandListener(  238): Trying to bring down wlan0
,D/NtpTrustedTime(  756): forceRefresh() from cache miss
,D/NtpTrustedTime(  756): forceRefresh Fail.
V/NetworkStats(  756): performPollLocked() took 16ms
,D/WifiHW  (  756): Skip the update_ctrl_interface
,D/WifiHW  (  756): Skip the update_ctrl_interface
,E/WifiHW  (  756): supplicant_name : p2p_supplicant
,I/wpa_supplicant( 4883): wpa_supplicant v2.1-devel-4.4.22014-11-04/18:06:52
I/wpa_supplicant( 4883): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 4883): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4883): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4883): getIMSI cannot open file
,E/wpa_supplicant( 4883): Interworking config: - SIM READ ERROR
,D/WifiMonitor(  756): startMonitoring(wlan0) with mConnected = false
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/knox    ( 3040): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/knox    ( 3040): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3040): KNOXAgentService : onCreate()
D/knox    ( 3040): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3040): KNOXAgentService. startJobThread() start
D/knox    ( 3040): KNOXAgentService. JobThread()
D/knox    ( 3040): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3040): KNOXAgentService. startJobThread() wait
,W/ContextImpl( 3040): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/wpa_supplicant( 4883): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4883): getIMSI cannot open file
E/wpa_supplicant( 4883): Interworking config: - SIM READ ERROR
I/wpa_supplicant( 4883): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 4883): rfkill: Cannot open RFKILL control device
D/Tethering(  756): interfaceLinkStateChanged wlan0, false
D/Tethering(  756): interfaceStatusChanged wlan0, false
I/SELinux ( 4885): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4885):  
D/knox    ( 3040): KNOXAgentService : onDestroy().
D/knox    ( 3040): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 4885): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4885):  
I/SELinux ( 4885):  
,I/SELinux ( 4885): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4885): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4885): >>>>> Normal User
,E/dalvikvm( 4885): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 4885): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/wpa_supplicant( 4883): wlan0: Setting scan request: 0 sec 100000 usec
,D/TimaKeyStoreProvider( 4885): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4885): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4885): Added TimaKesytore provider
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=4885, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
,I/wpa_supplicant( 4883): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4883): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4883): rfkill: Cannot open RFKILL control device
,D/Tethering(  756): interfaceLinkStateChanged p2p0, false
,D/Tethering(  756): interfaceStatusChanged p2p0, false
D/Tethering(  756): interfaceLinkStateChanged p2p0, false
,D/Tethering(  756): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4883): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/ActivityManager(  756): Killing 3639:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/wpa_supplicant( 4883): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
I/wpa_supplicant( 4883): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4883): Skip scan - bUseNetwork false
,D/WifiStateMachine(  756): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative(  756): callSECApiString - ID [21]
I/wpa_supplicant( 4883): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 4883): wlan0: HS20_DISABLED_COMPLETE normal
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1067): wifi: GONE sig=0 act=0
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/knox    ( 3040): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/knox    ( 3040): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/WifiNative(  756): callSECApiInt - ID [65]
,W/ContextImpl( 3040): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3040): KNOXAgentService : onCreate()
D/knox    ( 3040): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3040): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
D/knox    ( 3040): KNOXAgentService. startJobThread() start
D/knox    ( 3040): KNOXAgentService. JobThread()
D/knox    ( 3040): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3040): KNOXAgentService. startJobThread() wait
D/knox    ( 3040): KNOXAgentService : onDestroy().
D/knox    ( 3040): ModuleBase.cancelAllAlarmManageModule()
,E/WifiConfigStore(  756): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative(  756): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 4883): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 4883): reset timer : RESET_TIMER 0
I/wpa_supplicant( 4883): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 4883): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 4883): First Scan Start
,I/wpa_supplicant( 4883): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 2998): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine(  756): Set the Nv default ccode
,D/WifiStateMachine(  756): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine(  756): HS20_DISABLED_COMPLETEnormal
D/WifiP2pService(  756): P2pDisabledState{ what=131203 }
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.enterprise.wifi.WifiPolicy.asyncEnableNetwork:3065 com.android.server.enterprise.wifi.WifiPolicy.edmUpdateConfiguredNetworks:2530 com.android.server.enterprise.wifi.WifiPolicy$2$2.run:3022 java.lang.Thread.run:841 
,I/wpa_supplicant( 4883): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/CommandListener(  238): Setting iface cfg
,D/CommandListener(  238): Trying to bring up p2p0
,D/WifiMonitor(  756): startMonitoring(p2p0) with mConnected = true
,D/QuickConnect[1.1][2] ( 3096): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
D/WifiP2pService(  756): P2pEnablingState
D/WifiP2pService(  756): P2pEnablingState{ what=147457 }
D/WifiP2pService(  756): P2p socket connection successful
D/WifiP2pService(  756): P2pEnabledState
D/WifiP2pService(  756): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController(  756): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  756): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  756): disconnect
D/WifiDisplayController(  756): updateConnection
D/WifiDisplayController(  756): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  756): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 3096): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiDisplayAdapter(  756): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayController(  756): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/QuickConnect[1.1][2] ( 3096): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/QuickConnect[1.1][2] ( 3096): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/WifiP2pService(  756): DeviceAddress: 3a:06:dd
D/WifiDisplayController(  756): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy S5-2
D/WifiDisplayController(  756):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiDisplayController(  756):  primary type: 10-0050F204-5
D/WifiDisplayController(  756):  secondary type: null
D/WifiDisplayController(  756):  wps: 0
D/WifiDisplayController(  756):  grpcapab: 0
D/WifiDisplayController(  756):  devcapab: 0
D/WifiDisplayController(  756):  status: 3
D/WifiDisplayController(  756):  wfdInfo: null
D/WifiDisplayController(  756):  groupownerAddress: null
D/WifiDisplayController(  756):  GOdeviceName: null
D/WifiDisplayController(  756):  interfaceAddress: 
D/WifiDisplayController(  756):  SConnectInfo : null
,V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1308): MountReceiver.onReceive - Set preference state off
,D/QuickConnect[1.1][2] ( 3096): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,V/NearbySettings( 1308): MountReceiver.mPrefHandler - 7002
,E/WifiStateMachine(  756): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService(  756): sending p2p persistent groups changed broadcast
D/WifiP2pService(  756): InactiveState
D/WifiP2pService(  756): InactiveState{ what=139287 }
D/WifiP2pService(  756): P2pEnabledState{ what=139287 }
D/WifiP2pService(  756): DefaultState{ what=139287 }
,W/WifiP2pStateTracker(  756): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/FileShare-Server( 4137): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 4137): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,D/Tethering(  756): interfaceLinkStateChanged p2p0, false
,D/Tethering(  756): interfaceStatusChanged p2p0, false
,I/GAV2    ( 4705): Thread[GAThread,5,main]: No campaign data found.
,I/wpa_supplicant( 4883): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4883): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4883): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 4883): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 4883): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 4883): Trying to associate with  'G700'
,I/wpa_supplicant( 4883): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 4883): Cmd 35609 not handled
,D/Tethering(  756): interfaceLinkStateChanged wlan0, false
,D/Tethering(  756): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  756): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4883): Cmd 35605 not handled
I/wpa_supplicant( 4883): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 4883): Associated with C0.AA.48
E/wpa_supplicant( 4883): Cmd 35847 not handled
E/wpa_supplicant( 4883): Cmd 35848 not handled
,E/wpa_supplicant( 4883): Cmd 35605 not handled
,D/Tethering(  756): interfaceLinkStateChanged wlan0, false
,D/Tethering(  756): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 4883): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  756): interfaceLinkStateChanged wlan0, false
,D/Tethering(  756): interfaceStatusChanged wlan0, false
,D/Tethering(  756): interfaceLinkStateChanged wlan0, false
,D/Tethering(  756): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 4883): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 4883): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4883): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 4883): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative(  756): callSECApiVoid - ID [50]
,D/Tethering(  756): interfaceLinkStateChanged wlan0, true
,D/Tethering(  756): interfaceStatusChanged wlan0, true
,E/Tethering(  756): No numeric data
,D/Tethering(  756): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  756): forceRefresh() from cache miss
,D/NtpTrustedTime(  756): forceRefresh Fail.
I/ConnectivityService(  756): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  756): performPollLocked(flags=0x1)
,D/Tethering(  756): interfaceLinkStateChanged wlan0, true
,D/Tethering(  756): interfaceStatusChanged wlan0, true
D/Tethering(  756): interfaceLinkStateChanged wlan0, true
,D/Tethering(  756): interfaceStatusChanged wlan0, true
D/Tethering(  756): interfaceLinkStateChanged wlan0, true
,D/Tethering(  756): interfaceStatusChanged wlan0, true
D/Tethering(  756): interfaceLinkStateChanged wlan0, true
,D/Tethering(  756): interfaceStatusChanged wlan0, true
,V/NetworkStats(  756): performPollLocked() took 46ms
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/NtpTrustedTime(  756): forceRefresh() from cache miss
,D/NtpTrustedTime(  756): forceRefresh Fail.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 4925): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4925):  
,D/dalvikvm(  248): GC_EXPLICIT freed 43K, 50% free 9509K/18716K, paused 2ms+3ms, total 28ms
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 4925): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4925):  
I/SELinux ( 4925):  
,I/SELinux ( 4925): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4925): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4925): >>>>> Normal User
,E/dalvikvm( 4925): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 4925): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18716K, paused 2ms+5ms, total 23ms
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/WifiP2pService(  756): InactiveState{ what=143375 }
,D/WifiP2pService(  756): P2pEnabledState{ what=143375 }
D/TimaKeyStoreProvider( 4925): in addTimaSignatureService
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18716K, paused 2ms+3ms, total 22ms
,D/TimaKeyStoreProvider( 4925): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4925): Added TimaKesytore provider
,I/System.out( 4925): Inside WakeupProvider
,I/System.out( 4925): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 4925): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 4925): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 4925): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 4941): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 4941): bssid match
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1308): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1308): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  756): Killing 3687:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/DialogFlow( 4925): initQueue()
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/WifiP2pService(  756): InactiveState{ what=143375 }
,D/WifiP2pService(  756): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  756): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  756): evaluateTrafficStatsPolling
,D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
,I/WifiTrafficPoller(  756): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  756): mBoosterFLAG : 2
,I/WifiTrafficPoller(  756): current booster mode : BTCoexMode
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837939
D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
E/ConnectivityService(  756): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  756): net.tcp.delack.wifi not found in system properties. Using defaults
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService(  756): handleConnectivityChange: setting default proxy info 
,V/RouteController(  238): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1308): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1308): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,V/RouteController(  238): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/Toast   ( 1308):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1308): showing allowed
,V/RouteController(  238): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1308): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,I/SurfaceFlinger(  247): id=18 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  756): forceRefresh() from cache miss
V/NetworkStats(  756): updateIfacesLocked()
V/NetworkStats(  756): performPollLocked(flags=0x1)
,D/PowerManagerService(  756): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=756
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,V/NetworkStats(  756): performPollLocked() took 16ms
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  756): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449748688176 mCachedNtpElapsedRealtime : 131909 mCachedNtpCertainty : 11
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
D/NtpTrustedTime(  756): currentTimeMillis() cache hit
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
D/NtpTrustedTime(  756): currentTimeMillis() cache hit
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
V/NetworkStats(  756): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/Tethering(  756): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/NtpTrustedTime(  756): currentTimeMillis() cache hit
D/        (  756): Setting time of day to sec=1449748688
D/        (  756): Trying to open a file
,D/        (  756): File Open Success
D/        (  756): File Close Success
I/        (  756): DRM_TIME_PATH CHMOD 660 for resetState done 
,W/        (  756): Unable to set rtc to 1449748688: Invalid argument
V/AlarmManager(  756): waitForAlarm result :65540
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1443): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/LocSvc_java(  756): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  756): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  756): ignore wifi update if we are not in OPENING or CLOSING
,I/PCWCLIENTTRACE_PushUtil( 4486): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 4486): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4486): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4486): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,W/Settings(  756): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar-DoNotDistrub( 1067): Received intent with android.intent.action.TIME_SET action
D/StatusBar-DoNotDistrub( 1067): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,W/SEC_DRM_PLUGIN_Playready(  249): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1449748686 after conversion: 1449748686
,W/SEC_DRM_PLUGIN_Playready(  249): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1449748688 after conversion: 1449748688
,I/SensorManagerA(  756): getReportingMode :: sensor.mType = 5
I/AudioService(  756): getStreamVolume 5 index 110
D/Sensors (  756): LightSensor setDelay = 200000000
,D/Sensors (  756): LightSensor setSensorDelay = 200000000
D/Sensors (  756): Light sensor flush: not enabled 0
D/Sensors (  756): LightSensor enable = 1
D/Sensors (  756): LightSensor enableSensor = 1
,D/SensorManager(  756): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/accuweather( 1443): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1443): [KK AccuPhone]>>> SWW:452 [0:0] doChangeDayOrNight : 1
,D/accuweather( 1443): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
D/StatusBar-DoNotDistrub( 1067): sendBroadcast android.intent.action.DORMANT_MODE_OFF
D/STATUSBAR-NotificationService(  756): received android.intent.action.DORMANT_MODE_OFF
D/LightsService(  756): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 756) 
D/LightsService(  756): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/StatusBar-DoNotDistrub( 1067): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService(  756): manageDisableList what=0x0 pkg=com.android.systemui
,I/NetworkMonitor( 3720): type=WIFI subType= reason=null isConnected=true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 5011): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5011):  
,I/SELinux ( 5011): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5011):  
I/SELinux ( 5011):  
,I/SELinux ( 5011): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5011): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5011): >>>>> Normal User
,E/dalvikvm( 5011): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5011): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5011): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5011): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5011): Added TimaKesytore provider
,I/SELinux ( 5027): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5027):  
,D/Sensors (  756): LightSensor enable = 0
,D/Sensors (  756): LightSensor enableSensor = 0
,D/SensorManager(  756): unregisterListener ::   
D/LightsService(  756): [SvcLED]  onSensorChanged::light value = 35
I/SELinux ( 5027): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5027):  
I/SELinux ( 5027):  
,I/SELinux ( 5027): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5027): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5027): >>>>> Normal User
E/dalvikvm( 5027): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5027): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
D/LightsService(  756): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/TimaKeyStoreProvider( 5027): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5027): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5027): Added TimaKesytore provider
,I/dalvikvm( 1794): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1794): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1794): VFY: replacing opcode 0x6e at 0x003d
,E/ActivityThread( 1794): Failed to find provider info for com.android.contacts.metadata
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5011, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,D/SyncManager(  756): failed sync operation 
,D/SyncManager(  756): not retrying sync operation because the error is a hard error: 
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5027, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,D/DelayedSyncController( 5027): Delaying sync.
,I/SELinux ( 5050): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5050):  
,I/SELinux ( 5050): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5050):  
I/SELinux ( 5050):  
,I/SELinux ( 5050): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5050): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5050): >>>>> Normal User
,E/dalvikvm( 5050): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5050): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/PicasaService( 3811): start picasa sync
,D/PicasaService( 3811): end picasa sync
,D/TimaKeyStoreProvider( 5050): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5050): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5050): Added TimaKesytore provider
,D/SSRMv2:SIOP(  756): SIOP:: AP = 330, Delta = 20
,D/dalvikvm(  756): GC_EXPLICIT freed 2673K, 58% free 23388K/55032K, paused 7ms+14ms, total 139ms
,D/DelayedSyncController( 5027): Delaying sync.
,E/ConnectivityChangeReceiver( 1794): Ignoring connectivity change
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5050, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  756): Killing 3705:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/ActivityManager(  756): Killing 3933:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,I/SELinux ( 5066): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5066):  
,I/SELinux ( 5066): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5066):  
I/SELinux ( 5066):  
,I/SELinux ( 5066): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5066): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5066): >>>>> Normal User
E/dalvikvm( 5066): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5066): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/TimaKeyStoreProvider( 5066): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5066): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5066): Added TimaKesytore provider
,W/DriveInitializer( 1794): Awaiting to be initialized
,W/DriveInitializer( 1794): Background init thread started
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 1794): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5066, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,D/KLMS-2.3.201 : ( 5066): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5066): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449748689863
,I/KLMS-2.3.201 : ( 5066): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,W/DriveInitializer( 1794): Background init thread ended
,I/ActivityManager(  756): Killing 3957:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 5091): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5091):  
,I/LocationTagReadyService( 2339): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2339): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2339): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 5096): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5096):  
,I/SELinux ( 5091): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5091):  
I/SELinux ( 5091):  
,I/SELinux ( 5091): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5091): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5091): >>>>> Normal User
,E/dalvikvm( 5091): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5091): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5091): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5091): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5091): Added TimaKesytore provider
,I/SELinux ( 5096): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5096):  
I/SELinux ( 5096):  
,I/SELinux ( 5096): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5096): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5096): >>>>> Normal User
,E/dalvikvm( 5096): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,D/GalaxyFinderApplication( 2339): [Slink platform] The state of Slink geocode service is true
,E/SELinux ( 5096): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/GallerySearchProvider( 3811): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/TimaKeyStoreProvider( 5096): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5096): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5096): Added TimaKesytore provider
,I/SELinux ( 5116): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5116):  
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5091, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  756): Killing 3927:com.android.calendar/u0a142 (adj 15): empty #43
,D/SO_AGENT( 5091): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/SELinux ( 5116): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5116):  
I/SELinux ( 5116):  
,I/SELinux ( 5116): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5116): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5116): >>>>> Normal User
,E/dalvikvm( 5116): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5116): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SO_AGENT( 5091): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/TimaKeyStoreProvider( 5116): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5116): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5116): Added TimaKesytore provider
,E/SMD     (  241): DCD ON
,V/KVNProvider( 5116): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5116): getFindoCursor query string : 
,V/KVNProvider( 5116): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4655): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/ActivityManager(  756): Killing 3978:com.android.providers.calendar/u0a44 (adj 15): empty #43
,I/SA      ( 4655): [BDLM] already registered in spp
,I/SA      ( 4655): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4655): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4655): [SLFUCHKMGR] constructor called
,I/dalvikvm( 4596): Total arena pages for JIT: 11
,I/dalvikvm( 4596): Total arena pages for JIT: 12
I/dalvikvm( 4596): Total arena pages for JIT: 13
,I/dalvikvm( 4596): Total arena pages for JIT: 14
,I/SA      ( 4655): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4655): [OR] == isSIMCardReady false ==
,I/SA      ( 4655): [SCU] == networkStateCheck == true
I/SA      ( 4655): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4655): isChinaCountryCode : false
,I/SA      ( 4655): [OR] == networkStateCheck true ==
,I/SA      ( 4655): [OR] GetMyCountryZoneTask
,I/SA      ( 4655): [OR] onReceive END
,D/btif_config_util( 3125): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
I/ActivityManager(  756): Killing 3982:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,I/SA      ( 4655): [SRS] prepareGetMyCountryZone
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SA      ( 4655): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4655): [SSP] query invoked
,I/SELinux ( 5140): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5140):  
,I/SA      ( 4655): [TPMU] GetMccFromDB : null
I/SA      ( 4655): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4655): [TPM] isNoProxy(default) : true
,I/SA      ( 4655): [RC New] Execute method=[GET] start
,I/SELinux ( 5140): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5140):  
I/SELinux ( 5140):  
I/SELinux ( 5140): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5140): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5140): >>>>> Normal User
E/dalvikvm( 5140): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5140): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5140): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5140): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5140): Added TimaKesytore provider
,I/sCloudBackupApp( 5140): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5140): Other Intent
I/ActivityManager(  756): Killing 3910:com.sec.phone/1001 (adj 15): empty #43
,D/com.samsung.app( 1443): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1443): [KK_EASY_Accu]>>> WC:37 [0:0] oR : create UI manager : start
,D/com.samsung.app( 1443): [KK_EASY_Accu]>>> UIMEM:89 [0:0] getInstance
,D/com.samsung.app( 1443): [KK_EASY_Accu]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1443): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 1443): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1459): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1443): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1459): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1443): [KK AccuPhone]>>> DBH:3047 [0:0] gADWI : count = 0
,D/daemonapp( 1459): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 1443): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 1443): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5154): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5154):  
,I/Scheduler( 1219): Use legacy PeriodicScheduler
,W/InstanceID/Rpc( 1219): Found 10011
,I/SELinux ( 5154): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5154):  
I/SELinux ( 5154):  
,I/SELinux ( 5154): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5154): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5154): >>>>> Normal User
,E/dalvikvm( 5154): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10106 ]
,E/SELinux ( 5154): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 5154): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5154): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5154): Added TimaKesytore provider
,I/System.out( 4655): Thread-449(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4655): Thread-449(ApacheHTTPLog):isShipBuild true
,I/System.out( 4655): Thread-449(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/HeadlinesChannelApplication( 5154): [onCreate]
,D/Headlines( 5154): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5154, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,D/HeadlinesChannelUtil( 5154): getCountryCode(): countryCode = PL
,D/Headlines( 5154): Breath.onCreate
,D/HeadlinesCardManager( 5154): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 5154): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 5154): CardProvider Library : 13
,I/SELinux ( 5167): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5167):  
,D/MagazineService::CardProviderContentProvider( 4748): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 4748): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5154): registerCardProvider: provider already exists.
,I/Headlines( 5154): HeadlinesDataCenter ctor
,I/Headlines( 5154): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 5154): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 5154): HeadlinesCardManager : constructor welcome :YES
I/SELinux ( 5167): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5167):  
I/SELinux ( 5167):  
,I/SELinux ( 5167): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5167): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5167): >>>>> Normal User
,E/dalvikvm( 5167): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5167): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5167): in addTimaSignatureService
D/TimaKeyStoreProvider( 5167): Cannot add TimaSignature Service, License check Failed
,D/Headlines( 5154): Breath timer started. interval : 30000
,D/ActivityThread( 5167): Added TimaKesytore provider
D/Headlines( 5154): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5154): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5154): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5154): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5154): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5154): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5154): requestUpdateNewsWelcomeCard !!! no welcome card
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5167): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5167): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 5167): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 5167): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    (  228): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5167): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/WifiStateMachine(  756): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,V/WebViewChromium( 5167): Binding Chromium to the main looper Looper (main, tid 1) {42291210}
,I/chromium( 5167): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5167): Initializing chromium process, renderers=0
,W/chromium( 5167): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5167): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5167): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5167): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5167): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5167): Remote Branch: 
I/Adreno-EGL( 5167): Local Patches: 
I/Adreno-EGL( 5167): Reconstruct Branch: 
,I/NSApplication( 5167): Starting up...
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5167, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  756): Killing 3855:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 3096): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3096): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3096): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425c5e38
,I/SELinux ( 5204): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5204):  
,I/SurfaceFlinger(  247): id=18 Removed Uoast (11/12)
,I/SurfaceFlinger(  247): id=18 Removed Uoast (-2/12)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  756): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=756 (0x0)
,D/PowerManagerService(  756): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=756, ws=WorkSource{1000}) (elapsedTime=3465)
,I/ActivityManager(  756): Killing 2998:com.google.android.talk/u0a105 (adj 15): empty #43
,D/dalvikvm(  248): GC_EXPLICIT freed 43K, 50% free 9509K/18716K, paused 2ms+3ms, total 32ms
I/SELinux ( 5204): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5204):  
I/SELinux ( 5204):  
,I/SELinux ( 5204): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5204): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5204): >>>>> Normal User
,E/dalvikvm( 5204): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5204): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18716K, paused 3ms+3ms, total 21ms
,D/TimaKeyStoreProvider( 5204): in addTimaSignatureService
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18716K, paused 1ms+3ms, total 19ms
,D/TimaKeyStoreProvider( 5204): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5204): Added TimaKesytore provider
,D/RCPManagerService(  756): exchangeData() failure , invalid userId
,D/RCPManagerService(  756): exchangeData() failure , invalid userId
,D/RCPManagerService(  756): exchangeData() failure , invalid userId
,I/HarmonyEASService(  756): Updating for all 1
,I/SA      ( 4655): [RC New] [v2liruge] api execute + 1236
,I/SA      ( 4655): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4655): AsyncTask #1 calls detatch()
,I/SA      ( 4655): [TPMU] getNetworkMcc : 
,I/SA      ( 4655): [SCU] saveMccToPreferece Start
I/SA      ( 4655): [SCU] RegionMCC : 260
,I/SA      ( 4655): [SSP] query invoked
I/SA      ( 4655): [TPMU] GetMccFromDB : null
,I/SA      ( 4655): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4655): [SCU] saveMccToPreferece End
I/SA      ( 4655): [RC New] executeRequest [v2liruge] end. 1250
,I/SA      ( 4655): [RC New] Execute end
I/SA      ( 4655): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4655): [OR] GetMyCountryZoneTask Success
,D/RCPManagerService(  756): exchangeData() failure , invalid userId
,D/RCPManagerService(  756): exchangeData() failure , invalid userId
,D/RCPManagerService(  756): exchangeData() failure , invalid userId
,I/SELinux ( 5223): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5223):  
I/ActivityManager(  756): Killing 4002:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,I/SELinux ( 5227): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5227):  
,W/ActivityManager(  756): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5223): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5223):  
I/SELinux ( 5223):  
,I/SELinux ( 5223): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5223): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5223): >>>>> Normal User
,E/dalvikvm( 5223): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5223): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/SELinux ( 5227): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5227):  
I/SELinux ( 5227):  
,I/SELinux ( 5227): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/TimaKeyStoreProvider( 5223): in addTimaSignatureService
,E/SELinux ( 5227): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5227): >>>>> Normal User
,E/dalvikvm( 5227): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5227): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5223): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5223): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 5227): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5227): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5227): Added TimaKesytore provider
,I/ActivityManager(  756): Killing 2850:com.sec.knox.bridge/1000 (adj 15): empty #43
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5223, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/WaitQueueForNetworkActivate( 4799): notifyNetworkActivated
,D/BadgeProvider( 5227): onCreate
,D/BadgeProvider( 5227): DatabaseHelper
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5227, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5227): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ContextImpl( 4799): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager(  756): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/BadgeProvider( 5227): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5227): sendNotify, [notify] : null
,D/BadgeProvider( 5227): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5227): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5227): update, [UpdateCount] : 1
,D/Launcher.Model( 1261): reloadBadges entered.
,D/dalvikvm(  756): GC_EXPLICIT freed 1356K, 58% free 23289K/55032K, paused 5ms+11ms, total 126ms
,D/hcjo    ( 4799): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 4799): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 4799): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 4799): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 4799): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4799): exit::IDLE
,D/InitializeManagerStateMachine( 4799): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4799): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4799): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4799): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4799): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4799): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4799): entry::SUCCESS
,D/hcjo    ( 4799): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4799): AutoUpdateTriggerManager:IDLE:setInterval:345600000
D/hcjo    ( 4799): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4799): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4799): exit::SUCCESS
,D/InitializeManagerStateMachine( 4799): entry::IDLE
I/ActivityManager(  756): Killing 4200:com.wssyncmldm/1000 (adj 15): empty #43
,I/iu.SyncManager( 1794): SYNC; picasa accounts
,D/NetworkLogImpl( 1794): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1794): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1794): num queued entries: 0
,I/iu.UploadsManager( 1794): num updated entries: 0
,I/iu.SyncManager( 1794): NEXT; no task
,I/SELinux ( 5258): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5258):  
,I/SELinux ( 5258): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5258):  
I/SELinux ( 5258):  
,I/SELinux ( 5258): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5258): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5258): >>>>> Normal User
,E/dalvikvm( 5258): >>>>> com.android.calendar [ userId:0 | appId:10142 ]
,E/SELinux ( 5258): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5258): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5258): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5258): Added TimaKesytore provider
,I/GCM     ( 1304): GCM config loaded
,I/ActivityManager(  756): Killing 4385:com.android.defcontainer/u0a6 (adj 15): empty #43
D/BootCompletedReceiver(  756): onReceive
,I/KLMS-2.3.201 : ( 5066): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5066): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1449748692599
,I/KLMS-2.3.201 : ( 5066): StateImplV2() : dateTimeChanged() : Thu Dec 10 12:58:12 CET 2015
,D/SO_AGENT( 5091): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 5091): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 4655): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/Mms/MessagingNotification( 3744): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 3744): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 3744): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 3744): isDefault true
,D/TP/MmsSmsProvider( 1240): match 8:Elapsed time : 2.744 ms
,I/SELinux ( 5282): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5282):  
,D/TP/MmsSmsProvider( 1240): match 200:Elapsed time : 1.042 ms
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/BadgeProvider( 5227): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/Launcher.Model( 1261): reloadBadges entered.
D/BadgeProvider( 5227): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5227): sendNotify, [notify] : null
D/BadgeProvider( 5227): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5227): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5227): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 3744): setBadgeCount(), count=0
,D/MessagingNotification( 3744): remove alarm
I/SELinux ( 5282): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5282):  
I/SELinux ( 5282):  
,I/SELinux ( 5282): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5282): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5282): >>>>> Normal User
,E/dalvikvm( 5282): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 5282): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/Mms/MessagingNotification( 3744): [end]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 3744): updateAllHistoryAsRead()
,D/TimaKeyStoreProvider( 5282): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5282): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5282): Added TimaKesytore provider
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5282, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,D/com.samsung.app( 1443): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,I/ActivityManager(  756): Killing 3158:com.sec.android.inputmethod/1000 (adj 15): empty #43
D/com.samsung.app( 1443): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 5282): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 5302): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5302):  
,I/SELinux ( 5302): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5302):  
I/SELinux ( 5302):  
,I/SELinux ( 5302): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5302): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5302): >>>>> Normal User
,E/dalvikvm( 5302): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 5302): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5302): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5302): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5302): Added TimaKesytore provider
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5318): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5318):  
I/ActivityManager(  756): Killing 4442:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,I/SELinux ( 5318): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5318):  
I/SELinux ( 5318):  
,I/SELinux ( 5318): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5318): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5318): >>>>> Normal User
,E/dalvikvm( 5318): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 5318): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5318): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5318): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5318): Added TimaKesytore provider
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5318, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 5318): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
D/elm:14132( 5318): ELMEngine.ELMEngine( context ).
D/elm:14132( 5318): MDMBridge.setEnterpriseBridge()
D/elm:14132( 5318): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,I/knox    ( 3040): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 5318): ElmAgentService : onCreate()
D/knox    ( 3040): MainReceiver.listeningToTimeDateChanges( context, intent ).
,I/knox    ( 3040): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 5318): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/elm:14132( 5318): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 5318): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14132( 5318): ModuleBase.resetCalllogAPIAlarm()
W/ContextImpl( 3040): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,D/knox    ( 3040): KNOXAgentService : onCreate()
,D/knox    ( 3040): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3040): KNOXAgentService. startJobThread() start
D/knox    ( 3040): KNOXAgentService. JobThread()
,D/knox    ( 3040): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3040): KNOXAgentService. startJobThread() wait
,I/SELinux ( 5333): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5333):  
,D/elm:14132( 5318): ModuleBase.ModifySetAlarm()
,D/elm:14132( 5318): MDMBridge.getInstance()
,D/elm:14132( 5318): MDMBridge.getAllLicenseInfoFromSDK()
,D/knox    ( 3040): KNOXAgentService : onDestroy().
,D/knox    ( 3040): ModuleBase.cancelAllAlarmManageModule()
,D/elm:14132( 5318): ElmAgentService : onDestroy().
I/ActivityManager(  756): Killing 4457:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/SELinux ( 5333): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5333):  
I/SELinux ( 5333):  
,I/SELinux ( 5333): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5333): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5333): >>>>> Normal User
,E/dalvikvm( 5333): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10143 ]
,E/SELinux ( 5333): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5333): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5333): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5333): Added TimaKesytore provider
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5333, uid=10143 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5349): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5349):  
I/ActivityManager(  756): Killing 4471:com.android.musicfx/u0a24 (adj 15): empty #43
,I/SELinux ( 5349): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5349):  
I/SELinux ( 5349):  
,I/SELinux ( 5349): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5349): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5349): >>>>> Normal User
,E/dalvikvm( 5349): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
,E/SELinux ( 5349): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5349): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5349): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5349): Added TimaKesytore provider
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5349, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5361): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5361):  
I/ActivityManager(  756): Killing 4498:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty #43
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4486): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 4486): [hasSamungAccount] - No Samsung Account
,I/SELinux ( 5361): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5361):  
I/SELinux ( 5361):  
,I/SELinux ( 5361): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5361): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5361): >>>>> Normal User
,E/dalvikvm( 5361): >>>>> com.qualcomm.timeservice [ userId:0 | appId:10168 ]
V/AlarmManager(  756): waitForAlarm result :4
,V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
E/SELinux ( 5361): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5361): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5361): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5361): Added TimaKesytore provider
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5361, uid=10168 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 5361): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x425b6918, skipping init
D/TimeService( 5361): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449748693730
D/        ( 5361): TimeServiceNative: User Time to be set is 1449748693730
D/QC-time-services( 5361): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5361): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5361): Lib:time_genoff_operation: pargs->ts_val = 1449748693730
D/QC-time-services(  291): Daemon: Connection accepted:time_genoff
D/QC-time-services( 5361): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  291): Daemon: genoff_handler: Process name is omm.timeservice
D/QC-time-services(  291): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449748693730
D/QC-time-services(  291): Daemon:genoff_opr: Base = 2, val = 1449748693730, operation = 0
D/QC-time-services(  291): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/14/70 3:55:21
W/linker  ( 4486): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/QC-time-services(  291): Daemon:Value read from RTC seconds = 1137321000
D/QC-time-services(  291): Daemon:new time 1449748693730 
D/QC-time-services(  291): Daemon: delta 1448611372730 genoff 1448611372730 
D/QC-time-services(  291): Daemon:genoff_persistent_update: Writing genoff = 1448611372730 to memory
D/QC-time-services(  291): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  291): Daemon:time_persistent_memory_opr:Genoff write operation 
I/CSTORAGE( 4486): ================================================
I/CSTORAGE( 4486):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 4486): ================================================
D/dalvikvm( 4486): No JNI_OnLoad found in /system/lib/libterrier.so 0x425b6170, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4486): [GetString-S]
I/terrier ( 4486): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 4486): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 4486): App is not loaded in QSEE
D/QC-time-services(  291): Updating the TOD offset
D/QC-time-services(  291): Daemon:genoff_persistent_update: Writing genoff = 1448611372730 to memory
D/QC-time-services(  291): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  291): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  291): Daemon:Update to modem bit set
D/QC-time-services(  291): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  291): Daemon: Base = 2, Value being sent to MODEM = 1133783893730
E/QC-time-services( 5361): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  291): Daemon: Time-services: Waiting to acceptconnection
I/PowerManagerService(  756): [PWL] Off : 75s ago
I/PowerManagerService(  756): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  756): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  756): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=756, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=5110)
I/PowerManagerService(  756): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10084, pid=5302, ws=null) (elapsedTime=636)
E/QC-time-services(  291): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  756): Killing 4532:com.sec.android.service.health/u0a16 (adj 15): empty #43
D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
D/BatteryService(  756): stay LED for fully charged
D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3125): Disconnected process message: 10
D/UiModeManager(  756): mCoverManager.getCoverState() : true
D/daemonapp( 1459): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1459): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1459): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1459): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/QSEECOMAPI: ( 4486): Loaded image: APP id = 3
D/daemonapp( 1459): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 1459): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1459): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1459): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1459): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1459): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/daemonapp( 1459): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/QSEECOMAPI: ( 4486): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 4486): QSEECom_shutdown_app, app_id = 3
E/terrier ( 4486): com.sec.pcw.device: getString: failed to get string(-1)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4486): [GetString-E]
D/daemonapp( 1459): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
I/PCWCLIENTTRACE_PushUtil( 4486): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4486): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4486): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 4486): [ensureRegistration] - No Samsung account
D/daemonapp( 1459): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1459): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1459): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 1459): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
D/comdaemonstockapp( 1459): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 1459): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
I/CheckinService( 1794): Checkin interval check for package: unspecified last checkin: 1449576543959 min interval config: 0 actual interval: 172149887
W/WifiP2pStateTracker(  756): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
D/ConnectivityService(  756): handleConnectivityChange: setting default proxy info 
I/rmt_storage(  299): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7c80178
I/rmt_storage(  299): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  299): wakelock acquired: 1, error no: 42
I/rmt_storage(  299): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1211629848)
D/ConnectivityService(  756): updateSourceRoutes : no source routing conditions
D/dalvikvm( 1794): GC_CONCURRENT freed 1776K, 35% free 12250K/18716K, paused 4ms+8ms, total 53ms
I/rmt_storage(  299): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  299): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  299): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1211629848) wakelock released: 1, error no: 0
I/rmt_storage(  299): 
I/rmt_storage(  299): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7c80178
D/Mms/MessagesLockscreen( 3744): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
D/ContextualEventManager( 1067): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1067): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1067): updateContainer()
D/ContextualEventContainer( 1067): update()
D/ContextualEventContainer( 1067): handleUpdate()
D/ContextualEventManager( 1067): getTopEventView()
D/ContextualEventManager( 1067): getTopContextualEvent()
I/SELinux ( 5380): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5380):  
D/ContextualEventManager( 1067): top view = flightmode
I/KeyguardEffectViewMain( 1067): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1067): getTopEventClass()
D/ContextualEventManager( 1067): getTopContextualEvent()
D/ContextualEventManager( 1067): !isClockTop
D/ContextualEventManager( 1067): getTopEventClass()
D/ContextualEventManager( 1067): getTopContextualEvent()
D/ContextualEventManager( 1067): !isClockTop
D/ContextualEventManager( 1067): getTopEventClass()
D/ContextualEventManager( 1067): getTopContextualEvent()
D/UsbManager( 1067):  :::: isUsb30Available :: return = false from pid = 1067
D/SecContextualClockFlightMode( 1067): handleUpdateClock()
D/KeyguardProperties( 1067): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/SELinux ( 5380): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5380):  
I/SELinux ( 5380):  
I/SELinux ( 5380): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5380): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5380): >>>>> Normal User
E/dalvikvm( 5380): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
E/SELinux ( 5380): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5380): in addTimaSignatureService
D/TimaKeyStoreProvider( 5380): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5380): Added TimaKesytore provider
I/VacuumService( 1219): Vacuum at: now=1449748694207 tag=VacuumService
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5380, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,D/Headlines( 5154): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5154): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5154): Breath 3487 latestRequest time : 1449748691031 current time : 1449748694518
,V/AlarmManager(  756): waitForAlarm result :4
,V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/ActivityManager(  756): Killing 3824:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty #43
,D/Finsky  ( 3474): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3474): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/Watchdog(  756): !@Sync 4
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/GAV2    ( 5167): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4642): Test app app.js loaded
I/jxcore-log( 4642): 
,E/SMD     (  241): DCD ON
,I/chromium( 4642): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/AmoledAdjustTimer(  756): prevTemp = 296, currTemp = 301, prevStep = 4, currStep = 5
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
,W/ActivityThread(  756): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out(  756): Thread-162(HTTPLog):isShipBuild true
,I/System.out(  756): Thread-162(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 330, Delta = 0
,E/SMD     (  241): DCD ON
,D/PreloadUpdateManagerStateMachine( 4799): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4799): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4799): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4799): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 4799): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4799): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4799): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4799): entry::IDLE
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  756): stay LED for fully charged
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/ActivityManager(  756): Waited long enough for: ServiceRecord{44306988 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/dalvikvm(  756): GC_EXPLICIT freed 1759K, 58% free 23542K/55032K, paused 29ms+75ms, total 750ms
,D/AmoledAdjustTimer(  756): prevTemp = 301, currTemp = 302, prevStep = 5, currStep = 5
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 310, Delta = -20
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 302, currTemp = 302, prevStep = 5, currStep = 5
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = -10
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :4
,V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/ActivityThread( 1794): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  756): failed sync operation 
,D/SyncManager(  756): not retrying sync operation because the error is a hard error: 
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 105s ago
,E/Watchdog(  756): !@Sync 5
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 302, currTemp = 299, prevStep = 5, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :4
,V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5154): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5154): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5154): Breath 41535 latestRequest time : 1449748691031 current time : 1449748732566
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  756): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :4
,V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/AlarmManager(  756): waitForAlarm result :8
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/Headlines( 5154): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5154): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5154): Breath 60096 latestRequest time : 1449748691031 current time : 1449748751127
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 6
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 298, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService(  756): [PWL] Off : 140s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,D/Headlines( 5154): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5154): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5154): Breath 90055 latestRequest time : 1449748691031 current time : 1449748781086
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 7
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 180s ago
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  756): waitForAlarm result :8
,D/Headlines( 5154): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5154): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5154): Breath 120050 latestRequest time : 1449748691031 current time : 1449748811082
,D/Headlines( 5154): stop 
,D/Headlines( 5154): Breath.onDestroy : 
,I/ActivityManager(  756): Killing 2797:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 8
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 225s ago
,E/Watchdog(  756): !@Sync 9
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/TimaService(  756): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  756): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  756): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  756): initializing...
,I/TLC_TIMA_PKM_initialize(  756): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  756): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  756): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  756): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  756): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  756): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  756): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  756): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  756): App is not loaded in QSEE
,D/QSEECOMAPI: (  756): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  756): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  756): Trustlet response is completed
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  756): !@Sync 10
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 275s ago
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :4
,V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5503): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5503):  
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/dalvikvm(  248): GC_EXPLICIT freed 41K, 50% free 9509K/18716K, paused 24ms+36ms, total 341ms
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18716K, paused 23ms+11ms, total 150ms
,I/SELinux ( 5503): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5503):  
I/SELinux ( 5503):  
,I/SELinux ( 5503): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5503): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5503): >>>>> Normal User
,E/dalvikvm( 5503): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5503): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18716K, paused 7ms+4ms, total 70ms
,D/TimaKeyStoreProvider( 5503): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5503): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5503): Added TimaKesytore provider
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5503, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  756): Killing 4687:com.sec.android.service.cm/u0a78 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1304): GC_EXPLICIT freed 1259K, 43% free 10776K/18716K, paused 24ms+29ms, total 204ms
,D/dalvikvm( 3474): GC_CONCURRENT freed 2767K, 45% free 10434K/18716K, paused 6ms+7ms, total 75ms
,E/Watchdog(  756): !@Sync 11
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/jxcore-log( 4642): Toggling radios to false
I/jxcore-log( 4642): 
,D/BluetoothAdapterService(1113345416)( 3125): unRegister RemoteMessageListener
,D/HeadsetService( 3125): registerMessageListener
,D/HeadsetStateMachine( 3125): Disconnected process message: 80
,D/HeadsetStateMachine( 3125): processUnRegisterMessageListener : 2
,D/BluetoothAdapterState( 3125): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,I/BluetoothAdapterState( 3125): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 3125): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3125): updateAdapterState state is 13
,I/BluetoothPbapService( 3125): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,E/bt-btif ( 3125): bta_jv_rfcomm_stop_server
,I/WifiManager( 4642): packageName : com.test.thalitest
,I/WifiManager( 4642): setWifiEnabled : false
,I/WifiService(  756): setWifiEnabled: false pid=4642, uid=10179
,D/BluetoothAdapterService( 3125): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService( 3125): Autoconnection is available 
,D/BluetoothAdapterService( 3125): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 3125): terminating service from this receiver
,W/ContextImpl( 3125): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,W/InputMethodManagerService(  756): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  756): [BT Setting State] State =13
,D/GKI_LINUX( 3125): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BluetoothAdapterState( 3125): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(336), More:false, Req:false Child:2
,D/PhoneApp( 1240): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,I/jxcore-log( 4642): Radios toggled
I/jxcore-log( 4642): 
,I/QuickConnect[1.1][2] ( 3096): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
,D/GKI_LINUX( 3125): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
I/wpa_supplicant( 4883): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 4883): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 4883): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings(  756): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  756): ignore requestNetworkTransitionWakelock airplane:true
,D/BluetoothPbap( 1308): Proxy object disconnected
,D/WifiP2pService(  756): InactiveState{ what=143375 }
,D/WifiP2pService(  756): P2pEnabledState{ what=143375 }
,D/AmoledAdjustTimer(  756): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/PbapServerProfile( 1308): Bluetooth service disconnected
,V/BluetoothEventManager( 1308): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterState( 3125): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 3125): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 3125): bta_jv_rfcomm_stop_server
,E/BtOppRfcommListener( 3125): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 3125): bta_jv_rfcomm_stop_server
,E/bt-btif ( 3125): cmd socket is not created
,D/GKI_LINUX( 3125): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 3125): stopping Accept Thread
,D/btif_config_util( 3125): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/BtOppRfcommListener( 3125): BluetoothSocket listen thread finished
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  238): Clearing all IP addresses on wlan0
,D/IOP_DB_BT( 3125): db_close: nbr users 0
D/IOP_DB_BT( 3125): db_close: free database
,I/WifiTrafficPoller(  756): evaluateTrafficStatsPolling
D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  756): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  756): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  756): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  756): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/ConnectivityService(  756): Attempting to switch to mobile
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
E/WifiStateMachine(  756): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  756): Error! unhandled message{ when=-5ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  756): InactiveState{ what=131204 }
D/WifiP2pService(  756): P2pEnabledState{ what=131204 }
,D/DockEventReceiver( 1308): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
D/WifiP2pService(  756): sending p2p connection changed broadcast: FAILED
W/WifiP2pStateTracker(  756): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController(  756): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter(  756): onP2pDisconnected
D/IpRemoteDisplayController(  756): disconnectWfdBridgeServer
,D/IpRemoteDisplayController(  756): WfdBridgeServer is already null
D/QuickConnect[1.1][2] ( 3096): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/QuickConnect[1.1][2] ( 3096): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/AuthorizationBluetoothService( 1304): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/RouteController(  238): /system/bin/ip -6 route del default table 2 2>&1
,E/WifiStateMachine(  756): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/QuickConnect[1.1][2] ( 3096): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
D/QuickConnect[1.1][2] ( 3096): P2pHelper.cancelConnectPeer -  mTargetList clear all 
,D/QuickConnect[1.1][2] ( 3096): P2pHelper.removeP2pConfirm - skip: false
,D/QuickConnect[1.1][2] ( 3096): CentralActionManager.removeHoldingIntentAll - all request done.
D/WifiP2pService(  756): sending p2p connection changed broadcast: DISCONNECTED
D/WifiDisplayController(  756): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  756): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  756): disconnect
D/WifiDisplayController(  756): updateConnection
D/WifiDisplayController(  756): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter(  756): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: FAILED
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1308): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1308): MountReceiver.mPrefHandler - 7002
,D/QuickConnect[1.1][2] ( 3096): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiDisplayAdapter(  756): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/RouteController(  238): RTNETLINK answers: No such process
,D/QuickConnect[1.1][2] ( 3096): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,V/RouteController(  238): /system/bin/ip -6 rule del table 2 2>&1
,D/QuickConnect[1.1][2] ( 3096): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 3096): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/WifiP2pService(  756): P2pDisablingState
W/WifiP2pStateTracker(  756): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController(  756): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter(  756): onP2pDisconnected
D/IpRemoteDisplayController(  756): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  756): WfdBridgeServer is already null
D/WifiP2pService(  756): P2pDisablingState{ what=139287 }
D/WifiP2pService(  756): DefaultState{ what=139287 }
D/WifiP2pService(  756): P2pDisablingState{ what=147458 }
D/WifiP2pService(  756): p2p socket connection lost
D/WifiP2pService(  756): P2pDisabledState
D/WifiP2pService(  756): P2pDisabledState{ what=139376 }
D/WifiP2pService(  756): DefaultState{ what=139376 }
D/QuickConnect[1.1][2] ( 3096): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1308): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1308): MountReceiver.mPrefHandler - 7002
,D/BluetoothAdapterState( 3125): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 3125): isSecureModeOn:false
E/WifiP2pService(  756): Unhandled message { what=139376 }
D/WifiP2pService(  756): P2pDisabledState{ what=139287 }
,D/WifiP2pService(  756): DefaultState{ what=139287 }
W/BluetoothAdapterService( 3125): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3125): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3125): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 3125): Not skipping com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 3125): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3125): Not skipping com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 3125): Received stop request...Stopping profile...
W/BluetoothAdapterService( 3125): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 3125): Not skipping com.android.bluetooth.hid.HidService
D/FileShare-Server( 4137): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/QuickConnect[1.1][2] ( 3096): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
W/BluetoothAdapterService( 3125): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 3125): Not skipping com.android.bluetooth.hdp.HealthService
V/RouteController(  238): RTNETLINK answers: No such file or directory
D/A2dpService( 3125): Received stop request...Stopping profile...
D/HeadsetProfile( 1308): Bluetooth service disconnected
D/Avrcp   ( 3125): Unregistering previous receiver
D/A2dpStateMachine( 3125): Exit Disconnected: -1
D/MediaFocusControl(  756): <<< unregisterRemoteControlDisplay
D/CommandListener(  238): Clearing all IP addresses on wlan0
D/FileShare-Server( 4137): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() DISCONNECTED
W/BluetoothAdapterService( 3125): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 3125): Not skipping com.android.bluetooth.pan.PanService
W/NetworkManagementService(  756): route cmd failed: 
W/NetworkManagementService(  756): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '36 route del src v6 2' failed with '400 36 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  756): '
W/NetworkManagementService(  756): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  756): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  756): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  756): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  756): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  756): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  756): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  756): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  756): 	at com.android.server.ConnectivityService.a,ccess$1800(ConnectivityService.java:258)
W/NetworkManagementService(  756): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  756): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  756): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  756): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/RouteController(  238): /system/bin/ip -4 route del default table 2 2>&1
D/WifiNative(  756): callSECApiBoolean - ID [13]
D/BluetoothA2dp(  756): Proxy object disconnected
D/BluetoothA2dp( 3096): Proxy object disconnected
D/QuickConnect[1.1][2] ( 3096): A2dpProfile.onServiceConnected - Bluetooth service disconnected
D/BluetoothA2dp( 2024): Proxy object disconnected
I/WifiTrafficPoller(  756): evaluateTrafficStatsPolling
D/BluetoothA2dp( 1308): Proxy object disconnected
D/A2dpProfile( 1308): Bluetooth service disconnected
W/BluetoothAdapterService( 3125): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3125): Not skipping com.android.bluetooth.map.BluetoothMapService
,I/wpa_supplicant( 4883): USE_NETWORK : USE_NETWORK OFF
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  238): RTNETLINK answers: No such process
,D/BluetoothAdapterState( 3125): Stopping profile services that were post enabled
,D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
,D/BluetoothAdapterService( 3125): Profile still running: com.android.bluetooth.hdp.HealthService
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1067): wifi: GONE sig=0 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=0 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=0 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=0 act=2130837939
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,W/BluetoothHeadsetServiceJni( 3125): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3125): Cleaning up Bluetooth Handsfree callback object
D/HidService( 3125): Received stop request...Stopping profile...
,D/HidService( 3125): Stopping Bluetooth HidService
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
D/BluetoothInputDevice( 3096): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 3096): HidProfile.onServiceDisconnected - Bluetooth service disconnected
,V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
,D/HealthService( 3125): Received stop request...Stopping profile...
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1308): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1308): MountReceiver.mPrefHandler - 7002
,D/PanService( 3125): Received stop request...Stopping profile...
D/BluetoothInputDevice( 1308): Proxy object disconnected
,D/HidProfile( 1308): Bluetooth service disconnected
,D/BluetoothPan(  756): BluetoothPAN Proxy object disconnected
,D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3125): Profile still running: com.android.bluetooth.hdp.HealthService
I/GKI_LINUX( 3125): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
E/SMD     (  241): DCD ON
I/GKI_LINUX( 3125): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 3125): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothMapService( 3125): Received stop request...Stopping profile...
,D/BluetoothPan( 1308): BluetoothPAN Proxy object disconnected
,D/PanProfile( 1308): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3125): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 3125): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3125): Cleaning up Bluetooth GID callback object
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3125): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3125): Cleaning up Bluetooth Health Interface...
D/BluetoothMap( 1308): Proxy object disconnected
D/MapProfile( 1308): Bluetooth service disconnected
W/BluetoothHealthServiceJni( 3125): Cleaning up Bluetooth Health object
D/BtSettings.ProfileConfig( 3125): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3125): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3125): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3125): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterService( 3125): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
D/BluetoothAdapterState( 3125): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 3125): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3125): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3125): updateAdapterState state is 10
,I/knox    ( 3040): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/BluetoothAdapterService( 3125): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3125): Autoconnection is available 
,D/GKI_LINUX( 3125): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
D/BluetoothAdapterService( 3125): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 3125): Entering OffState
,D/BluetoothA2dp( 1308): onBluetoothStateChange: up=false
,D/NetUtils(  756): android_net_utils_resetConnections in env=0x784954b8 clazz=0x6e700001 iface=wlan0 mask=0x3
E/WifiStateMachine(  756): Error! unhandled message{ when=-62ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  756): Error! unhandled message{ when=-62ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  756): Error! unhandled message{ when=-44ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  756): Error! unhandled message{ when=-44ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): resetConnections(wlan0, 3)
W/ContextImpl( 3040): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3040): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3040): KNOXAgentService : onCreate()
,D/knox    ( 3040): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3040): KNOXAgentService. startJobThread() start
D/knox    ( 3040): KNOXAgentService. JobThread()
D/knox    ( 3040): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3040): KNOXAgentService. startJobThread() wait
,D/BluetoothInputDevice( 1308): onBluetoothStateChange: up=false
,D/knox    ( 3040): KNOXAgentService : onDestroy().
D/Bluetoothsap( 1308): onBluetoothStateChange: up=false
D/Bluetoothsap( 1308): Unbinding service...
,D/knox    ( 3040): ModuleBase.cancelAllAlarmManageModule()
,D/BluetoothPbap( 1308): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  756): onBluetoothStateChange: up=false
,D/BluetoothMap( 1308): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3096): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3096): onBluetoothStateChange: up=false
D/Bluetoothsap( 1308): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1308): Unbinding service...
,D/BluetoothA2dp( 2024): onBluetoothStateChange: up=false
W/InputMethodManagerService(  756): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  756): [BT Setting State] State =10
,I/InputMethodManagerService(  756): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/WifiTrafficPoller(  756): mBoosterFLAG : 0
I/WifiTrafficPoller(  756): current booster mode : FullMode
D/PhoneApp( 1240): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
I/QuickConnect[1.1][2] ( 3096): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
V/BluetoothEventManager( 1308): Received android.bluetooth.adapter.action.STATE_CHANGED
,W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 1308): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,V/NativeCrypto( 1304): Read error: ssl=0x7bbc3658: I/O error during system call, Connection timed out
,V/NativeCrypto( 1304): SSL shutdown failed: ssl=0x7bbc3658: I/O error during system call, Broken pipe
,D/Tethering(  756): interfaceLinkStateChanged p2p0, false
,D/Tethering(  756): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4883): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering(  756): interfaceLinkStateChanged wlan0, true
,D/Tethering(  756): interfaceStatusChanged wlan0, true
,D/AuthorizationBluetoothService( 1304): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 4883): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 4883): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 4883): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  756): interfaceLinkStateChanged wlan0, false
,D/Tethering(  756): interfaceStatusChanged wlan0, false
,D/Tethering(  756): InitialState.processMessage what=4
,E/Tethering(  756): No numeric data
D/Tethering(  756): interfaceLinkStateChanged wlan0, false
D/Tethering(  756): interfaceStatusChanged wlan0, false
,D/Tethering(  756): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  756): interfaceLinkStateChanged wlan0, false
,D/Tethering(  756): interfaceStatusChanged wlan0, false
I/ConnectivityService(  756): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
V/NetworkStats(  756): performPollLocked(flags=0x1)
,D/BluetoothTethering(  756): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  756): attempted to stop reverse tether with nothing tethered
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
D/NtpTrustedTime(  756): currentTimeMillis() cache hit
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
V/NetworkStats(  756): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
V/NetworkStats(  756): performPollLocked() took 32ms
V/NetworkStats(  756): updateIfacesLocked()
,V/NetworkStats(  756): performPollLocked(flags=0x1)
D/NtpTrustedTime(  756): currentTimeMillis() cache hit
D/NtpTrustedTime(  756): currentTimeMillis() cache hit
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
,V/NetworkStats(  756): performPollLocked() took 25ms
D/Tethering(  756): interfaceLinkStateChanged wlan0, false
D/Tethering(  756): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 4883): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiStateMachine(  756): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,W/Settings( 1219): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/knox    ( 3040): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3040): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3040): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3040): KNOXAgentService : onCreate()
,D/knox    ( 3040): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3040): KNOXAgentService. startJobThread() start
D/knox    ( 3040): KNOXAgentService. JobThread()
D/knox    ( 3040): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3040): KNOXAgentService. startJobThread() wait
,D/knox    ( 3040): KNOXAgentService : onDestroy().
,D/knox    ( 3040): ModuleBase.cancelAllAlarmManageModule()
,W/Netd    (  238): No subsystem found in netlink event
,D/Tethering(  756): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  756): MasterInitialState.processMessage what=3
,I/ApplicationPolicy(  756): updateDataUsageMap
D/NetlinkEvent(  238): Unexpected netlink message. type=0x11
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/LocSvc_java(  756): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  756): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  756): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1443): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_PushUtil( 4486): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4486): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4486): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4486): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4486): noConnectivity : true
D/Vpn     (  756): Interface removed : wlan0
D/Tethering(  756): interfaceRemoved wlan0
,E/Tethering(  756): attempting to remove unknown iface (wlan0), ignoring
,I/NetworkMonitor( 3720): type=WIFI subType= reason=null isConnected=false
,W/Netd    (  238): No subsystem found in netlink event
D/NetlinkEvent(  238): Unexpected netlink message. type=0x11
,D/Vpn     (  756): Interface removed : p2p0
,D/Tethering(  756): interfaceRemoved p2p0
,E/Tethering(  756): attempting to remove unknown iface (p2p0), ignoring
,I/KLMS-2.3.201 : ( 5066): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5066): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449748919826
,D/WifiStateMachine(  756): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,I/KLMS-2.3.201 : ( 5066): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5091): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5091): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4655): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4655): [BDLM] already registered in spp
,I/SA      ( 4655): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
I/SA      ( 4655): [OR] == ACTION_CONNECTIVITY_CHANGE ==
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
I/SA      ( 4655): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4655): [OR] == isSIMCardReady false ==
I/SA      ( 4655): [SCU] == networkStateCheck == false
I/SA      ( 4655): [OR] onReceive END
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5140): Other Intent
,D/com.samsung.app( 1443): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1443): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 5154): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5154): getCountryCode(): countryCode = PL
,D/Headlines( 5154): Breath.onCreate
,D/Headlines( 5154): Breath timer started. interval : 30000
,D/Headlines( 5154): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5154): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5154): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5154): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5154): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5154): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5154): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager(  756): waitForAlarm result :8
,D/dalvikvm( 4150): GC_FOR_ALLOC freed 4070K, 37% free 11961K/18716K, paused 89ms, total 89ms
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 16.712MB for 2129936-byte allocation
,D/QuickConnect[1.1][2] ( 3096): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3096): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3096): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425c5e38
,D/dalvikvm( 4150): GC_CONCURRENT freed 30K, 26% free 14023K/18716K, paused 20ms+17ms, total 105ms
,D/dalvikvm( 4150): WAIT_FOR_CONCURRENT_GC blocked 61ms
,D/RCPManagerService(  756): exchangeData() failure , invalid userId
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 18.726MB for 2129936-byte allocation
,D/RCPManagerService(  756): exchangeData() failure , invalid userId
,D/dalvikvm( 4150): GC_CONCURRENT freed 14K, 23% free 16094K/20800K, paused 12ms+14ms, total 93ms
,I/iu.Environment( 1794): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1794): num queued entries: 0
,I/iu.UploadsManager( 1794): num updated entries: 0
,I/iu.SyncManager( 1794): NEXT; no task
,D/Headlines( 5154): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5154): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5154): Breath 458 latestRequest time : 1449748920226 current time : 1449748920684
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,I/ActivityManager(  756): Waited long enough for: ServiceRecord{4407ba78 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,E/Watchdog(  756): !@Sync 12
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 330s ago
,V/AlarmManager(  756): waitForAlarm result :8
,D/Headlines( 5154): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5154): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5154): Breath 30041 latestRequest time : 1449748920226 current time : 1449748950268
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/dalvikvm(  756): GC_CONCURRENT freed 3377K, 58% free 23572K/55032K, paused 41ms+36ms, total 538ms
,D/AmoledAdjustTimer(  756): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 13
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,V/AlarmManager(  756): waitForAlarm result :8
,D/Headlines( 5154): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5154): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5154): Breath 60045 latestRequest time : 1449748920226 current time : 1449748980272
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 14
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 390s ago
,V/AlarmManager(  756): waitForAlarm result :8
,D/Headlines( 5154): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5154): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5154): Breath 90046 latestRequest time : 1449748920226 current time : 1449749010272
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 15
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  756): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,V/AlarmManager(  756): waitForAlarm result :8
,D/Headlines( 5154): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5154): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5154): Breath 120045 latestRequest time : 1449748920226 current time : 1449749040271
,D/Headlines( 5154): stop 
,D/Headlines( 5154): Breath.onDestroy : 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 16
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  756): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  756): [PWL] Off : 455s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 17
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 18
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/AmoledAdjustTimer(  756): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  756): [PWL] Off : 525s ago
,E/Watchdog(  756): !@Sync 19
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  756): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  756): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  756): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  756): !@Sync 20
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 21
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 600s ago
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 22
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 23
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  756): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  756): <AppSync3 Whitelist>
,V/AlarmManager(  756): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,I/SensorManagerA(  756): getReportingMode :: sensor.mType = 5
,D/LightsService(  756): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  756): LightSensor setDelay = 200000000
D/Sensors (  756): LightSensor setSensorDelay = 200000000
D/Sensors (  756): Light sensor flush: not enabled 0
D/Sensors (  756): LightSensor enable = 1
D/Sensors (  756): LightSensor enableSensor = 1
D/SensorManager(  756): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  756): LightSensor enable = 0
,D/Sensors (  756): LightSensor enableSensor = 0
,D/SensorManager(  756): unregisterListener ::   
D/LightsService(  756): [SvcLED]  onSensorChanged::light value = 37
D/LightsService(  756): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 24
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService(  756): [PWL] Off : 680s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 25
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): stay LED for fully charged
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 26
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 765s ago
,E/Watchdog(  756): !@Sync 27
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  756): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/dalvikvm(  756): GC_CONCURRENT freed 3496K, 57% free 23505K/54260K, paused 35ms+39ms, total 584ms
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 28
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 29
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/TimaService(  756): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  756): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  756): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  756): [PWL] Off : 855s ago
,I/PowerManagerService(  756): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  756): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  756): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=756, ws=null) (elapsedTime=4039)
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  756): !@Sync 30
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 31
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 32
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 33
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService(  756): [PWL] Off : 950s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 34
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 35
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 36
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 37
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 38
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 39
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/TimaService(  756): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  756): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  756): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 1155s ago
,I/PowerManagerService(  756): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  756): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  756): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=756, ws=null) (elapsedTime=4054)
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  756): !@Sync 40
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,E/SMD     (  241): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  756): !@Sync 41
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  756): !@Sync 42
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  756): !@Sync 43
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  756): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  756): <AppSync3 Whitelist>
,V/AlarmManager(  756): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 1265s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,I/SensorManagerA(  756): getReportingMode :: sensor.mType = 5
,D/Sensors (  756): LightSensor setDelay = 200000000
,D/LightsService(  756): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  756): LightSensor setSensorDelay = 200000000
D/Sensors (  756): Light sensor flush: not enabled 0
D/Sensors (  756): LightSensor enable = 1
D/Sensors (  756): LightSensor enableSensor = 1
,D/SensorManager(  756): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  756): LightSensor enable = 0
,D/Sensors (  756): LightSensor enableSensor = 0
,D/SensorManager(  756): unregisterListener ::   
D/LightsService(  756): [SvcLED]  onSensorChanged::light value = 41
D/LightsService(  756): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm(  756): GC_CONCURRENT freed 3399K, 57% free 23511K/54260K, paused 62ms+18ms, total 627ms
,E/Watchdog(  756): !@Sync 44
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/BatteryService(  756): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  756): !@Sync 45
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  756): !@Sync 46
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,E/SMD     (  241): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  756): !@Sync 47
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 1380s ago
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  756): !@Sync 48
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  756): !@Sync 49
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/TimaService(  756): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  756): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  756): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,E/Watchdog(  756): !@Sync 50
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 51
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 1500s ago
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 52
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,E/SMD     (  241): DCD ON
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 53
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog(  756): !@Sync 54
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog(  756): !@Sync 55
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  756): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog(  756): !@Sync 56
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog(  756): !@Sync 57
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog(  756): !@Sync 58
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 59
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/dalvikvm(  756): GC_CONCURRENT freed 3271K, 57% free 23646K/54260K, paused 15ms+19ms, total 219ms
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/TimaService(  756): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  756): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  756): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 1755s ago
,I/PowerManagerService(  756): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  756): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  756): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=756, ws=null) (elapsedTime=4067)
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 60
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 61
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,I/ProcessStatsService(  756): Prepared write state in 152ms
,I/ProcessStatsService(  756): Prepared write state in 166ms
,I/ProcessStatsService(  756): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-52-47.bin
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 62
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 63
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  756): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  756): <AppSync3 Whitelist>
,V/AlarmManager(  756): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,E/SMD     (  241): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  756): !@Sync 64
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  241): DCD ON
D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  756): mCoverManager.getCoverState() : true
D/BatteryService(  756): stay LED for fully charged
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
I/PowerManagerService(  756): [PWL] Off : 1890s ago
E/SMD     (  241): DCD ON
D/AndroidRuntime( 5920): 
D/AndroidRuntime( 5920): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5920): CheckJNI is OFF
D/AndroidRuntime( 5920): setted country_code = Poland
D/AndroidRuntime( 5920): setted countryiso_code = PL
D/AndroidRuntime( 5920): setted sales_code = XEO
D/AndroidRuntime( 5920): readGMSProperty: start
D/AndroidRuntime( 5920): readGMSProperty: already setted!!
D/AndroidRuntime( 5920): readGMSProperty: end
D/AndroidRuntime( 5920): addProductProperty: start
D/dalvikvm( 5920): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5920): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5920): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5920): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5920): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5920): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5920): failed to load memtrack module: -2
D/dalvikvm( 5920): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5920): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  756): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  756): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  756): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  756): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  756): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  756): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  756): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  756): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  756): getApplicationUninstallationEnabled
D/PackageManager(  756): START PACKAGE DELETE: observer{1141384904}
D/PackageManager(  756): pkg{<packageName>}
D/PackageManager(  756): user{0}
D/PackageManager(  756): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  756): [MSG] DELETE_PACKAGE_AS_USER
D/ApplicationPolicy(  756): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  756): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  756): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  756): Killing 4642:com.test.thalitest/u0a179 (adj 0): stop com.test.thalitest
I/ActivityManager(  756): Killing 5333:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty for 1815s
I/ActivityManager(  756): Killing 5380:com.android.providers.calendar/u0a44 (adj 15): empty for 1815s
I/ActivityManager(  756): Killing 5258:com.android.calendar/u0a142 (adj 15): empty for 1815s
I/ActivityManager(  756): Killing 3744:com.android.mms/u0a48 (adj 15): empty for 1816s
I/ActivityManager(  756): Killing 5361:com.qualcomm.timeservice/u0a168 (adj 15): empty for 1817s
I/ActivityManager(  756): Killing 5349:com.sec.android.app.taskmanager/u0a166 (adj 15): empty for 1817s
I/ActivityManager(  756): Killing 5318:com.sec.esdk.elm/u0a94 (adj 15): empty for 1817s
I/ActivityManager(  756): Killing 5302:com.sec.android.app.clockpackage/u0a84 (adj 15): empty for 1818s
I/ActivityManager(  756): Killing 5282:com.samsung.android.scloud.sync/u0a62 (adj 15): empty for 1818s
I/ActivityManager(  756): Killing 4514:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1818s
I/ActivityManager(  756): Killing 5227:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1819s
I/ActivityManager(  756): Killing 4748:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1820s
I/ActivityManager(  756): Killing 5116:com.sec.android.app.voicenote/1000 (adj 15): empty for 1820s
I/ActivityManager(  756): Killing 5096:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1820s
I/ActivityManager(  756): Killing 4787:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1829s
I/ActivityManager(  756): Killing 4775:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1829s
I/ActivityManager(  756): Killing 4760:com.samsung.helphub/1000 (adj 15): empty for 1829s
I/ActivityManager(  756): Killing 4733:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1830s
I/ActivityManager(  756): Killing 4705:com.google.android.apps.docs/u0a90 (adj 15): empty for 1830s
D/CustomFrequencyManagerService(  756): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  756): mDVFSHelper.acquire()
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1261): destroyHardwareResources():1125881808
I/SurfaceFlinger(  247): id=17 Removed NainActivit (7/11)
I/SurfaceFlinger(  247): id=17 Removed NainActivit (-2/11)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/WindowState(  756): WIN DEATH: Window{42e81130 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  247): id=17 Removed NainActivit (-2/11)
W/PackageSettings(  756): Skipping PackageSetting{42a92db8 com.example.hello/10180} due to missing metadata
D/PackageManager(  756): queryIntentReceivers - Execution time: 164 ms
D/LockPatternUtils( 1067): isPcwEnable = null
D/PackageManager(  756): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/CountryDetector(  756): No listener is left
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/Launcher( 1261): onRestart, Launcher: 1113945832
D/Launcher( 1261): onStart, Launcher: 1113945832
D/Launcher.HomeView( 1261): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1443): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1443): [237392/5] SurfaceWidget drawing first frame
D/dalvikvm( 2120): GC_EXPLICIT freed 537K, 42% free 10954K/18716K, paused 7ms+4ms, total 43ms
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/dalvikvm( 1794): GC_EXPLICIT freed 351K, 36% free 12107K/18716K, paused 4ms+8ms, total 64ms
W/SQLiteConnectionPool( 1794): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/PackageManager(  756): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/SurfaceFlinger(  247): id=19 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/dalvikvm( 1403): GC_EXPLICIT freed 4299K, 47% free 10020K/18716K, paused 5ms+4ms, total 69ms
I/SurfaceFlinger(  247): id=20 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/AdaptiveEventManager( 1067): action=android.intent.action.PACKAGE_REMOVED
I/FPMS_FingerprintManagerService( 1086): onReceive: android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3096): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 1219): Ignoring removeGeofence because network location is disabled.
I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
I/SELinux ( 5954): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5954):  
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  247): id=21 createSurf (707x984),1 flag=4, TettingsRec
D/dalvikvm(  756): GC_EXPLICIT freed 2409K, 57% free 23664K/54260K, paused 7ms+23ms, total 183ms
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 120ms
I/SELinux ( 5954): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5954):  
I/SELinux ( 5954):  
I/SELinux ( 5954): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
E/SELinux ( 5954): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5954): >>>>> Normal User
I/PackageManager(  756):   Scheme: "smsto"
E/dalvikvm( 5954): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 5954): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 5954): in addTimaSignatureService
D/CustomFrequencyManagerService(  756): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@5
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  756): mDVFSHelper.release()
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "mms"
D/TimaKeyStoreProvider( 5954): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5954): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  756): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/RCPManagerService(  756): PackageReceiver onReceive()
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/HarmonyEASService(  756): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  756): Package has changed for user 0
D/EnterpriseDeviceManagerService(  756): Admin package name: com.google.android.gms
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  756):   Scheme: "mms"
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5954, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5954): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5954): ELMEngine.ELMEngine( context ).
D/elm:14132( 5954): MDMBridge.setEnterpriseBridge()
D/dalvikvm(  756): GC_EXPLICIT freed 792K, 57% free 23558K/54260K, paused 7ms+19ms, total 203ms
D/PackageManager(  756): delete sourFile : 
D/elm:14132( 5954): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5954): ElmAgentService : onCreate()
D/elm:14132( 5954): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5954): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5954): MDMBridge.getInstance()
D/elm:14132( 5954): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 5954): MDMBridge.getAllLicenseInfoFromSDK()
D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  756): removePackageParticipantsLocked: uid=10179 #1
I/SELinux ( 5969): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5969):  
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 5954): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 5954): ElmAgentService : onDestroy().
D/AndroidRuntime( 5920): Shutting down VM
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  756): delete native library directory: 
D/PackageManager(  756): return delete result to caller: 1141384904
D/PackageManager(  756): returnCode: 1
D/dalvikvm( 5920): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 4ms
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "smsto"
I/SELinux ( 5969): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5969):  
I/SELinux ( 5969):  
I/SELinux ( 5969): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SELinux ( 5969): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5969): >>>>> Normal User
E/dalvikvm( 5969): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 5969): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5969): in addTimaSignatureService
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 5969): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5969): Added TimaKesytore provider
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5969, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Launcher.HomeView( 1261): onStop
D/dalvikvm( 5969): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425b0b50, skipping init
I/SecureStorage( 5969): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 5969): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5969
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 5969): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  756): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  756): clearDefaults: com.test.thalitest
I/SecureStorage( 5969): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5969
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
D/InputReader(  756): Processing first event
I/EventHub(  756): Removing device sec_touchscreen due to epoll hang-up event.
I/EventHub(  756): Removed device: path=/dev/input/event1 name=sec_touchscreen id=6 fd=217 classes=0x94
I/InputReader(  756): Device removed: id=6, name='sec_touchscreen', sources=0x80001002
D/InputReader(  756): Could not retrieve current multitouch slot index.  status=-1
D/InputReader(  756): MultiTouchMotionAccumulator: initial slot number is -1
I/EventHub(  756): Removing device '/dev/input/event1' due to inotify event
I/ActivityManager(  756): Config changes=8 {0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
D/InputDispatcher(  756): setInputDispatchMode: enabled=0, frozen=1
I/SurfaceFlinger(  247): id=22 createSurf (720x1280),2 flag=404, TcreenshotS
D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (463 us)
D/dalvikvm( 4150): GC_FOR_ALLOC freed 5K, 21% free 18171K/22884K, paused 16ms, total 16ms
I/dalvikvm-heap( 4150): Grow heap (frag case) to 22.777MB for 2129936-byte allocation
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
