#### Test 506502784dae475_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
V/MediaPlayer( 4488): decode(61, 33979084, 48105)
V/MediaPlayerService(  252): decode(35, 33979084, 48105)
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
V/StagefrightPlayer(  252): setDataSource(35, 33979084, 48105)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883ff50, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb883ff50, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883ff50, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883ff50, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb883ff50, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
--------- beginning of /dev/log/system
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=4509, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883ff50, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883ff50, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883ff50, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(62, 33914984, 10421)
V/MediaPlayerService(  252): decode(35, 33914984, 10421)
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
V/StagefrightPlayer(  252): setDataSource(35, 33914984, 10421)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8852dd0, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb8852dd0, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8852dd0, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8852dd0, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
D/dalvikvm( 4509): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42538b78, skipping init
I/SecureStorage( 4509): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4509): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  303): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4509
I/SecureStorage(  303): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4509): [INFO]: SPID(0x00000000)SS Daemon is running
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8852dd0, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb8852dd0, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8852dd0, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8852dd0, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(63, 37457308, 34198)
V/MediaPlayerService(  252): decode(35, 37457308, 34198)
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
V/StagefrightPlayer(  252): setDataSource(35, 37457308, 34198)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883f7b8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
I/SecureStorage( 4509): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  303): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4509
I/SecureStorage(  303): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
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
V/AudioCache(  252): notify(0xb883f7b8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883f7b8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883f7b8, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb883f7b8, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb883f7b8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883f7b8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883f7b8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(64, 33862452, 7405)
V/MediaPlayerService(  252): decode(35, 33862452, 7405)
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
V/StagefrightPlayer(  252): setDataSource(35, 33862452, 7405)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8844db8, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb8844db8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8844db8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8844db8, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb8844db8, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb8844db8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8844db8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): addBatteryData
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8844db8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(65, 37547940, 5555)
V/MediaPlayerService(  252): decode(35, 37547940, 5555)
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
V/StagefrightPlayer(  252): setDataSource(35, 37547940, 5555)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884c308, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb884c308, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884c308, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884c308, 1, 0, 0)
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
I/AudioPlayer(  252): First fillBuffer call!!
V/AudioCache(  252): notify(0xb884c308, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb884c308, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884c308, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884c308, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(66, 30367732, 5085)
V/MediaPlayerService(  252): decode(35, 30367732, 5085)
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
V/StagefrightPlayer(  252): setDataSource(35, 30367732, 5085)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884cf10, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb884cf10, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884cf10, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884cf10, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb884cf10, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb884cf10, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884cf10, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884cf10, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(68, 30372876, 21552)
V/MediaPlayerService(  252): decode(35, 30372876, 21552)
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
V/StagefrightPlayer(  252): setDataSource(35, 30372876, 21552)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb88515d8, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb88515d8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb88515d8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb88515d8, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb88515d8, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb88515d8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb88515d8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb88515d8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(69, 37543652, 4230)
V/MediaPlayerService(  252): decode(35, 37543652, 4230)
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
V/StagefrightPlayer(  252): setDataSource(35, 37543652, 4230)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883abe0, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb883abe0, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883abe0, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883abe0, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb883abe0, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883abe0, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883abe0, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): addBatteryData
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883abe0, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(70, 30337076, 9400)
V/MediaPlayerService(  252): decode(35, 30337076, 9400)
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
V/StagefrightPlayer(  252): setDataSource(35, 30337076, 9400)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8847a28, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb8847a28, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8847a28, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8847a28, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb8847a28, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/AudioPlayer(  252): First fillBuffer call!!
I/SELinux ( 4576): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4576):  
I/ActivityManager(  736): Killing 3062:com.sec.android.app.mt/1000 (adj 15): empty #43
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8847a28, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8847a28, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8847a28, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(71, 33925464, 44276)
V/MediaPlayerService(  252): decode(35, 33925464, 44276)
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
V/StagefrightPlayer(  252): setDataSource(35, 33925464, 44276)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884e200, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb884e200, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884e200, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884e200, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb884e200, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/SELinux ( 4576): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4576):  
I/SELinux ( 4576):  
I/SELinux ( 4576): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4576): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4576): >>>>> Normal User
E/dalvikvm( 4576): >>>>> com.policyd,m [ userId:0 | appId:1000 ]
E/SELinux ( 4576): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4576): in addTimaSignatureService
D/TimaKeyStoreProvider( 4576): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4576): Added TimaKesytore provider
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884e200, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884e200, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb884e200, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(72, 33885672, 29256)
V/MediaPlayerService(  252): decode(35, 33885672, 29256)
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
V/StagefrightPlayer(  252): setDataSource(35, 33885672, 29256)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883abf8, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb883abf8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883abf8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883abf8, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb883abf8, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb883abf8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883abf8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883abf8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(73, 37491572, 52024)
V/MediaPlayerService(  252): decode(35, 37491572, 52024)
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
V/StagefrightPlayer(  252): setDataSource(35, 37491572, 52024)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8841830, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb8841830, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8841830, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8841830, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb8841830, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/SELinux ( 4605): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4605):  
I/ActivityManager(  736): Killing 3120:com.sec.android.app.camera/u0a147 (adj 15): empty #43
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8841830, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8841830, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
D/dalvikvm(  250): GC_EXPLICIT freed 44K, 49% free 9508K/18468K, paused 4ms+3ms, total 36ms
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8841830, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(74, 33969800, 9226)
V/MediaPlayerService(  252): decode(35, 33969800, 9226)
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
V/StagefrightPlayer(  252): setDataSource(35, 33969800, 9226)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883f7b8, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb883f7b8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883f7b8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883f7b8, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb883f7b8, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/SELinux ( 4605): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4605):  
I/SELinux ( 4605):  
I/SELinux ( 4605): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4605): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4605): >>>>> Normal User
E/dalvikvm( 4605): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 4605): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 49% free 9508K/18468K, paused 2ms+4ms, total 30ms
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883f7b8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883f7b8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb883f7b8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4488): decode(75, 30402580, 4509)
V/MediaPlayerService(  252): decode(35, 30402580, 4509)
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
V/StagefrightPlayer(  252): setDataSource(35, 30402580, 4509)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb88420f8, 8, 0, 0)
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
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 49% free 9508K/18468K, paused 3ms+3ms, total 26ms
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
V/AudioCache(  252): notify(0xb88420f8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb88420f8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb88420f8, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb88420f8, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/AudioPlayer(  252): First fillBuffer call!!
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb88420f8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb88420f8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb88420f8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
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
D/TimaKeyStoreProvider( 4605): in addTimaSignatureService
D/TimaKeyStoreProvider( 4605): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4605): Added TimaKesytore provider
I/SA      ( 4605): [SSP] onCreated
I/SA      ( 4605): [TPM] There is no property file
I/SA      ( 4605): [SCU] isHaveSA() - false
I/SA      ( 4605): [TPM] getModelProperty : null
I/SA      ( 4605): [TPM] getCSCProperty : null
I/SA      ( 4605): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4605): [DM] init START
I/SA      ( 4605): [DM] This device is not a Vodafone
I/SA      ( 4605): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4605): support phone number id : false
I/SA      ( 4605): [DM] init END
I/SA      ( 4605): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4605): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  736): Killing 3211:com.android.email/u0a155 (adj 15): empty #43
D/Mms/PackageInstallReceiver( 3703): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2129): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 2800): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 4633): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4633):  
I/SELinux ( 4633): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4633):  
I/SELinux ( 4633):  
I/SELinux ( 4633): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4633): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4633): >>>>> Normal User
E/dalvikvm( 4633): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 4633): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 4633): in addTimaSignatureService
D/TimaKeyStoreProvider( 4633): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4633): Added TimaKesytore provider
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=4633, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 2129): GC_CONCURRENT freed 6479K, 40% free 11208K/18468K, paused 36ms+5ms, total 107ms
D/dalvikvm( 2129): WAIT_FOR_CONCURRENT_GC blocked 53ms
D/CapabilityManagerService New( 4633): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
D/AndroidRuntime( 4625): 
D/AndroidRuntime( 4625): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4625): CheckJNI is OFF
D/AndroidRuntime( 4625): setted country_code = Poland
D/AndroidRuntime( 4625): setted countryiso_code = PL
D/AndroidRuntime( 4625): setted sales_code = XEO
D/AndroidRuntime( 4625): readGMSProperty: start
D/AndroidRuntime( 4625): readGMSProperty: already setted!!
D/AndroidRuntime( 4625): readGMSProperty: end
D/AndroidRuntime( 4625): addProductProperty: start
I/ActivityManager(  736): Killing 3206:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
I/SELinux ( 4645): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4645):  
D/dalvikvm( 4625): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4625): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4625): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4625): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4625): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 4645): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4645):  
I/SELinux ( 4645):  
I/SELinux ( 4645): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4645): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4645): >>>>> Normal User
E/dalvikvm( 4645): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 4645): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/IcingCorporaProvider( 2129): UpdateCorporaTask done [took 278 ms] updated apps [took 278 ms] 
D/TimaKeyStoreProvider( 4645): in addTimaSignatureService
D/TimaKeyStoreProvider( 4645): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4645): Added TimaKesytore provider
E/memtrack( 4625): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4625): failed to load memtrack module: -2
D/dalvikvm( 4625): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SecureStorage(  303): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  303): [INFO]: SPID(0x00000003)PID: 4509, TID: 4509
D/AndroidRuntime( 4625): Calling main entry com.android.commands.am.Am
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=4645, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
I/SecureStorage( 4509): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4509): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4509): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4509): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 4509): Open platform.db in secure mode
V/ApplicationPolicy(  736): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  736): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 736  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  736): mDVFSHelper.acquire()
I/SELinux ( 4666): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4666):  
D/LockPatternUtils( 1068): isPcwEnable = null
D/AndroidRuntime( 4625): Shutting down VM
D/dalvikvm( 4625): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 2ms
I/SELinux ( 4666): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4666):  
I/SELinux ( 4666):  
I/SELinux ( 4666): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4666): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4666): >>>>> Normal User
E/dalvikvm( 4666): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 4666): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 4666): in addTimaSignatureService
D/TimaKeyStoreProvider( 4666): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4666): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4509): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 4509): ...getDatabaseLocked(b,b,pwd)
D/LockPatternUtils( 1068): isPcwEnable = null
I/SurfaceFlinger(  249): id=16 Removed TettingsRec (9/13)
I/SurfaceFlinger(  249): id=16 Removed TettingsRec (-2/13)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  249): id=13 Removed CatteryCove (8/12)
I/SurfaceFlinger(  249): id=13 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SQLiteSecureOpenHelper( 2029): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2029): getDatabaseLocked(b,b,pwd)...
D/SurfaceWidgetView( 1263): destroyHardwareResources():1125361448
I/SurfaceFlinger(  249): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  249): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  736): Killing 3236:com.sec.modem.settings/1000 (adj 15): empty #43
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=4666, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1444): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1263): onTrimMemory. Level: 20
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=4666, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 4666): Binding Chromium to the background looper Looper (main, tid 1) {4220b1e8}
I/chromium( 4666): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4666): Initializing chromium process, renderers=0
W/chromium( 4666): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4666): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4666): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4666): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4666): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4666): Remote Branch: 
I/Adreno-EGL( 4666): Local Patches: 
I/Adreno-EGL( 4666): Reconstruct Branch: 
,I/dalvikvm( 4666): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4666): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4666): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4666): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4666): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4666): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4666): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4666): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4666): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4666): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4666): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4666): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4666): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4666): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4666): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4666): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4666): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4666): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4666): CordovaWebView is running on device made by: samsung
I/SELinux ( 4697): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4697):  
I/ActivityManager(  736): Killing 1340:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
W/GAV2    ( 4645): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 4697): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4697):  
I/SELinux ( 4697):  
I/SELinux ( 4697): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4697): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4697): >>>>> Normal User
E/dalvikvm( 4697): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 4697): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4697): in addTimaSignatureService
D/TimaKeyStoreProvider( 4697): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4697): Added TimaKesytore provider
I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 4666): EGLImpl-HWUI Protected EGL context created
D/PackageIntentReceiver( 4697): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 4697): Not GearManger package! 
D/OpenGLRenderer( 4666): Enabling debug mode 0
I/SELinux ( 4724): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4724):  
W/AwContents( 4666): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  736): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 736  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  736): mDVFSHelper.release()
D/CustomFrequencyManagerService(  736): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 736  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SELinux ( 4724): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4724):  
I/SELinux ( 4724):  
I/SELinux ( 4724): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4724): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4724): >>>>> Normal User
E/dalvikvm( 4724): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 4724): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4724): in addTimaSignatureService
D/TimaKeyStoreProvider( 4724): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4724): Added TimaKesytore provider
D/MagazineService Version( 4724): Magazine-Channel: 13
D/MagazineService Version( 4724): Magazine-Provider: 13
D/MagazineService Version( 4724): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 4724): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 4724): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=4724, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 4724): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 4739): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4739):  
D/MagazineService::MagazineService( 4724): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  736): Killing 3256:tv.peel.smartremote/u0a163 (adj 15): empty #43
W/GAV2    ( 4645): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  736): Killing 3282:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
I/SELinux ( 4739): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4739):  
I/SELinux ( 4739):  
I/SELinux ( 4739): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4739): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4739): >>>>> Normal User
E/dalvikvm( 4739): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 4739): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4739): in addTimaSignatureService
D/TimaKeyStoreProvider( 4739): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4739): Added TimaKesytore provider
D/JsMessageQueue( 4666): Set native->JS mode to OnlineEventsBridgeMode
,I/SELinux ( 4756): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4756):  
I/ActivityManager(  736): Killing 3331:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/dalvikvm( 4666): Trying to load lib /data/app-lib/com.test.thalitest-28/libjxcore.so 0x42531f20
,D/dalvikvm( 4666): Added shared lib /data/app-lib/com.test.thalitest-28/libjxcore.so 0x42531f20
D/jxcore_app_log( 4666): JniHelper::setJavaVM(0x416f2528), pthread_self() = 1924576648
,D/JX-Cordova( 4666): jxcore cordova android initializing
,D/AmoledAdjustTimer(  736): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
I/dalvikvm( 4666): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4666): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4666): VFY: replacing opcode 0x6e at 0x0045
I/SELinux ( 4756): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4756):  
I/SELinux ( 4756):  
I/SELinux ( 4756): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4756): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4756): >>>>> Normal User
E/dalvikvm( 4756): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 4756): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4756): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4756): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4756): Added TimaKesytore provider
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=4756, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4756): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4768): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4768):  
,I/ActivityManager(  736): Killing 3346:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,I/SELinux ( 4768): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4768):  
I/SELinux ( 4768):  
,I/SELinux ( 4768): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4768): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4768): >>>>> Normal User
,E/dalvikvm( 4768): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4768): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4768): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4768): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4768): Added TimaKesytore provider
,I/SELinux ( 4780): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4780):  
I/ActivityManager(  736): Killing 3361:com.google.android.youtube/u0a175 (adj 15): empty #43
,E/SMD     (  243): DCD ON
I/SELinux ( 4780): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4780):  
I/SELinux ( 4780):  
,I/SELinux ( 4780): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4780): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4780): >>>>> Normal User
,E/dalvikvm( 4780): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4780): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4780): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4780): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4780): Added TimaKesytore provider
,D/dalvikvm( 4666): GC_CONCURRENT freed 4925K, 31% free 12763K/18468K, paused 3ms+3ms, total 37ms
,D/dalvikvm( 4666): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4666): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager(  736): Killing 3554:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/Finsky  ( 3432): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 1785): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1785): Loading module APK com.google.android.play.games
I/dalvikvm( 1785): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1785): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0053
,D/CustomFrequencyManagerService(  736): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 736  tag : ACTIVITY_RESUME_BOOSTER@9
,I/dalvikvm( 1785): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1785): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1785): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1785): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1785): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1785): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1785): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1785): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1785): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1785): Submit a task: k
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/dalvikvm( 1785): GC_CONCURRENT freed 1854K, 39% free 11401K/18468K, paused 8ms+5ms, total 117ms
,D/dalvikvm( 1785): WAIT_FOR_CONCURRENT_GC blocked 25ms
D/dalvikvm( 1785): WAIT_FOR_CONCURRENT_GC blocked 26ms
D/dalvikvm( 1785): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 1785): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/k       ( 1785): Processing package: com.test.thalitest
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,D/GassUtils( 1785): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1785): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,D/dalvikvm( 1323): GC_EXPLICIT freed 893K, 42% free 10753K/18468K, paused 4ms+5ms, total 39ms
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,D/dalvikvm( 4666): GC_FOR_ALLOC freed 4698K, 26% free 15766K/21264K, paused 37ms, total 39ms
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/dalvikvm( 1785): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1785): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1785): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x000e
,W/dalvikvm( 1785): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1785): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1785): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1785): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1785): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1785): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1785): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1785): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1785): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1785): cleanUpNonGplusAccounts done.
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
D/BatteryService(  736): stay LED for fully charged
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1785): Module APK com.google.android.play.games already loaded
,D/SSRMv2:SIOP(  736): SIOP:: AP = 330, Delta = 20
,D/dalvikvm( 4666): GC_FOR_ALLOC freed 5048K, 30% free 16772K/23936K, paused 38ms, total 40ms
,I/dalvikvm-heap( 4666): Grow heap (frag case) to 21.484MB for 2459024-byte allocation
,D/dalvikvm( 4666): GC_FOR_ALLOC freed 3768K, 34% free 17453K/26340K, paused 34ms, total 35ms
,D/dalvikvm( 4666): GC_FOR_ALLOC freed 1223K, 35% free 17358K/26340K, paused 30ms, total 32ms
,I/Icing   ( 1785): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,W/jxcore-log( 4666): Initializing JXcore engine
,W/jxcore-log( 4666): JXcore engine is ready
,I/Icing   ( 1785): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,W/jxcore-log( 4666): Starting JXcore engine
,W/jxcore-log( 4666): Platform android
W/jxcore-log( 4666): 
,W/jxcore-log( 4666): Process ARCH arm
W/jxcore-log( 4666): 
,E/SMD     (  243): DCD ON
,I/jxcore-log( 4666): JXcore Cordova bridge is ready!
I/jxcore-log( 4666): 
,W/jxcore-log( 4666): JXcore engine is started
,I/chromium( 4666): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4666): Toggling radios to true
I/jxcore-log( 4666): 
,D/dalvikvm(  736): GC_EXPLICIT freed 2049K, 60% free 23227K/57728K, paused 5ms+13ms, total 123ms
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=4666, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  736): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  736): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4666, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  736): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/BluetoothManagerService(  736): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService(  736): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  736): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService(  736): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService(  736): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService(  736): foregroundUser: 0
,E/BluetoothManagerService(  736): Package is exist.
,I/WifiManager( 4666): packageName : com.test.thalitest
,I/WifiManager( 4666): setWifiEnabled : true
I/WifiService(  736): setWifiEnabled: true pid=4666, uid=10179
,D/BluetoothAdapterState( 3106): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 3106): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3106): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3106): updateAdapterState state is 11
,D/BluetoothAdapterService( 3106): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3106): Autoconnection is available 
D/BluetoothAdapterService( 3106): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=4666, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothAdapterService( 3106): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/WifiService(  736): Failed getting userId using ActivityManagerNative
W/WifiService(  736): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4666, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  736): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  736): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  736): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  736): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  736): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  736): 	at dalvik.system.NativeStart.run(Native Method)
,W/BluetoothAdapterService( 3106): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/PhoneApp( 1241): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
W/BluetoothAdapterService( 3106): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/InputMethodManagerService(  736): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  736): [BT Setting State] State =11
I/QuickConnect[1.1][2] ( 3076): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
I/WifiService(  736): disconnect: pid=4666, uid=10179
E/WifiHW  (  736): ##################### set firmware type 0 #####################
W/BluetoothAdapterService( 3106): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
I/jxcore-log( 4666): Radios toggled
I/jxcore-log( 4666): 
D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 3106): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 3106): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3106): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3106): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 3106): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 3106): Not skipping com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3106): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3106): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3106): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3106): Not skipping com.android.bluetooth.hid.HidService
,D/HeadsetService( 3106): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3106): classInitNative: succeeds
D/HeadsetStateMachine( 3106): Version 1.6
,D/HeadsetStateMachine( 3106): make
,W/BluetoothAdapterService( 3106): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3106): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3106): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/QuickConnect[1.1][2] ( 3076): HeadsetProfile.onServiceConnected - Bluetooth service connected
D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3106): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3106): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3106): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3106): Not skipping com.android.bluetooth.map.BluetoothMapService
,E/HeadsetStateMachine( 3106): # of Max HF connection is 2
,I/BluetoothAdapterState( 3106): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3106): get_profile_interface handsfree
,D/BluetoothAtMessage( 3106): createCMTIContentObservers
,D/HeadsetStateMachine( 3106): Enter Disconnected: -2
,E/HeadsetStateMachine( 3106): set to mRemoteBrsf = 0
,D/HeadsetStateMachine( 3106): map size, before remove : 0
D/HeadsetStateMachine( 3106): map size, after remove: 0
,D/HeadsetStateMachine( 3106): mNextConnectingDevice : null
,D/BluetoothA2dp(  736): Proxy object connected
,D/BluetoothA2dp( 3076): Proxy object connected
,D/QuickConnect[1.1][2] ( 3076): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/A2dpService( 3106): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 3106): classInitNative: succeeds
,D/A2dpStateMachine( 3106): make
,I/bluedroid( 3106): get_profile_interface a2dp
,I/GKI_LINUX( 3106): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothAvrcpServiceJni( 3106): classInitNative: succeeds
,I/bluedroid( 3106): get_profile_interface avrcp
,D/A2dpStateMachine( 3106): Enter Disconnected: -2
D/BluetoothA2dp( 2029): Proxy object connected
,D/BluetoothNotiBroadcastReceiver( 1307): onReceive
,D/MediaFocusControl(  736): >>> registerRemoteControlDisplay
,E/MediaFocusControl(  736): Error updating focussed RCC to RCD 
E/MediaFocusControl(  736): java.util.EmptyStackException
E/MediaFocusControl(  736): 	at java.util.Stack.peek(Stack.java:57)
E/MediaFocusControl(  736): 	at android.media.MediaFocusControl.registerRemoteControlDisplay_int(MediaFocusControl.java:2308)
E/MediaFocusControl(  736): 	at android.media.MediaFocusControl.registerRemoteControlDisplay(MediaFocusControl.java:250)
E/MediaFocusControl(  736): 	at android.media.AudioService.registerRemoteControlDisplay(AudioService.java:6425)
E/MediaFocusControl(  736): 	at android.media.IAudioService$Stub.onTransact(IAudioService.java:593)
E/MediaFocusControl(  736): 	at android.os.Binder.execTransact(Binder.java:404)
E/MediaFocusControl(  736): 	at dalvik.system.NativeStart.run(Native Method)
,I/BluetoothHidServiceJni( 3106): classInitNative: succeeds
,D/BluetoothInputDevice( 3076): Proxy object connected
,D/HidService( 3106): Received start request. Starting profile...
I/bluedroid( 3106): get_profile_interface hidhost
,D/HidService( 3106): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 3106): classInitNative: succeeds
,D/QuickConnect[1.1][2] ( 3076): HidProfile.onServiceConnected - Bluetooth service connected
,D/HealthService( 3106): Received start request. Starting profile...
,I/bluedroid( 3106): get_profile_interface health
,I/BluetoothPanServiceJni( 3106): classInitNative(L105): succeeds
D/PanService( 3106): Received start request. Starting profile...
D/BluetoothPan(  736): BluetoothPAN Proxy object connected
,D/BluetoothPanServiceJni( 3106): initializeNative(L110): pan
,I/bluedroid( 3106): get_profile_interface pan
,D/BluetoothTethering(  736): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 3106): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 3106): mAccount : null
,D/HeadsetStateMachine( 3106): Try to query the phonestate on bind
,D/BluetoothPhoneService( 1241): handleMessage: 4
,V/BluetoothPhoneService( 1241): Call state Converted2: IDLE/IDLE -> 6
D/HeadsetStateMachine( 3106): Proxy object connected
,W/BluetoothHeadset( 1241): Proxy not attached to service
,D/HeadsetPhoneState( 3106): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3106): sendDeviceDataStateChanged
D/HeadsetPhoneState( 3106): Signal level : previous=0 curr=0
V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3106): Disconnected process message: 11
,D/BluetoothAdapterService( 3106): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetStateMachine( 3106): Disconnected process message: 20
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
D/HeadsetPhoneState( 3106): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 3106): Disconnected process message: 11
D/BluetoothAdapterService( 3106): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3106): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3106): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3106): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterState( 3106): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3106): enable
,D/GKI_LINUX( 3106): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 3106): Calling BTA_HhEnable
,E/bt-btif ( 3106): btif_storage_get_adapter_property service_mask:0x140040
E/BluetoothServiceJni( 3106): populateRssiValuesNative
I/bluedroid( 3106): getModelRssiValues
,E/BluetoothServiceJni( 3106): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/AuthorizationBluetoothService( 1323): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 241
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 241
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 241
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 241
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 241
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 241
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 10
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 241
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 10
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 241
,E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
E/BluetoothRemoteDevices( 3106): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 241
E/bt-btif ( 3106): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 3106): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 3106): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 3106): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 3106): db_open: db_open : handle 2013606680l, read 9734 bytes onto local cache
,D/IOP_DB_BT( 3106): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 3106): db_query: result 1
I/        ( 3106): iop_db_open: iop_db_open status 0
,I/bte_conf( 3106): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3106): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 3106): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3106): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 3106): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3106): ScanMode =  20
,D/BluetoothAdapterProperties( 3106): State =  11
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
D/BtConfig.SecureMode( 3106): isSecureModeOn:false
D/BtConfig.SecureMode( 3106): isSecureModeOn:false
D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
D/BtConfig.SecureMode( 3106): isSecureModeOn:false
D/BtConfig.SecureMode( 3106): isSecureModeOn:false
D/BtConfig.SecureMode( 3106): isSecureModeOn:false
D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,D/BtConfig.SecureMode( 3106): isSecureModeOn:false
,I/BluetoothAdapterState( 3106): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3106): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3106): updateAdapterState state is 12
,D/BluetoothAdapterService( 3106): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService(1112825120)( 3106): Register RemoteMessageListener
,D/HeadsetService( 3106): registerMessageListener
D/BluetoothAdapterService( 3106): Autoconnection is available 
D/BluetoothAdapterService( 3106): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 3106): starting service from this receiver
,D/BluetoothA2dp(  736): onBluetoothStateChange: up=true
D/BluetoothA2dp( 3076): onBluetoothStateChange: up=true
,D/HeadsetStateMachine( 3106): Disconnected process message: 70
D/HeadsetStateMachine( 3106): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@42588b90
D/BluetoothPanServiceJni( 3106): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,D/BluetoothInputDevice( 3076): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 2029): onBluetoothStateChange: up=true
,D/BluetoothAdapterService( 3106): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[91]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[92]}
,D/bluedroid( 3106): init_wake_lock lock_fd:91, unlock_fd:92
,W/ContextImpl( 3106): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
I/WifiTrafficPoller(  736): mBoosterFLAG : 2
,I/WifiTrafficPoller(  736): current booster mode : BTCoexMode
,D/PhoneApp( 1241): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
W/InputMethodManagerService(  736): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  736): [BT Setting State] State =12
,I/InputMethodManagerService(  736): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/BluetoothAdapterService(1112825120)( 3106): Get Bonded Devices being called
I/QuickConnect[1.1][2] ( 3076): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
,D/BluetoothHeadset( 1241): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@422065e8, true
,I/BluetoothAdapterState( 3106): Entering On State from state = 11
,D/BluetoothHeadset( 1241): registerMessageListener
,D/HeadsetService( 3106): registerMessageListener
D/HeadsetService( 3106): registerMessageListener
D/HeadsetStateMachine( 3106): Disconnected process message: 70
,D/HeadsetStateMachine( 3106): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@42612df8
,D/PhoneApp( 1241): registerMessageListener
,I/BluetoothPbapService( 3106): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/BluetoothPbapService( 3106): Handler(): got msg=1
,V/BluetoothPbapService( 3106): PBAP Service initSocket try: 0
D/STATUSBAR-IconMerger( 1068): checkOverflow(336), More:false, Req:false Child:2
,D/BluetoothMapMasInstance( 3106): set MAP SDP message type : 1
,W/BluetoothAdapter( 3106): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3106): SOCK FLAG = 1 ***********************
,W/BluetoothAdapter( 3106): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothPbapService( 3106): PBAP Socket is BluetoothServerSocket
,E/BluetoothServiceJni( 3106): SOCK FLAG = 3 ***********************
,D/LocalBluetoothProfileManager( 1307): Adding local A2DP profile
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,D/LocalBluetoothProfileManager( 1307): Adding local HEADSET profile
,E/BluetoothHeadset( 1307): BTStateChangeCB is registed
,E/BluetoothHeadset( 1307): BluetoothHeadset service is binded
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,D/Bluetoothsap( 1307): bindService called to Bluetooth SAP Service
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 1307): PANU : true
,D/LocalBluetoothProfileManager( 1307): Adding local MAP profile
,D/BluetoothMap( 1307): Create BluetoothMap proxy object
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
,D/GKI_LINUX( 3106): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1307): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1307): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1307): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1307): onReceive
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/BtConfig.SecureMode( 3106): isSecureModeOn:false
D/BluetoothA2dp( 1307): Proxy object connected
D/A2dpProfile( 1307): Bluetooth service connected
,D/AuthorizationBluetoothService( 1323): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1323): Proximity feature is not enabled.
,D/HeadsetProfile( 1307): Bluetooth service connected
,D/BluetoothInputDevice( 1307): Proxy object connected
,D/HidProfile( 1307): Bluetooth service connected
,D/BluetoothPan( 1307): BluetoothPAN Proxy object connected
,D/PanProfile( 1307): Bluetooth service connected
,D/BluetoothMap( 1307): Proxy object connected
,D/MapProfile( 1307): Bluetooth service connected
,D/BluetoothPbap( 1307): Proxy object connected
,D/PbapServerProfile( 1307): Bluetooth service connected
,W/BluetoothAdapter( 3106): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3106): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 3106): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 3106): Accept thread started.
,D/Tethering(  736): interfaceAdded wlan0
,E/Tethering(  736): No numeric data
D/Tethering(  736): interfaceLinkStateChanged wlan0, false
,D/Tethering(  736): interfaceStatusChanged wlan0, false
,D/Tethering(  736): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  736): forceRefresh() from cache miss
,D/Tethering(  736): InitialState.processMessage what=4
,E/Tethering(  736): No numeric data
,D/Tethering(  736): sendTetherStateChangedBroadcast 0, 0, 0
I/ConnectivityService(  736): defaultVal : 1, tetherEnabledInSettings : true
,I/ConnectivityService(  736): defaultVal : 1, tetherEnabledInSettings : true
D/NtpTrustedTime(  736): forceRefresh Fail.
D/Tethering(  736): interfaceAdded p2p0
,D/Tethering(  736): p2p0 is not a tetherable iface, ignoring
V/NetworkStats(  736): performPollLocked(flags=0x1)
,D/Tethering(  736): interfaceLinkStateChanged p2p0, false
,D/Tethering(  736): interfaceStatusChanged p2p0, false
,I/WifiHW  (  240): wifi_change_fw_path(): fwpath = sta
,D/SoftapController(  240): Softap fwReload - Ok
,D/NtpTrustedTime(  736): forceRefresh() from cache miss
,D/NtpTrustedTime(  736): forceRefresh Fail.
,D/NtpTrustedTime(  736): forceRefresh() from cache miss
,D/NtpTrustedTime(  736): forceRefresh Fail.
V/NetworkStats(  736): performPollLocked() took 18ms
,V/NetworkStats(  736): performPollLocked(flags=0x1)
D/CommandListener(  240): Setting iface cfg
,D/CommandListener(  240): Trying to bring down wlan0
,D/NtpTrustedTime(  736): forceRefresh() from cache miss
,D/NtpTrustedTime(  736): forceRefresh Fail.
D/WifiHW  (  736): Skip the update_ctrl_interface
,D/WifiHW  (  736): Skip the update_ctrl_interface
,E/WifiHW  (  736): supplicant_name : p2p_supplicant
V/NetworkStats(  736): performPollLocked() took 16ms
,D/WifiMonitor(  736): startMonitoring(wlan0) with mConnected = false
,D/GKI_LINUX( 3106): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/knox    ( 3017): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 3017): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3017): KNOXAgentService : onCreate()
,D/knox    ( 3017): KNOXAgentService : set alarms for deniallog and usage data upload
,I/wpa_supplicant( 4857): wpa_supplicant v2.1-devel-4.4.22014-11-04/18:06:52
I/wpa_supplicant( 4857): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 4857): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4857): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4857): getIMSI cannot open file
,E/wpa_supplicant( 4857): Interworking config: - SIM READ ERROR
,I/SELinux ( 4859): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4859):  
,D/knox    ( 3017): KNOXAgentService. startJobThread() start
D/knox    ( 3017): KNOXAgentService. JobThread()
D/knox    ( 3017): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3017): KNOXAgentService. startJobThread() wait
,D/knox    ( 3017): KNOXAgentService : onDestroy().
,D/knox    ( 3017): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 4859): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4859):  
I/SELinux ( 4859):  
,I/SELinux ( 4859): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4859): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4859): >>>>> Normal User
,E/dalvikvm( 4859): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 4859): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/GAV2    ( 4645): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 4859): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4859): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4859): Added TimaKesytore provider
,I/wpa_supplicant( 4857): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4857): getIMSI cannot open file
E/wpa_supplicant( 4857): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 4857): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4857): rfkill: Cannot open RFKILL control device
,D/Tethering(  736): interfaceLinkStateChanged wlan0, false
,D/Tethering(  736): interfaceStatusChanged wlan0, false
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=4859, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
,I/wpa_supplicant( 4857): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant( 4857): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4857): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4857): rfkill: Cannot open RFKILL control device
D/Tethering(  736): interfaceLinkStateChanged p2p0, false
,D/Tethering(  736): interfaceStatusChanged p2p0, false
D/Tethering(  736): interfaceLinkStateChanged p2p0, false
,D/Tethering(  736): interfaceStatusChanged p2p0, false
,I/ActivityManager(  736): Killing 3601:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/wpa_supplicant( 4857): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4857): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4857): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4857): Skip scan - bUseNetwork false
,D/WifiStateMachine(  736): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative(  736): callSECApiString - ID [21]
I/wpa_supplicant( 4857): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 4857): wlan0: HS20_DISABLED_COMPLETE normal
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
,I/knox    ( 3017): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3017): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,I/knox    ( 3017): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3017): KNOXAgentService : onCreate()
,D/knox    ( 3017): KNOXAgentService : set alarms for deniallog and usage data upload
,W/ContextImpl( 3017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/WifiNative(  736): callSECApiInt - ID [65]
,D/knox    ( 3017): KNOXAgentService. startJobThread() start
,D/knox    ( 3017): KNOXAgentService. JobThread()
D/knox    ( 3017): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3017): KNOXAgentService. startJobThread() wait
,E/WifiConfigStore(  736): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/knox    ( 3017): KNOXAgentService : onDestroy().
,D/knox    ( 3017): ModuleBase.cancelAllAlarmManageModule()
,D/WifiNative(  736): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 4857): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 4857): reset timer : RESET_TIMER 0
I/wpa_supplicant( 4857): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 4857): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 4857): First Scan Start
,I/wpa_supplicant( 4857): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  736): Set the Nv default ccode
,W/Settings( 2968): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  736): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine(  736): HS20_DISABLED_COMPLETEnormal
D/WifiP2pService(  736): P2pDisabledState{ what=131203 }
,I/wpa_supplicant( 4857): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
W/ContextImpl(  736): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.enterprise.wifi.WifiPolicy.asyncEnableNetwork:3065 com.android.server.enterprise.wifi.WifiPolicy.edmUpdateConfiguredNetworks:2530 com.android.server.enterprise.wifi.WifiPolicy$2$2.run:3022 java.lang.Thread.run:841 
,D/CommandListener(  240): Setting iface cfg
,D/CommandListener(  240): Trying to bring up p2p0
,D/WifiMonitor(  736): startMonitoring(p2p0) with mConnected = true
,D/QuickConnect[1.1][2] ( 3076): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,E/WifiStateMachine(  736): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService(  736): P2pEnablingState
D/WifiP2pService(  736): P2pEnablingState{ what=147457 }
D/WifiP2pService(  736): P2p socket connection successful
D/WifiP2pService(  736): P2pEnabledState
D/WifiDisplayController(  736): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  736): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  736): disconnect
D/WifiDisplayController(  736): updateConnection
D/WifiDisplayController(  736): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  736): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService(  736): sending p2p connection changed broadcast: IDLE
,D/QuickConnect[1.1][2] ( 3076): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiDisplayAdapter(  736): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/WifiP2pStateTracker(  736): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/QuickConnect[1.1][2] ( 3076): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDisplayController(  736): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/QuickConnect[1.1][2] ( 3076): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
D/WifiDisplayController(  736): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy S5-2
D/WifiDisplayController(  736):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiDisplayController(  736):  primary type: 10-0050F204-5
D/WifiDisplayController(  736):  secondary type: null
D/WifiDisplayController(  736):  wps: 0
D/WifiDisplayController(  736):  grpcapab: 0
D/WifiDisplayController(  736):  devcapab: 0
D/WifiDisplayController(  736):  status: 3
D/WifiDisplayController(  736):  wfdInfo: null
D/WifiDisplayController(  736):  groupownerAddress: null
D/WifiDisplayController(  736):  GOdeviceName: null
D/WifiDisplayController(  736):  interfaceAddress: 
D/WifiDisplayController(  736):  SConnectInfo : null
,D/FileShare-Server( 4094): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 4094): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
D/WifiP2pService(  736): DeviceAddress: 3a:06:dd
,D/WifiP2pService(  736): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  736): InactiveState
D/WifiP2pService(  736): InactiveState{ what=139287 }
D/WifiP2pService(  736): P2pEnabledState{ what=139287 }
,D/QuickConnect[1.1][2] ( 3076): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService(  736): DefaultState{ what=139287 }
,D/Tethering(  736): interfaceLinkStateChanged p2p0, false
,D/Tethering(  736): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4857): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4857): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4857): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant( 4857): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 4857): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 4857): Trying to associate with  'G700'
,I/wpa_supplicant( 4857): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 4857): Cmd 35609 not handled
,D/Tethering(  736): interfaceLinkStateChanged wlan0, false
,D/Tethering(  736): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  736): Error! unhandled message{ when=0 what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4857): Cmd 35605 not handled
E/wpa_supplicant( 4857): Cmd 35847 not handled
E/wpa_supplicant( 4857): Cmd 35848 not handled
,E/wpa_supplicant( 4857): Cmd 35605 not handled
I/wpa_supplicant( 4857): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 4857): Associated with C0.AA.48
,I/wpa_supplicant( 4857): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  736): interfaceLinkStateChanged wlan0, false
,D/Tethering(  736): interfaceStatusChanged wlan0, false
,D/Tethering(  736): interfaceLinkStateChanged wlan0, false
,D/Tethering(  736): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 4857): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 4857): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4857): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 4857): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  736): interfaceLinkStateChanged wlan0, false
D/WifiNative(  736): callSECApiVoid - ID [50]
,D/Tethering(  736): interfaceStatusChanged wlan0, false
,D/Tethering(  736): interfaceLinkStateChanged wlan0, true
,D/Tethering(  736): interfaceStatusChanged wlan0, true
,E/Tethering(  736): No numeric data
D/Tethering(  736): interfaceLinkStateChanged wlan0, true
,D/Tethering(  736): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering(  736): interfaceStatusChanged wlan0, true
,I/ConnectivityService(  736): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  736): interfaceLinkStateChanged wlan0, true
D/Tethering(  736): interfaceStatusChanged wlan0, true
D/Tethering(  736): interfaceLinkStateChanged wlan0, true
D/Tethering(  736): interfaceStatusChanged wlan0, true
D/Tethering(  736): interfaceLinkStateChanged wlan0, true
,D/Tethering(  736): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/NtpTrustedTime(  736): forceRefresh() from cache miss
,D/NtpTrustedTime(  736): forceRefresh Fail.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
V/NetworkStats(  736): performPollLocked(flags=0x1)
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,V/NetworkStats(  736): performPollLocked() took 15ms
I/SELinux ( 4901): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4901):  
D/NtpTrustedTime(  736): forceRefresh() from cache miss
D/NtpTrustedTime(  736): forceRefresh Fail.
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/dalvikvm(  250): GC_EXPLICIT freed 43K, 49% free 9508K/18468K, paused 3ms+3ms, total 29ms
,I/SELinux ( 4901): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4901):  
I/SELinux ( 4901):  
,I/SELinux ( 4901): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4901): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 4901): >>>>> Normal User
,E/dalvikvm( 4901): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 49% free 9508K/18468K, paused 2ms+3ms, total 21ms
,E/SELinux ( 4901): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/WifiP2pService(  736): InactiveState{ what=143375 }
,D/WifiP2pService(  736): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider( 4901): in addTimaSignatureService
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 49% free 9508K/18468K, paused 2ms+4ms, total 22ms
,D/TimaKeyStoreProvider( 4901): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4901): Added TimaKesytore provider
,I/System.out( 4901): Inside WakeupProvider
,I/System.out( 4901): Inside onCreate() of WakeupTriggerProvide
,E/SMD     (  243): DCD ON
,I/VlingoApplication( 4901): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 4901): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 4901): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 4916): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 4916): bssid match
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  736): Killing 3646:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/DialogFlow( 4901): initQueue()
,D/WifiP2pService(  736): InactiveState{ what=143375 }
,D/WifiP2pService(  736): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  736): VerifyingLinkState enter
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
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  736): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  736): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  736): evaluateTrafficStatsPolling
,D/WifiStateMachine(  736): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  736): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  736): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,I/WifiTrafficPoller(  736): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  736): mBoosterFLAG : 2
,I/WifiTrafficPoller(  736): current booster mode : BTCoexMode
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
D/ConnectivityService(  736): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  736): net.tcp.usercfg.wifi not found in system properties. Using defaults
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
E/ConnectivityService(  736): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService(  736): handleConnectivityChange: setting default proxy info 
,V/RouteController(  240): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,V/RouteController(  240): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  240): RTNETLINK answers: No such file or directory
,V/RouteController(  240): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
,D/Toast   ( 1307):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1307): showing allowed
,V/RouteController(  240): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  240): RTNETLINK answers: No such process
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,V/RouteController(  240): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
,I/SurfaceFlinger(  249): id=18 createSurf (1x1),1 flag=4, Uoast
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  736): forceRefresh() from cache miss
V/NetworkStats(  736): updateIfacesLocked()
V/NetworkStats(  736): performPollLocked(flags=0x1)
,D/PowerManagerService(  736): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=736
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
V/NetworkStats(  736): performPollLocked() took 19ms
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  736): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449751064585 mCachedNtpElapsedRealtime : 129648 mCachedNtpCertainty : 12
,D/NtpTrustedTime(  736): currentTimeMillis() cache hit
,D/NtpTrustedTime(  736): currentTimeMillis() cache hit
,D/NtpTrustedTime(  736): currentTimeMillis() cache hit
D/NtpTrustedTime(  736): currentTimeMillis() cache hit
D/NtpTrustedTime(  736): currentTimeMillis() cache hit
,D/NtpTrustedTime(  736): currentTimeMillis() cache hit
V/NetworkStats(  736): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/Tethering(  736): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  736): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  736): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/NtpTrustedTime(  736): currentTimeMillis() cache hit
,D/        (  736): Setting time of day to sec=1449751065
D/        (  736): Trying to open a file
D/        (  736): File Open Success
,D/        (  736): File Close Success
,I/        (  736): DRM_TIME_PATH CHMOD 660 for resetState done 
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,W/        (  736): Unable to set rtc to 1449751065: Invalid argument
,D/LocSvc_java(  736): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  736): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  736): ignore wifi update if we are not in OPENING or CLOSING
V/AlarmManager(  736): waitForAlarm result :65536
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
D/StatusBar-DoNotDistrub( 1068): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 1068): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/accuweather( 1444): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 1444): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionTIME_SET
W/Settings(  736): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AlarmManager(  736): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  736): waitForAlarm result :4
,I/AudioService(  736): getStreamVolume 5 index 110
I/PCWCLIENTTRACE_PushUtil( 4460): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4460): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4460): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4460): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/StatusBar-DoNotDistrub( 1068): sendBroadcast android.intent.action.DORMANT_MODE_OFF
D/StatusBar-DoNotDistrub( 1068): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService(  736): manageDisableList what=0x0 pkg=com.android.systemui
,W/SEC_DRM_PLUGIN_Playready(  251): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1449751064 after conversion: 1449751064
,W/SEC_DRM_PLUGIN_Playready(  251): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1449751065 after conversion: 1449751065
,I/SensorManagerA(  736): getReportingMode :: sensor.mType = 5
,D/Sensors (  736): LightSensor setDelay = 200000000
D/Sensors (  736): LightSensor setSensorDelay = 200000000
D/Sensors (  736): Light sensor flush: not enabled 0
D/Sensors (  736): LightSensor enable = 1
,D/Sensors (  736): LightSensor enableSensor = 1
D/STATUSBAR-NotificationService(  736): received android.intent.action.DORMANT_MODE_OFF
D/LightsService(  736): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 736) 
,D/LightsService(  736): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/SensorManager(  736): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/NetworkMonitor( 3682): type=WIFI subType= reason=null isConnected=true
D/accuweather( 1444): [KK AccuPhone]>>> SWW:452 [0:0] doChangeDayOrNight : 1
,D/accuweather( 1444): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 4995): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4995):  
,I/SELinux ( 4995): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4995):  
I/SELinux ( 4995):  
,I/SELinux ( 4995): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4995): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4995): >>>>> Normal User
,E/dalvikvm( 4995): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 4995): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4995): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4995): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4995): Added TimaKesytore provider
,D/Sensors (  736): LightSensor enable = 0
,D/Sensors (  736): LightSensor enableSensor = 0
,D/SensorManager(  736): unregisterListener ::   
D/LightsService(  736): [SvcLED]  onSensorChanged::light value = 30
D/LightsService(  736): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/SELinux ( 5013): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5013):  
,I/SELinux ( 5013): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5013):  
I/SELinux ( 5013):  
,I/SELinux ( 5013): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5013): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5013): >>>>> Normal User
,E/dalvikvm( 5013): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5013): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,I/dalvikvm( 1785): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1785): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x003d
,D/TimaKeyStoreProvider( 5013): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5013): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5013): Added TimaKesytore provider
,D/dalvikvm( 1785): GC_CONCURRENT freed 1655K, 37% free 11776K/18468K, paused 4ms+4ms, total 66ms
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=4995, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5013, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,E/ActivityThread( 1785): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  736): failed sync operation 
,D/SyncManager(  736): not retrying sync operation because the error is a hard error: 
,D/DelayedSyncController( 5013): Delaying sync.
,I/SELinux ( 5037): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5037):  
,W/WifiP2pStateTracker(  736): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  736): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  736):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  736): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  736): updateSourceRoutes : no source routing conditions
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5037): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5037):  
I/SELinux ( 5037):  
,I/SELinux ( 5037): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5037): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5037): >>>>> Normal User
,E/dalvikvm( 5037): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5037): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5037): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5037): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5037): Added TimaKesytore provider
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5037, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  736): Killing 3665:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/ActivityManager(  736): Killing 3898:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,I/SELinux ( 5049): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5049):  
,E/SMD     (  243): DCD ON
,I/SELinux ( 5049): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5049):  
I/SELinux ( 5049):  
,I/SELinux ( 5049): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5049): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5049): >>>>> Normal User
,E/dalvikvm( 5049): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5049): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5049): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5049): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5049): Added TimaKesytore provider
,D/dalvikvm(  736): GC_EXPLICIT freed 2596K, 60% free 23373K/57728K, paused 7ms+14ms, total 138ms
,D/DelayedSyncController( 5013): Delaying sync.
,D/PicasaService( 3766): start picasa sync
,D/PicasaService( 3766): end picasa sync
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5049, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5049): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5049): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449751066308
,I/KLMS-2.3.201 : ( 5049): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/ActivityManager(  736): Killing 3906:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 5066): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5066):  
,I/LocationTagReadyService( 2359): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2359): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2359): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3766): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/GalaxyFinderApplication( 2359): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 5066): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5066):  
I/SELinux ( 5066):  
,I/SELinux ( 5066): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5066): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5066): >>>>> Normal User
,E/dalvikvm( 5066): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5066): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5066): in addTimaSignatureService
,I/SELinux ( 5077): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5077):  
,D/TimaKeyStoreProvider( 5066): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5066): Added TimaKesytore provider
,I/SELinux ( 5082): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5082):  
I/SELinux ( 5077): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5077):  
I/SELinux ( 5077):  
,I/SELinux ( 5077): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5077): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5077): >>>>> Normal User
,E/dalvikvm( 5077): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5077): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5077): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5077): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5077): Added TimaKesytore provider
,I/SELinux ( 5082): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5082):  
I/SELinux ( 5082):  
,I/SELinux ( 5082): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5082): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5082): >>>>> Normal User
,E/dalvikvm( 5082): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5082): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5082): in addTimaSignatureService
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5066, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
D/TimaKeyStoreProvider( 5082): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5082): Added TimaKesytore provider
,D/btif_config_util( 3106): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SO_AGENT( 5066): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,V/KVNProvider( 5082): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5082): getFindoCursor query string : 
,I/SO_AGENT( 5066): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/dalvikvm( 1204): GC_EXPLICIT freed 445K, 46% free 10041K/18468K, paused 4ms+5ms, total 62ms
,V/KVNProvider( 5082): getTagSearchCursor() tagSearchCursor count : 0
I/ActivityManager(  736): Killing 3934:com.android.providers.calendar/u0a44 (adj 15): empty #43
,I/ActivityManager(  736): Killing 3882:com.android.calendar/u0a142 (adj 15): empty #43
,D/AmoledAdjustTimer(  736): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,I/SA      ( 4605): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4605): [BDLM] already registered in spp
I/SA      ( 4605): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4605): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4605): [SLFUCHKMGR] constructor called
,I/SA      ( 4605): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4605): [OR] == isSIMCardReady false ==
,W/DriveInitializer( 1785): Awaiting to be initialized
,W/DriveInitializer( 1785): Background init thread started
,I/SA      ( 4605): [SCU] == networkStateCheck == true
I/SA      ( 4605): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4605): isChinaCountryCode : false
,I/SA      ( 4605): [OR] == networkStateCheck true ==
,I/dalvikvm( 4576): Total arena pages for JIT: 11
,I/dalvikvm( 4576): Total arena pages for JIT: 12
I/dalvikvm( 4576): Total arena pages for JIT: 13
,I/dalvikvm( 4576): Total arena pages for JIT: 14
,I/SA      ( 4605): [OR] GetMyCountryZoneTask
,I/SA      ( 4605): [OR] onReceive END
,I/SA      ( 4605): [SRS] prepareGetMyCountryZone
I/ActivityManager(  736): Killing 3938:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,I/SA      ( 4605): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4605): [SSP] query invoked
,E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 1785): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,I/SELinux ( 5117): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5117):  
,I/SELinux ( 5117): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5117):  
I/SELinux ( 5117):  
,I/SELinux ( 5117): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5117): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5117): >>>>> Normal User
,E/dalvikvm( 5117): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5117): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 4605): [TPMU] GetMccFromDB : null
I/SA      ( 4605): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4605): [TPM] isNoProxy(default) : true
,I/SA      ( 4605): [RC New] Execute method=[GET] start
,D/TimaKeyStoreProvider( 5117): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5117): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5117): Added TimaKesytore provider
,W/DriveInitializer( 1785): Background init thread ended
,I/sCloudBackupApp( 5117): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5117): Other Intent
I/ActivityManager(  736): Killing 3865:com.sec.phone/1001 (adj 15): empty #43
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> WC:37 [0:0] oR : create UI manager : start
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:89 [0:0] getInstance
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1444): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 1444): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1444): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1444): [KK AccuPhone]>>> DBH:3047 [0:0] gADWI : count = 0
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/HarmonyEASService(  736): Updating for all 1
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/System.out( 4605): Thread-446(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4605): Thread-446(ApacheHTTPLog):isShipBuild true
,I/System.out( 4605): Thread-446(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux ( 5140): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5140):  
,I/SELinux ( 5140): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5140):  
I/SELinux ( 5140):  
,I/SELinux ( 5140): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5140): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5140): >>>>> Normal User
,E/dalvikvm( 5140): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10106 ]
,E/SELinux ( 5140): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5140): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5140): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5140): Added TimaKesytore provider
,D/HeadlinesChannelApplication( 5140): [onCreate]
,D/Headlines( 5140): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5140, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,D/HeadlinesChannelUtil( 5140): getCountryCode(): countryCode = PL
,D/Headlines( 5140): Breath.onCreate
,D/HeadlinesCardManager( 5140): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 5140): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 5140): CardProvider Library : 13
,I/SELinux ( 5152): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5152):  
,D/MagazineService::CardProviderContentProvider( 4724): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 4724): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5140): registerCardProvider: provider already exists.
,I/Headlines( 5140): HeadlinesDataCenter ctor
I/Headlines( 5140): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 5140): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 5140): HeadlinesCardManager : constructor welcome :YES
,D/Headlines( 5140): Breath timer started. interval : 30000
I/SELinux ( 5152): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5152):  
I/SELinux ( 5152):  
,I/SELinux ( 5152): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/Headlines( 5140): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5140): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5140): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5140): queryCategory.  mRequest is not initialized.
E/SELinux ( 5152): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/HeadlinesCardManager( 5140): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5140): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,E/dalvikvm( 5152): >>>>> Normal User
E/dalvikvm( 5152): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,D/HeadlinesDataCenter( 5140): requestUpdateNewsWelcomeCard !!! no welcome card
,E/SELinux ( 5152): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5152): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5152): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5152): Added TimaKesytore provider
,E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5152): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/GAV2    ( 5152): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
,W/Vold    (  230): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5152): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5152): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5152): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
,E/WifiStateMachine(  736): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,V/WebViewChromium( 5152): Binding Chromium to the main looper Looper (main, tid 1) {42212178}
,I/chromium( 5152): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5152): Initializing chromium process, renderers=0
,W/chromium( 5152): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5152): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5152): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5152): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5152): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5152): Remote Branch: 
I/Adreno-EGL( 5152): Local Patches: 
I/Adreno-EGL( 5152): Reconstruct Branch: 
,I/NSApplication( 5152): Starting up...
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5152, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  736): Killing 3812:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 3076): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3076): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3076): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42546be0
,I/SELinux ( 5190): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5190):  
,D/dalvikvm( 4109): GC_FOR_ALLOC freed 4062K, 36% free 11947K/18468K, paused 31ms, total 45ms
,I/dalvikvm-heap( 4109): Grow heap (frag case) to 16.458MB for 2129936-byte allocation
,I/SurfaceFlinger(  249): id=18 Removed Uoast (11/12)
,I/SurfaceFlinger(  249): id=18 Removed Uoast (-2/12)
I/ActivityManager(  736): Killing 2968:com.google.android.talk/u0a105 (adj 15): empty #43
,D/dalvikvm(  250): GC_EXPLICIT freed 43K, 49% free 9508K/18468K, paused 2ms+2ms, total 37ms
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  736): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=736 (0x0)
D/PowerManagerService(  736): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=736, ws=WorkSource{1000}) (elapsedTime=3459)
,I/SELinux ( 5190): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5190):  
I/SELinux ( 5190):  
,I/SELinux ( 5190): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5190): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5190): >>>>> Normal User
,E/dalvikvm( 5190): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5190): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 49% free 9508K/18468K, paused 2ms+3ms, total 20ms
,I/SA      ( 4605): [RC New] [v2liruge] api execute + 1047
,I/SA      ( 4605): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4605): AsyncTask #1 calls detatch()
,D/TimaKeyStoreProvider( 5190): in addTimaSignatureService
,I/SA      ( 4605): [TPMU] getNetworkMcc : 
,D/TimaKeyStoreProvider( 5190): Cannot add TimaSignature Service, License check Failed
,D/dalvikvm( 4109): GC_CONCURRENT freed 35K, 25% free 14009K/18468K, paused 4ms+9ms, total 61ms
,D/ActivityThread( 5190): Added TimaKesytore provider
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 49% free 9508K/18468K, paused 2ms+3ms, total 21ms
I/SA      ( 4605): [SCU] saveMccToPreferece Start
I/SA      ( 4605): [SCU] RegionMCC : 260
,I/SA      ( 4605): [SSP] query invoked
I/SA      ( 4605): [TPMU] GetMccFromDB : null
,I/SA      ( 4605): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4605): [SCU] saveMccToPreferece End
I/SA      ( 4605): [RC New] executeRequest [v2liruge] end. 1071
,I/SA      ( 4605): [RC New] Execute end
I/SA      ( 4605): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4605): [OR] GetMyCountryZoneTask Success
,D/RCPManagerService(  736): exchangeData() failure , invalid userId
,D/RCPManagerService(  736): exchangeData() failure , invalid userId
,D/RCPManagerService(  736): exchangeData() failure , invalid userId
,D/RCPManagerService(  736): exchangeData() failure , invalid userId
,D/RCPManagerService(  736): exchangeData() failure , invalid userId
,D/RCPManagerService(  736): exchangeData() failure , invalid userId
,I/SELinux ( 5209): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5209):  
,I/ActivityManager(  736): Killing 3958:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,I/SELinux ( 5213): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5213):  
D/SSRMv2:SIOP(  736): SIOP:: AP = 340, Delta = 10
,I/SELinux ( 5209): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5209):  
I/SELinux ( 5209):  
,I/SELinux ( 5209): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5209): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5209): >>>>> Normal User
,E/dalvikvm( 5209): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5209): [DEBUG] seapp_context_lookup: seinfoCategory = shared
W/ActivityManager(  736): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 5209): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5209): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5209): Added TimaKesytore provider
,I/SELinux ( 5213): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5213):  
I/SELinux ( 5213):  
,I/SELinux ( 5213): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5213): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5213): >>>>> Normal User
,E/dalvikvm( 5213): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5213): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5213): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5213): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5213): Added TimaKesytore provider
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5209, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  736): Killing 2847:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/WaitQueueForNetworkActivate( 4780): notifyNetworkActivated
,W/ContextImpl( 4780): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager(  736): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/BadgeProvider( 5213): onCreate
,D/BadgeProvider( 5213): DatabaseHelper
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5213, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5213): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5213): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5213): sendNotify, [notify] : null
D/BadgeProvider( 5213): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5213): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5213): update, [UpdateCount] : 1
,D/Launcher.Model( 1263): reloadBadges entered.
,D/hcjo    ( 4780): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 4780): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 4780): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 4780): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 4780): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4780): exit::IDLE
,D/InitializeManagerStateMachine( 4780): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4780): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4780): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4780): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4780): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4780): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 4780): entry::SUCCESS
,D/hcjo    ( 4780): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4780): AutoUpdateTriggerManager:IDLE:setInterval:345600000
D/hcjo    ( 4780): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4780): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4780): exit::SUCCESS
,D/InitializeManagerStateMachine( 4780): entry::IDLE
I/ActivityManager(  736): Killing 4158:com.wssyncmldm/1000 (adj 15): empty #43
,I/iu.SyncManager( 1785): SYNC; picasa accounts
,D/NetworkLogImpl( 1785): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1785): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1785): num queued entries: 0
,I/iu.UploadsManager( 1785): num updated entries: 0
,I/iu.SyncManager( 1785): NEXT; no task
,I/SELinux ( 5241): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5241):  
,I/SELinux ( 5241): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5241):  
I/SELinux ( 5241):  
,I/SELinux ( 5241): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5241): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5241): >>>>> Normal User
,E/dalvikvm( 5241): >>>>> com.android.calendar [ userId:0 | appId:10142 ]
,E/SELinux ( 5241): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5241): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5241): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5241): Added TimaKesytore provider
,I/GCM     ( 1323): GCM config loaded
,D/dalvikvm(  736): GC_EXPLICIT freed 1371K, 60% free 23259K/57728K, paused 6ms+13ms, total 148ms
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/BootCompletedReceiver(  736): onReceive
,I/ActivityManager(  736): Killing 4363:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/KLMS-2.3.201 : ( 5049): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5049): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1449751069007
,I/KLMS-2.3.201 : ( 5049): StateImplV2() : dateTimeChanged() : Thu Dec 10 13:37:49 CET 2015
,E/SMD     (  243): DCD ON
,D/SO_AGENT( 5066): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 5066): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 4605): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/Mms/MessagingNotification( 3703): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 3703): sDisableVibrateForCamera = false
,D/Mms/MessagingNotification( 3703): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 3703): isDefault true
,I/SELinux ( 5268): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5268):  
,D/TP/MmsSmsProvider( 1241): match 200:Elapsed time : 1.526 ms
,I/SELinux ( 5268): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5268):  
I/SELinux ( 5268):  
,I/SELinux ( 5268): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5268): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 5268): >>>>> Normal User
,E/dalvikvm( 5268): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 5268): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5268): in addTimaSignatureService
,D/BadgeProvider( 5213): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 5268): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5268): Added TimaKesytore provider
,D/Launcher.Model( 1263): reloadBadges entered.
,D/BadgeProvider( 5213): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5213): sendNotify, [notify] : null
,D/BadgeProvider( 5213): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5213): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5213): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 3703): setBadgeCount(), count=0
,D/MessagingNotification( 3703): remove alarm
,D/Mms/MessagingNotification( 3703): [end]    nonBlockingUpdateMessageIndicator()
,D/TP/MmsSmsProvider( 1241): match 8:Elapsed time : 70.909 ms
,D/Mms/MessagingNotification( 3703): updateAllHistoryAsRead()
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5268, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/ActivityManager(  736): Killing 3138:com.sec.android.inputmethod/1000 (adj 15): empty #43
,I/ Time Manager ( 5268): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 5287): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5287):  
,I/SELinux ( 5287): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5287):  
I/SELinux ( 5287):  
,I/SELinux ( 5287): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5287): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5287): >>>>> Normal User
,E/dalvikvm( 5287): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 5287): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5287): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5287): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5287): Added TimaKesytore provider
,D/ConnectivityService(  736): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5303): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5303):  
I/ActivityManager(  736): Killing 4416:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 5303): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5303):  
I/SELinux ( 5303):  
,I/SELinux ( 5303): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5303): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5303): >>>>> Normal User
,E/dalvikvm( 5303): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 5303): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5303): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5303): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5303): Added TimaKesytore provider
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5303, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 5303): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 5303): ELMEngine.ELMEngine( context ).
,D/elm:14132( 5303): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 5303): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,I/knox    ( 3017): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 5303): ElmAgentService : onCreate()
,W/ContextImpl( 3017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3017): MainReceiver.listeningToTimeDateChanges( context, intent ).
I/knox    ( 3017): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/elm:14132( 5303): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/elm:14132( 5303): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 5303): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14132( 5303): ModuleBase.resetCalllogAPIAlarm()
D/knox    ( 3017): KNOXAgentService : onCreate()
D/knox    ( 3017): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3017): KNOXAgentService. startJobThread() start
D/knox    ( 3017): KNOXAgentService. JobThread()
D/knox    ( 3017): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3017): KNOXAgentService. startJobThread() wait
,I/SELinux ( 5318): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5318):  
W/ContextImpl(  736): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/knox    ( 3017): KNOXAgentService : onDestroy().
,D/elm:14132( 5303): ModuleBase.ModifySetAlarm()
,D/knox    ( 3017): ModuleBase.cancelAllAlarmManageModule()
D/elm:14132( 5303): MDMBridge.getInstance()
,D/elm:14132( 5303): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 5303): ElmAgentService : onDestroy().
I/ActivityManager(  736): Killing 4433:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/SELinux ( 5318): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5318):  
I/SELinux ( 5318):  
,I/SELinux ( 5318): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5318): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5318): >>>>> Normal User
,E/dalvikvm( 5318): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10143 ]
,E/SELinux ( 5318): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5318): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5318): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5318): Added TimaKesytore provider
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5318, uid=10143 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5330): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5330):  
I/ActivityManager(  736): Killing 4445:com.android.musicfx/u0a24 (adj 15): empty #43
,I/SELinux ( 5330): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5330):  
I/SELinux ( 5330):  
,I/SELinux ( 5330): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5330): >>>>> Normal User
,E/dalvikvm( 5330): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
,E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5330): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5330): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5330): Added TimaKesytore provider
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5330, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5342): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5342):  
I/ActivityManager(  736): Killing 4472:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty #43
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4460): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 4460): [hasSamungAccount] - No Samsung Account
,V/AlarmManager(  736): waitForAlarm result :4
,V/AlarmManager(  736): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5342): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5342):  
I/SELinux ( 5342):  
,I/SELinux ( 5342): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5342): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5342): >>>>> Normal User
,E/dalvikvm( 5342): >>>>> com.qualcomm.timeservice [ userId:0 | appId:10168 ]
,E/SELinux ( 5342): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5342): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5342): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5342): Added TimaKesytore provider
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5342, uid=10168 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm( 5342): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42537a20, skipping init
D/TimeService( 5342): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449751070186
D/        ( 5342): TimeServiceNative: User Time to be set is 1449751070187
D/QC-time-services( 5342): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5342): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 5342): Lib:time_genoff_operation: pargs->ts_val = 1449751070187
,D/QC-time-services( 5342): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  294): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  294): Daemon: genoff_handler: Process name is omm.timeservice
D/QC-time-services(  294): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449751070187
D/QC-time-services(  294): Daemon:genoff_opr: Base = 2, val = 1449751070187, operation = 0
D/QC-time-services(  294): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/14/70 4:34:57
D/QC-time-services(  294): Daemon:Value read from RTC seconds = 1139697000
,D/QC-time-services(  294): Daemon:new time 1449751070187 
D/QC-time-services(  294): Daemon: delta 1448611373187 genoff 1448611373187 
D/QC-time-services(  294): Daemon:genoff_persistent_update: Writing genoff = 1448611373187 to memory
D/QC-time-services(  294): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  294): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  294): Updating the TOD offset
D/QC-time-services(  294): Daemon:genoff_persistent_update: Writing genoff = 1448611373187 to memory
D/QC-time-services(  294): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  294): Daemon:time_persistent_memory_opr:Genoff write operation 
,W/linker  ( 4460): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,E/QC-time-services(  294): Daemon:Update to modem bit set
D/QC-time-services(  294): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  294): Daemon: Base = 2, Value being sent to MODEM = 1133786270187
E/QC-time-services( 5342): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/CSTORAGE( 4460): ================================================
I/CSTORAGE( 4460):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 4460): ================================================
D/dalvikvm( 4460): No JNI_OnLoad found in /system/lib/libterrier.so 0x42537130, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4460): [GetString-S]
I/terrier ( 4460): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 4460): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 4460): App is not loaded in QSEE
,E/QC-time-services(  294): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  294): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  736): stay LED for fully charged
I/ActivityManager(  736): Killing 4509:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3106): Disconnected process message: 10
D/daemonapp( 1462): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1462): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1462): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1462): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1462): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1462): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/QSEECOMAPI: ( 4460): Loaded image: APP id = 3
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/daemonapp( 1462): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/QSEECOMAPI: ( 4460): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 4460): QSEECom_shutdown_app, app_id = 3
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
E/terrier ( 4460): com.sec.pcw.device: getString: failed to get string(-1)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4460): [GetString-E]
D/daemonapp( 1462): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
I/PCWCLIENTTRACE_PushUtil( 4460): SPPPushClient is installed : true
D/daemonapp( 1462): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
I/PCWCLIENTTRACE_PushUtil( 4460): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4460): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 4460): [ensureRegistration] - No Samsung account
D/daemonapp( 1462): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 1462): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1462): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 1785): Checkin interval check for package: unspecified last checkin: 1449576543959 min interval config: 0 actual interval: 174526352
,I/rmt_storage(  302): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8ef8178
I/rmt_storage(  302): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  302): wakelock acquired: 1, error no: 42
,I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1192263960)
,I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1192263960) wakelock released: 1, error no: 0
I/rmt_storage(  302): 
,I/rmt_storage(  302): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8ef8178
,D/Mms/MessagesLockscreen( 3703): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,D/ContextualEventManager( 1068): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1068): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1068): updateContainer()
D/ContextualEventContainer( 1068): update()
,D/ContextualEventContainer( 1068): handleUpdate()
D/ContextualEventManager( 1068): getTopEventView()
,D/ContextualEventManager( 1068): getTopContextualEvent()
,D/ContextualEventManager( 1068): top view = flightmode
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/UsbManager( 1068):  :::: isUsb30Available :: return = false from pid = 1068
,I/SELinux ( 5363): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5363):  
,D/SecContextualClockFlightMode( 1068): handleUpdateClock()
,D/KeyguardProperties( 1068): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SELinux ( 5363): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5363):  
I/SELinux ( 5363):  
,I/SELinux ( 5363): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5363): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5363): >>>>> Normal User
,E/dalvikvm( 5363): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
,E/SELinux ( 5363): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5363): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5363): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5363): Added TimaKesytore provider
,I/VacuumService( 1220): Vacuum at: now=1449751070660 tag=VacuumService
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=5363, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,D/Headlines( 5140): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5140): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5140): Breath 3429 latestRequest time : 1449751067495 current time : 1449751070924
,V/AlarmManager(  736): waitForAlarm result :4
,V/AlarmManager(  736): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/ActivityManager(  736): Killing 3779:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty #43
,E/SMD     (  243): DCD ON
,D/Finsky  ( 3432): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3432): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/PowerManagerService(  736): [PWL] Off : 75s ago
I/PowerManagerService(  736): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  736): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  736): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10084, pid=5287, ws=null) (elapsedTime=3001)
,I/GAV2    ( 5152): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4666): Test app app.js loaded
I/jxcore-log( 4666): 
,I/chromium( 4666): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/Watchdog(  736): !@Sync 4
,E/SMD     (  243): DCD ON
,D/CaptivePortalTracker(  736): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  736): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  736): Checking http://216.58.209.46/generate_204
W/ActivityThread(  736): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out(  736): Thread-162(HTTPLog):isShipBuild true
,I/System.out(  736): Thread-162(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker(  736): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  736): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  736): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  736): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  736): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AmoledAdjustTimer(  736): prevTemp = 298, currTemp = 302, prevStep = 4, currStep = 5
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  736): SIOP:: AP = 320, Delta = -20
,D/PreloadUpdateManagerStateMachine( 4780): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4780): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4780): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4780): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 4780): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4780): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4780): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4780): entry::IDLE
,V/AlarmManager(  736): waitForAlarm result :8
,V/AlarmManager(  736): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  736): stay LED for fully charged
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
,E/SMD     (  243): DCD ON
,I/ActivityManager(  736): Waited long enough for: ServiceRecord{435e4d70 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  736): prevTemp = 302, currTemp = 303, prevStep = 5, currStep = 5
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  736): SIOP:: AP = 310, Delta = -10
,W/ContextImpl(  736): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  736): waitForAlarm result :4
,V/AlarmManager(  736): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  736): stay LED for fully charged
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  736): prevTemp = 303, currTemp = 300, prevStep = 5, currStep = 5
,D/SyncManager(  736): failed sync operation 
,D/SyncManager(  736): not retrying sync operation because the error is a hard error: 
E/ActivityThread( 1785): Failed to find provider info for com.android.contacts.metadata
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = -10
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  736): [PWL] Off : 105s ago
,E/Watchdog(  736): !@Sync 5
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  736): prevTemp = 300, currTemp = 300, prevStep = 5, currStep = 5
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  736): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,V/AlarmManager(  736): waitForAlarm result :4
,V/AlarmManager(  736): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5140): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5140): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5140): Breath 43691 latestRequest time : 1449751067495 current time : 1449751111186
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/BatteryService(  736): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm(  736): GC_EXPLICIT freed 2095K, 60% free 23504K/57728K, paused 29ms+24ms, total 634ms
,D/dalvikvm( 1323): GC_EXPLICIT freed 1349K, 42% free 10767K/18468K, paused 5ms+7ms, total 47ms
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype for one-off execution 114 seconds from now (1449751112477)
,D/GetConfigurationSnapshotOperation( 1220): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1220): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1220): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  736): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1220): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1220): Thread-107(HTTPLog):isShipBuild true
,I/System.out( 1220): Thread-107(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1220): GC_CONCURRENT freed 1472K, 36% free 11862K/18468K, paused 5ms+6ms, total 59ms
,D/LocationManagerService(  736): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  736): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  736): prevTemp = 300, currTemp = 298, prevStep = 5, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  736): waitForAlarm result :4
,V/AlarmManager(  736): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/AmoledAdjustTimer(  736): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService(  736): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  736): waitForAlarm result :8
,D/Headlines( 5140): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5140): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5140): Breath 60051 latestRequest time : 1449751067495 current time : 1449751127546
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,W/ContextImpl(  736): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  736): !@Sync 6
,E/SMD     (  243): DCD ON
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/AmoledAdjustTimer(  736): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  736): stay LED for fully charged
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
,I/PowerManagerService(  736): [PWL] Off : 140s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  736): waitForAlarm result :8
,V/AlarmManager(  736): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  736): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/BatteryService(  736): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  736): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  736): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager(  736): waitForAlarm result :8
,D/Headlines( 5140): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5140): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5140): Breath 90049 latestRequest time : 1449751067495 current time : 1449751157544
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  736): stay LED for fully charged
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  736): !@Sync 7
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  736): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  736): stay LED for fully charged
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  736): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  736): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  736): [PWL] Off : 180s ago
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  736): stay LED for fully charged
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  736): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager(  736): waitForAlarm result :8
,D/Headlines( 5140): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5140): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5140): Breath 120046 latestRequest time : 1449751067495 current time : 1449751187541
,D/Headlines( 5140): stop 
,D/Headlines( 5140): Breath.onDestroy : 
,I/ActivityManager(  736): Killing 2800:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/BatteryService(  736): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3106): Disconnected process message: 10
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  736): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  736): !@Sync 8
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  736): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  736): stay LED for fully charged
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  736): waitForAlarm result :8
,V/AlarmManager(  736): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  736): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  736): stay LED for fully charged
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  736): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  736): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  736): stay LED for fully charged
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  736): [PWL] Off : 225s ago
,E/Watchdog(  736): !@Sync 9
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  736): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  736): mCoverManager.getCoverState() : true
,D/BatteryService(  736): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3106): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 3106): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  736): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  736): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON

```
