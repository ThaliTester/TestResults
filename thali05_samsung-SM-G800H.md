#### Test 50242285576d0b0_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b45890, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b45890, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b45890, 8, 0, 0)
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
V/MediaPlayer( 2423): decode(68, 30372876, 21552)
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
V/AudioCache(  250): notify(0xb8b49d10, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b49d10, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b49d10, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b49d10, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b49d10, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8b49d10, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b49d10, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b49d10, 8, 0, 0)
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
V/MediaPlayer( 2423): decode(69, 37543652, 4230)
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
V/AudioCache(  250): notify(0xb8b52188, 8, 0, 0)
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
W/ApplicationsProvider( 1409): Could not fetch usage stats
W/ApplicationsProvider( 1409): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1409): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1409): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1409): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1409): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1409): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1409): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb8b52188, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b52188, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b52188, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b52188, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b52188, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b52188, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b52188, 8, 0, 0)
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
V/MediaPlayer( 2423): decode(70, 30337076, 9400)
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
V/AudioCache(  250): notify(0xb8b44338, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
I/Process ( 2423): Sending signal. PID: 2423 SIG: 9
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
V/AudioCache(  250): notify(0xb8b44338, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b44338, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b44338, 1, 0, 0)
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
E/IMemory (  250): binder=0xb8b0f7e8 transaction failed fd=-2147483647, size=0, err=-32 (Broken pipe)
E/IMemory (  250): cannot dup fd=-2147483647, size=0, err=-32 (Bad file number)
E/IMemory (  250): cannot map BpMemoryHeap (binder=0xb8b0f7e8), size=0, fd=-1 (Bad file number)
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b44338, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() stop AudioSource since AudioPlayer not exist
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x28, OMX_CommandStateSet, OMX_StateIdle)
--------- beginning of /dev/log/system
I/ActivityManager(  729): Process com.sec.android.app.shealth (pid 2423) (adj 0) has died.
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
I/SELinux ( 2493): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2493):  
D/SensorService(  729):   -0.1 -0.1 9.6
I/SELinux ( 2493): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2493):  
I/SELinux ( 2493):  
I/SELinux ( 2493): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2493): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2493): >>>>> Normal User
E/dalvikvm( 2493): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 2493): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 2493): in addTimaSignatureService
D/TimaKeyStoreProvider( 2493): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2493): Added TimaKesytore provider
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=2493, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 2493): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences( 2493): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 2493): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 2493): ContentProvider is not null
V/MediaPlayer( 2493): decode(61, 33979084, 48105)
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
V/AudioCache(  250): notify(0xb8b48730, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b48730, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b48730, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b48730, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b48730, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8b48730, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b48730, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b48730, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(63, 33914984, 10421)
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
V/AudioCache(  250): notify(0xb8b515e8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b515e8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b515e8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b515e8, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b515e8, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8b515e8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b515e8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b515e8, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(64, 37457308, 34198)
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
V/AudioCache(  250): notify(0xb8b44d20, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b44d20, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b44d20, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b44d20, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b44d20, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8b44d20, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b44d20, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b44d20, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(65, 33862452, 7405)
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
V/AudioCache(  250): notify(0xb8b45bd8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b45bd8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b45bd8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b45bd8, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b45bd8, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8b45bd8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b45bd8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b45bd8, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(66, 37547940, 5555)
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
V/AudioCache(  250): notify(0xb8b50910, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b50910, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b50910, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b50910, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b50910, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8b50910, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b50910, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b50910, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(67, 30367732, 5085)
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
V/AudioCache(  250): notify(0xb8b42548, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b42548, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b42548, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b42548, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b42548, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
I/ServiceManager(  285): Waiting for service AtCmdFwd...
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b42548, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b42548, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b42548, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(68, 30372876, 21552)
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
V/AwesomePlayer,(  250): setListener
V/StagefrightPlayer(  250): initCheck
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(33, 30372876, 21552)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b44910, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b44910, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b44910, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b44910, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b44910, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8b44910, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b44910, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b44910, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(69, 37543652, 4230)
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
V/AudioCache(  250): notify(0xb8b533e0, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b533e0, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b533e0, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b533e0, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b533e0, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b533e0, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b533e0, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b533e0, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(70, 30337076, 9400)
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
V/AudioCache(  250): notify(0xb8b55560, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b55560, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b55560, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b55560, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
I/SELinux ( 2560): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2560):  
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
V/AudioCache(  250): notify(0xb8b55560, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8b55560, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b55560, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b55560, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(71, 33925464, 44276)
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
V/AudioCache(  250): notify(0xb8b542c8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b542c8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b542c8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b542c8, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
I/SELinux ( 2560): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2560):  
I/SELinux ( 2560):  
I/SELinux ( 2560): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
E/SELinux ( 2560): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2560): >>>>> Normal User
E/dalvikvm( 2560): >>>>> com.sec.android.app.sns3 [ userId:0 | appId:10036 ]
E/SELinux ( 2560): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b542c8, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
D/TimaKeyStoreProvider( 2560): in addTimaSignatureService
D/TimaKeyStoreProvider( 2560): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2560): Added TimaKesytore provider
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b542c8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b542c8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b542c8, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(72, 33885672, 29256)
V/MediaPlayerService(  250): decode(33, 33885672, 29256)
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
V/AudioCache(  250): notify(0xb8b45c38, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b45c38, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b45c38, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b45c38, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b45c38, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8b45c38, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b45c38, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b45c38, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(73, 37491572, 52024)
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
V/AudioCache(  250): notify(0xb8b464a0, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b464a0, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b464a0, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b464a0, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b464a0, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb8b464a0, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b464a0, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b464a0, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(74, 33969800, 9226)
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
V/AudioCache(  250): notify(0xb8b46ae0, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b46ae0, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b46ae0, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b46ae0, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b46ae0, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=2560, uid=10036 requires android.permission.INTERACT_ACROSS_USERS
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b46ae0, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b46ae0, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b46ae0, 8, 0, 0)
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
V/MediaPlayer( 2493): decode(75, 30402580, 4509)
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
V/AudioCache(  250): notify(0xb8b48390, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb8b48390, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b48390, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b48390, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb8b48390, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b48390, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b48390, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb8b48390, 8, 0, 0)
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
I/Process ( 2560): Sending signal. PID: 2560 SIG: 9
I/ActivityManager(  729): Process com.sec.android.app.sns3 (pid 2560) (adj 0) has died.
I/SELinux ( 2608): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2608):  
I/SELinux ( 2608): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2608):  
I/SELinux ( 2608):  
I/SELinux ( 2608): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2608): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2608): >>>>> Normal User
E/dalvikvm( 2608): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 2608): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 2608): in addTimaSignatureService
D/TimaKeyStoreProvider( 2608): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2608): Added TimaKesytore provider
I/SELinux ( 2626): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2626):  
I/SELinux ( 2626): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2626):  
I/SELinux ( 2626):  
I/SELinux ( 2626): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2626): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2626): >>>>> Normal User
E/dalvikvm( 2626): >>>>> com.sec.spp.push [ userId:0 | appId:10038 ]
E/SELinux ( 2626): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 2626): in addTimaSignatureService
D/TimaKeyStoreProvider( 2626): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2626): Added TimaKesytore provider
E/SPPClientService( 2626): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 2626): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 2626): PushLog.txt file is not deleted.
D/SPPClientService( 2626): PushLog.txt file is not deleted.
D/SPPClientService( 2626): ============PushLog. stop!
E/SPPClientService( 2626): [SystemStateMoniter] ACTION_BOOT_COMPLETED
I/SELinux ( 2639): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2639):  
I/SELinux ( 2639): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2639):  
I/SELinux ( 2639):  
I/SELinux ( 2639): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2639): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2639): >>>>> Normal User
E/dalvikvm( 2639): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 2639): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 2639): in addTimaSignatureService
D/TimaKeyStoreProvider( 2639): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2639): Added TimaKesytore provider
I/SA      ( 2639): [SSP] onCreated
I/SA      ( 2639): [TPM] There is no property file
I/SA      ( 2639): [SCU] isHaveSA() - false
I/SA      ( 2639): [TPM] getModelProperty : null
I/SA      ( 2639): [TPM] getCSCProperty : null
I/SA      ( 2639): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED
I/SA      ( 2639): [DM] init START
I/SA      ( 2639): [DM] This device is not a Vodafone
I/SA      ( 2639): [DM] getCountryCodeFromCSC : PL
I/SA      ( 2639): support phone number id : false
I/SA      ( 2639): [DM] init END
I/SA      ( 2639): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 2639): [BDLM] already registered in spp
I/SA      ( 2639): [OR] onReceive Intent=[ action_BOOT_COMPLETED ]
I/SA      ( 2639): [OR] onReceive END
I/SA      ( 2639): [BDC] create
I/SA      ( 2639): [DBMV2] getEmailID
I/SA      ( 2639): [DBMV2] getDataV02ForItems
I/SA      ( 2639): [SSP] query invoked
I/SELinux ( 2658): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2658):  
I/SA      ( 2639): [SCU] get signed id from samsung account2.0 DB.
I/SA      ( 2639): [SCU] get signed id from samsung account1.0 DB.
I/SA      ( 2639): [BDC] destroy
I/ServiceManager(  285): Waiting for service AtCmdFwd...
I/SELinux ( 2658): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2658):  
I/SELinux ( 2658):  
I/SELinux ( 2658): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2658): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2658): >>>>> Normal User
E/dalvikvm( 2658): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
E/SELinux ( 2658): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:45, charge type:1, power sharing:false
D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  729): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/TimaKeyStoreProvider( 2658): in addTimaSignatureService
D/TimaKeyStoreProvider( 2658): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2658): Added TimaKesytore provider
D/PowerManagerService(  729): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=1067
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
D/NotificationService(  729): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200dd contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/RCPManagerService(  729): NotificationReceiver onReceive()
D/RCPManagerService(  729):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService(  729): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967296729
D/RCPManagerService(  729): getPolicy: policy value returned = false
D/RCPManagerService(  729): going to get the app label for pkg == com.android.systemui
D/RCPManagerService(  729): app label == com.android.systemui
E/SMD     (  241): DCD ON
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService(  729): sendNotification(1) - 5
W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/UserManagerService(  729): User -1does not exists!!
D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:1
D/RCPManagerService(  729): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967296729
D/RCPManagerService(  729): getPolicy: policy value returned = true
D/RCPManagerService(  729): Calling User is -1
D/RCPManagerService(  729): userid of SBN ==-1
E/PersonaManagerService(  729): returning null in  getPersonasForUser
D/ProgressBar( 1067): setProgressDrawable drawableHeight = 12
D/PhoneStatusBar( 1067): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422c8aa0
D/BatteryMeterView( 1067): onDraw batteryColor : -1
D/AndroidRuntime( 2663): 
D/AndroidRuntime( 2663): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2663): CheckJNI is OFF
D/AndroidRuntime( 2663): setted country_code = Poland
D/AndroidRuntime( 2663): setted countryiso_code = PL
D/AndroidRuntime( 2663): setted sales_code = XEO
D/AndroidRuntime( 2663): readGMSProperty: start
D/AndroidRuntime( 2663): readGMSProperty: already setted!!
D/AndroidRuntime( 2663): readGMSProperty: end
D/AndroidRuntime( 2663): addProductProperty: start
D/dalvikvm( 2663): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2663): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2663): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2663): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2663): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=2658, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
D/MediaScannerReceiver( 1207): action: android.intent.action.BOOT_COMPLETED
E/memtrack( 2663): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 2663): failed to load memtrack module: -2
D/dalvikvm( 2663): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/MediaScannerService( 1207): !@start scanning volume internal: [/system/media]
D/TP/MmsProvider( 1241): Update uri=content://mms, match=0
D/TP/MmsProvider( 1241): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1241): need read changed broadcast:false
I/Mms:transaction( 1727): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 1727): [start]    nonBlockingUpdateMessageIndicator()
I/Mms/ReservationManager( 1727): resetAfterConnected()
D/TP/MmsSmsProvider( 1241): match 7:Elapsed time : 3.258 ms
D/Mms/MessagingNotification( 1727): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1727): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1727): isDefault true
D/AndroidRuntime( 2663): Calling main entry com.android.commands.am.Am
I/Mms/ReservationManager( 1727): getReservedSendMessageCount(): retMessageCount=0
I/SELinux ( 2698): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2698):  
D/TP/MmsSmsProvider( 1241): match 200:Elapsed time : 1.519 ms
V/ApplicationPolicy(  729): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/BadgeProvider( 1340): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/Mms/TelephonyPermission( 1727): isDefault true
D/Mms/SmsReceiverService( 1727): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 1727): [start]    handleBootCompleted()
I/SELinux ( 2698): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2698):  
I/SELinux ( 2698):  
I/SELinux ( 2698): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (, 2698): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2698): >>>>> Normal User
E/dalvikvm( 2698): >>>>> com.sec.android.app.safetyassurance [ userId:0 | appId:10050 ]
E/SELinux ( 2698): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  729): mDVFSHelper.acquire()
I/SurfaceFlinger(  247): id=14 createSurf (1x1),1 flag=404, iello
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 2698): in addTimaSignatureService
D/TimaKeyStoreProvider( 2698): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2698): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/MediaScanner( 1207): Prescan. DB items number : 156 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
V/MediaScanner( 1207): processDirectory :  /system/media
V/MediaScanner( 1207):  prescan time: 102ms (DB items: 156)
V/MediaScanner( 1207):     scan time: 49ms (Caching mode: true), (makeEntry time: 21ms ~42%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1207): postscan time: 1ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1207):    total time: 152ms
V/MediaScanner( 1207): checked files: 149  directories : 5  (I: 0, U: 0)
D/MediaScanner( 1207): checkDefaultSounds
D/MediaScanner( 1207): system alarm_alert  : Vwiurug_etwofi5wgg
W/Atfwd_Sendcmd(  285): AtCmdFwd service not published, waiting... retryCnt : 3
I/WindowManager(  729): Screenshot max retries 4 of Token{429f0cc8 ActivityRecord{429960a8 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42a80f30 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
W/WindowManager(  729): Screenshot failure taking screenshot for (720x1280) to layer 21005
D/LockPatternUtils( 1067): isPcwEnable = null
D/AndroidRuntime( 2663): Shutting down VM
D/dalvikvm( 2663): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 2711): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2711):  
D/Launcher.HomeView( 1247): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1451): [237392/5] Surface widget pause on instance = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1451): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 1451): [KK AccuPhone]>>> SWW:224 [0:0] [SWW] onPause : instance = 1
D/accuweather( 1451): [KK AccuPhone]>>> SWW:239 [0:0] onPause : size = 0
D/accuweather( 1451): [KK AccuPhone]>>> SWW:517 [0:0]  unRegisterTTReceiver !! 
D/accuweather( 1451): [KK AccuPhone]>>> WR:149 [0:0] onPause
D/accuweather( 1451): [KK AccuPhone]>>> SM:526 [0:0] onPause
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/BadgeProvider( 1340): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): sendNotify, [notify] : null
D/BadgeProvider( 1340): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1340): update, [UpdateCount] : 1
D/Launcher( 1247): onTrimMemory. Level: 20
D/Mms/MessagingNotification( 1727): setBadgeCount(), count=0
D/MediaScanner( 1207): OK. alarm_alert is already exist in setting DB.
D/MediaScanner( 1207): system notification_sound  : K_Oprkltf5wgg
D/TP/MmsSmsProvider( 1241): deleteConversation threadId: 9223372036854775806
D/SurfaceWidgetView( 1247): destroyHardwareResources():1125992144
D/MessagingNotification( 1727): remove alarm
I/SELinux ( 2711): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2711):  
I/SELinux ( 2711):  
I/SELinux ( 2711): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2711): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2711): >>>>> Normal User
E/dalvikvm( 2711): >>>>> com.example.hello [ userId:0 | appId:10180 ]
E/SELinux ( 2711): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/MediaScanner( 1207): OK. notification_sound is already exist in setting DB.
W/dalvikvm( 2698): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
D/TP/MmsSmsProvider( 1241): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/Mms/MessagingNotification( 1727): updateAllHistoryAsRead()
D/TP/MmsSmsProvider( 1241): delete threadId: 9223372036854775806
D/MediaScanner( 1207): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/TimaKeyStoreProvider( 2711): in addTimaSignatureService
D/Launcher.Model( 1247): reloadBadges entered.
D/TimaKeyStoreProvider( 2711): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2711): Added TimaKesytore provider
D/MediaScanner( 1207): OK. ringtone is already exist in setting DB.
D/MediaScanner( 1207): system ringtone_2  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1207): OK. ringtone_2 is already exist in setting DB.
D/TP/MmsSmsProvider( 1241): need read changed broadcast:false
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/LockPatternUtils( 1067): isPcwEnable = null
D/MediaScanner( 1207): system notification_sound_2  : K_Oprkltf5wgg
D/SafetyAssuranceAppFeatures( 2698): init start
I/SafetyAssuranceAppFeatures( 2698): mLoadBaiduMap:false
I/SafetyAssuranceAppFeatures( 2698): mFeatureEnableMultiSim true
D/MediaScanner( 1207): OK. notification_sound_2 is already exist in setting DB.
D/SafetyAssuranceAppFeatures( 2698): init end
D/Mms/Conversation( 1727): deleteTempConversation(),deleted=0
D/SafetyAssuranceReceiver( 2698): onReceive
I/SafetyAssuranceApp( 2698): Acquire WL
D/MediaScannerService( 1207): !@done scanning volume internal
D/MediaScannerService( 1207): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=2711, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=2711, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
,D/SafetyAssuranceConfig( 2698): getAppState : 1
D/SafetyAssuranceReceiver( 2698): onReceive - action:android.intent.action.BOOT_COMPLETED, currentAppState:1
D/SafetyAssuranceReceiver( 2698): Init App state
D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
V/WebViewChromium( 2711): Binding Chromium to the background looper Looper (main, tid 1) {422aa108}
I/chromium( 2711): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 2711): Initializing chromium process, renderers=0
D/MediaProvider( 1207): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter finished
,I/HarmonyEASService(  729): Updating for all 1
,D/SafetyAssuranceConfig( 2698): setAppState : 1
W/BackupManagerService(  729): dataChanged but no participant pkg='com.android.providers.settings' uid=10050
,D/SafetyAssuranceApp( 2698): topActivity's name is=.MainActivity
,W/chromium( 2711): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/SafetyAssuranceApp( 2698): Release WL
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,D/MediaScanner( 1207): Prescan. DB items number : 20 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/Adreno-EGL( 2711): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2711): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2711): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2711): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2711): Remote Branch: 
I/Adreno-EGL( 2711): Local Patches: 
I/Adreno-EGL( 2711): Reconstruct Branch: 
,D/dalvikvm(  729): GC_EXPLICIT freed 3158K, 20% free 22598K/28080K, paused 8ms+17ms, total 191ms
,D/SmsProvider( 1241): Update uri=content://sms/outbox, match=8
,I/NetworkStatusReceiver( 1241): action: android.intent.action.BOOT_COMPLETED
,D/TP/MmsSmsProvider( 1241): need read changed broadcast:false
D/Mms/SmsReceiverService( 1727): sendFirstQueuedMessage()
,D/Mms/SmsReceiverService( 1727): [SIM-1]sendFirstQueuedMessage()
,D/Mms/MessagingNotification( 1727): [end]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 1727): sDisableVibrateForCamera = false
,V/MediaScanner( 1207): processDirectory :  /storage/emulated/0
D/MediaScanner( 1207): Skipping:
,D/MediaScanner( 1207): 7klwibgf7fvntblfd7(75ebcf7
,D/NearbySettings( 1320): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1320): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 1320): MountReceiver.onReceive - Create mPrefHandler
D/Mms/MessagingNotification( 1727): isBlockingModeEnable() = false
D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,D/Mms/TelephonyPermission( 1727): isDefault true
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.ssrm.u.i:-1 com.android.server.ssrm.ai.run:-1 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 
,V/NearbySettings( 1320): MountReceiver.mPrefHandler - 7002
,I/iu.UploadsManager( 1644): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,I/dalvikvm( 2711): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2711): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2711): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2711): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2711): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 2711): VFY: replacing opcode 0x6e at 0x0008
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/NearbySettings( 1320): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1320): MountReceiver.onReceive - Internal Path
,D/PowerManagerService(  729): [s] UserActivityState : 1 -> 0
I/PowerManagerService(  729): [PWL] On : 0 (39325 ms ago)
I/PowerManagerService(  729): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  729): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1067, ws=null) (elapsedTime=1338)
D/DisplayPowerController(  729): animation target = 4 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/MediaScanner( 1207): Skipping:
D/MediaScanner( 1207): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,D/PowerManagerService(  729): [s] mDisplayPowerControllerCallbacks : onStateChanged()
W/dalvikvm( 2711): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2711): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2711): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2711): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2711): VFY: replacing opcode 0x6f at 0x001a
D/lights  (  729): lcd : 6 +
V/MediaScanner( 1207): processDirectory :  /storage/extSdCard
W/MediaScanner( 1207): Error opening directory, reason : Permission denied.
W/MediaScanner( 1207): 7klwibgf7fxlKdCbid7
W/dalvikvm( 2711): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2711): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2711): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2711): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2711): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2711): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2711): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2711): CordovaWebView is running on device made by: samsung
D/TP/MmsSmsProvider( 1241): match 200:Elapsed time : 0.941 ms
,D/lights  (  729): lcd : 6 -
,D/lights  (  729): lcd : 4 +
D/RampAnimator(  729): Light Animator Finished currentValue=4
,E/File    ( 1207): fail readDirectory() errno=2
,V/MediaScanner( 1207): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@426aa7c0
,V/MediaScanner( 1207): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@426aa7c0
V/MediaScanner( 1207):  prescan time: 97ms (DB items: 20)
V/MediaScanner( 1207):     scan time: 45ms (Caching mode: true), (makeEntry time: 38ms ~84%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 1ms ~2%)
V/MediaScanner( 1207): postscan time: 27ms (bulkDeleter : 0), (delete DeadThumbnail time : 5ms)
V/MediaScanner( 1207):    total time: 169ms
V/MediaScanner( 1207): checked files: 3  directories : 17  (I: 0, U: 0)
,I/AccessibilityManagerService(  729): setmDNIeNegative (false)
D/MediaScannerService( 1207): !@done scanning volume external
D/MediaScannerService( 1207): send command to ssrm : REQ_DROP_CACHE
,D/lights  (  729): lcd : 4 -
,D/BadgeProvider( 1340): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/iu.UploadsManager( 1644): End new media; added: 0, uploading: 0, time: 100 ms
D/SSRMv2:SIOP(  729): SIOP:: AP = 330, Delta = 10
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=15 createSurf (720x1280),1 flag=404, NainActivit
D/BadgeProvider( 1340): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): sendNotify, [notify] : null
D/BadgeProvider( 1340): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1340): update, [UpdateCount] : 1
,D/Launcher.Model( 1247): reloadBadges entered.
,D/Mms/MessagingNotification( 1727): setBadgeCount(), count=0
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/MessagingNotification( 1727): remove alarm
,I/HWUI    ( 2711): EGLImpl-HWUI Protected EGL context created
,D/Mms/MessagingNotification( 1727): updateAllHistoryAsRead()
,D/Mms/SmsReceiverService( 1727): [end]    handleBootCompleted()
,D/OpenGLRenderer( 2711): Enabling debug mode 0
,W/AwContents( 2711): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetView( 1247): destroyHardwareResources():1125992144
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  729): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SurfaceFlinger(  247): id=14 Removed iello (9/13)
I/SurfaceFlinger(  247): id=14 Removed iello (-2/13)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=7 Removed Mauncher (7/12)
I/SurfaceFlinger(  247): id=7 Removed Mauncher (-2/12)
I/SurfaceFlinger(  247): id=13 Removed CatteryCove (7/11)
,I/SurfaceFlinger(  247): id=13 Removed CatteryCove (-2/11)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
E/ActivityThread( 1843): Performing stop of activity that is not resumed: {com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover}
E/ActivityThread( 1843): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover}
E/ActivityThread( 1843): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3536)
E/ActivityThread( 1843): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3623)
E/ActivityThread( 1843): 	at android.app.ActivityThread.access$1200(ActivityThread.java:172)
E/ActivityThread( 1843): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1335)
E/ActivityThread( 1843): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1843): 	at android.os.Looper.loop(Looper.java:146)
E/ActivityThread( 1843): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/ActivityThread( 1843): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread( 1843): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread( 1843): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/ActivityThread( 1843): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/ActivityThread( 1843): 	at dalvik.system.NativeStart.main(Native Method)
,W/Settings( 1320): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SettingSearch/SearchIntentReceiver( 1320): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1320): search setting db init!!
,W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:40 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:60 
,I/SettingSearch/SearchIntentReceiver( 1320): BOOT_COMPLETED call InitSerachDBThread thread start!
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,W/BackupManagerService(  729): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
,I/SELinux ( 2763): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2763):  
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/BootupListener( 1241): mPendingNetworkManualSelection : false
,I/ManualSelectionReceiver( 1241): onReceive : Intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.phone/.ManualSelectionReceiver (has extras) }
,I/chromium( 2711): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/SELinux ( 2767): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2767):  
,D/SensorService(  729):   -0.1 -0.1 9.6
,I/SELinux ( 2763): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2763):  
I/SELinux ( 2763):  
,I/SELinux ( 2763): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2763): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2763): >>>>> Normal User
,E/dalvikvm( 2763): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10160 ]
,E/SELinux ( 2763): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/chromium( 2711): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/TimaKeyStoreProvider( 2763): in addTimaSignatureService
I/SELinux ( 2767): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2767):  
I/SELinux ( 2767):  
,I/SELinux ( 2767): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2767): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2767): >>>>> Normal User
,E/dalvikvm( 2767): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
D/TimaKeyStoreProvider( 2763): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2763): Added TimaKesytore provider
E/SELinux ( 2767): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/libGLESv2( 2711): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
E/libGLESv2( 2711): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,D/TimaKeyStoreProvider( 2767): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2767): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2767): Added TimaKesytore provider
,I/chromium( 2711): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 2711): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=2763, uid=10160 requires android.permission.INTERACT_ACROSS_USERS
,D/JsMessageQueue( 2711): Set native->JS mode to OnlineEventsBridgeMode
,I/DBG_DM  ( 2767): [][Line:95][onCreate] 
E/DBG_DM  ( 2767): BootingfileStream is null
,E/DBG_DM  ( 2767): xdmCreateBootingFilestream
,I/DBG_DM  ( 2767): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DM  ( 2767): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
,I/DBG_DM  ( 2767): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
,I/DBG_DM  ( 2767): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
,E/libGLESv2( 2711): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,E/libGLESv2( 2711): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,D/dalvikvm( 2711): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x425d0e98
,I/DBG_DM  ( 2767): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
,I/DBG_DM  ( 2767): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
,I/DBG_DM  ( 2767): [3.19.140541][Line:36][onCreate] myUserId : 0
,I/DBG_DM  ( 2767): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 0
,I/DBG_DM  ( 2767): [3.19.140541][Line:2702][xdmdbsqlGetDownloadPostponeStatus] xdbsqlGetDownloadPostponeStatus : 0
,I/DBG_DM  ( 2767): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
,I/DBG_DM  ( 2767): [3.19.140541][Line:99][onCreate] DMApplication NOT Start !
,I/DBG_DM  ( 2767): [3.19.140541][Line:139][onReceive] android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1067): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1067): into the SAFE_MODE_ACTION
,D/OverheatReceiver( 1067): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1067): isSafeMode = false
,D/dalvikvm( 2711): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x425d0e98
D/jxcore_app_log( 2711): JniHelper::setJavaVM(0x416b4528), pthread_self() = 1920304592
,D/JX-Cordova( 2711): jxcore cordova android initializing
,D/LocationManagerService(  729): getProviders()=[passive]
,E/Tethering(  729): No numeric data
,E/Tethering(  729): No numeric data
,E/Tethering(  729): No numeric data
,E/Tethering(  729): No numeric data
I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
,E/Tethering(  729): No numeric data
,E/Tethering(  729): No numeric data
I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
,I/ContactAccountLoggerTas( 2136): canRun() : Opted Out
,I/Velvet.VelvetFactory( 2136): refreshing internal icing corpora
,I/ActivityManager(  729): Waited long enough for: ServiceRecord{42f87988 u0 com.google.android.gms/.gcm.GcmService}
,I/Velvet.VelvetFactory( 2136): checking for language pack updates
W/jxcore-log( 2711): Initializing JXcore engine
,W/jxcore-log( 2711): JXcore engine is ready
,W/jxcore-log( 2711): Starting JXcore engine
,E/Tethering(  729): No numeric data
,E/Tethering(  729): No numeric data
,E/Tethering(  729): No numeric data
I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
,E/Tethering(  729): No numeric data
,V/NFC     ( 1320): this device does not have NFC support
,V/NFC     ( 1320): this device does not have NFC support
,V/NFC     ( 1320): this device does not have NFC support
,V/NFC     ( 1320): this device does not have NFC support
I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
,W/dalvikvm( 2136): method Lcom/google/android/search/core/state/QueryState;.a incorrectly overrides package-private method with same name in Lcfl;
,V/VibratorService(  729): hasVibrator - useVibetonz: false
,D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@9
,D/WifiDisplayAdapter(  729): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  729): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService(  729): getStreamVolume 3 index 0
,I/MediaRouter( 2136): Found default route: MediaRouter.RouteInfo{ uniqueId=android/kb:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/WifiDisplayAdapter(  729): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/Velvet.VelvetFactory( 2136): refreshing search history.
,I/SELinux ( 2809): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2809):  
,D/dalvikvm(  248): GC_EXPLICIT freed 44K, 51% free 9504K/19332K, paused 2ms+3ms, total 27ms
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9504K/19332K, paused 2ms+3ms, total 20ms
I/SELinux ( 2809): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2809):  
I/SELinux ( 2809):  
,I/SELinux ( 2809): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2809): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2809): >>>>> Normal User
,E/dalvikvm( 2809): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 2809): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9504K/19332K, paused 2ms+2ms, total 21ms
,D/TimaKeyStoreProvider( 2809): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2809): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2809): Added TimaKesytore provider
,V/WebViewChromium( 2136): Binding Chromium to the main looper Looper (main, tid 1) {422aa7f8}
,I/chromium( 2136): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 2136): Initializing chromium process, renderers=0
,W/jxcore-log( 2711): Platform android
W/jxcore-log( 2711): 
,W/jxcore-log( 2711): Process ARCH arm
W/jxcore-log( 2711): 
,W/chromium( 2136): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 2136): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2136): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2136): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2136): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2136): Remote Branch: 
I/Adreno-EGL( 2136): Local Patches: 
I/Adreno-EGL( 2136): Reconstruct Branch: 
,I/LockPatternUtils( 1320): isSmartCardAuthenticationAvailable: false
,W/GAV2    ( 2136): Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/jxcore-log( 2711): JXcore Cordova bridge is ready!
I/jxcore-log( 2711): 
,W/jxcore-log( 2711): JXcore engine is started
,W/GAV2    ( 2136): Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/Search.GservicesUpdateTask( 2136): Updating Gservices keys
,I/ContactAccountLoggerTas( 2136): canRun() : Opted Out
,D/UserAnalysis.PlaceProvider( 2809): Create SecureDbHelper
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=2809, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 2809): Create SecureDbHelper
,I/SQLiteSecureOpenHelper( 2809): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2809): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2809): Open Place.db in secure mode
,E/jxcore-log( 2711): >> samsung-SM-G800H
E/jxcore-log( 2711): 
,I/jxcore-log( 2711): Total memory 1454641152
I/jxcore-log( 2711): 
I/jxcore-log( 2711): Free memory 446353408
I/jxcore-log( 2711): 
I/jxcore-log( 2711): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2711): 
,I/jxcore-log( 2711): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2711): 
,I/jxcore-log( 2711): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2711): 
,I/jxcore-log( 2711): Size 720 1280
I/jxcore-log( 2711): 
,I/jxcore-log( 2711): Screen Brightness 134
I/jxcore-log( 2711): 
,E/jxcore-log( 2711): Dummy Error Log.
E/jxcore-log( 2711): 
,I/ContactAccountLoggerTas( 2136): canRun() : Opted Out
,E/SMD     (  241): DCD ON
,I/ContactAccountLoggerTas( 2136): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2136): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2136): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2136): canRun() : Opted Out
,I/IcingCorporaProvider( 2136): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,I/ContactAccountLoggerTas( 2136): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2136): canRun() : Opted Out
V/VibratorService(  729): hasVibrator - useVibetonz: false
,I/SQLiteSecureOpenHelper( 2809): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2809): ...getDatabaseLocked(b,b,pwd)
,I/SQLiteSecureOpenHelper( 2809): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2809): getDatabaseLocked(b,b,pwd)...
D/AmoledAdjustTimer(  729): prevTemp = 286, currTemp = 288, prevStep = 4, currStep = 4
,D/dalvikvm( 2136): GC_CONCURRENT freed 6430K, 42% free 11255K/19332K, paused 5ms+6ms, total 82ms
D/dalvikvm( 2136): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 2136): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 2136): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/UserAnalysis.CarAnalyzer( 2809): Create SecureDbHelper
,D/dalvikvm( 2136): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 2136): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/SQLiteSecureOpenHelper( 2809): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2809): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2809): Open Place.db in secure mode
,I/dalvikvm( 1644): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 1644): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1644): VFY: replacing opcode 0x6e at 0x002b
I/dalvikvm( 1308): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.n.a
W/dalvikvm( 1308): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1308): VFY: replacing opcode 0x6e at 0x001c
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 2136): OkHttp exception
,I/ContactAccountLoggerTas( 2136): canRun() : Opted Out
,D/dalvikvm( 1644): Trying to load lib /data/app-lib/com.google.android.gms-1/libAppDataSearch.so 0x425e0968
,I/dalvikvm( 1308): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.o.a
W/dalvikvm( 1308): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 1308): VFY: replacing opcode 0x6e at 0x001f
,D/dalvikvm( 1644): Added shared lib /data/app-lib/com.google.android.gms-1/libAppDataSearch.so 0x425e0968
,D/dalvikvm( 1644): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libAppDataSearch.so 0x425e0968, skipping init
,I/LockPatternUtils( 1320): isSmartCardAuthenticationAvailable: false
,D/dalvikvm( 1308): GC_CONCURRENT freed 2003K, 45% free 10713K/19332K, paused 4ms+11ms, total 37ms
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SQLiteSecureOpenHelper( 2809): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2809): ...getDatabaseLocked(b,b,pwd)
,I/GoogleURLConnFactory( 1308): Using platform SSLCertificateSocketFactory
,I/Icing   ( 1644): Storage manager: low false usage 1.39MB avail 9.54GB capacity 10.16GB
I/dalvikvm( 1308): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.r.a
W/dalvikvm( 1308): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 1308): VFY: replacing opcode 0x6e at 0x0041
,I/dalvikvm( 1644): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.b.g.a
,W/dalvikvm( 1644): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1644): VFY: replacing opcode 0x6e at 0x0029
,I/SELinux ( 2851): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2851):  
,E/dalvikvm( 1308): Could not find class 'android.net.Network', referenced from method com.google.android.gms.auth.be.k.a
W/dalvikvm( 1308): VFY: unable to resolve check-cast 195 (Landroid/net/Network;) in Lcom/google/android/gms/auth/be/k;
,D/dalvikvm( 1308): VFY: replacing opcode 0x1f at 0x0149
,I/GLSUser ( 1308): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/SELinux ( 2851): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2851):  
I/SELinux ( 2851):  
,I/SELinux ( 2851): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2851): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2851): >>>>> Normal User
,E/dalvikvm( 2851): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 2851): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2851): in addTimaSignatureService
,I/GoogleURLConnFactory( 1308): Using platform SSLCertificateSocketFactory
,D/TimaKeyStoreProvider( 2851): Cannot add TimaSignature Service, License check Failed
I/dalvikvm( 1308): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1308): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1308): VFY: replacing opcode 0x6e at 0x0033
,D/ActivityThread( 2851): Added TimaKesytore provider
,I/System.out( 1308): Thread-53(HTTPLog):isShipBuild true
,I/System.out( 1308): Thread-53(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/GLSUser ( 1308): [GLSUser] IOException in getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> exception: Unable to resolve host "android.clients.google.com": No address associated with hostname)
,I/GLSUser ( 1308): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> status: NETWORK_ERROR)
,I/GLSUser ( 1308): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1308): gms.StatusHelper Status from wire: NetworkError status: NETWORK_ERROR
,W/Search.LoginHelper( 2136): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/jxcore-log( 2711): getBuffer is called!!!!
I/jxcore-log( 2711): 
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1308): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1308): [GLSUser] IOException in getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> exception: Unable to resolve host "android.clients.google.com": No address associated with hostname)
,I/GLSUser ( 1308): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> status: NETWORK_ERROR)
I/GLSUser ( 1308): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1308): gms.StatusHelper Status from wire: NetworkError status: NETWORK_ERROR
,W/Search.LoginHelper( 2136): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1308): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/sCloudBackupApp( 2851): sCloudBackupApp Version Info : 3.7.3.KK_APP
,W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:129 <bottom of call stack> 
I/GLSUser ( 1308): [GLSUser] IOException in getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> exception: Unable to resolve host "android.clients.google.com": No address associated with hostname)
I/GLSUser ( 1308): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> status: NETWORK_ERROR)
I/GLSUser ( 1308): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1308): gms.StatusHelper Status from wire: NetworkError status: NETWORK_ERROR
I/SettingSearch/SearchIntentReceiver( 1320): InitSerachDBThread thread end!
W/Search.LoginHelper( 2136): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/PackageManager(  729): [MSG] MCS_UNBIND
I/PackageManager(  729): calling disconnectService()
,D/PackageManager(  729): Trying to unbind to DefaultContainerService
,I/SELinux ( 2867): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2867):  
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1308): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/SELinux ( 2867): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2867):  
I/SELinux ( 2867):  
,I/SELinux ( 2867): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2867): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2867): >>>>> Normal User
,E/dalvikvm( 2867): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 2867): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/GLSUser ( 1308): [GLSUser] IOException in getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> exception: Unable to resolve host "android.clients.google.com": No address associated with hostname)
,I/GLSUser ( 1308): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> status: NETWORK_ERROR)
I/GLSUser ( 1308): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1308): gms.StatusHelper Status from wire: NetworkError status: NETWORK_ERROR
,W/Search.LoginHelper( 2136): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/TimaKeyStoreProvider( 2867): in addTimaSignatureService
,I/ContactAccountLoggerTas( 2136): canRun() : Opted Out
,D/TimaKeyStoreProvider( 2867): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2867): Added TimaKesytore provider
,I/dalvikvm( 1644): Total arena pages for JIT: 11
,I/dalvikvm( 1644): Total arena pages for JIT: 12
I/dalvikvm( 1644): Total arena pages for JIT: 13
,I/dalvikvm( 1644): Total arena pages for JIT: 14
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=2867, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,I/Icing   ( 1644): updateResources: need to parse f{com.google.android.gms}
,I/SELinux ( 2881): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2881):  
,W/BackupManagerService(  729): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/BackupManagerService(  729): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/SELinux ( 2881): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2881):  
I/SELinux ( 2881):  
,I/SELinux ( 2881): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2881): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2881): >>>>> Normal User
E/dalvikvm( 2881): >>>>> com.wssnps [ userId:0 | appId:1000 ]
,E/SELinux ( 2881): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2881): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2881): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2881): Added TimaKesytore provider
,D/NPS_WSSNPS( 2881): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2881): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.wssnps.smlNpsReceiver.onReceive:380 android.app.ActivityThread.handleReceiver:2698 
D/NPS_WSSNPS( 2881): [] Service onCreate!!
,I/SELinux ( 2893): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2893):  
,I/SELinux ( 2893): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2893):  
I/SELinux ( 2893):  
,I/SELinux ( 2893): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2893): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2893): >>>>> Normal User
E/dalvikvm( 2893): >>>>> com.samsung.android.app.accesscontrol [ userId:0 | appId:10064 ]
,E/SELinux ( 2893): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2893): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2893): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2893): Added TimaKesytore provider
,D/dalvikvm(  729): GC_EXPLICIT freed 1651K, 20% free 22577K/28080K, paused 5ms+10ms, total 117ms
,D/NPS_WSSNPS( 2881): [] NpsServiceTask Start
,I/NPS_WSSNPS( 2881): [44.140541] loadCryptionkeyLibrary
,I/NPS_WSSNPS( 2881): [44.140541] FirstLoad Or Not Exist
,D/dalvikvm( 2881): Trying to load lib /data/data/com.wssnps/files/libCryptionkey.so 0x425cd920
,D/dalvikvm( 2881): Added shared lib /data/data/com.wssnps/files/libCryptionkey.so 0x425cd920
,D/NPS_WSSNPS( 2881): [44.140541] smlDBHelper
,I/NPS_WSSNPS( 2881): [44.140541] AsyncBulkFlagCheck
,I/NPS_WSSNPS( 2881): [44.140541] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 2881): [44.140541] IsRemain_Asyncing nothing
,D/NPS_WSSNPS( 2881): [44.140541] Service onDestroy
,W/ContextImpl( 2881): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 com.wssnps.smlNpsService$1.run:108 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/NPS_WSSNPS( 2881): [44.140541] smlBRConfigurationDelete
I/NPS_WSSNPS( 2881): [44.140541] smlBRMessageDelete
I/NPS_WSSNPS( 2881): [44.140541] smlBREmailDelete
I/NPS_WSSNPS( 2881): [44.140541] smlBRNetworkDelete
I/NPS_WSSNPS( 2881): [44.140541] smlBRCallLogDelete
I/Icing   ( 1644): Internal init done: storage state 0
I/NPS_WSSNPS( 2881): [44.140541] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 2881): [44.140541] smlBRPenMemoMDelete
I/NPS_WSSNPS( 2881): [44.140541] smlBRSMemoDelete
I/NPS_WSSNPS( 2881): [44.140541] cpuBooster release : false
I/Icing   ( 1644): Post-init done
D/NPS_WSSNPS( 2881): [44.140541] dsServerSocket close
,I/SELinux ( 2912): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2912):  
,I/SELinux ( 2912): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2912):  
I/SELinux ( 2912):  
,I/SELinux ( 2912): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2912): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2912): >>>>> Normal User
,E/dalvikvm( 2912): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
,E/SELinux ( 2912): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2912): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2912): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2912): Added TimaKesytore provider
,D/FileShare-Server( 2912): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/SELinux ( 2930): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2930):  
,D/dalvikvm( 1644): GC_CONCURRENT freed 6371K, 42% free 11236K/19332K, paused 4ms+9ms, total 47ms
I/ActivityManager(  729): Killing 1287:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #43
,I/SELinux ( 2930): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2930):  
I/SELinux ( 2930):  
,I/SELinux ( 2930): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2930): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2930): >>>>> Normal User
,E/dalvikvm( 2930): >>>>> com.sec.android.nearby.mediaserver [ userId:0 | appId:10070 ]
,E/SELinux ( 2930): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2930): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2930): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2930): Added TimaKesytore provider
,I/AllShare(ASF-DMSLIB)( 2930): DMSReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,W/BackupManagerService(  729): dataChanged but no participant pkg='com.android.providers.settings' uid=10070
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/IcingCorporaProvider( 2136): UpdateCorporaTask done [took 1605 ms] updated apps [took 1605 ms] 
,I/SELinux ( 2945): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2945):  
I/ActivityManager(  729): Killing 1340:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/SELinux ( 2945): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2945):  
I/SELinux ( 2945):  
,I/SELinux ( 2945): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2945): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2945): >>>>> Normal User
,E/dalvikvm( 2945): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 2945): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2945): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2945): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2945): Added TimaKesytore provider
,W/ContextImpl( 2945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:61 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2958): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2958):  
,I/SELinux ( 2958): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2958):  
I/SELinux ( 2958):  
,I/SELinux ( 2958): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2958): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2958): >>>>> Normal User
,E/dalvikvm( 2958): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
,E/SELinux ( 2958): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2958): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2958): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2958): Added TimaKesytore provider
,D/BluetoothBDAdrressReceiver( 2958): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2958): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
W/ContextImpl( 2958): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2970): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2970):  
,D/BluetoothBDTestService( 1241): onCreate()
E/BluetoothBDTestService( 1241): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
,E/BluetoothBDTestService( 1241): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1241): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/ActivityManager(  729): Killing 1273:com.android.printspooler/u0a144 (adj 15): empty #43
,I/SELinux ( 2970): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2970):  
I/SELinux ( 2970):  
,I/SELinux ( 2970): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2970): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2970): >>>>> Normal User
,E/dalvikvm( 2970): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 2970): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 2970): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2970): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2970): Added TimaKesytore provider
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=2970, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 2982): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2982):  
,I/ActivityManager(  729): Killing 1774:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2945): Resource data:2131165197
,D/SensorService(  729):   -0.1 -0.1 9.6
I/SELinux ( 2982): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2982):  
I/SELinux ( 2982):  
,I/SELinux ( 2982): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2982): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2982): >>>>> Normal User
,E/dalvikvm( 2982): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 2982): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2945): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2945): Resource data:2131165194
I/AMMetaDataParserService( 2945): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 2982): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2982): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2982): Added TimaKesytore provider
,I/ActivityManager(  729): Waited long enough for: ServiceRecord{42ff4818 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/AMMetaDataParserService( 2945): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,I/AMMetaDataParserService( 2945): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
E/PersonaManagerService(  729): returning null in  getPersonasForUser
,I/SELinux ( 2994): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2994):  
I/ActivityManager(  729): Killing 1787:com.sec.modem.settings/1000 (adj 15): empty #43
,D/dalvikvm(  248): GC_EXPLICIT freed 47K, 51% free 9504K/19332K, paused 2ms+3ms, total 27ms
,I/AMMetaDataParserService( 2945): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,I/SELinux ( 2994): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2994):  
I/SELinux ( 2994):  
,I/SELinux ( 2994): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2994): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2994): >>>>> Normal User
,E/dalvikvm( 2994): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9504K/19332K, paused 2ms+3ms, total 19ms
,E/SELinux ( 2994): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2994): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2994): Cannot add TimaSignature Service, License check Failed
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9504K/19332K, paused 2ms+2ms, total 19ms
,D/ActivityThread( 2994): Added TimaKesytore provider
,I/AMMetaDataParserService( 2945): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
V/AlarmManager(  729): waitForAlarm result :4
,V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
I/AMMetaDataParserService( 2945): Resource data:2131165194
I/AMMetaDataParserService( 2945): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/AMMetaDataParserService( 2945): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,I/AMMetaDataParserService( 2945): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,I/AMMetaDataParserService( 2945): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
W/BackupManagerService(  729): dataChanged but no participant pkg='com.android.providers.settings' uid=10084
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/AMMetaDataParserService( 2945): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,I/AMMetaDataParserService( 2945): Resource data:2131165195
I/AMMetaDataParserService( 2945): getResourceName:com.sec.android.gallery3d:xml/device_filter
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2945): Resource data:2131165204
I/AMMetaDataParserService( 2945): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2945): Resource data:2131165204
I/AMMetaDataParserService( 2945): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2945): Resource data:2131165204
I/AMMetaDataParserService( 2945): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 2945): getResourceTypeNamexml
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2945): Resource data:2131099676
,I/AMMetaDataParserService( 2945): getResourceName:com.android.mms:xml/spellscroll
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/AMMetaDataParserService( 2945): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2945): Resource data:2131099648
,I/AMMetaDataParserService( 2945): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/AMMetaDataParserService( 2945): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 3007): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3007):  
I/ActivityManager(  729): Killing 1799:com.sec.tcpdumpservice/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2945): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2945): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
I/SELinux ( 3007): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3007):  
I/SELinux ( 3007):  
,I/SELinux ( 3007): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3007): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3007): >>>>> Normal User
,E/dalvikvm( 3007): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
,E/SELinux ( 3007): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3007): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3007): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3007): Added TimaKesytore provider
,I/AMMetaDataParserService( 2945): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2945): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2945): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2945): Resource data:2131099648
I/AMMetaDataParserService( 2945): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/SELinux ( 3019): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3019):  
I/ActivityManager(  729): Killing 1827:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,I/AMMetaDataParserService( 2945): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2945): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 3019): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3019):  
I/SELinux ( 3019):  
,I/SELinux ( 3019): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3019): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/AMMetaDataParserService( 2945): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
E/dalvikvm( 3019): >>>>> Normal User
,E/dalvikvm( 3019): >>>>> com.dropbox.android [ userId:0 | appId:10091 ]
,E/SELinux ( 3019): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 3019): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3019): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3019): Added TimaKesytore provider
,I/AMMetaDataParserService( 2945): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2945): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2945): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2945): Resource data:2131099648
,I/AMMetaDataParserService( 2945): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/AMMetaDataParserService( 2945): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2945): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3019): Setting receiver enabled: false
,I/AMMetaDataParserService( 2945): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/com.dropbox.sync.android.a( 3019): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/AMMetaDataParserService( 2945): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,E/SMD     (  241): DCD ON
,I/com.dropbox.sync.android.aa( 3019): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800H armeabi-v7a; en_US))
,I/AMMetaDataParserService( 2945): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,I/AMMetaDataParserService( 2945): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=3019, uid=10091 requires android.permission.INTERACT_ACROSS_USERS
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
I/AMMetaDataParserService( 2945): Resource data:2131099648
I/SELinux ( 3044): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3044):  
I/ActivityManager(  729): Killing 1747:com.sec.android.app.mt/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2945): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/SELinux ( 3044): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3044):  
I/SELinux ( 3044):  
,I/SELinux ( 3044): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3044): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 3044): >>>>> Normal User
,E/dalvikvm( 3044): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 3044): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3044): in addTimaSignatureService
,I/AMMetaDataParserService( 2945): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/TimaKeyStoreProvider( 3044): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3044): Added TimaKesytore provider
,I/AMMetaDataParserService( 2945): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2945): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=3044, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 3044): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 3044): ELMEngine.ELMEngine( context ).
,D/elm:14132( 3044): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 3044): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 3044): ElmAgentService : onCreate()
,D/elm:14132( 3044): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 3044): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:14132( 3044): BootCompletedState : startBootCompleted() call
,D/elm:14132( 3044): ModuleBase.resetCalllogAPIAlarm()
,I/AMMetaDataParserService( 2945): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 3069): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3069):  
,D/elm:14132( 3044): MDMBridge.getAllLicenseInfoFromSDK()
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/elm:14132( 3044): Get License : 0
,D/elm:14132( 3044): ElmAgentService : onDestroy().
I/ActivityManager(  729): Killing 1883:com.sec.phone/1001 (adj 15): empty #43
,I/AMMetaDataParserService( 2945): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
I/PowerManagerService(  729): [PWL] On : 0 (44326 ms ago)
I/PowerManagerService(  729): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  729): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1067, ws=null) (elapsedTime=6339)
,I/SELinux ( 3069): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3069):  
I/SELinux ( 3069):  
,I/SELinux ( 3069): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3069): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3069): >>>>> Normal User
,E/dalvikvm( 3069): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,E/SELinux ( 3069): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2945): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,D/TimaKeyStoreProvider( 3069): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3069): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3069): Added TimaKesytore provider
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2945): Resource data:2131099648
,I/AMMetaDataParserService( 2945): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/AMMetaDataParserService( 2945): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2945): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 3082): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3082):  
I/ActivityManager(  729): Killing 1991:com.google.android.configupdater/u0a3 (adj 15): empty #43
,I/AMMetaDataParserService( 2945): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/System.out( 3019): Thread-258(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/AMMetaDataParserService( 2945): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
I/SELinux ( 3082): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3082):  
I/SELinux ( 3082):  
,I/SELinux ( 3082): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/System.out( 3019): Thread-258(ApacheHTTPLog):isShipBuild true
,I/System.out( 3019): Thread-258(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/SELinux ( 3082): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3082): >>>>> Normal User
,E/dalvikvm( 3082): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,E/SELinux ( 3082): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/System.out( 3019): pool-4-thread-1 calls detatch()
,D/TimaKeyStoreProvider( 3082): in addTimaSignatureService
,I/AMMetaDataParserService( 2945): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/TimaKeyStoreProvider( 3082): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3082): Added TimaKesytore provider
,I/AMMetaDataParserService( 2945): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2945): Resource data:2131099648
I/AMMetaDataParserService( 2945): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/CameraApp( 3082): CameraApp.onCreate()... mFeature : null
I/testFeature( 3082): Feature.Feature(context)
I/testFeature( 3082): Feature.readInternalDefaultXml()
,I/testFeature( 3082): ResetFeatureValue
,I/AMMetaDataParserService( 2945): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
I/CameraFirmware_broadcast( 3082): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 3082): CameraApp.getAppFeature()...
,I/SELinux ( 3097): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3097):  
,I/ActivityManager(  729): Killing 2115:com.sec.dsm.system/1000 (adj 15): empty #43
I/AMMetaDataParserService( 2945): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2945): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/SELinux ( 3097): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3097):  
I/SELinux ( 3097):  
,I/SELinux ( 3097): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3097): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3097): >>>>> Normal User
,E/dalvikvm( 3097): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 3097): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3097): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3097): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3097): Added TimaKesytore provider
,I/AMMetaDataParserService( 2945): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2945): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/PackageIntentReceiver( 3097): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3097): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager(  729): Killing 2163:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2945): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2945): Resource data:2131099671
I/AMMetaDataParserService( 2945): getResourceName:com.android.mms:xml/searchable
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2945): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
,I/SELinux ( 3112): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3112):  
,I/SELinux ( 3112): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3112):  
I/SELinux ( 3112):  
,I/SELinux ( 3112): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3112): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3112): >>>>> Normal User
,E/dalvikvm( 3112): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
,E/SELinux ( 3112): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3112): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3112): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3112): Added TimaKesytore provider
,D/dalvikvm( 2945): GC_CONCURRENT freed 4985K, 35% free 12699K/19332K, paused 2ms+3ms, total 31ms
,D/dalvikvm( 2945): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2945): Resource data:2131165216
,I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/AMMetaDataParserService( 2945): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,I/AMMetaDataParserService( 2945): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.TimDataConnectionDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2945): Resource data:2131429159
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2945): Resource data:2131296695
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2945): Resource data:2131429159
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2945): Resource data:2131429144
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429144
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429144
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131297114
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ApnSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ApnSettingsTabActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=3112, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429146
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429146
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429168
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/mirror_link_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429159
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131296695
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429159
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131296695
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429144
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131297114
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429159
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131296695
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429159
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2945): Resource data:2131296695
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429159
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131296695
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429159
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131296695
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2945): Resource data:2131429159
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131296695
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429219
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2945): Resource data:2131429191
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429191
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429191
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2945): Resource data:2131429191
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429191
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/language_settings,
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429191
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131298419
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429191
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131298419
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429191
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131298419
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429176
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429176
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429173
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429173
,I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429172
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2945): Resource data:2131429172
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429182
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429173
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429186
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429186
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429173
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131297804
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429173
I/AMMetaDataParserService( 2945): getResour,ceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429228
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.users.UserOptions
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429128
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429128
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/application_settings
,I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429128
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/Babel   ( 3112): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3112): MmsConfig.loadMmsSettings
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429127
I/Babel   ( 3112): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
I/Babel   ( 3112): MmsConfig.loadFromDatabase
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429127
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429128
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429128
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/application_settings
,I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429127
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.HomeSettings
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429127
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429128
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429153
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429224
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.CarrierMatchSetting
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429224
,I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131296750
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2945): Resource data:2131429224
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429123
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/privacy_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429224
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131296750
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/security_settings_title
,I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429224
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131296750
,I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429187
,I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
E/Babel   ( 3112): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3112): MmsConfig.loadFromResources
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429187
E/Babel   ( 3112): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3112): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131298587
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429187
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131298587
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429191
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429180
,I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/driving_mode
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/Settings( 3112): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2945): Resource data:2131429223
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
D/dalvikvm( 3112): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3112): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3112): VFY: replacing opcode 0x62 at 0x000a
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
D/dalvikvm( 3112): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3112): VFY: unable to resolve instance field 46
D/dalvikvm( 3112): VFY: replacing opcode 0x54 at 0x005f
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429225
D/dalvikvm( 3112): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3112): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3112): VFY: replacing opcode 0x62 at 0x0047
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429159
D/dalvikvm( 3112): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 3112): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131296695
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429165
,D/dalvikvm( 3112): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426d6618
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429225
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429223
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2945): Resource data:2131297938
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429223
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131297938
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429161
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 2945): getResourceTypeNameid
,D/dalvikvm( 3112): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426d6618
D/dalvikvm( 3112): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426d6618, skipping init
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429163
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 2945): getResourceTypeNameid
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429167
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131296695
,D/dalvikvm( 3112): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426d6618
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429221
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429221
D/dalvikvm( 3112): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426d6618
V/JNIHelp ( 3112): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429119
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429217
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 2945): getResourceTypeNameid
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429224
,I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429224
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429159
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2945): Resource data:2131429173
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429208
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429286
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2945): Resource data:2131429224
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2945): Resource data:2131429201
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429185
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429185
,I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131299843
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/power_saving_mode_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429185
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429185
V/Babel   ( 3112): babel boot account: thalitester@gmail.com
,V/Babel   ( 3112): babel boot account: SMS
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ModePreview
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429222
I/ActivityManager(  729): Waited long enough for: ServiceRecord{430e88a8 u0 com.samsung.android.providers.context/.ContextService}
,I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/power_settings
,I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429186
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 2945): Resource data:1
W/ResourceType( 2945): No package identifier when getting name for resource number 0x00000001
W/System.err( 2945): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 2945): 	at android.content.res.Resources.getResourceName(Resources.java:3017)
W/System.err( 2945): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 2945): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
,W/System.err( 2945): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 2945): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2945): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 2945): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429199
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131301070
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429173
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131297804
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429203
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429193
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429194
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMeta,DataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429206
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131300118
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429196
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429260
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429197
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429291
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429228
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 2945): Resour,ce data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429199
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429199
I/SELinux ( 3137): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3137):  
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429199
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/pen_settings_menu
,I/ActivityManager(  729): Killing 2176:com.sec.kidsplat.installer/u0a158 (adj 15): empty #43
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429199
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.NetworkManagement
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.MultiSimCardManagerPreference
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.NetworkManagementSetting
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.DualHelpActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.DualSoundRingtoneSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.RingtoneSettingTabActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.IccLockTabSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429173
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.s,ettings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429285
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429172
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131301505
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429203
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429203
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131302910
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429179
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2130838248
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2945): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429216
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429209
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429209
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAlertDialogActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429177
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429212
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429213
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429153
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131302078
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429153
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131302078
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429153
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131302107
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429159
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429159
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429117
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/SELinux ( 3137): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3137):  
I/SELinux ( 3137):  
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/SELinux ( 3137): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429122
E/SELinux ( 3137): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
E/dalvikvm( 3137): >>>>> Normal User
E/dalvikvm( 3137): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429195
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131297804
E/SELinux ( 3137): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429151
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429204
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429204
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429195
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2130838300
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2945): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2130838300
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2945): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429202
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429202
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2945): Resource data:2131165381
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:xml/searchable
I/AMMetaDataParserService( 2945): getResourceTypeNamexml
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429124
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
D/dalvikvm( 3112): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426d6618
D/dalvikvm( 3112): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x426d6618
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
D/dalvikvm( 3112): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426d6618
D/dalvikvm( 3112): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x426d6618
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429187
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2945): Resource data:2131298587
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2945): getResourceTypeNamestring
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429198
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429258
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429220
D/TimaKeyStoreProvider( 3137): in addTimaSignatureService
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429220
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429276
D/TimaKeyStoreProvider( 3137): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429276
D/ActivityThread( 3137): Added TimaKesytore provider
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429148
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429242
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.KnoxSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429211
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2130838248
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2945): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2945): Resource data:2131429192
I/AMMetaDataParserService( 2945): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 2945): getResourceTypeNameid
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintOnehandGrip
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2945): Resource data:2131034120
I/AMMetaDataParserService( 2945): getResourceName:com.android.contacts:xml/searchable
I/AMMetaDataParserService( 2945): getResourceTypeNamexml
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
I/AMMetaDataParserService( 2945): Resource data:2131034113
I/AMMetaDataParserService( 2945): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
I/AMMetaDataParserService( 2945): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
I/ProviderInstaller( 3112): Installed default security provider GmsCore_OpenSSL
V/AlarmManager(  729): waitForAlarm result :4
V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager(  729): waitForAlarm result :4
V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/AMMetaDataParserService( 2945): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/SELinux ( 3153): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3153):  
I/ActivityManager(  729): Killing 2210:com.sec.factory/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2945): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/SELinux ( 3153): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3153):  
I/SELinux ( 3153):  
,I/SELinux ( 3153): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3153): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3153): >>>>> Normal User
,E/dalvikvm( 3153): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
,E/SELinux ( 3153): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2945): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,D/TimaKeyStoreProvider( 3153): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3153): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
D/ActivityThread( 3153): Added TimaKesytore provider
,I/AMMetaDataParserService( 2945): Resource data:2131034113
I/AMMetaDataParserService( 2945): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/AMMetaDataParserService( 2945): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/AMMetaDataParserService( 2945): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
W/ContextImpl( 3153): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 3153): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3153): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
,I/knox    ( 3153): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3153): KNOXAgentService : onCreate()
,D/knox    ( 3153): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 3153): KNOXAgentService. startJobThread() start
,D/knox    ( 3153): KNOXAgentService. JobThread()
,D/knox    ( 3153): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3153): KNOXAgentService. startJobThread() wait
,I/AMMetaDataParserService( 2945): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/SELinux ( 3168): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3168):  
,D/knox    ( 3153): mKnoxAgentEngine.ELMEngine( context , reStart:true).
,D/knox    ( 3153): KNOXAgentService : onDestroy().
D/knox    ( 3153): ELMEngine.ServiceHandler.handleMessage( DEFAULT ).
,D/knox    ( 3153): ModuleBase.cancelAllAlarmManageModule()
,I/AMMetaDataParserService( 2945): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 2945): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 2945): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 2945): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2945): Resource data:2131034112
I/AMMetaDataParserService( 2945): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/AMMetaDataParserService( 2945): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
I/SELinux ( 3168): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3168):  
I/SELinux ( 3168):  
,I/SELinux ( 3168): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3168): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3168): >>>>> Normal User
,E/dalvikvm( 3168): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
,E/SELinux ( 3168): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3168): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3168): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3168): Added TimaKesytore provider
,I/AMMetaDataParserService( 2945): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
,I/AMMetaDataParserService( 2945): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
,E/KnoxSetupWizardClient( 3168): isShipMode : 1
,I/KnoxSetupWizardClient( 3168): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 2945): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
,W/System.err( 3168): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 3168): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 3168): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 3168): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3168): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 3168): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
,W/System.err( 3168): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
W/System.err( 3168): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
W/System.err( 3168): 	at android.os.Parcel.readException(Parcel.java:1469)
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 2945,): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
I/AMMetaDataParserService( 2945): Resource data:2131034113
I/AMMetaDataParserService( 2945): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 2945): getResourceTypeNamexml
W/System.err( 3168): 	at android.os.Pa,rcel.readException(Parcel.java:1419)
W/System.err( 3168): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3168): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
D/ShortcutReceiver( 3168):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
W/System.err( 3168): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
W/System.err( 3168): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
I/yash    ( 3168): setDisableWidget>size:0
W/System.err( 3168): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
I/AMMetaDataParserService( 2945): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
I/SELinux ( 3181): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3181):  
I/ActivityManager(  729): Killing 2237:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2945): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/dalvikvm(  248): GC_EXPLICIT freed 47K, 51% free 9504K/19332K, paused 2ms+3ms, total 29ms
,I/SELinux ( 3181): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3181):  
I/SELinux ( 3181):  
,I/SELinux ( 3181): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3181): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3181): >>>>> Normal User
,E/dalvikvm( 3181): >>>>> com.LocalFota [ userId:0 | appId:10110 ]
,D/dalvikvm( 2945): GC_CONCURRENT freed 2271K, 37% free 12369K/19332K, paused 3ms+2ms, total 42ms
,I/AMMetaDataParserService( 2945): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,E/SELinux ( 3181): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9504K/19332K, paused 1ms+5ms, total 22ms
,D/TimaKeyStoreProvider( 3181): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3181): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3181): Added TimaKesytore provider
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9504K/19332K, paused 2ms+3ms, total 22ms
,I/AMMetaDataParserService( 2945): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2945): Resource data:2131034116
I/AMMetaDataParserService( 2945): getResourceName:com.android.contacts:xml/findo_searchable
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2945): Resource data:2131099668
,I/AMMetaDataParserService( 2945): getResourceName:com.sec.android.app.sbrowser:xml/searchable
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/AMMetaDataParserService( 2945): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 2945): Resource data:2131099650
I/AMMetaDataParserService( 2945): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=3181, uid=10110 requires android.permission.INTERACT_ACROSS_USERS
I/DBG_WSS_LF( 3181): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
I/DBG_WSS_LF( 3181): [20.0040.140326][Line:27][<init>] First call
I/AMMetaDataParserService( 2945): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,I/AMMetaDataParserService( 2945): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
,I/GAV2    ( 2136): Thread[GAThread,5,main]: No campaign data found.
,I/DBG_WSS_LF( 3181): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_WSS_LF( 3181): [20.0040.140326][Line:31][onReceive] *** boot complete ***
,I/DBG_WSS_LF( 3181): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
,I/DBG_WSS_LF( 3181): [20.0040.140326][Line:41][onReceive] nStatus : -1
,I/AMMetaDataParserService( 2945): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 2945): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/SELinux ( 3198): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3198):  
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/ActivityManager(  729): Killing 1699:com.fmm.dm/1000 (adj 15): empty #43
,I/GAv4-SVC( 1644): Google Analytics 8.3.01 is starting up.
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAutoDiscover
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2945): Resource data:2131099667
,I/AMMetaDataParserService( 2945): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/SELinux ( 3198): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3198):  
I/SELinux ( 3198):  
,I/SELinux ( 3198): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3198): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3198): >>>>> Normal User
E/dalvikvm( 3198): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
,I/AMMetaDataParserService( 2945): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559
,E/SELinux ( 3198): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3198): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3198): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3198): Added TimaKesytore provider
,I/AMMetaDataParserService( 2945): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558
,I/AMMetaDataParserService( 2945): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
,D/StatusChecker( 3198): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 2945): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
,I/SELinux ( 3215): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3215):  
,E/BluetoothManagerService(  729): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 2711): packageName : com.example.hello
,I/WifiManager( 2711): setWifiEnabled : false
,I/WifiService(  729): setWifiEnabled: false pid=2711, uid=10180
,I/ActivityManager(  729): Killing 2251:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
I/jxcore-log( 2711): ****TEST TOOK:  5071  ms ****
I/jxcore-log( 2711): 
I/jxcore-log( 2711): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2711): 
,I/AMMetaDataParserService( 2945): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
,I/SELinux ( 3215): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3215):  
I/SELinux ( 3215):  
,I/SELinux ( 3215): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3215): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3215): >>>>> Normal User
,E/dalvikvm( 3215): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10133 ]
,E/SELinux ( 3215): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2945): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
,D/TimaKeyStoreProvider( 3215): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3215): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3215): Added TimaKesytore provider
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
,I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2945): Resource data:2131099689
I/AMMetaDataParserService( 2945): getResourceName:com.android.email:xml/spellscroll
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2945): Resource data:2131099685
I/AMMetaDataParserService( 2945): getResourceName:com.android.email:xml/searchable
I/AMMetaDataParserService( 2945): getResourceTypeNamexml
I/AMMetaDataParserService( 2945): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 2945): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2945): getResourcePackageName:com.android.keyguard.layout
,I/AMMetaDataParserService( 2945): Resource data:2130903052
I/AMMetaDataParserService( 2945): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
I/AMMetaDataParserService( 2945): getResourceTypeNamelayout
I/AMMetaDataParserService( 2945): getResourcePackageName:assistant
I/AMMetaDataParserService( 2945): Resource data:2131034112
I/AMMetaDataParserService( 2945): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 2945): getResourceTypeNamexml
,I/AMMetaDataParserService( 2945): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,I/AMMetaDataParserService( 2945): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
,D/QuickConnect( 3215): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 2945): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,D/QuickConnect( 3215): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 3215): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
W/BackupManagerService(  729): dataChanged but no participant pkg='com.android.providers.settings' uid=10133
,I/ActivityManager(  729): Killing 2267:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #43
V/QuickConnect( 3215): SconnectManager.getInstance - () return existing instance null
W/ContextImpl( 3215): Implicit intents with startService are not safe: Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } android.content.ContextWrapper.startServiceAsUser:517 android.content.ContextWrapper.startServiceAsUser:517 com.samsung.android.sconnect.periph.PeriphStartReceiver.onReceive:30 
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/QuickConnect( 3215): PeriphService.onCreate - [START]
,I/SELinux ( 3234): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3234):  
,I/QuickConnect( 3215): PeriphService.onCreate - [START] USER_OWNER
,D/QuickConnect( 3215): PeriphService.setProcessForeground - Build.VERSION.SDK_INT = 19
,I/QuickConnect( 3215): PeriphService.setProcessForeground - true of JB_MR2 complete 
I/QuickConnect( 3215): PeriphService.setState - 0 >> 1
,V/QuickConnect( 3215): PeriphService.runService - 
,I/QuickConnect[1.1][2] ( 3215): SconnectManager.SconnectManager - initiate from com.samsung.android.sconnect.periph.PeriphService@425d5498
,I/QuickConnect[1.1][2] ( 3215): SconnectManager.SconnectManager - set getApplicationContext android.app.Application@425cd420
,D/QuickConnect[1.1][2] ( 3215): SconnectManager.registerBroadcast - --
,D/QuickConnect[1.1][2] ( 3215): SconnectManager.SconnectManager - REQUEST_ID :  1
,D/QuickConnect[1.1][2] ( 3215): ScanThread.ScanThread - created!
,V/QuickConnect[1.1][2] ( 3215): BluetoothHelper.BluetoothHelper - 
,I/SELinux ( 3234): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3234):  
I/SELinux ( 3234):  
,I/SELinux ( 3234): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3234): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3234): >>>>> Normal User
,E/dalvikvm( 3234): >>>>> com.sec.android.service.bezel [ userId:0 | appId:1000 ]
,E/SELinux ( 3234): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3234): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3234): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3234): Added TimaKesytore provider
,D/dalvikvm(  729): GC_EXPLICIT freed 1426K, 20% free 22715K/28080K, paused 4ms+11ms, total 135ms
,D/QuickConnect[1.1][2] ( 3215): BluetoothHelper.registerBluetoothAdapterReceiver - mIsBluetoothAdapterReceiver = false
,V/QuickConnect[1.1][2] ( 3215): BleHelper.BleHelper - Constructor
,D/BezelQuickConnect( 3234): BezelBroadcastReceiver - onReceive : android.intent.action.BOOT_COMPLETED
,D/BezelQuickConnect( 3234): BezelBroadcastReceiver - StartBezelInteractionService
,D/BezelQuickConnect( 3234): BezelManagerService - setProcessForeground, Build.VERSION.SDK_INT = 19
,I/BezelQuickConnect( 3234): BezelManagerService - setProcessForeground, true of JB_MR2 complete 
,D/BezelQuickConnect( 3234): BezelBroadcastReceiver - onReceive : Send to quickpanel - service.ENABLED
,V/PhoneStatusBar( 1067): onReceive: Intent { act=com.sec.android.sconnect.service.ENABLED flg=0x10 }mQconnectEnable = true
W/ContextImpl( 3234): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.android.service.bezel.BezelBroadcastReceiver.onReceive:40 android.app.ActivityThread.handleReceiver:2698 
D/STATUSBAR-PhoneStatusBar( 1067): showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
,E/NetworkSettingsReceiver( 1761): onReceive: android.intent.action.BOOT_COMPLETED
,E/QuickConnect[1.1][2] ( 3215): BleHelper.startScan - not isGattServiceReady. Try to BLE On calling addLeRadioReference()
,D/BluetoothRadioManager( 3215): addLeRadioReference: Add CB  com.samsung.android.sconnect.common.net.BleHelper$GattServiceStateChangeCallback@425e88c8
D/BluetoothRadioManager( 3215):  addRadioReference enabled = false
,D/BluetoothRadioManager( 3215):  BLE Radio count is : 1
D/BluetoothRadioManager( 3215): addLeRadioReference: isRadioEnabled() =  false
V/QuickConnect[1.1][2] ( 3215): BleHelper.mSearchWearable - true
,D/BluetoothManagerService(  729): foregroundUser: 0
,V/QuickConnect[1.1][2] ( 3215): UpnpHelper.UpnpHelper - 
,V/QuickConnect[1.1][2] ( 3215): JmdnsHelper.JmdnsHelper - Constructor
,V/QuickConnect[1.1][2] ( 3215): P2pHelper.P2pHelper - EXEC
,D/QuickConnect[1.1][2] ( 3215): p2pHelperWorkThread.p2pHelperWorkThread - created!
,E/BluetoothManagerService(  729): Package is exist.
,D/SensorService(  729):   -0.1 -0.1 9.6
W/BroadcastQueue(  729): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.android.calendar/.magazine.CalendarUpdateRelatedDataReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/SELinux ( 3251): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3251):  
,D/AndroidRuntime( 3228): 
D/AndroidRuntime( 3228): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3228): CheckJNI is OFF
,I/SELinux ( 3255): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3255):  
,D/AndroidRuntime( 3228): setted country_code = Poland
,D/AndroidRuntime( 3228): setted countryiso_code = PL
D/AndroidRuntime( 3228): setted sales_code = XEO
D/AndroidRuntime( 3228): readGMSProperty: start
,D/AndroidRuntime( 3228): readGMSProperty: already setted!!
D/AndroidRuntime( 3228): readGMSProperty: end
,D/AndroidRuntime( 3228): addProductProperty: start
,D/QuickConnect[1.1][2] ( 3215): WifiHelper.WifiHelper -  -- 
,D/dalvikvm( 3228): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3228): Added shared lib libjavacore.so 0x0
,I/SELinux ( 3251): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3251):  
I/SELinux ( 3251):  
,I/SELinux ( 3251): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3251): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3251): >>>>> Normal User
,E/dalvikvm( 3251): >>>>> com.sec.android.app.camera [ userId:0 | appId:10147 ]
D/dalvikvm( 3228): Trying to load lib libnativehelper.so 0x0
,D/dalvikvm( 3228): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3228): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/SELinux ( 3251): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3251): in addTimaSignatureService
,I/QuickConnect[1.1][2] ( 3215): CentralActionManager.CentralActionManager - EXEC
V/QuickConnect[1.1][2] ( 3215): BluetoothOppActionHelper.BluetoothOppActionHelper - 
,D/TimaKeyStoreProvider( 3251): Cannot add TimaSignature Service, License check Failed
I/SELinux ( 3255): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3255):  
I/SELinux ( 3255):  
,I/SELinux ( 3255): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/WifiDisplayAdapter(  729): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/SELinux ( 3255): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3255): >>>>> Normal User
E/dalvikvm( 3255): >>>>> com.android.bluetooth [ userId:0 | appId:1002 ]
D/ActivityThread( 3251): Added TimaKesytore provider
E/SELinux ( 3255): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/QuickConnect[1.1][2] ( 3215): GroupVoiceTalkActionHelper.GroupVoiceTalkActionHelper -  --
V/QuickConnect[1.1][2] ( 3215): SmartHomeActionHelper.SmartHomeActionHelper - --
V/QuickConnect[1.1][2] ( 3215): ScreenMirrorActionHelper.ScreenMirrorActionHelper - 
V/QuickConnect[1.1][2] ( 3215): BluetoothActionHelper.BluetoothActionHelper - 
D/BluetoothAdapter( 3215): 1113475864: getState() :  mService = null. Returning STATE_OFF
,D/TimaKeyStoreProvider( 3255): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3255): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3255): Added TimaKesytore provider
,E/BluetoothHeadset( 3215): BTStateChangeCB is registed
,E/BluetoothHeadset( 3215): BluetoothHeadset service is binded
,I/QuickConnect[1.1][2] ( 3215): SconnectManager.getInstance - make new instance com.samsung.android.sconnect.SconnectManager@425d70d0
,V/QuickConnect[1.1][2] ( 3215): SconnectManager.getInstance - return existing instance com.samsung.android.sconnect.SconnectManager@425d70d0
,V/QuickConnect[1.1][2] ( 3215): PreDiscoveryHelper.PreDiscoveryHelper -  -- 
,D/QuickConnect[1.1][2] ( 3215): PreDiscoveryHelper.setVisibilityFromSystemDb - --
,D/QuickConnect[1.1][2] ( 3215): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,D/QuickConnect[1.1][2] ( 3215): Utils.getFromDb -  Key[quick_connect_contact_only], isEnabled [1] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 3215): PreDiscoveryHelper.setVisibilityFromSystemDb - isAllowToConnect : false, isContactOnly : true, visibilitySetting : 2
D/QuickConnect[1.1][2] ( 3215): PreDiscoveryHelper.changeResponseSetting - changed: 2
V/QuickConnect[1.1][2] ( 3215): PreDiscoveryHelper.updateAdvData - 
W/dalvikvm( 3251): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,V/QuickConnect[1.1][2] ( 3215): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425d70d0
,V/QuickConnect[1.1][2] ( 3215): PreDiscoveryHelper.updateRespTarget - 
,D/QuickConnect[1.1][2] ( 3215): PreDiscoveryHelper.initializeAdvData - 
,V/QuickConnect[1.1][2] ( 3215): PreDiscoveryHelper.initializeAdvData - name: Galaxy S5-2(11)
D/QuickConnect[1.1][2] ( 3215): PreDiscoveryHelper.initializeAdvData - name selected: Galaxy S5-2(11)
,V/QuickConnect[1.1][2] ( 3215): CONTACT_Info.getMyMobileNumber - 
,D/QuickConnect[1.1][2] ( 3215): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3215): CONTACT_Info.getMyMobileNumber - null 
,D/QuickConnect[1.1][2] ( 3215): NetUtil.getP2pMacFromWifiMac - ($)
,V/QuickConnect[1.1][2] ( 3215): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425d70d0
,W/QuickConnect[1.1][2] ( 3215): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.emeeting.b2c.hancom
,D/QuickConnect[1.1][2] ( 3215): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.emeeting
,D/QuickConnect[1.1][2] ( 3215): AppPackageUtil.isStubApk - but Stub version[2.7.025] of com.samsung.groupcast
W/QuickConnect[1.1][2] ( 3215): AppPackageUtil.isAppInstalled - this is Stub - com.samsung.groupcast
D/QuickConnect[1.1][2] ( 3215): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.samsung.groupcast
W/QuickConnect[1.1][2] ( 3215): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3215): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.sidesync30
,I/SELinux ( 3291): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3291):  
I/ActivityManager(  729): Killing 2291:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 3215): PeriphService.registerUserReceiver - mIsUserReceiver == false
,D/BtSettings.ProfileConfig( 3255): Adding GattService
,I/QuickConnect[1.1][2] ( 3215): PeriphService.onStartCommand - USER_OWNER
I/QuickConnect[1.1][2] ( 3215): PeriphService.onStartCommand - Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } flags[0] startId[1]
I/QuickConnect[1.1][2] ( 3215): PeriphService.onStartCommand - Action: com.samsung.android.sconnect.periph.START_SERVICE
D/BtSettings.ProfileConfig( 3255): Adding HeadsetService
,D/BtSettings.ProfileConfig( 3255): Adding A2dpService
D/BtSettings.ProfileConfig( 3255): Adding HidService
D/BtSettings.ProfileConfig( 3255): Adding HealthService
D/BtSettings.ProfileConfig( 3255): Adding PanService
,D/BtSettings.ProfileConfig( 3255): Adding BluetoothMapService
,E/memtrack( 3228): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3228): failed to load memtrack module: -2
,D/BluetoothAdapterService( 3255): REFCOUNT: CREATED. INSTANCE_COUNT1
,I/SELinux ( 3291): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3291):  
I/SELinux ( 3291):  
,I/SELinux ( 3291): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3291): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3291): >>>>> Normal User
,E/dalvikvm( 3291): >>>>> com.sec.android.inputmethod [ userId:0 | appId:1000 ]
,E/SELinux ( 3291): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BluetoothAdapterState( 3255): make
I/bluedroid( 3255): init
,D/dalvikvm( 3228): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,I/BluetoothAdapterState( 3255): Entering OffState
,I/bte_conf( 3255): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bluedroid( 3255): get_profile_interface socket
,I/GKI_LINUX( 3255): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/TimaKeyStoreProvider( 3291): in addTimaSignatureService
,D/BluetoothAdapterService( 3255):  checkAddrForIOP: Loading from conf
E/BluetoothServiceJni( 3255): populateRssiValuesNative
I/bluedroid( 3255): getModelRssiValues
,E/BluetoothServiceJni( 3255): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/TimaKeyStoreProvider( 3291): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3291): Added TimaKesytore provider
,I/bluedroid( 3255): config_hci_snoop_log
,D/AndroidRuntime( 3228): Calling main entry com.android.commands.pm.Pm
,D/BluetoothManagerService(  729): Broadcasting onBluetoothServiceUp() to 11 receivers.
,D/PackageManagerService(  729): deletePackageAsUser- pkg:com.example.hello, userId:0
D/PersonaManagerService(  729): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  729): isFromApprovedUnInstaller: isApproved : true
,D/PersonaManagerService(  729): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  729): START PACKAGE DELETE: observer{1120937648}
D/PackageManager(  729): pkg{<packageName>}
D/PackageManager(  729): user{0}
D/PackageManager(  729): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  729): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService(  729): deletePackage- pkg:com.example.hello, edmuserId:0
,D/PackageManagerService(  729): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  729): getApplicationUninstallationEnabled
D/ApplicationPolicy(  729): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService(  729): deletePackageX- pkg:com.example.hello, userId:0
D/PackageManager(  729): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  729): [MSG] DELETE_PACKAGE_AS_USER
,D/BluetoothRadioManager( 3215): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4263fe40
,D/BluetoothRadioManager( 3215): onBluetoothServiceUp()  registerRadioClient mUUID = 01318daa-caa3-4cb0-bfc6-47da49d81f66
,I/bluedroid( 3255): update_radio_count
D/BluetoothAdapterState( 3255): CURRENT_STATE=OFF, MSG = USER_TURN_ON_RADIO
I/BluetoothAdapterState( 3255): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=false
D/BluetoothAdapterState( 3255): CURRENT_STATE=PENDING, MSG = BEGIN_ENABLE_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
,I/bluedroid( 3255): enable
,I/bt_hci_bdroid( 3255): init
I/bt_vendor( 3255): bt-vendor : init
I/bt_vendor( 3255): bt-vendor : get_bt_soc_type
E/bt_vendor( 3255): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 3255): init: Local BD Address : dc:06:b5:96:94:38
D/bt_userial_mct( 3255): userial_init
I/bt_vendor( 3255): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3255): Starting hciattach daemon
I/bt_vendor( 3255): try to set false
,I/bt_hci_bdroid( 3255): bt_hc_worker_thread started
I/bt_vendor( 3255): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 3255): Starting hciattach daemon
,I/bt_vendor( 3255): try to set true
,D/PackageManager(  729): !@killApplicatoin: 10180, uninstall pkg
,I/SELinux ( 3311): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3311):  
I/ActivityManager(  729): Killing 2311:com.sec.android.app.mss/u0a21 (adj 15): empty #43
I/ActivityManager(  729): Killing 2711:com.example.hello/u0a180 (adj 0): stop com.example.hello
,I/qcom-bluetooth( 3310): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/SurfaceFlinger(  247): id=15 Removed NainActivit (7/10)
,I/SurfaceFlinger(  247): id=15 Removed NainActivit (-2/10)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/WindowState(  729): WIN DEATH: Window{42ce7ec0 u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger(  247): id=15 Removed NainActivit (-2/10)
I/SELinux ( 3311): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3311):  
I/SELinux ( 3311):  
I/SELinux ( 3311): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3311): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3311): >>>>> Normal User
E/dalvikvm( 3311): >>>>> com.android.email [ userId:0 | appId:10155 ]
E/SELinux ( 3311): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3311): in addTimaSignatureService
D/TimaKeyStoreProvider( 3311): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3311): Added TimaKesytore provider
,I/qcom-bluetooth( 3328): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 3329): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,E/SMD     (  241): DCD ON
W/PackageSettings(  729): Skipping PackageSetting{42426200 com.test.thalitest/10179} due to missing metadata
,I/qcom-bluetooth( 3331): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3332): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,D/PackageManager(  729): queryIntentReceivers - Execution time: 146 ms
,D/LockPatternUtils( 1067): isPcwEnable = null
,I/SQLiteSecureOpenHelper( 2047): getWritableDatabase(pwd)
W/ActivityManager(  729): Force removing ActivityRecord{431dd008 u0 com.example.hello/.MainActivity t3}: app died, no saved state
D/PackageManager(  729): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10180, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/SQLiteSecureOpenHelper( 2047): getDatabaseLocked(b,b,pwd)...
,I/qcom-bluetooth( 3333): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  729): mDVFSHelper.acquire()
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/qcom-bluetooth( 3334): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/SurfaceWidgetView( 1247): destroyHardwareResources():1125992144
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/PackageManager(  729): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10180, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1247): onRestart, Launcher: 1114056736
D/Launcher( 1247): onStart, Launcher: 1114056736
,D/Launcher.HomeView( 1247): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1451): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1451): [237392/5] SurfaceWidget drawing first frame
,I/FPMS_FingerprintManagerService( 1086): onReceive: android.intent.action.PACKAGE_REMOVED
,D/AdaptiveEventManager( 1067): action=android.intent.action.PACKAGE_REMOVED
,W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
,D/QuickConnect[1.1][2] ( 3215): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.example.hello
,I/InputReader(  729): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 1409): GC_EXPLICIT freed 4145K, 49% free 9983K/19332K, paused 3ms+5ms, total 61ms
,I/SurfaceFlinger(  247): id=16 createSurf (720x1280),1 flag=4, Mauncher
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "sms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=17 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/RCPManagerService(  729): PackageReceiver onReceive()
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/HarmonyEASService(  729): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PackageManager(  729):   Scheme: "smsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  729):   Scheme: "mms"
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  729): mDVFSHelper.release()
D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@9
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "mmsto"
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
D/EnterpriseDeviceManagerService(  729): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  729): Admin package name: com.google.android.gms
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "sms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/dalvikvm(  729): GC_EXPLICIT freed 1756K, 19% free 22817K/28080K, paused 15ms+13ms, total 231ms
,D/PackageManager(  729): delete sourFile : 
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "smsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/PackageManager(  729): delete native library directory: 
D/PackageManager(  729): return delete result to caller: 1120937648
,D/AndroidRuntime( 3228): Shutting down VM
,D/dalvikvm( 3228): GC_CONCURRENT freed 96K, 13% free 670K/768K, paused 0ms+0ms, total 3ms
D/PackageManager(  729): returnCode: 1
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729):   Scheme: "mms"
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "mmsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "sms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "smsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "mms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3346): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3346):  
,D/BackupManagerService(  729): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  729): removePackageParticipantsLocked: uid=10180 #1
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "mmsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3346): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3346):  
I/SELinux ( 3346):  
,I/SELinux ( 3346): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3346): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 3346): >>>>> Normal User
,E/dalvikvm( 3346): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 3346): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 3346): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3346): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3346): Added TimaKesytore provider
,I/SELinux ( 3363): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3363):  
I/ActivityManager(  729): Killing 2325:com.sec.android.app.msa/u0a23 (adj 15): empty #43
W/ActivityManager(  729): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager(  729): Killing 1189:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
,W/ActivityManager(  729): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 3363): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3363):  
I/SELinux ( 3363):  
,I/SELinux ( 3363): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3363): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3363): >>>>> Normal User
,E/dalvikvm( 3363): >>>>> com.android.exchange [ userId:0 | appId:10156 ]
,E/SELinux ( 3363): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/Process ( 3311): Sending signal. PID: 3311 SIG: 9
,D/TimaKeyStoreProvider( 3363): in addTimaSignatureService
,D/BadgeProvider( 3346): onCreate
,D/BadgeProvider( 3346): DatabaseHelper
,D/TimaKeyStoreProvider( 3363): Cannot add TimaSignature Service, License check Failed
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=3346, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/ActivityThread( 3363): Added TimaKesytore provider
I/ActivityManager(  729): Process com.android.email (pid 3311) (adj 9) has died.
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/InputReader(  729): Processing first event
,W/ApplicationsProvider( 1409): Could not fetch usage stats
W/ApplicationsProvider( 1409): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1409): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1409): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1409): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1409): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1409): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1409): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
