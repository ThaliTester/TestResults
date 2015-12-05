#### Test 50388019f33194e_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2397): decode(69, 37543652, 4230)
V/MediaPlayerService(  244): decode(34, 37543652, 4230)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(34, 37543652, 4230)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab09a8, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8ab09a8, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab09a8, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab09a8, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  244): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab09a8, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/MediaPlayerService(  244): wait for playback complete
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab09a8, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab09a8, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  244): addBatteryData
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab09a8, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x27, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2397): decode(70, 30337076, 9400)
V/MediaPlayerService(  244): decode(34, 30337076, 9400)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(34, 30337076, 9400)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8aacdf8, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
I/Process ( 2397): Sending signal. PID: 2397 SIG: 9
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8aacdf8, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8aacdf8, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8aacdf8, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  244): open(44100, 1, 0x0, 1, 4)
E/IMemory (  244): binder=0xb8aa8418 transaction failed fd=-2147483647, size=0, err=-32 (Broken pipe)
E/IMemory (  244): cannot dup fd=-2147483647, size=0, err=-32 (Bad file number)
E/IMemory (  244): cannot map BpMemoryHeap (binder=0xb8aa8418), size=0, fd=-1 (Bad file number)
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8aacdf8, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() stop AudioSource since AudioPlayer not exist
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x28, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
--------- beginning of /dev/log/system
I/ActivityManager(  741): Process com.sec.android.app.shealth (pid 2397) (adj 0) has died.
I/SELinux ( 2468): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2468):  
I/SELinux ( 2468): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2468):  
I/SELinux ( 2468):  
I/SELinux ( 2468): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2468): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2468): >>>>> Normal User
E/dalvikvm( 2468): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 2468): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 2468): in addTimaSignatureService
D/TimaKeyStoreProvider( 2468): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2468): Added TimaKesytore provider
W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=2468, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 2468): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences( 2468): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 2468): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 2468): ContentProvider is not null
V/MediaPlayer( 2468): decode(61, 33979084, 48105)
V/MediaPlayerService(  244): decode(33, 33979084, 48105)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(33, 33979084, 48105)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab4b50, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8ab4b50, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab4b50, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab4b50, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  244): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab4b50, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/MediaPlayerService(  244): wait for playback complete
I/ServiceManager(  282): Waiting for service AtCmdFwd...
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab4b50, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab4b50, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): addBatteryData
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab4b50, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x29, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(63, 33914984, 10421)
V/MediaPlayerService(  244): decode(33, 33914984, 10421)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(33, 33914984, 10421)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abe160, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8abe160, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abe160, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abe160, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  244): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abe160, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/MediaPlayerService(  244): wait for playback complete
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abe160, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abe160, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): addBatteryData
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abe160, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x2a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(64, 37457308, 34198)
V/MediaPlayerService(  244): decode(33, 37457308, 34198)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(33, 37457308, 34198)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8aacda0, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8aacda0, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8aacda0, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8aacda0, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  244): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8aacda0, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/MediaPlayerService(  244): wait for playback complete
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8aacda0, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8aacda0, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  244): addBatteryData
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8aacda0, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x2b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(65, 33862452, 7405)
V/MediaPlayerService(  244): decode(33, 33862452, 7405)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(33, 33862452, 7405)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0970, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0970, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0970, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0970, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  244): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0970, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
I/AudioPlayer(  244): First fillBuffer call!!
V/MediaPlayerService(  244): wait for playback complete
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0970, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0970, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): addBatteryData
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0970, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x2c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(66, 37547940, 5555)
V/MediaPlayerService(  244): decode(33, 37547940, 5555)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  244): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/MediaPlayerService(  244): wait for playback complete
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  244): addBatteryData
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x2d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(67, 30367732, 5085)
V/MediaPlayerService(  244): decode(33, 30367732, 5085)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab5510, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8ab5510, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab5510, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab5510, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  244): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab5510, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/MediaPlayerService(  244): wait for playback complete
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab5510, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab5510, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): addBatteryData
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab5510, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x2e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(68, 30372876, 21552)
V/MediaPlayerService(  244): decode(30, 30372876, 21552)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(30, 30372876, 21552)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0600, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0600, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0600, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0600, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  244): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0600, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/MediaPlayerService(  244): wait for playback complete
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0600, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0600, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  244): addBatteryData
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ac0600, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x2f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(69, 37543652, 4230)
V/MediaPlayerService(  244): decode(33, 37543652, 4230)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3cf8, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3cf8, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3cf8, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3cf8, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCach,e(  244): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3cf8, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/MediaPlayerService(  244): wait for playback complete
I/AudioPlayer(  244): First fillBuffer call!!
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3cf8, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3cf8, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  244): addBatteryData
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3cf8, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x30, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(70, 30337076, 9400)
V/MediaPlayerService(  244): decode(34, 30337076, 9400)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(34, 30337076, 9400)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abdd78, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8abdd78, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abdd78, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abdd78, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/SELinux ( 2538): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2538):  
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  244): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abdd78, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/MediaPlayerService(  244): wait for playback complete
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abdd78, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abdd78, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  244): addBatteryData
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abdd78, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x31, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(71, 33925464, 44276)
V/MediaPlayerService(  244): decode(33, 33925464, 44276)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(33, 33925464, 44276)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abfc10, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8abfc10, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abfc10, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abfc10, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  244): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abfc10, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/MediaPlayerService(  244): wait for playback complete
I/SELinux ( 2538): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2538):  
I/SELinux ( 2538):  
I/SELinux ( 2538): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2538): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2538): >>>>> Normal User
E/dalvikvm( 2538): >>>>> com.sec.android.app.sns3 [ userId:0 | appId:10036 ]
E/SELinux ( 2538): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 2538): in addTimaSignatureService
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
D/TimaKeyStoreProvider( 2538): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2538): Added TimaKesytore provider
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abfc10, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abfc10, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  244): addBatteryData
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abfc10, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x32, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(72, 33885672, 29256)
V/MediaPlayerService(  244): decode(33, 33885672, 29256)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(33, 33885672, 29256)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  244): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/MediaPlayerService(  244): wait for playback complete
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  244): addBatteryData
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf930, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x33, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(73, 37491572, 52024)
V/MediaPlayerService(  244): decode(33, 37491572, 52024)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(33, 37491572, 52024)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3c48, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3c48, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3c48, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3c48, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  244): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3c48, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
I/AudioPlayer(  244): First fillBuffer call!!
V/MediaPlayerService(  244): wait for playback complete
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3c48, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3c48, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  244): addBatteryData
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8ab3c48, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x34, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(74, 33969800, 9226)
V/MediaPlayerService(  244): decode(33, 33969800, 9226)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(33, 33969800, 9226)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf468, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8abf468, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf468, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf468, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  244): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf468, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/MediaPlayerService(  244): wait for playback complete
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf468, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf468, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  244): addBatteryData
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abf468, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x35, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/MediaPlayer( 2468): decode(75, 30402580, 4509)
V/MediaPlayerService(  244): decode(33, 30402580, 4509)
V/MediaPlayerService(  244): player type = 3
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): constructor
V/AwesomePlayer(  244): setDefault
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): StagefrightPlayer
V/AwesomePlayer(  244): setListener
V/StagefrightPlayer(  244): initCheck
V/AwesomePlayer(  244): setAudioSink
V/StagefrightPlayer(  244): setDataSource(33, 30402580, 4509)
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abcd08, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  244): mBitrate = -1 bits/sec
V/AwesomePlayer(  244): current audio track index (0) is added to vector
V/AwesomePlayer(  244): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  244): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  244): prepare
V/AwesomePlayer(  244): prepareAsync
V/MediaPlayerService(  244): wait for prepare
V/AwesomePlayer(  244): onPrepareAsyncEvent
I/SecMediaClock(  244): SecMediaClock constructor
I/SecMediaClock(  244): reset
V/AwesomePlayer(  244): initAudioDecoder
V/AwesomePlayer(  244): checkOffloadExceptions is true
I/OMXCodec(  244): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  244): mDispatchers.add
I/OMXCodec(  244): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  244): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  244): finishAsyncPrepare_l
V/AwesomePlayer(  244): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  244): notify(0xb8abcd08, 200, 973, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abcd08, 5, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abcd08, 1, 0, 0)
V/AudioCache(  244): prepared
V/AudioCache(  244): wait - success
V/MediaPlayerService(  244): start
V/StagefrightPlayer(  244): start
V/AwesomePlayer(  244): play
V/AwesomePlayer(  244): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  244): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  244): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  244): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  244):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  244): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  244): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abcd08, 6, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): addBatteryData
V/AwesomePlayer(  244): postAudioEOS delayUs (0)
V/AwesomePlayer(  244): onCheckAudioStatus
V/MediaPlayerService(  244): wait for playback complete
V/AwesomePlayer(  244): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  244): onStreamDone
V/AwesomePlayer(  244): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  244): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abcd08, 2, 0, 0)
V/AudioCache(  244): playback complete - thread will wake up later
V/AwesomePlayer(  244): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abcd08, 7, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  244): addBatteryData
V/AudioCache(  244): wait - success
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  244): notify(0xb8abcd08, 8, 0, 0)
V/AudioCache(  244): ignored
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stop() sendCommand(0x36, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  244): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  244): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  244): instance freeNode
I/AudioPlayer(  244): reset out
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  244): SecMediaClock destructor
V/AwesomePlayer(  244): mSecMediaClock clear
V/StagefrightPlayer(  244): ~StagefrightPlayer
V/StagefrightPlayer(  244): reset
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
V/AwesomePlayer(  244): destructor
V/AwesomePlayer(  244): reset_l()
V/AwesomePlayer(  244): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  244): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  244): mAudioTrackVector clear
V/AwesomePlayer(  244): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  244): mSecMediaClock clear
W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=2538, uid=10036 requires android.permission.INTERACT_ACROSS_USERS
D/BatteryService(  741): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:24, charge type:1, power sharing:false
D/BatteryService(  741): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  741): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/Process ( 2538): Sending signal. PID: 2538 SIG: 9
D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
I/ActivityManager(  741): Process com.sec.android.app.sns3 (pid 2538) (adj 0) has died.
I/SELinux ( 2584): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2584):  
I/SELinux ( 2584): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2584):  
I/SELinux ( 2584):  
I/SELinux ( 2584): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2584): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2584): >>>>> Normal User
E/dalvikvm( 2584): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 2584): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 2584): in addTimaSignatureService
D/TimaKeyStoreProvider( 2584): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2584): Added TimaKesytore provider
I/SELinux ( 2604): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2604):  
E/SMD     (  233): DCD ON
I/SELinux ( 2604): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2604):  
I/SELinux ( 2604):  
I/SELinux ( 2604): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2604): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2604): >>>>> Normal User
E/dalvikvm( 2604): >>>>> com.sec.spp.push [ userId:0 | appId:10038 ]
E/SELinux ( 2604): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 2604): in addTimaSignatureService
D/TimaKeyStoreProvider( 2604): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2604): Added TimaKesytore provider
E/SPPClientService( 2604): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 2604): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 2604): PushLog.txt file is not deleted.
D/SPPClientService( 2604): PushLog.txt file is not deleted.
D/SPPClientService( 2604): ============PushLog. stop!
I/ServiceManager(  282): Waiting for service AtCmdFwd...
E/SPPClientService( 2604): [SystemStateMoniter] ACTION_BOOT_COMPLETED
I/SELinux ( 2617): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2617):  
I/SELinux ( 2617): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2617):  
I/SELinux ( 2617):  
I/SELinux ( 2617): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2617): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2617): >>>>> Normal User
E/dalvikvm( 2617): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 2617): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 2617): in addTimaSignatureService
D/TimaKeyStoreProvider( 2617): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2617): Added TimaKesytore provider
I/SA      ( 2617): [SSP] onCreated
I/SA      ( 2617): [TPM] There is no property file
I/SA      ( 2617): [SCU] isHaveSA() - false
I/SA      ( 2617): [TPM] getModelProperty : null
I/SA      ( 2617): [TPM] getCSCProperty : null
I/SA      ( 2617): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED
I/SA      ( 2617): [DM] init START
I/SA      ( 2617): [DM] This device is not a Vodafone
I/SA      ( 2617): [DM] getCountryCodeFromCSC : PL
I/SA      ( 2617): support phone number id : false
I/SA      ( 2617): [DM] init END
I/SA      ( 2617): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 2617): [BDLM] already registered in spp
I/SA      ( 2617): [OR] onReceive Intent=[ action_BOOT_COMPLETED ]
I/SA      ( 2617): [OR] onReceive END
I/SA      ( 2617): [BDC] create
I/SA      ( 2617): [DBMV2] getEmailID
I/SA      ( 2617): [DBMV2] getDataV02ForItems
I/SA      ( 2617): [SSP] query invoked
I/SA      ( 2617): [SCU] get signed id from samsung account2.0 DB.
I/SELinux ( 2633): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2633):  
I/SA      ( 2617): [SCU] get signed id from samsung account1.0 DB.
I/SA      ( 2617): [BDC] destroy
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
D/AndroidRuntime( 2645): 
D/AndroidRuntime( 2645): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2645): CheckJNI is OFF
W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=2633, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
D/AndroidRuntime( 2645): setted country_code = Poland
D/AndroidRuntime( 2645): setted countryiso_code = PL
D/AndroidRuntime( 2645): setted sales_code = XEO
D/AndroidRuntime( 2645): readGMSProperty: start
D/AndroidRuntime( 2645): readGMSProperty: already setted!!
D/AndroidRuntime( 2645): readGMSProperty: end
D/AndroidRuntime( 2645): addProductProperty: start
D/dalvikvm( 2645): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2645): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2645): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2645): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2645): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/MediaScannerReceiver( 1208): action: android.intent.action.BOOT_COMPLETED
D/MediaScannerService( 1208): !@start scanning volume internal: [/system/media]
D/TP/MmsProvider( 1241): Update uri=content://mms, match=0
D/TP/MmsProvider( 1241): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1241): need read changed broadcast:false
I/Mms:transaction( 1727): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 1727): [start]    nonBlockingUpdateMessageIndicator()
I/Mms/ReservationManager( 1727): resetAfterConnected()
D/Mms/MessagingNotification( 1727): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1727): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1727): isDefault true
D/TP/MmsSmsProvider( 1241): match 7:Elapsed time : 4.388 ms
I/Mms/ReservationManager( 1727): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1241): match 200:Elapsed time : 1.173 ms
I/SELinux ( 2668): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2668):  
D/BadgeProvider( 1340): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/SELinux ( 2668): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2668):  
I/SELinux ( 2668):  
I/SELinux ( 2668): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2668): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2668): >>>>> Normal User
E/dalvikvm( 2668): >>>>> com.sec.android.app.safetyassurance [ userId:0 | appId:10050 ]
E/SELinux ( 2668): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/memtrack( 2645): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 2645): failed to load memtrack module: -2
D/Mms/TelephonyPermission( 1727): isDefault true
D/Mms/SmsReceiverService( 1727): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 1727): [start]    handleBootCompleted()
D/TimaKeyStoreProvider( 2668): in addTimaSignatureService
D/TimaKeyStoreProvider( 2668): Cannot add TimaSignature Service, License check Failed
D/Launcher.Model( 1252): reloadBadges entered.
D/BadgeProvider( 1340): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): sendNotify, [notify] : null
D/BadgeProvider( 1340): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1340): update, [UpdateCount] : 1
D/ActivityThread( 2668): Added TimaKesytore provider
D/Mms/MessagingNotification( 1727): setBadgeCount(), count=0
D/MessagingNotification( 1727): remove alarm
D/dalvikvm( 2645): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/TP/MmsSmsProvider( 1241): deleteConversation threadId: 9223372036854775806
D/Mms/MessagingNotification( 1727): updateAllHistoryAsRead()
D/TP/MmsSmsProvider( 1241): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
D/Mms/MessagingNotification( 1727): [end]    nonBlockingUpdateMessageIndicator()
D/TP/MmsSmsProvider( 1241): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1241): need read changed broadcast:false
W/dalvikvm( 2668): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
D/Mms/Conversation( 1727): deleteTempConversation(),deleted=0
D/MediaScanner( 1208): Prescan. DB items number : 156 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/AndroidRuntime( 2645): Calling main entry com.android.commands.am.Am
D/SafetyAssuranceAppFeatures( 2668): init start
I/SafetyAssuranceAppFeatures( 2668): mLoadBaiduMap:false
I/SafetyAssuranceAppFeatures( 2668): mFeatureEnableMultiSim true
D/SafetyAssuranceAppFeatures( 2668): init end
D/SafetyAssuranceReceiver( 2668): onReceive
D/SmsProvider( 1241): Update uri=content://sms/outbox, match=8
I/SafetyAssuranceApp( 2668): Acquire WL
D/TP/MmsSmsProvider( 1241): need read changed broadcast:false
D/Mms/SmsReceiverService( 1727): sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 1727): [SIM-1]sendFirstQueuedMessage()
D/SafetyAssuranceConfig( 2668): getAppState : 1
D/SafetyAssuranceReceiver( 2668): onReceive - action:android.intent.action.BOOT_COMPLETED, currentAppState:1
D/SafetyAssuranceReceiver( 2668): Init App state
W/BackupManagerService(  741): dataChanged but no participant pkg='com.android.providers.settings' uid=10050
W/Atfwd_Sendcmd(  282): AtCmdFwd service not published, waiting... retryCnt : 3
V/ApplicationPolicy(  741): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService(  741): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 741  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  741): mDVFSHelper.acquire()
I/SurfaceFlinger(  239): id=15 createSurf (1x1),1 flag=404, iello
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/dalvikvm(  741): GC_EXPLICIT freed 2470K, 19% free 22509K/27484K, paused 6ms+12ms, total 141ms
D/SafetyAssuranceConfig( 2668): setAppState : 1
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
V/MediaScanner( 1208): processDirectory :  /system/media
I/HarmonyEASService(  741): Updating for all 1
V/MediaScanner( 1208):  prescan time: 418ms (DB items: 156)
V/MediaScanner( 1208):     scan time: 48ms (Caching mode: true), (makeEntry time: 22ms ~45%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1208): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1208):    total time: 466ms
V/MediaScanner( 1208): checked files: 149  directories : 5  (I: 0, U: 0)
D/MediaScanner( 1208): checkDefaultSounds
D/MediaScanner( 1208): system alarm_alert  : Vwiurug_etwofi5wgg
I/WindowManager(  741): Screenshot max retries 4 of Token{42ea9c90 ActivityRecord{43111a08 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42d22a58 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
W/WindowManager(  741): Screenshot failure taking screenshot for (720x1280) to layer 21005
D/LockPatternUtils( 1069): isPcwEnable = null
D/AndroidRuntime( 2645): Shutting down VM
D/SafetyAssuranceApp( 2668): topActivity's name is=.MainActivity
D/dalvikvm( 2645): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 5ms
I/SafetyAssuranceApp( 2668): Release WL
D/MediaScanner( 1208): OK. alarm_alert is already exist in setting DB.
D/MediaScanner( 1208): system notification_sound  : K_Oprkltf5wgg
D/MediaScanner( 1208): OK. notification_sound is already exist in setting DB.
D/MediaScanner( 1208): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1208): OK. ringtone is already exist in setting DB.
D/MediaScanner( 1208): system ringtone_2  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1208): OK. ringtone_2 is already exist in setting DB.
D/MediaScanner( 1208): system notification_sound_2  : K_Oprkltf5wgg
I/SELinux ( 2685): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2685):  
D/MediaScanner( 1208): OK. notification_sound_2 is already exist in setting DB.
D/Mms/MessagingNotification( 1727): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1727): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1727): isDefault true
D/MediaScannerService( 1208): !@done scanning volume internal
D/MediaScannerService( 1208): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
D/MediaProvider( 1208): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1208): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/MediaProvider( 1208): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/MediaProvider( 1208): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1208): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1208): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1208): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1208): savePlaylistTableInBulkDeleter finished
I/NetworkStatusReceiver( 1241): action: android.intent.action.BOOT_COMPLETED
D/TP/MmsSmsProvider( 1241): match 200:Elapsed time : 4.640 ms
I/SELinux ( 2685): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2685):  
I/SELinux ( 2685):  
I/SELinux ( 2685): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2685): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2685): >>>>> Normal User
E/dalvikvm( 2685): >>>>> com.example.hello [ userId:0 | appId:10180 ]
D/MediaScanner( 1208): Prescan. DB items number : 20 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
E/SELinux ( 2685): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/NearbySettings( 1313): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1313): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1313): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
D/TimaKeyStoreProvider( 2685): in addTimaSignatureService
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
I/NearbySettings( 1313): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1313): MountReceiver.onReceive - Internal Path
D/TimaKeyStoreProvider( 2685): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2685): Added TimaKesytore provider
V/MediaScanner( 1208): processDirectory :  /storage/emulated/0
D/Launcher.HomeView( 1252): onStop
D/MediaScanner( 1208): Skipping:
D/MediaScanner( 1208): 7klwibgf7fvntblfd7(75ebcf7
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1453): [237392/5] Surface widget pause on instance = 1
D/accuweather( 1453): [KK AccuPhone]>>> SWW:224 [0:0] [SWW] onPause : instance = 1
D/accuweather( 1453): [KK AccuPhone]>>> SWW:239 [0:0] onPause : size = 0
D/accuweather( 1453): [KK AccuPhone]>>> SWW:517 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1453): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/Launcher( 1252): onTrimMemory. Level: 20
D/LockPatternUtils( 1069): isPcwEnable = null
D/accuweather( 1453): [KK AccuPhone]>>> WR:149 [0:0] onPause
D/accuweather( 1453): [KK AccuPhone]>>> SM:526 [0:0] onPause
D/SurfaceWidgetView( 1252): destroyHardwareResources():1130458416
I/AccessibilityManagerService(  741): setmDNIeNegative (false)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/BadgeProvider( 1340): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=2685, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
D/MediaScanner( 1208): Skipping:
D/MediaScanner( 1208): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
D/BadgeProvider( 1340): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): sendNotify, [notify] : null
D/Launcher.Model( 1252): reloadBadges entered.
D/BadgeProvider( 1340): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1340): update, [UpdateCount] : 1
,I/iu.UploadsManager( 1644): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,D/Mms/MessagingNotification( 1727): setBadgeCount(), count=0
V/MediaScanner( 1208): processDirectory :  /storage/extSdCard
,W/MediaScanner( 1208): Error opening directory, reason : Permission denied.
,W/MediaScanner( 1208): 7klwibgf7fxlKdCbid7
,W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=2685, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
D/MessagingNotification( 1727): remove alarm
,D/Mms/MessagingNotification( 1727): updateAllHistoryAsRead()
,E/File    ( 1208): fail readDirectory() errno=2
,V/MediaScanner( 1208): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@42ae5538
,V/MediaScanner( 1208): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@42ae5538
,V/WebViewChromium( 2685): Binding Chromium to the background looper Looper (main, tid 1) {426ed198}
,I/chromium( 2685): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 2685): Initializing chromium process, renderers=0
V/MediaScanner( 1208):  prescan time: 56ms (DB items: 20)
V/MediaScanner( 1208):     scan time: 91ms (Caching mode: true), (makeEntry time: 72ms ~79%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1208): postscan time: 10ms (bulkDeleter : 0), (delete DeadThumbnail time : 4ms)
V/MediaScanner( 1208):    total time: 157ms
V/MediaScanner( 1208): checked files: 3  directories : 17  (I: 0, U: 0)
D/MediaScannerService( 1208): !@done scanning volume external
W/ContextImpl(  741): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Mms/SmsReceiverService( 1727): [end]    handleBootCompleted()
D/MediaScannerService( 1208): send command to ssrm : REQ_DROP_CACHE
,D/lights  (  741): lcd : 2 +
,W/chromium( 2685): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/PowerManagerService(  741): [s] UserActivityState : 1 -> 0
I/PowerManagerService(  741): [PWL] On : 0 (39691 ms ago)
I/PowerManagerService(  741): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  741): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1069, ws=null) (elapsedTime=18536)
D/DisplayPowerController(  741): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService(  741): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/RampAnimator(  741): Light Animator Finished currentValue=2
,I/Adreno-EGL( 2685): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2685): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2685): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2685): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2685): Remote Branch: 
I/Adreno-EGL( 2685): Local Patches: 
I/Adreno-EGL( 2685): Reconstruct Branch: 
,D/lights  (  741): lcd : 2 -
,I/iu.UploadsManager( 1644): End new media; added: 0, uploading: 0, time: 107 ms
,I/dalvikvm( 2685): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2685): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2685): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2685): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2685): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 2685): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 2685): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2685): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2685): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2685): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 2685): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 2685): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2685): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2685): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2685): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2685): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2685): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 2685): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 2685): CordovaWebView is running on device made by: samsung
,D/SensorService(  741):   -0.0 -0.1 9.6
,W/Settings( 1313): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  239): id=16 createSurf (720x1280),1 flag=404, NainActivit
I/SettingSearch/SearchIntentReceiver( 1313): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1313): search setting db init!!
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SettingSearch/SearchIntentReceiver( 1313): BOOT_COMPLETED call InitSerachDBThread thread start!
,W/ContextImpl( 1313): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:40 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:60 
I/HWUI    ( 2685): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 2685): Enabling debug mode 0
,I/SELinux ( 2734): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2734):  
,W/AwContents( 2685): nativeOnDraw failed; clearing to background color.
D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,W/BackupManagerService(  741): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
,W/ContextImpl(  741): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.ssrm.u.i:-1 com.android.server.ssrm.ai.run:-1 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 
,D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
,I/BootupListener( 1241): mPendingNetworkManualSelection : false
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/ManualSelectionReceiver( 1241): onReceive : Intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.phone/.ManualSelectionReceiver (has extras) }
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetView( 1252): destroyHardwareResources():1130458416
,I/SELinux ( 2739): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2739):  
,I/SELinux ( 2734): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2734):  
I/SELinux ( 2734):  
,I/SELinux ( 2734): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/CustomFrequencyManagerService(  741): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 741  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  741): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  741): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 741  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SurfaceFlinger(  239): id=15 Removed iello (10/13)
E/SELinux ( 2734): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/SurfaceFlinger(  239): id=15 Removed iello (-2/13)
E/dalvikvm( 2734): >>>>> Normal User
,E/dalvikvm( 2734): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10160 ]
,E/SELinux ( 2734): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  239): id=9 Removed Mauncher (8/12)
,I/SurfaceFlinger(  239): id=9 Removed Mauncher (-2/12)
,D/SSRMv2:SIOP(  741): SIOP:: AP = 330, Delta = 10
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  239): id=14 Removed CatteryCove (8/11)
,I/SurfaceFlinger(  239): id=14 Removed CatteryCove (-2/11)
,D/TimaKeyStoreProvider( 2734): in addTimaSignatureService
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/TimaKeyStoreProvider( 2734): Cannot add TimaSignature Service, License check Failed
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/ActivityThread( 2734): Added TimaKesytore provider
,I/SELinux ( 2739): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2739):  
I/SELinux ( 2739):  
,I/SELinux ( 2739): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2739): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2739): >>>>> Normal User
,E/dalvikvm( 2739): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
,E/SELinux ( 2739): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2739): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2739): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2739): Added TimaKesytore provider
,W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=2734, uid=10160 requires android.permission.INTERACT_ACROSS_USERS
,I/DBG_DM  ( 2739): [][Line:95][onCreate] 
,E/DBG_DM  ( 2739): BootingfileStream is null
E/DBG_DM  ( 2739): xdmCreateBootingFilestream
,I/DBG_DM  ( 2739): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DM  ( 2739): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
,I/DBG_DM  ( 2739): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
,I/DBG_DM  ( 2739): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
,I/chromium( 2685): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/DBG_DM  ( 2739): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
,I/DBG_DM  ( 2739): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
,I/DBG_DM  ( 2739): [3.19.140541][Line:36][onCreate] myUserId : 0
,I/DBG_DM  ( 2739): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 0
,I/DBG_DM  ( 2739): [3.19.140541][Line:2702][xdmdbsqlGetDownloadPostponeStatus] xdbsqlGetDownloadPostponeStatus : 0
,I/chromium( 2685): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/DBG_DM  ( 2739): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
,I/DBG_DM  ( 2739): [3.19.140541][Line:99][onCreate] DMApplication NOT Start !
E/libGLESv2( 2685): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,E/libGLESv2( 2685): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,I/DBG_DM  ( 2739): [3.19.140541][Line:139][onReceive] android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1069): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1069): into the SAFE_MODE_ACTION
,D/OverheatReceiver( 1069): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1069): isSafeMode = false
,E/AndroidProtocolHandler( 2685): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium( 2685): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 2685): Set native->JS mode to OnlineEventsBridgeMode
,E/Tethering(  741): No numeric data
,E/Tethering(  741): No numeric data
,E/Tethering(  741): No numeric data
,E/Tethering(  741): No numeric data
I/ConnectivityService(  741): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  741): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  741): defaultVal : 1, tetherEnabledInSettings : true
,I/ConnectivityService(  741): defaultVal : 1, tetherEnabledInSettings : true
,D/LocationManagerService(  741): getProviders()=[passive]
,E/Tethering(  741): No numeric data
,E/Tethering(  741): No numeric data
I/ConnectivityService(  741): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  741): defaultVal : 1, tetherEnabledInSettings : true
,I/ActivityManager(  741): Waited long enough for: ServiceRecord{432e26a8 u0 com.google.android.gms/.gcm.GcmService}
,D/dalvikvm( 2685): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42a13fa8
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
E/libGLESv2( 2685): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,E/libGLESv2( 2685): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,I/Velvet.VelvetFactory( 2135): refreshing internal icing corpora
,I/Velvet.VelvetFactory( 2135): checking for language pack updates
,E/Tethering(  741): No numeric data
,E/Tethering(  741): No numeric data
,E/Tethering(  741): No numeric data
,E/Tethering(  741): No numeric data
V/NFC     ( 1313): this device does not have NFC support
V/NFC     ( 1313): this device does not have NFC support
V/NFC     ( 1313): this device does not have NFC support
I/ConnectivityService(  741): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  741): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  741): defaultVal : 1, tetherEnabledInSettings : true
,I/ConnectivityService(  741): defaultVal : 1, tetherEnabledInSettings : true
V/NFC     ( 1313): this device does not have NFC support
,V/VibratorService(  741): hasVibrator - useVibetonz: false
,D/dalvikvm( 2685): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42a13fa8
D/jxcore_app_log( 2685): JniHelper::setJavaVM(0x41c2e4f8), pthread_self() = 1922879504
,D/JX-Cordova( 2685): jxcore cordova android initializing
,I/Velvet.VelvetFactory( 2135): refreshing search history.
,W/dalvikvm( 2135): method Lcom/google/android/search/core/state/QueryState;.a incorrectly overrides package-private method with same name in Lcfl;
,D/LockPatternUtils( 1069): isPcwEnable = null
,W/GAV2    ( 2135): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 2135): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/Search.GservicesUpdateTask( 2135): Updating Gservices keys
,V/WebViewChromium( 2135): Binding Chromium to the main looper Looper (main, tid 1) {426ed7e0}
D/WifiDisplayAdapter(  741): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService(  741): getStreamVolume 3 index 0
,D/WifiDisplayAdapter(  741): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/MediaRouter( 2135): Found default route: MediaRouter.RouteInfo{ uniqueId=android/kb:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
W/jxcore-log( 2685): Initializing JXcore engine
W/jxcore-log( 2685): JXcore engine is ready
,W/jxcore-log( 2685): Starting JXcore engine
,D/LockPatternUtils( 1069): isPcwEnable = null
,E/SMD     (  233): DCD ON
,I/SELinux ( 2791): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2791):  
,I/chromium( 2135): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 2135): Initializing chromium process, renderers=0
,D/dalvikvm(  240): GC_EXPLICIT freed 44K, 51% free 9505K/19096K, paused 2ms+3ms, total 28ms
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 51% free 9505K/19096K, paused 2ms+2ms, total 19ms
I/SELinux ( 2791): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2791):  
I/SELinux ( 2791):  
,I/SELinux ( 2791): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2791): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2791): >>>>> Normal User
,E/dalvikvm( 2791): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 2791): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 51% free 9505K/19096K, paused 2ms+3ms, total 21ms
,D/TimaKeyStoreProvider( 2791): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2791): Cannot add TimaSignature Service, License check Failed
,W/chromium( 2135): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/ActivityThread( 2791): Added TimaKesytore provider
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
,I/Adreno-EGL( 2135): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2135): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2135): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2135): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2135): Remote Branch: 
I/Adreno-EGL( 2135): Local Patches: 
I/Adreno-EGL( 2135): Reconstruct Branch: 
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
,I/LockPatternUtils( 1313): isSmartCardAuthenticationAvailable: false
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
D/CustomFrequencyManagerService(  741): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 741  tag : ACTIVITY_RESUME_BOOSTER@9
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
,D/WifiDisplayAdapter(  741): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/IcingCorporaProvider( 2135): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,D/PowerManagerService(  741): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=1069 (0x0)
,I/PowerManagerService(  741): Nap time...
D/PowerManagerService(  741): [s] WAKEFULNESS_NAPPING
,I/PowerManagerService(  741): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService(  741): Going to sleep due to screen timeout...
,D/PowerManagerService(  741): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController(  741): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController(  741): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/Sensors (  741): LightSensor enable = 0
,D/Sensors (  741): LightSensor enableSensor = 0
,D/SensorManager(  741): unregisterListener ::   
,I/Sensors (  741): HAL:resetDataRates mEnabled=4
D/DisplayPowerController(  741): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,D/SensorManager(  741): unregisterListener ::   
,I/dalvikvm( 1644): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 1644): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1644): VFY: replacing opcode 0x6e at 0x002b
,I/SurfaceFlinger(  239): id=17 createSurf (720x1280),-1 flag=20004, FlectronBea
,D/UserAnalysis.PlaceProvider( 2791): Create SecureDbHelper
W/jxcore-log( 2685): Platform android
W/jxcore-log( 2685): 
,W/jxcore-log( 2685): Process ARCH arm
W/jxcore-log( 2685): 
D/DisplayPowerController(  741): !@ElectronBeam entry
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 2791): Create SecureDbHelper
W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=2791, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
,I/SQLiteSecureOpenHelper( 2791): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2791): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2791): Open Place.db in secure mode
,D/dalvikvm( 1644): Trying to load lib /data/app-lib/com.google.android.gms-1/libAppDataSearch.so 0x42a23978
,I/jxcore-log( 2685): JXcore Cordova bridge is ready!
I/jxcore-log( 2685): 
,W/jxcore-log( 2685): JXcore engine is started
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
V/VibratorService(  741): hasVibrator - useVibetonz: false
,D/dalvikvm( 1644): Added shared lib /data/app-lib/com.google.android.gms-1/libAppDataSearch.so 0x42a23978
,D/dalvikvm( 1644): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libAppDataSearch.so 0x42a23978, skipping init
,D/dalvikvm( 2135): GC_CONCURRENT freed 6416K, 42% free 11231K/19096K, paused 10ms+6ms, total 88ms
,D/dalvikvm( 2135): WAIT_FOR_CONCURRENT_GC blocked 41ms
,I/SQLiteSecureOpenHelper( 2791): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2791): ...getDatabaseLocked(b,b,pwd)
,E/jxcore-log( 2685): >> samsung-SM-G800H
E/jxcore-log( 2685): 
,I/SQLiteSecureOpenHelper( 2791): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2791): getDatabaseLocked(b,b,pwd)...
I/jxcore-log( 2685): Total memory 1454641152
I/jxcore-log( 2685): 
I/jxcore-log( 2685): Free memory 426569728
I/jxcore-log( 2685): 
,I/jxcore-log( 2685): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2685): 
,I/jxcore-log( 2685): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2685): 
,I/dalvikvm( 1308): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.n.a
W/dalvikvm( 1308): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1308): VFY: replacing opcode 0x6e at 0x001c
,D/UserAnalysis.CarAnalyzer( 2791): Create SecureDbHelper
,I/jxcore-log( 2685): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2685): 
,I/jxcore-log( 2685): Size 720 1280
I/jxcore-log( 2685): 
,I/jxcore-log( 2685): Screen Brightness 134
I/jxcore-log( 2685): 
,E/jxcore-log( 2685): Dummy Error Log.
E/jxcore-log( 2685): 
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/lights  (  741): lcd : 0 +
D/AmoledAdjustTimer(  741): prevTemp = 286, currTemp = 288, prevStep = 4, currStep = 4
,I/SQLiteSecureOpenHelper( 2791): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2791): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 2791): Open Place.db in secure mode
,D/lights  (  741): lcd : 0 -
D/PowerManagerService(  741): blankAllDisplays() is called.
D/MISC PowerHAL(  741): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL(  741): sysfs_write +: /sys/class/input/input1/enabled: 0
,V/WindowOrientationListener(  741): WindowOrientationListener disabled
,D/MISC PowerHAL(  741): sysfs_write -: /sys/class/input/input1/enabled: 0
,D/SensorService(  741): AutoRotationSensor::activate (ident=0x758aa790, enabled=0)
D/MISC PowerHAL(  741): miscpower_set_interactive: /sys/class/input/input6/enabled
,I/Sensors (  741): HAL: batch Dry Run is complete
,D/KeyguardViewMediator( 1069): onScreenTurnedOff(3)
,D/MISC PowerHAL(  741): sysfs_write +: /sys/class/input/input6/enabled: 0
D/MISC PowerHAL(  741): sysfs_write -: /sys/class/input/input6/enabled: 0
D/KeyguardViewMediator( 1069): notifyScreenOffLocked
E/KeyguardViewMediator( 1069): resetStateLocked
D/KeyguardViewMediator( 1069): handleNotifyScreenOff
,D/KeyguardViewManager( 1069): onScreenTurnedOff()
D/KeyguardHostView( 1069): screen off, instance 429aed90 at 41489
D/PowerManagerService(  741): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService(  741): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  741): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL(  741): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
I/Sensors (  741): HAL:resetDataRates mEnabled=4
D/MISC PowerHAL(  741): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL(  741): Got set_interactive hint
,I/Icing   ( 1644): Storage manager: low false usage 1.67MB avail 9.54GB capacity 10.16GB
D/LockPatternUtils( 1069): isPcwEnable = null
D/SurfaceFlinger(  239): Screen released, type=0 flinger=0xb8712980
,D/qdhwcomposer(  239): hwc_blank: Blanking display: 0
,D/SensorManager(  741): unregisterListener ::   
,D/PowerManagerService(  741): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
V/KeyguardHostView( 1069): showPrimarySecurityScreen(turningOff=true)
I/MDPP    ( 1069): Property: Empty
D/KeyguardHostView( 1069): showSecurityScreen(None)
D/SecCameraShortcut( 1069): onScreenTurnedOff
D/InputDispatcher(  741): setInputDispatchMode: enabled=0, frozen=0
D/SensorManager( 1069): unregisterListener ::   
I/KeyguardEffectViewMain( 1069): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 1069): KeyguardEffectViewParticleSpace : screenTurnedOff
D/VisualEffectParticleEffect( 1069): clearEffect
D/PersonaManager( 1069): isKioskContainerExistOnDevice
D/KeyguardViewMediator( 1069): Kiosk container not exists on device or sim lock exists.
D/KeyguardViewMediator( 1069): handleReset
D/KeyguardViewManager( 1069): reset()
D/KeyguardHostView( 1069): onSaveInstanceState, tstate=1
D/KeyguardGuestSelectorView( 1069): onDetachedFromWindow()
V/KeyguardUpdateMonitor( 1069): *** unregister callback for com.android.keyguard.CarrierText$1@42c87158
V/KeyguardUpdateMonitor( 1069): *** unregister callback for com.android.keyguard.MSimCarrierText$1@42c87530
V/KeyguardUpdateMonitor( 1069): *** unregister callback for com.android.keyguard.CarrierText$1@42c73d28
V/KeyguardUpdateMonitor( 1069): *** unregister callback for com.android.keyguard.EmergencyButton$1@42c83f60
,I/dalvikvm( 1644): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.b.g.a
W/dalvikvm( 1644): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1644): VFY: replacing opcode 0x6e at 0x0029
,W/NetworkUtils( 2135): OkHttp exception
,I/LockPatternUtils( 1313): isSmartCardAuthenticationAvailable: false
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
,I/SQLiteSecureOpenHelper( 2791): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2791): ...getDatabaseLocked(b,b,pwd)
,D/PackageManager(  741): [MSG] MCS_UNBIND
I/PackageManager(  741): calling disconnectService()
,D/qdhwcomposer(  239): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  741): Excessive delay in blankDisplay() while turning screen off: 249ms
I/libsuspend(  741): !@[s] autosuspend_autosleep_enable
,I/libsuspend(  741): !@[s] autosuspend_autosleep_enable done
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/PackageManager(  741): Trying to unbind to DefaultContainerService
D/PowerManagerService(  741): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 249ms
D/PowerManagerService(  741): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService(  741): [PWL] Off : 0s ago
I/PowerManagerService(  741): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  741): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  741): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10011, pid=1644, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=512)
I/PowerManagerService(  741): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=741, ws=null) (elapsedTime=236)
I/PowerManagerService(  741): [PWL]   PowerManagerService.Broadcasts: ref count=1
,I/WindowManager(  741): Screenshot max retries 4 of Token{43463fb8 ActivityRecord{43463e38 u0 com.example.hello/.MainActivity t3}} appWin=Window{426d8de0 u0 com.example.hello/com.example.hello.MainActivity} drawState=4
,W/WindowManager(  741): Screenshot failure taking screenshot for (720x1280) to layer 21010
,I/SQLiteSecureOpenHelper( 2048): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2048): getDatabaseLocked(b,b,pwd)...
,V/KeyguardUpdateMonitor( 1069): *** unregister callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@42a59f70
,D/LightsService(  741): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 741) 
,I/SensorManagerA(  741): getReportingMode :: sensor.mType = 5
,D/Sensors (  741): LightSensor setDelay = 200000000
D/Sensors (  741): LightSensor setSensorDelay = 200000000
D/Sensors (  741): Light sensor flush: not enabled 0
D/Sensors (  741): LightSensor enable = 1
,D/Sensors (  741): LightSensor enableSensor = 1
,D/SensorManager(  741): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/LightsService(  741): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService(  741): turn on LED for fully charged
D/VibratorService(  741): JNI vibratorOff()
,I/SELinux ( 2828): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2828):  
,I/dalvikvm( 1308): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.o.a
W/dalvikvm( 1308): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 1308): VFY: replacing opcode 0x6e at 0x001f
,V/KeyguardUpdateMonitor( 1069): *** unregister callback for com.android.keyguard.KeyguardHostView$2@429b01e0
,E/KeyguardHostView( 1069): KeyguardHostView()
,D/ContextualEventManager( 1069): setOnClickHandler()
,I/GoogleURLConnFactory( 1308): Using platform SSLCertificateSocketFactory
,W/InputMethodManagerService(  741): Ignoring setImeWindowStatus of uid 1000 token: null
V/KeyguardHostView( 1069): mIsMultipleLockOn is false
D/KeyguardHostView( 1069): mIsVoiceUnlockOn=false
V/KeyguardHostView( 1069): Initial transport state: 1, pbstate=0
I/KeyguardEffectViewMain( 1069): *** KeyguardEffectView getInstance ***
I/SELinux ( 2828): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2828):  
I/SELinux ( 2828):  
I/SELinux ( 2828): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/LockPatternUtils( 1069): isPcwEnable = null
E/SELinux ( 2828): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2828): >>>>> Normal User
,E/dalvikvm( 2828): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 2828): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/audio_hw_primary(  244): adev_set_parameters: enter: screen_state=off
V/voice   (  244): voice_set_parameters: enter: screen_state=off
V/voice   (  244): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  244): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  244): platform_set_parameters: exit with code(-2)
,V/audio_hw_primary(  244): adev_set_parameters: exit
D/STATUSBAR-NotificationService(  741): ACTION_SCREEN_OFF
D/LightsService(  741): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 741) 
,D/LightsService(  741): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/SecExternalDisplayIntents_Java(  741): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/ContextualEventContainer( 1069): ContextualEventContainer()
D/IpRemoteDisplayController(  741): intent received android.intent.action.SCREEN_OFF
V/KeyguardUpdateMonitor( 1069): *** register callback for com.android.keyguard.KeyguardMessageArea$2@42a14e58
V/KeyguardUpdateMonitor( 1069): *** unregister callback for null
D/IpRemoteDisplayController(  741): Bridge Server is not available
D/ContextualEventContainer( 1069): onFinishInflate()
D/ContextualEventContainer( 1069): update()
D/LockPatternUtils( 1069): isPcwEnable = null
,D/PersonaManagerService(  741): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  741): MSG_ACTION_SCREEN_OFF called
,D/TimaKeyStoreProvider( 2828): in addTimaSignatureService
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/TimaKeyStoreProvider( 2828): Cannot add TimaSignature Service, License check Failed
,D/KeyguardHostView( 1069): mIsFMMEnabled = false, mIsCarrierLockEnabled = false, mIsCarrierLockPlusEnabled = false
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/ActivityThread( 2828): Added TimaKesytore provider
,V/KeyguardHostView( 1069): showPrimarySecurityScreen(turningOff=false)
I/MDPP    ( 1069): Property: Empty
D/KeyguardHostView( 1069): showSecurityScreen(None)
,V/KeyguardHostView( 1069): inflating id = 2130903095
,D/dalvikvm( 1308): GC_CONCURRENT freed 1969K, 44% free 10710K/19096K, paused 4ms+16ms, total 73ms
,D/SecuritySelectorView( 1069): explore by touch mode off
,I/dalvikvm( 1308): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.r.a
W/dalvikvm( 1308): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 1308): VFY: replacing opcode 0x6e at 0x0041
,I/KeyguardEffectViewMain( 1069): *** KeyguardEffectView getInstance ***
,I/KeyguardEffectViewMain( 1069): *** KeyguardEffectView getInstance ***
,D/SecCameraShortcut( 1069): shortcutSetting:1
,D/SecCameraShortcut( 1069): isKidsMode:false
,D/SecCameraShortcut( 1069): isEmergencyMode:false
,E/dalvikvm( 1308): Could not find class 'android.net.Network', referenced from method com.google.android.gms.auth.be.k.a
,W/dalvikvm( 1308): VFY: unable to resolve check-cast 195 (Landroid/net/Network;) in Lcom/google/android/gms/auth/be/k;
,D/dalvikvm( 1308): VFY: replacing opcode 0x1f at 0x0149
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/EmergencyButton( 1069): enabled = false, :0
,D/LockPatternUtils( 1069): isPcwEnable = null
,I/KeyguardEffectViewMain( 1069): *** KeyguardEffectView getInstance ***
,D/SecCameraShortcut( 1069): setCallback(): null
,D/KeyguardVoiceEngineThread( 1069): condition = 0
,D/SecuritySelectorView( 1069): mIsAirViewEnabled =false
D/SecCameraShortcut( 1069): setCallback(): not null
,D/SecuritySelectorView( 1069): hideBouncer mBouncerHelpText != null
,D/SecCameraShortcut( 1069): setCallback(): not null
D/SecCameraShortcut( 1069): setCallback(): not null
,D/SecuritySelectorView( 1069): hideBouncer mBouncerHelpText != null
,D/KeyguardHostView( 1069): mKeyguardHelpOverlay : null
D/KeyguardHostView( 1069): AUTO_WIPE = false , IT Policy = false
D/ContextualEventManager( 1069): setOnClickHandler()
,E/LSO     ( 1069): LSO Service is not yet ready!!!
V/KeyguardUpdateMonitor( 1069): *** register callback for com.android.keyguard.KeyguardHostView$2@4273b038
V/KeyguardUpdateMonitor( 1069): *** unregister callback for null
V/KeyguardHostView( 1069): music state changed: 0
,D/KeyguardProperties( 1069): isIgnoreNationalRoaming() = false
D/VisualEffectCircleUnlockEffect( 1069): KeyguardEffectViewNone : Constructor
D/VisualEffectCircleUnlockEffect( 1069): screenWidth : 720
D/VisualEffectCircleUnlockEffect( 1069): screenHeight : 1280
D/VisualEffectCircleUnlockEffect( 1069): ratio : 0.6666667
,D/VisualEffectCircleUnlockEffect( 1069): Constructor
,I/GLSUser ( 1308): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
D/VisualEffectCircleUnlockEffect( 1069): arrowImageId = 2130837796
D/VisualEffectCircleUnlockEffect( 1069): circleUnlockMaxWidth = 576
D/VisualEffectCircleUnlockEffect( 1069): circleUnlockMinWidth = 172
D/VisualEffectCircleUnlockEffect( 1069): outerStrokeWidth = 2
D/VisualEffectCircleUnlockEffect( 1069): innerStrokeWidth = 4
,D/VisualEffectCircleUnlockEffect( 1069): lockSequenceTotal = 30
,I/jxcore-log( 2685): getBuffer is called!!!!
I/jxcore-log( 2685): 
V/KeyguardUpdateMonitor( 1069): *** register callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@42a0a840
,V/KeyguardUpdateMonitor( 1069): *** unregister callback for null
V/KeyguardUpdateMonitor( 1069): *** register callback for com.android.keyguard.MSimCarrierText$1@429ccf90
,V/KeyguardUpdateMonitor( 1069): *** unregister callback for null
D/MSimCarrierText( 1069):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 0
D/CarrierText( 1069): getCarrierTextForSimState: status = Normal
D/CarrierText( 1069): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1069): updateCarrierText: text = 
D/CarrierText( 1069): getCarrierTextForSimState: status = SimNotReady
,D/CarrierText( 1069): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1069): updateCarrierText: text = 
D/MSimCarrierText( 1069):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 1
D/CarrierText( 1069): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1069): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1069): updateCarrierText: text = 
D/CarrierText( 1069): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1069): getCarrierTextForSimState: status = SimNotReady
D/MSimCarrierText( 1069): updateCarrierText: text = null
V/KeyguardUpdateMonitor( 1069): *** register callback for com.android.keyguard.EmergencyButton$1@42a55730
,V/KeyguardUpdateMonitor( 1069): *** unregister callback for null
,D/LockPatternUtils( 1069): isPcwEnable = null
D/EmergencyButton( 1069): enabled = false, :0
D/SecCameraShortcut( 1069): setCallback(): not null
D/SecuritySelectorView( 1069): hideBouncer mBouncerHelpText != null
D/KeyguardViewManager( 1069): mWindowLayoutParams not null
D/KeyguardHostView( 1069): onRestoreInstanceState, transport=1
I/KeyguardEffectViewMain( 1069): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 1069): KeyguardEffectViewParticleSpace : reset
I/Choreographer( 1069): Skipped 30 frames!  The application may be doing too much work on its main thread.
D/Sensors (  741): LightSensor enable = 0
D/Sensors (  741): LightSensor enableSensor = 0
D/SensorManager(  741): unregisterListener ::   
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/lights  (  741): led_pattern : 5 +
D/LightsService(  741): [SvcLED]  onSensorChanged::light value = 0
D/lights  (  741): led_pattern : 5 -
D/LightsService(  741): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/ContextualEventContainer( 1069): handleUpdate()
D/ContextualEventManager( 1069): getTopEventView()
D/ContextualEventManager( 1069): getTopContextualEvent()
,D/ContextualEventManager( 1069): top view = flightmode
I/KeyguardEffectViewMain( 1069): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1069): getTopEventClass()
,D/ContextualEventManager( 1069): getTopContextualEvent()
,D/ContextualEventManager( 1069): !isClockTop
D/ContextualEventManager( 1069): getTopEventClass()
,D/ContextualEventManager( 1069): getTopContextualEvent()
I/GoogleURLConnFactory( 1308): Using platform SSLCertificateSocketFactory
D/ContextualEventManager( 1069): !isClockTop
D/ContextualEventManager( 1069): getTopEventClass()
,D/ContextualEventManager( 1069): getTopContextualEvent()
I/dalvikvm( 1308): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1308): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1308): VFY: replacing opcode 0x6e at 0x0033
D/UsbManager( 1069):  :::: isUsb30Available :: return = false from pid = 1069
,W/ContextImpl( 1313): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:129 <bottom of call stack> 
,D/dalvikvm(  741): GC_EXPLICIT freed 1538K, 18% free 22603K/27484K, paused 7ms+12ms, total 149ms
,I/SettingSearch/SearchIntentReceiver( 1313): InitSerachDBThread thread end!
,I/System.out( 1308): Thread-53(HTTPLog):isShipBuild true
,I/System.out( 1308): Thread-53(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1069): GC_EXPLICIT freed 13140K, 32% free 31345K/46084K, paused 3ms+7ms, total 45ms
,I/sCloudBackupApp( 2828): sCloudBackupApp Version Info : 3.7.3.KK_APP
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
D/STATUSBAR-PhoneStatusBar( 1069): makeExpandedInvisible
D/PhoneStatusBarView( 1069): marqueeStatusBar:121, mClearCover:0
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
D/SecContextualClockFlightMode( 1069): handleUpdateClock()
D/KeyguardProperties( 1069): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1308): [GLSUser] IOException in getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> exception: Unable to resolve host "android.clients.google.com": No address associated with hostname)
,I/GLSUser ( 1308): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> status: NETWORK_ERROR)
,D/SecKeyguardFlightModeView( 1069): received broadcast android.intent.action.SCREEN_OFF
,I/GLSUser ( 1308): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1308): gms.StatusHelper Status from wire: NetworkError status: NETWORK_ERROR
,I/SELinux ( 2847): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2847):  
,W/Search.LoginHelper( 2135): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/accuweather( 1453): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1453): [KK AccuPhone]>>> SWW:440 [0:0] stopRefreshIcon : 1
,D/accuweather( 1453): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
,I/dalvikvm( 1644): Total arena pages for JIT: 11
,I/dalvikvm( 1644): Total arena pages for JIT: 12
I/dalvikvm( 1644): Total arena pages for JIT: 13
,I/dalvikvm( 1644): Total arena pages for JIT: 14
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SELinux ( 2847): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2847):  
I/SELinux ( 2847):  
,I/SELinux ( 2847): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2847): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2847): >>>>> Normal User
,E/dalvikvm( 2847): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,D/LockPatternUtils( 1069): isPcwEnable = null
,E/SELinux ( 2847): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/PowerManagerService(  741): [PWL] sb release: PowerManagerService.Broadcasts
,D/TimaKeyStoreProvider( 2847): in addTimaSignatureService
D/TimaKeyStoreProvider( 2847): Cannot add TimaSignature Service, License check Failed
,I/GLSUser ( 1308): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,D/ActivityThread( 2847): Added TimaKesytore provider
,D/SSRMv2:SIOP(  741): SIOP:: AP = 330, Delta = 0
,I/GLSUser ( 1308): [GLSUser] IOException in getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> exception: Unable to resolve host "android.clients.google.com": No address associated with hostname)
I/GLSUser ( 1308): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> status: NETWORK_ERROR)
I/GLSUser ( 1308): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1308): gms.StatusHelper Status from wire: NetworkError status: NETWORK_ERROR
,W/Search.LoginHelper( 2135): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/Icing   ( 1644): updateResources: need to parse f{com.google.android.gms}
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1308): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1308): [GLSUser] IOException in getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> exception: Unable to resolve host "android.clients.google.com": No address associated with hostname)
I/GLSUser ( 1308): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> status: NETWORK_ERROR)
I/GLSUser ( 1308): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1308): gms.StatusHelper Status from wire: NetworkError status: NETWORK_ERROR
,W/Search.LoginHelper( 2135): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=2847, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,I/GLSUser ( 1308): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/SELinux ( 2862): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2862):  
,I/GLSUser ( 1308): [GLSUser] IOException in getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> exception: Unable to resolve host "android.clients.google.com": No address associated with hostname)
I/GLSUser ( 1308): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> status: NETWORK_ERROR)
I/GLSUser ( 1308): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1308): gms.StatusHelper Status from wire: NetworkError status: NETWORK_ERROR
,W/Search.LoginHelper( 2135): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2135): canRun() : Opted Out
W/BackupManagerService(  741): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/BackupManagerService(  741): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,I/SELinux ( 2862): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2862):  
I/SELinux ( 2862):  
,I/SELinux ( 2862): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2862): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2862): >>>>> Normal User
,E/dalvikvm( 2862): >>>>> com.wssnps [ userId:0 | appId:1000 ]
,E/SELinux ( 2862): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2862): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2862): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2862): Added TimaKesytore provider
,I/Icing   ( 1644): Internal init done: storage state 0
,I/Icing   ( 1644): Post-init done
,D/NPS_WSSNPS( 2862): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2862): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.wssnps.smlNpsReceiver.onReceive:380 android.app.ActivityThread.handleReceiver:2698 
D/NPS_WSSNPS( 2862): [] Service onCreate!!
,I/SELinux ( 2878): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2878):  
,D/NPS_WSSNPS( 2862): [] NpsServiceTask Start
,I/NPS_WSSNPS( 2862): [44.140541] loadCryptionkeyLibrary
,I/NPS_WSSNPS( 2862): [44.140541] FirstLoad Or Not Exist
,D/dalvikvm( 2862): Trying to load lib /data/data/com.wssnps/files/libCryptionkey.so 0x42a10850
,D/dalvikvm( 2862): Added shared lib /data/data/com.wssnps/files/libCryptionkey.so 0x42a10850
,D/NPS_WSSNPS( 2862): [44.140541] smlDBHelper
,I/NPS_WSSNPS( 2862): [44.140541] AsyncBulkFlagCheck
,I/NPS_WSSNPS( 2862): [44.140541] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 2862): [44.140541] IsRemain_Asyncing nothing
,W/ContextImpl( 2862): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 com.wssnps.smlNpsService$1.run:108 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
D/NPS_WSSNPS( 2862): [44.140541] Service onDestroy
I/NPS_WSSNPS( 2862): [44.140541] smlBRConfigurationDelete
I/NPS_WSSNPS( 2862): [44.140541] smlBRMessageDelete
I/NPS_WSSNPS( 2862): [44.140541] smlBREmailDelete
I/NPS_WSSNPS( 2862): [44.140541] smlBRNetworkDelete
I/NPS_WSSNPS( 2862): [44.140541] smlBRCallLogDelete
I/NPS_WSSNPS( 2862): [44.140541] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 2862): [44.140541] smlBRPenMemoMDelete
I/NPS_WSSNPS( 2862): [44.140541] smlBRSMemoDelete
I/SELinux ( 2878): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2878):  
I/SELinux ( 2878):  
I/SELinux ( 2878): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/NPS_WSSNPS( 2862): [44.140541] cpuBooster release : false
E/SELinux ( 2878): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2878): >>>>> Normal User
E/dalvikvm( 2878): >>>>> com.samsung.android.app.accesscontrol [ userId:0 | appId:10064 ]
D/NPS_WSSNPS( 2862): [44.140541] dsServerSocket close
E/SELinux ( 2878): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2878): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2878): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2878): Added TimaKesytore provider
,I/SELinux ( 2895): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2895):  
,D/dalvikvm( 1644): GC_CONCURRENT freed 6343K, 42% free 11239K/19096K, paused 5ms+7ms, total 41ms
,I/SELinux ( 2895): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2895):  
I/SELinux ( 2895):  
,I/SELinux ( 2895): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2895): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2895): >>>>> Normal User
,E/dalvikvm( 2895): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
,E/SELinux ( 2895): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2895): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2895): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2895): Added TimaKesytore provider
,D/FileShare-Server( 2895): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/SELinux ( 2912): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2912):  
I/ActivityManager(  741): Killing 1294:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #43
,I/SELinux ( 2912): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2912):  
I/SELinux ( 2912):  
,I/SELinux ( 2912): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2912): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2912): >>>>> Normal User
,E/dalvikvm( 2912): >>>>> com.sec.android.nearby.mediaserver [ userId:0 | appId:10070 ]
,E/SELinux ( 2912): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2912): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2912): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2912): Added TimaKesytore provider
,I/AllShare(ASF-DMSLIB)( 2912): DMSReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,W/BackupManagerService(  741): dataChanged but no participant pkg='com.android.providers.settings' uid=10070
,I/SELinux ( 2927): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2927):  
I/ActivityManager(  741): Killing 1276:com.android.printspooler/u0a144 (adj 15): empty #43
,I/SELinux ( 2927): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2927):  
I/SELinux ( 2927):  
,I/SELinux ( 2927): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2927): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2927): >>>>> Normal User
,E/dalvikvm( 2927): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 2927): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2927): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2927): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2927): Added TimaKesytore provider
,I/IcingCorporaProvider( 2135): UpdateCorporaTask done [took 2279 ms] updated apps [took 2279 ms] 
,W/ContextImpl( 2927): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:61 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2942): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2942):  
,I/SELinux ( 2942): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2942):  
I/SELinux ( 2942):  
,I/SELinux ( 2942): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2942): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2942): >>>>> Normal User
,E/dalvikvm( 2942): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
,E/SELinux ( 2942): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2942): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2942): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2942): Added TimaKesytore provider
,D/BluetoothBDAdrressReceiver( 2942): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2942): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
W/ContextImpl( 2942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2954): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2954):  
D/BluetoothBDTestService( 1241): onCreate()
E/BluetoothBDTestService( 1241): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
E/BluetoothBDTestService( 1241): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1241): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/ActivityManager(  741): Killing 1774:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #43
I/ActivityManager(  741): Waited long enough for: ServiceRecord{4357d988 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/SELinux ( 2954): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2954):  
I/SELinux ( 2954):  
,I/SELinux ( 2954): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2954): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2954): >>>>> Normal User
,E/dalvikvm( 2954): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 2954): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 2954): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2954): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2954): Added TimaKesytore provider
,W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=2954, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,V/AlarmManager(  741): waitForAlarm result :4
,I/SELinux ( 2970): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2970):  
V/AlarmManager(  741): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
I/ActivityManager(  741): Killing 1787:com.sec.modem.settings/1000 (adj 15): empty #43
,I/SELinux ( 2970): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2970):  
I/SELinux ( 2970):  
,I/SELinux ( 2970): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2970): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2970): >>>>> Normal User
,E/dalvikvm( 2970): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 2970): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2970): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2970): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2970): Added TimaKesytore provider
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2927): Resource data:2131165197
,I/AMMetaDataParserService( 2927): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2927): Resource data:2131165194
I/AMMetaDataParserService( 2927): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/AMMetaDataParserService( 2927): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,E/PersonaManagerService(  741): returning null in  getPersonasForUser
,I/SELinux ( 2985): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2985):  
,I/ActivityManager(  741): Killing 1800:com.sec.tcpdumpservice/1000 (adj 15): empty #43
E/SMD     (  233): DCD ON
I/AMMetaDataParserService( 2927): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,D/dalvikvm(  240): GC_EXPLICIT freed 46K, 51% free 9505K/19096K, paused 3ms+3ms, total 28ms
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 51% free 9505K/19096K, paused 1ms+2ms, total 18ms
,I/SELinux ( 2985): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2985):  
I/SELinux ( 2985):  
,I/SELinux ( 2985): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2985): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2985): >>>>> Normal User
,E/dalvikvm( 2985): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 2985): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 51% free 9505K/19096K, paused 2ms+3ms, total 20ms
,I/AMMetaDataParserService( 2927): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,D/TimaKeyStoreProvider( 2985): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2985): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2985): Added TimaKesytore provider
,I/AMMetaDataParserService( 2927): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2927): Resource data:2131165194
I/AMMetaDataParserService( 2927): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/AMMetaDataParserService( 2927): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,I/AMMetaDataParserService( 2927): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,I/AMMetaDataParserService( 2927): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,I/AMMetaDataParserService( 2927): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
W/BackupManagerService(  741): dataChanged but no participant pkg='com.android.providers.settings' uid=10084
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,I/AMMetaDataParserService( 2927): Resource data:2131165195
I/AMMetaDataParserService( 2927): getResourceName:com.sec.android.gallery3d:xml/device_filter
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2927): Resource data:2131165204
I/AMMetaDataParserService( 2927): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2927): Resource data:2131165204
I/AMMetaDataParserService( 2927): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2927): Resource data:2131165204
I/AMMetaDataParserService( 2927): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2927): Resource data:2131099676
,I/AMMetaDataParserService( 2927): getResourceName:com.android.mms:xml/spellscroll
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
I/AMMetaDataParserService( 2927): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2927): Resource data:2131099648
I/AMMetaDataParserService( 2927): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/AMMetaDataParserService( 2927): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 2998): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2998):  
,I/AMMetaDataParserService( 2927): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
I/ActivityManager(  741): Killing 1841:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,I/AMMetaDataParserService( 2927): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/SELinux ( 2998): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2998):  
I/SELinux ( 2998):  
,I/SELinux ( 2998): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2998): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2927): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
E/dalvikvm( 2998): >>>>> Normal User
,E/dalvikvm( 2998): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
,E/SELinux ( 2998): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2998): in addTimaSignatureService
,I/AMMetaDataParserService( 2927): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/TimaKeyStoreProvider( 2998): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2998): Added TimaKesytore provider
,I/AMMetaDataParserService( 2927): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
I/AMMetaDataParserService( 2927): Resource data:2131099648
I/AMMetaDataParserService( 2927): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/AMMetaDataParserService( 2927): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/Icing   ( 1644): Indexing 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B from com.google.android.googlequicksearchbox
,I/AMMetaDataParserService( 2927): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 3010): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3010):  
I/ActivityManager(  741): Killing 1747:com.sec.android.app.mt/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2927): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/AMMetaDataParserService( 2927): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 3010): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3010):  
I/SELinux ( 3010):  
,I/SELinux ( 3010): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3010): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 3010): >>>>> Normal User
,E/dalvikvm( 3010): >>>>> com.dropbox.android [ userId:0 | appId:10091 ]
,E/SELinux ( 3010): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/Icing   ( 1644): Loaded CLD2 Version V2.0 - 20141016
,D/TimaKeyStoreProvider( 3010): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3010): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3010): Added TimaKesytore provider
,I/AMMetaDataParserService( 2927): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2927): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/Icing   ( 1644): Indexing done 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2927): Resource data:2131099648
,I/AMMetaDataParserService( 2927): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/AMMetaDataParserService( 2927): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2927): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2927): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3010): Setting receiver enabled: false
W/ContextImpl(  741): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/AMMetaDataParserService( 2927): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/com.dropbox.sync.android.a( 3010): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/AMMetaDataParserService( 2927): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/com.dropbox.sync.android.aa( 3010): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800H armeabi-v7a; en_US))
,I/AMMetaDataParserService( 2927): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=3010, uid=10091 requires android.permission.INTERACT_ACROSS_USERS
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2927): Resource data:2131099648
I/AMMetaDataParserService( 2927): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/SELinux ( 3032): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3032):  
I/ActivityManager(  741): Killing 1892:com.sec.phone/1001 (adj 15): empty #43
,I/AMMetaDataParserService( 2927): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2927): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 3032): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3032):  
I/SELinux ( 3032):  
,I/SELinux ( 3032): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3032): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3032): >>>>> Normal User
E/dalvikvm( 3032): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 3032): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2927): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/TimaKeyStoreProvider( 3032): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3032): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3032): Added TimaKesytore provider
,I/AMMetaDataParserService( 2927): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2927): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=3032, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 3032): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 3032): ELMEngine.ELMEngine( context ).
,D/elm:14132( 3032): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 3032): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/AMMetaDataParserService( 2927): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/SELinux ( 3046): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3046):  
,D/elm:14132( 3032): ElmAgentService : onCreate()
,D/elm:14132( 3032): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14132( 3032): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:14132( 3032): BootCompletedState : startBootCompleted() call
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2927): Resource data:2131099648
,D/elm:14132( 3032): ModuleBase.resetCalllogAPIAlarm()
I/AMMetaDataParserService( 2927): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,D/elm:14132( 3032): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:14132( 3032): Get License : 0
,D/elm:14132( 3032): ElmAgentService : onDestroy().
I/ActivityManager(  741): Killing 1992:com.google.android.configupdater/u0a3 (adj 15): empty #43
,I/AMMetaDataParserService( 2927): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 3046): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3046):  
I/SELinux ( 3046):  
,I/SELinux ( 3046): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3046): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3046): >>>>> Normal User
,E/dalvikvm( 3046): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,E/SELinux ( 3046): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2927): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/TimaKeyStoreProvider( 3046): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3046): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3046): Added TimaKesytore provider
,I/AMMetaDataParserService( 2927): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/AMMetaDataParserService( 2927): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2927): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/System.out( 3010): Thread-258(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3010): Thread-258(ApacheHTTPLog):isShipBuild true
,I/System.out( 3010): Thread-258(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux ( 3063): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3063):  
I/ActivityManager(  741): Killing 2115:com.sec.dsm.system/1000 (adj 15): empty #43
,I/System.out( 3010): pool-4-thread-1 calls detatch()
,I/AMMetaDataParserService( 2927): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2927): Resource data:2131099648
I/AMMetaDataParserService( 2927): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/SELinux ( 3063): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3063):  
I/SELinux ( 3063):  
,I/SELinux ( 3063): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3063): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3063): >>>>> Normal User
,E/dalvikvm( 3063): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,E/SELinux ( 3063): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2927): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/TimaKeyStoreProvider( 3063): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3063): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3063): Added TimaKesytore provider
,I/AMMetaDataParserService( 2927): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2927): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/CameraApp( 3063): CameraApp.onCreate()... mFeature : null
I/testFeature( 3063): Feature.Feature(context)
I/testFeature( 3063): Feature.readInternalDefaultXml()
,I/testFeature( 3063): ResetFeatureValue
I/CameraFirmware_broadcast( 3063): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 3063): CameraApp.getAppFeature()...
,I/AMMetaDataParserService( 2927): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 3077): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3077):  
I/ActivityManager(  741): Killing 2155:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2927): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2927): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/SELinux ( 3077): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3077):  
I/SELinux ( 3077):  
I/SELinux ( 3077): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
,E/SELinux ( 3077): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
E/dalvikvm( 3077): >>>>> Normal User
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
E/dalvikvm( 3077): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2927): Resource data:2131099671
E/SELinux ( 3077): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2927): getResourceName:com.android.mms:xml/searchable
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
,D/TimaKeyStoreProvider( 3077): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3077): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3077): Added TimaKesytore provider
,D/PackageIntentReceiver( 3077): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3077): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager(  741): Killing 2180:com.sec.kidsplat.installer/u0a158 (adj 15): empty #43
,D/dalvikvm( 2927): GC_CONCURRENT freed 4985K, 34% free 12701K/19096K, paused 4ms+4ms, total 48ms
,D/dalvikvm( 2927): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.GridSettings
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2927): Resource data:2131165216
,I/SELinux ( 3097): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3097):  
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/AMMetaDataParserService( 2927): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,I/AMMetaDataParserService( 2927): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SubSettings
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.TimDataConnectionDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429159
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296695
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429159
I/SELinux ( 3097): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3097):  
I/SELinux ( 3097):  
,I/SELinux ( 3097): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429144
E/SELinux ( 3097): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429144
E/dalvikvm( 3097): >>>>> Normal User
E/dalvikvm( 3097): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429144
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131297114
E/SELinux ( 3097): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ApnSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ApnSettingsTabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429146
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429146
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429168
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/mirror_link_settings
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429159
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296695
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.TetherSettings
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429159
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296695
D/TimaKeyStoreProvider( 3097): in addTimaSignatureService
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429144
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131297114
,D/TimaKeyStoreProvider( 3097): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429159
,D/ActivityThread( 3097): Added TimaKesytore provider
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296695
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429159
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296695
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429159
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296695
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429159
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296695
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429159
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296695
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429219
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429191
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429191
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429191
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429191
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429191
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429191
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131298419
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429191
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131298419
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/language_keyboard_settings_title
,I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429191
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131298419
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429176
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429176
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/sound_settings
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429173
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/display_settings
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429173
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429172
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429172
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429182
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/block_settings
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429173
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429186
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.DockSettings
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429186
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429173
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131297804
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429173
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/display_settings
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429228
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.users.UserOptions
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429128
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429128
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/application_settings
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429128
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429127
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429127
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429128
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429128
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429127
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429127
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429128
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429153
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429224
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.CarrierMatchSetting
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429224
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296750
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/security_settings_title
,I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429224
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429123
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/privacy_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429224
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296750
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429224
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296750
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429187
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429187
I/ActivityManager(  741): Waited long enough for: ServiceRecord{435d3450 u0 com.samsung.android.providers.context/.ContextService}
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/accessibility_settings
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131298587
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429187
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131298587
,D/dalvikvm(  741): GC_EXPLICIT freed 1411K, 18% free 22683K/27484K, paused 4ms+10ms, total 123ms
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429191
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429180
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/driving_mode
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429223
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429225
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429159
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296695
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429165
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429225
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429223
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131297938
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429223
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131297938
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429161
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429163
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429167
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131296695
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429221
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429221
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429119
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429217
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429224
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429224
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429159
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429173
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429208
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429286
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429224
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429201
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429185
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429185
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2927): Resource data:2131299843
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/power_saving_mode_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429185
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429185
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429222
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/power_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429186
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 2927): Resource data:1
W/ResourceType( 2927): No package identifier when getting name for resource number 0x00000001
W/System.err( 2927): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 2927): 	at android.content.res.Resources.getResourceName(Resources.java:3017)
W/System.err( 2927): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 2927): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 2927): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 2927): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2927): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 2927): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429199
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2927): Resource data:2131301070
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429173
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2927): Resource data:2131297804
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429203
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429193
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429194
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429206
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2927): Resource data:2131300118
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429196
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429260
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429197
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429291
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429228
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429199
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429199
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429199
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429199
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.NetworkManagement
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.MultiSimCardManagerPreference
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.NetworkManagementSetting
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.DualHelpActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.DualSoundRingtoneSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.RingtoneSettingTabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.IccLockTabSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429173
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429285
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429172
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2927): Resource data:2131301505
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429203
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429203
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2927): Resource data:2131302910
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429179
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2130838248
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2927): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429216
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429209
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429209
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAlertDialogActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429177
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429212
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429213
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429153
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2927): Resource data:2131302078
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429153
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2927): Resource data:2131302078
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429153
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2927): Resource data:2131302107
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429159
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429159
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429117
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429122
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429195
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2927): Resource data:2131297804
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 2927):, Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429151
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429204
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429204
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429195
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2130838300
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2927): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2130838300
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2927): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429202
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/header_display_multi_window
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429202
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2927): Resource data:2131165381
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:xml/searchable
I/AMMetaDataParserService( 2927): getResourceTypeNamexml
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429124
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429187
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/accessibility_settings
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2927): Resource data:2131298587
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2927): getResourceTypeNamestring
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429198
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429258
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429220
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/safetycare_settings
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429220
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429276
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429276
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2927): Resource data:2131429148
,I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429242
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/toddler_mode
,I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.KnoxSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429211
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2130838248
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
,I/AMMetaDataParserService( 2927): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2927): Resource data:2131429192
I/AMMetaDataParserService( 2927): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 2927): getResourceTypeNameid
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintOnehandGrip
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
,I/GAV2    ( 2135): Thread[GAThread,5,main]: No campaign data found.
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2927): Resource data:2131034120
I/GAv4-SVC( 1644): Google Analytics 8.3.01 is starting up.
,W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=3097, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
I/AMMetaDataParserService( 2927): getResourceName:com.android.contacts:xml/searchable
I/AMMetaDataParserService( 2927): getResourceTypeNamexml
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
I/AMMetaDataParserService( 2927): Resource data:2131034113
I/AMMetaDataParserService( 2927): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/AMMetaDataParserService( 2927): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/AMMetaDataParserService( 2927): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/Babel   ( 3097): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3097): MmsConfig.loadMmsSettings
I/Babel   ( 3097): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,I/Babel   ( 3097): MmsConfig.loadFromDatabase
,E/Babel   ( 3097): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3097): MmsConfig.loadFromResources
,E/Babel   ( 3097): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3097): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,I/AMMetaDataParserService( 2927): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,D/dalvikvm( 3097): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3097): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3097): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 3097): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3097): VFY: unable to resolve instance field 46
,D/dalvikvm( 3097): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 3097): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3097): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3097): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 3097): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3097): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 3097): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42b38ab0
,W/Settings( 3097): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 3097): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42b38ab0
,D/dalvikvm( 3097): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42b38ab0, skipping init
,D/dalvikvm( 3097): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42b38ab0
,D/dalvikvm( 3097): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42b38ab0
,V/JNIHelp ( 3097): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/AMMetaDataParserService( 2927): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2927): Resource data:2131034113
I/AMMetaDataParserService( 2927): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,V/Babel   ( 3097): babel boot account: thalitester@gmail.com
,V/Babel   ( 3097): babel boot account: SMS
,I/AMMetaDataParserService( 2927): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/SELinux ( 3133): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3133):  
I/ActivityManager(  741): Killing 2193:com.sec.factory/1000 (adj 15): empty #43
,D/dalvikvm( 3097): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42b38ab0
,D/dalvikvm( 3097): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42b38ab0
D/dalvikvm( 3097): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42b38ab0
,D/dalvikvm( 3097): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42b38ab0
,I/AMMetaDataParserService( 2927): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/AMMetaDataParserService( 2927): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
I/SELinux ( 3133): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3133):  
I/SELinux ( 3133):  
,I/SELinux ( 3133): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3133): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3133): >>>>> Normal User
,E/dalvikvm( 3133): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 3133): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3133): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3133): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3133): Added TimaKesytore provider
,I/AMMetaDataParserService( 2927): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 2927): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 2927): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 2927): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
I/AMMetaDataParserService( 2927): Resource data:2131034112
,I/AMMetaDataParserService( 2927): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/AMMetaDataParserService( 2927): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
,I/ProviderInstaller( 3097): Installed default security provider GmsCore_OpenSSL
,V/AlarmManager(  741): waitForAlarm result :4
,V/AlarmManager(  741): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  741): waitForAlarm result :4
,V/AlarmManager(  741): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/AMMetaDataParserService( 2927): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
,I/SELinux ( 3149): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3149):  
I/ActivityManager(  741): Killing 2214:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2927): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
,I/AMMetaDataParserService( 2927): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sams,ung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
I/AMMetaDataParserService( 2927): Resource data:2131034113
I/AMMetaDataParserService( 2927): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/SELinux ( 3149): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3149):  
I/SELinux ( 3149):  
,I/SELinux ( 3149): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3149): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3149): >>>>> Normal User
,E/dalvikvm( 3149): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
,I/AMMetaDataParserService( 2927): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,E/SELinux ( 3149): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3149): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3149): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3149): Added TimaKesytore provider
,I/AMMetaDataParserService( 2927): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/dalvikvm( 2927): GC_CONCURRENT freed 2269K, 36% free 12372K/19096K, paused 2ms+2ms, total 28ms
,I/AMMetaDataParserService( 2927): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/AMMetaDataParserService( 2927): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
W/ContextImpl( 3149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3149): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2927): Resource data:2131034116
,W/ContextImpl( 3149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
I/knox    ( 3149): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/AMMetaDataParserService( 2927): getResourceName:com.android.contacts:xml/findo_searchable
I/AMMetaDataParserService( 2927): getResourceTypeNamexml
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
D/knox    ( 3149): KNOXAgentService : onCreate()
D/knox    ( 3149): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3149): KNOXAgentService. startJobThread() start
D/knox    ( 3149): KNOXAgentService. JobThread()
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2927): Resource data:2131099668
D/knox    ( 3149): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3149): KNOXAgentService. startJobThread() wait
I/AMMetaDataParserService( 2927): getResourceName:com.sec.android.app.sbrowser:xml/searchable
I/AMMetaDataParserService( 2927): getResourceTypeNamexml
I/SELinux ( 3167): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3167):  
I/AMMetaDataParserService( 2927): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 2927): Resource data:2131099650
D/knox    ( 3149): mKnoxAgentEngine.ELMEngine( context , reStart:true).
I/AMMetaDataParserService( 2927): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 2927): getResourceTypeNamexm,l
D/knox    ( 3149): KNOXAgentService : onDestroy().
D/knox    ( 3149): ModuleBase.cancelAllAlarmManageModule()
,I/AMMetaDataParserService( 2927): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,I/AMMetaDataParserService( 2927): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
I/SELinux ( 3167): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3167):  
I/SELinux ( 3167):  
,I/SELinux ( 3167): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3167): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3167): >>>>> Normal User
,E/dalvikvm( 3167): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
,E/SELinux ( 3167): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3167): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3167): Cannot add TimaSignature Service, License check Failed
,I/AMMetaDataParserService( 2927): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
,D/ActivityThread( 3167): Added TimaKesytore provider
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 2927): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAutoDiscover
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
,I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2927): Resource data:2131099667
,I/AMMetaDataParserService( 2927): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,E/KnoxSetupWizardClient( 3167): isShipMode : 1
,I/KnoxSetupWizardClient( 3167): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 2927): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559
,D/ShortcutReceiver( 3167):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/yash    ( 3167): setDisableWidget>size:0
,E/BluetoothManagerService(  741): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 2685): packageName : com.example.hello
,I/WifiManager( 2685): setWifiEnabled : false
,I/WifiService(  741): setWifiEnabled: false pid=2685, uid=10180
,I/jxcore-log( 2685): ****TEST TOOK:  5086  ms ****
I/jxcore-log( 2685): 
,I/jxcore-log( 2685): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2685): 
,I/AMMetaDataParserService( 2927): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558
,W/System.err( 3167): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 3167): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 3167): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 3167): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3167): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 3167): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
,W/System.err( 3167): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/System.err( 3167): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
,W/System.err( 3167): 	at android.os.Parcel.readException(Parcel.java:1469)
,I/SELinux ( 3181): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3181):  
,I/AMMetaDataParserService( 2927): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
I/ActivityManager(  741): Killing 1698:com.fmm.dm/1000 (adj 15): empty #43
,W/System.err( 3167): 	at android.os.Parcel.readException(Parcel.java:1419)
,W/System.err( 3167): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
D/dalvikvm(  240): GC_EXPLICIT freed 47K, 51% free 9505K/19096K, paused 2ms+2ms, total 25ms
W/System.err( 3167): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
,W/System.err( 3167): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
W/System.err( 3167): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
,W/System.err( 3167): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 51% free 9505K/19096K, paused 1ms+3ms, total 18ms
I/SELinux ( 3181): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3181):  
I/SELinux ( 3181):  
,I/SELinux ( 3181): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3181): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3181): >>>>> Normal User
,E/dalvikvm( 3181): >>>>> com.LocalFota [ userId:0 | appId:10110 ]
,E/SELinux ( 3181): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 51% free 9505K/19096K, paused 2ms+3ms, total 20ms
,I/AMMetaDataParserService( 2927): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
,D/TimaKeyStoreProvider( 3181): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3181): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3181): Added TimaKesytore provider
,I/AMMetaDataParserService( 2927): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
,I/AMMetaDataParserService( 2927): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
,I/DBG_WSS_LF( 3181): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
,I/DBG_WSS_LF( 3181): [20.0040.140326][Line:27][<init>] First call
W/ActivityManager(  741): Permission Denial: getCurrentUser() from pid=3181, uid=10110 requires android.permission.INTERACT_ACROSS_USERS
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2927): Resource data:2131099689
,I/AMMetaDataParserService( 2927): getResourceName:com.android.email:xml/spellscroll
I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2927): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2927): Resource data:2131099685
I/AMMetaDataParserService( 2927): getResourceName:com.android.email:xml/searchable
I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/AMMetaDataParserService( 2927): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 2927): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2927): getResourcePackageName:com.android.keyguard.layout
,I/AMMetaDataParserService( 2927): Resource data:2130903052
,I/AMMetaDataParserService( 2927): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
I/AMMetaDataParserService( 2927): getResourceTypeNamelayout
I/AMMetaDataParserService( 2927): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2927): Resource data:2131034112
I/AMMetaDataParserService( 2927): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 2927): getResourceTypeNamexml
,I/DBG_WSS_LF( 3181): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_WSS_LF( 3181): [20.0040.140326][Line:31][onReceive] *** boot complete ***
,I/DBG_WSS_LF( 3181): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
,I/DBG_WSS_LF( 3181): [20.0040.140326][Line:41][onReceive] nStatus : -1
,I/AMMetaDataParserService( 2927): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,I/SELinux ( 3204): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3204):  
I/ActivityManager(  741): Killing 2228:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
,I/AMMetaDataParserService( 2927): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 2927): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
I/PowerManagerService(  741): [PWL] Off : 5s ago
I/PowerManagerService(  741): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/ActivityManager(  741): Killing 2240:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #43
I/PowerManagerService(  741): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  741): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=741, ws=WorkSource{10044}) (elapsedTime=2992)
I/PowerManagerService(  741): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10084, pid=2985, ws=null) (elapsedTime=2587)
,I/SELinux ( 3204): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3204):  
I/SELinux ( 3204):  
,I/SELinux ( 3204): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3204): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3204): >>>>> Normal User
,E/dalvikvm( 3204): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
,E/SELinux ( 3204): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3204): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3204): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3204): Added TimaKesytore provider
,D/StatusChecker( 3204): onReceive : android.intent.action.BOOT_COMPLETED
,I/SELinux ( 3218): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3218):  
I/ActivityManager(  741): Killing 2263:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,I/SELinux ( 3218): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3218):  
I/SELinux ( 3218):  
,I/SELinux ( 3218): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3218): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3218): >>>>> Normal User
,E/dalvikvm( 3218): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10133 ]
,E/SELinux ( 3218): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3218): in addTimaSignatureService
,E/SMD     (  233): DCD ON
,D/TimaKeyStoreProvider( 3218): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3218): Added TimaKesytore provider
,D/AndroidRuntime( 3189): 
D/AndroidRuntime( 3189): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3189): CheckJNI is OFF
,D/AndroidRuntime( 3189): setted country_code = Poland
,D/AndroidRuntime( 3189): setted countryiso_code = PL
D/AndroidRuntime( 3189): setted sales_code = XEO
D/AndroidRuntime( 3189): readGMSProperty: start
,D/AndroidRuntime( 3189): readGMSProperty: already setted!!
D/AndroidRuntime( 3189): readGMSProperty: end
,D/AndroidRuntime( 3189): addProductProperty: start
,D/QuickConnect( 3218): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 3189): Trying to load lib libjavacore.so 0x0
,W/BackupManagerService(  741): dataChanged but no participant pkg='com.android.providers.settings' uid=10133
D/dalvikvm( 3189): Added shared lib libjavacore.so 0x0
D/QuickConnect( 3218): Utils.setQCRunningSetting - set : 0
I/QuickConnect( 3218): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
D/dalvikvm( 3189): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3189): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3189): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
V/QuickConnect( 3218): SconnectManager.getInstance - () return existing instance null
W/ContextImpl( 3218): Implicit intents with startService are not safe: Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } android.content.ContextWrapper.startServiceAsUser:517 android.content.ContextWrapper.startServiceAsUser:517 com.samsung.android.sconnect.periph.PeriphStartReceiver.onReceive:30 
I/QuickConnect( 3218): PeriphService.onCreate - [START]
,I/SELinux ( 3237): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3237):  
,I/QuickConnect( 3218): PeriphService.onCreate - [START] USER_OWNER
,D/QuickConnect( 3218): PeriphService.setProcessForeground - Build.VERSION.SDK_INT = 19
,I/QuickConnect( 3218): PeriphService.setProcessForeground - true of JB_MR2 complete 
I/QuickConnect( 3218): PeriphService.setState - 0 >> 1
,V/QuickConnect( 3218): PeriphService.runService - 
,I/QuickConnect[1.1][2] ( 3218): SconnectManager.SconnectManager - initiate from com.samsung.android.sconnect.periph.PeriphService@42a185a0
I/QuickConnect[1.1][2] ( 3218): SconnectManager.SconnectManager - set getApplicationContext android.app.Application@42a10528
,D/QuickConnect[1.1][2] ( 3218): SconnectManager.registerBroadcast - --
,D/QuickConnect[1.1][2] ( 3218): SconnectManager.SconnectManager - REQUEST_ID :  1
,D/QuickConnect[1.1][2] ( 3218): ScanThread.ScanThread - created!
,V/QuickConnect[1.1][2] ( 3218): BluetoothHelper.BluetoothHelper - 
,D/QuickConnect[1.1][2] ( 3218): BluetoothHelper.registerBluetoothAdapterReceiver - mIsBluetoothAdapterReceiver = false
,V/QuickConnect[1.1][2] ( 3218): BleHelper.BleHelper - Constructor
,I/SELinux ( 3237): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3237):  
I/SELinux ( 3237):  
,I/SELinux ( 3237): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3237): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3237): >>>>> Normal User
,E/dalvikvm( 3237): >>>>> com.sec.android.service.bezel [ userId:0 | appId:1000 ]
,E/SELinux ( 3237): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/QuickConnect[1.1][2] ( 3218): BleHelper.startScan - not isGattServiceReady. Try to BLE On calling addLeRadioReference()
,D/BluetoothRadioManager( 3218): addLeRadioReference: Add CB  com.samsung.android.sconnect.common.net.BleHelper$GattServiceStateChangeCallback@42a2b950
D/BluetoothRadioManager( 3218):  addRadioReference enabled = false
,D/BluetoothRadioManager( 3218):  BLE Radio count is : 1
D/BluetoothRadioManager( 3218): addLeRadioReference: isRadioEnabled() =  false
V/QuickConnect[1.1][2] ( 3218): BleHelper.mSearchWearable - true
,D/BluetoothManagerService(  741): foregroundUser: 0
,D/TimaKeyStoreProvider( 3237): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3237): Cannot add TimaSignature Service, License check Failed
,V/QuickConnect[1.1][2] ( 3218): UpnpHelper.UpnpHelper - 
V/QuickConnect[1.1][2] ( 3218): JmdnsHelper.JmdnsHelper - Constructor
,D/ActivityThread( 3237): Added TimaKesytore provider
V/QuickConnect[1.1][2] ( 3218): P2pHelper.P2pHelper - EXEC
,D/QuickConnect[1.1][2] ( 3218): p2pHelperWorkThread.p2pHelperWorkThread - created!
,E/BluetoothManagerService(  741): Package is exist.
,I/SELinux ( 3251): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3251):  
,D/QuickConnect[1.1][2] ( 3218): WifiHelper.WifiHelper -  -- 
,D/WifiDisplayAdapter(  741): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/memtrack( 3189): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3189): failed to load memtrack module: -2
I/QuickConnect[1.1][2] ( 3218): CentralActionManager.CentralActionManager - EXEC
V/QuickConnect[1.1][2] ( 3218): BluetoothOppActionHelper.BluetoothOppActionHelper - 
V/QuickConnect[1.1][2] ( 3218): GroupVoiceTalkActionHelper.GroupVoiceTalkActionHelper -  --
V/QuickConnect[1.1][2] ( 3218): SmartHomeActionHelper.SmartHomeActionHelper - --
V/QuickConnect[1.1][2] ( 3218): ScreenMirrorActionHelper.ScreenMirrorActionHelper - 
V/QuickConnect[1.1][2] ( 3218): BluetoothActionHelper.BluetoothActionHelper - 
D/BluetoothAdapter( 3218): 1117944800: getState() :  mService = null. Returning STATE_OFF
D/BezelQuickConnect( 3237): BezelBroadcastReceiver - onReceive : android.intent.action.BOOT_COMPLETED
D/BezelQuickConnect( 3237): BezelBroadcastReceiver - StartBezelInteractionService
D/BezelQuickConnect( 3237): BezelManagerService - setProcessForeground, Build.VERSION.SDK_INT = 19
I/BezelQuickConnect( 3237): BezelManagerService - setProcessForeground, true of JB_MR2 complete 
,D/BezelQuickConnect( 3237): BezelBroadcastReceiver - onReceive : Send to quickpanel - service.ENABLED
,V/PhoneStatusBar( 1069): onReceive: Intent { act=com.sec.android.sconnect.service.ENABLED flg=0x10 }mQconnectEnable = true
W/ContextImpl( 3237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.android.service.bezel.BezelBroadcastReceiver.onReceive:40 android.app.ActivityThread.handleReceiver:2698 
,E/BluetoothHeadset( 3218): BTStateChangeCB is registed
,E/NetworkSettingsReceiver( 1761): onReceive: android.intent.action.BOOT_COMPLETED
,E/BluetoothHeadset( 3218): BluetoothHeadset service is binded
D/STATUSBAR-PhoneStatusBar( 1069): showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
,I/SELinux ( 3251): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3251):  
I/SELinux ( 3251):  
,I/SELinux ( 3251): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3251): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3251): >>>>> Normal User
,E/dalvikvm( 3251): >>>>> com.android.bluetooth [ userId:0 | appId:1002 ]
,I/QuickConnect[1.1][2] ( 3218): SconnectManager.getInstance - make new instance com.samsung.android.sconnect.SconnectManager@42a1a198
,V/QuickConnect[1.1][2] ( 3218): SconnectManager.getInstance - return existing instance com.samsung.android.sconnect.SconnectManager@42a1a198
,E/SELinux ( 3251): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,V/QuickConnect[1.1][2] ( 3218): PreDiscoveryHelper.PreDiscoveryHelper -  -- 
,D/QuickConnect[1.1][2] ( 3218): PreDiscoveryHelper.setVisibilityFromSystemDb - --
,D/QuickConnect[1.1][2] ( 3218): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 3218): Utils.getFromDb -  Key[quick_connect_contact_only], isEnabled [1] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 3218): PreDiscoveryHelper.setVisibilityFromSystemDb - isAllowToConnect : false, isContactOnly : true, visibilitySetting : 2
D/QuickConnect[1.1][2] ( 3218): PreDiscoveryHelper.changeResponseSetting - changed: 2
V/QuickConnect[1.1][2] ( 3218): PreDiscoveryHelper.updateAdvData - 
,V/QuickConnect[1.1][2] ( 3218): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a1a198
,D/dalvikvm( 3189): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,V/QuickConnect[1.1][2] ( 3218): PreDiscoveryHelper.updateRespTarget - 
,D/TimaKeyStoreProvider( 3251): in addTimaSignatureService
,W/BroadcastQueue(  741): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.android.calendar/.magazine.CalendarUpdateRelatedDataReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
D/TimaKeyStoreProvider( 3251): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3251): Added TimaKesytore provider
,I/SELinux ( 3266): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3266):  
,D/QuickConnect[1.1][2] ( 3218): PreDiscoveryHelper.initializeAdvData - 
,V/QuickConnect[1.1][2] ( 3218): PreDiscoveryHelper.initializeAdvData - name: Galaxy S5-2(11)
D/QuickConnect[1.1][2] ( 3218): PreDiscoveryHelper.initializeAdvData - name selected: Galaxy S5-2(11)
,V/QuickConnect[1.1][2] ( 3218): CONTACT_Info.getMyMobileNumber - 
,D/AndroidRuntime( 3189): Calling main entry com.android.commands.pm.Pm
,D/QuickConnect[1.1][2] ( 3218): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3218): CONTACT_Info.getMyMobileNumber - null 
I/SELinux ( 3266): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3266):  
I/SELinux ( 3266):  
,I/SELinux ( 3266): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3266): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3266): >>>>> Normal User
,E/dalvikvm( 3266): >>>>> com.sec.android.app.camera [ userId:0 | appId:10147 ]
,D/QuickConnect[1.1][2] ( 3218): NetUtil.getP2pMacFromWifiMac - ($)
,V/QuickConnect[1.1][2] ( 3218): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a1a198
,E/SELinux ( 3266): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/QuickConnect[1.1][2] ( 3218): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.emeeting.b2c.hancom
,D/QuickConnect[1.1][2] ( 3218): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.emeeting
,D/PackageManagerService(  741): deletePackageAsUser- pkg:com.example.hello, userId:0
D/PersonaManagerService(  741): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/QuickConnect[1.1][2] ( 3218): AppPackageUtil.isStubApk - but Stub version[2.7.025] of com.samsung.groupcast
,W/QuickConnect[1.1][2] ( 3218): AppPackageUtil.isAppInstalled - this is Stub - com.samsung.groupcast
D/QuickConnect[1.1][2] ( 3218): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.samsung.groupcast
,D/PersonaManagerService(  741): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  741): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  741): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  741): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/TimaKeyStoreProvider( 3266): in addTimaSignatureService
W/QuickConnect[1.1][2] ( 3218): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3218): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3218): PeriphService.registerUserReceiver - mIsUserReceiver == false
D/PackageManagerService(  741): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  741): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy(  741): getApplicationUninstallationEnabled
I/QuickConnect[1.1][2] ( 3218): PeriphService.onStartCommand - USER_OWNER
I/QuickConnect[1.1][2] ( 3218): PeriphService.onStartCommand - Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } flags[0] startId[1]
,I/QuickConnect[1.1][2] ( 3218): PeriphService.onStartCommand - Action: com.samsung.android.sconnect.periph.START_SERVICE
D/ApplicationPolicy(  741): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService(  741): deletePackageX- pkg:com.example.hello, userId:0
,D/TimaKeyStoreProvider( 3266): Cannot add TimaSignature Service, License check Failed
D/PackageManager(  741): START PACKAGE DELETE: observer{1118253216}
D/PackageManager(  741): pkg{<packageName>}
D/PackageManager(  741): user{0}
D/PackageManager(  741): deletePackageAsUser : uid = 2000 userId = 0
,D/PackageManager(  741): [MSG] DELETE_PACKAGE_AS_USER
D/ActivityThread( 3266): Added TimaKesytore provider
,D/BtSettings.ProfileConfig( 3251): Adding GattService
,D/BtSettings.ProfileConfig( 3251): Adding HeadsetService
D/BtSettings.ProfileConfig( 3251): Adding A2dpService
D/BtSettings.ProfileConfig( 3251): Adding HidService
D/BtSettings.ProfileConfig( 3251): Adding HealthService
,D/BtSettings.ProfileConfig( 3251): Adding PanService
,D/BtSettings.ProfileConfig( 3251): Adding BluetoothMapService
,W/dalvikvm( 3266): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,D/PackageManager(  741): !@killApplicatoin: 10180, uninstall pkg
,I/ActivityManager(  741): Killing 2685:com.example.hello/u0a180 (adj 0): stop com.example.hello
,D/CustomFrequencyManagerService(  741): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 741  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  741): mDVFSHelper.acquire()
,D/BluetoothAdapterService( 3251): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterState( 3251): make
I/bluedroid( 3251): init
,I/BluetoothAdapterState( 3251): Entering OffState
,I/SurfaceFlinger(  239): id=16 Removed NainActivit (7/11)
,I/SurfaceFlinger(  239): id=16 Removed NainActivit (-2/11)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/WindowState(  741): WIN DEATH: Window{426d8de0 u0 com.example.hello/com.example.hello.MainActivity}
I/bte_conf( 3251): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/SurfaceFlinger(  239): id=16 Removed NainActivit (-2/11)
,I/bluedroid( 3251): get_profile_interface socket
,I/GKI_LINUX( 3251): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterService( 3251):  checkAddrForIOP: Loading from conf
E/BluetoothServiceJni( 3251): populateRssiValuesNative
I/bluedroid( 3251): getModelRssiValues
,E/BluetoothServiceJni( 3251): model_rssi_values_callback: low = -70, mid = -60, high = 127
,W/PackageSettings(  741): Skipping PackageSetting{4309f7e8 com.test.thalitest/10179} due to missing metadata
,D/PackageManager(  741): setPackageStoppedState - Execution time: 143 ms
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/PackageManager(  741): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10180, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/SurfaceWidgetView( 1252): destroyHardwareResources():1130458416
,I/bluedroid( 3251): config_hci_snoop_log
,D/BluetoothManagerService(  741): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/BluetoothRadioManager( 3218): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42a82f60
,D/BluetoothRadioManager( 3218): onBluetoothServiceUp()  registerRadioClient mUUID = 7cfea7e1-63a5-4d2a-aed6-f01afc0f6ce7
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/PackageManager(  741): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10180, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/bluedroid( 3251): update_radio_count
,D/BluetoothAdapterState( 3251): CURRENT_STATE=OFF, MSG = USER_TURN_ON_RADIO
I/BluetoothAdapterState( 3251): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=false
D/BluetoothAdapterState( 3251): CURRENT_STATE=PENDING, MSG = BEGIN_ENABLE_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
,I/bluedroid( 3251): enable
,I/bt_hci_bdroid( 3251): init
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/bt_vendor( 3251): bt-vendor : init
I/bt_vendor( 3251): bt-vendor : get_bt_soc_type
E/bt_vendor( 3251): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 3251): init: Local BD Address : dc:06:b5:96:94:38
,D/bt_userial_mct( 3251): userial_init
I/bt_vendor( 3251): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3251): Starting hciattach daemon
,I/bt_vendor( 3251): try to set false
D/Launcher( 1252): onRestart, Launcher: 1118525368
D/Launcher( 1252): onStart, Launcher: 1118525368
,D/Launcher.HomeView( 1252): onStart
I/bt_vendor( 3251): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 3251): Starting hciattach daemon
,I/bt_vendor( 3251): try to set true
,D/AdaptiveEventManager( 1069): action=android.intent.action.PACKAGE_REMOVED
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1453): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1453): [237392/5] SurfaceWidget drawing first frame
,W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  741): Reconfiguring input devices.  changes=0x00000010
,I/FPMS_FingerprintManagerService( 1088): onReceive: android.intent.action.PACKAGE_REMOVED
,D/QuickConnect[1.1][2] ( 3218): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.example.hello
I/PackageManager(  741):   Action: "android.intent.action.SENDTO"
I/PackageManager(  741):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  741):   Scheme: "sms"
I/PackageManager(  741): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 1412): GC_EXPLICIT freed 4145K, 48% free 9984K/19096K, paused 3ms+5ms, total 77ms
,I/qcom-bluetooth( 3289): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/bt_hci_bdroid( 3251): bt_hc_worker_thread started
,D/dalvikvm( 2135): GC_EXPLICIT freed 1290K, 41% free 11341K/19096K, paused 3ms+20ms, total 116ms
,I/PackageManager(  741):   Action: "android.intent.action.SENDTO"
I/PackageManager(  741):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  741):   Scheme: "smsto"
I/PackageManager(  741): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  741):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  741):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  741):   Scheme: "mms"
I/PackageManager(  741): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3295): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3295):  
I/PackageManager(  741):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  741):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  741):   Scheme: "mmsto"
I/PackageManager(  741): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/ActivityManager(  741): Killing 2283:com.sec.android.app.mss/u0a21 (adj 15): empty #43
,I/SurfaceFlinger(  239): id=18 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/qcom-bluetooth( 3299): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/SurfaceFlinger(  239): id=19 createSurf (1x1),2 flag=404, CatteryCove
,I/PackageManager(  741):   Action: "android.intent.action.SENDTO"
I/PackageManager(  741):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  741):   Scheme: "sms"
,I/qcom-bluetooth( 3301): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/RCPManagerService(  741): PackageReceiver onReceive()
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,I/PackageManager(  741): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SELinux ( 3295): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3295):  
I/SELinux ( 3295):  
I/SELinux ( 3295): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3295): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3295): >>>>> Normal User
E/dalvikvm( 3295): >>>>> com.sec.android.inputmethod [ userId:0 | appId:1000 ]
E/SELinux ( 3295): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/HarmonyEASService(  741): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/qcom-bluetooth( 3307): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/PackageManager(  741):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  741):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  741):   Scheme: "smsto"
,I/PackageManager(  741): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/qcom-bluetooth( 3310): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3312): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/TimaKeyStoreProvider( 3295): in addTimaSignatureService
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/qcom-bluetooth( 3314): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/PackageManager(  741):   Action: "android.intent.action.SENDTO"
I/PackageManager(  741):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  741):   Scheme: "mms"
I/PackageManager(  741): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/CustomFrequencyManagerService(  741): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 741  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  741): mDVFSHelper.release()
,D/TimaKeyStoreProvider( 3295): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3295): Added TimaKesytore provider
D/CustomFrequencyManagerService(  741): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 741  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/PackageManager(  741):   Action: "android.intent.action.SENDTO"
I/PackageManager(  741):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  741):   Scheme: "mmsto"
I/PackageManager(  741): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/EnterpriseDeviceManagerService(  741): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  741): Admin package name: com.google.android.gms
,D/dalvikvm(  741): GC_EXPLICIT freed 2407K, 17% free 22946K/27484K, paused 7ms+14ms, total 268ms
D/PackageManager(  741): delete sourFile : 
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 3189): Shutting down VM
D/PackageManager(  741): delete native library directory: 
D/PackageManager(  741): return delete result to caller: 1118253216
,D/PackageManager(  741): returnCode: 1
D/dalvikvm( 3189): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 2ms
,I/PackageManager(  741):   Action: "android.intent.action.SENDTO"
I/PackageManager(  741):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  741):   Scheme: "sms"
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  741): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  741):   Action: "android.intent.action.SENDTO"
I/PackageManager(  741):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  741):   Scheme: "smsto"
I/PackageManager(  741): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/BackupManagerService(  741): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  741): removePackageParticipantsLocked: uid=10180 #1
I/PackageManager(  741):   Action: "android.intent.action.SENDTO"
I/PackageManager(  741):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  741):   Scheme: "mms"
I/PackageManager(  741): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3317): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3317):  
I/ActivityManager(  741): Killing 2297:com.sec.android.app.msa/u0a23 (adj 15): empty #43
,I/PackageManager(  741):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  741):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  741):   Scheme: "mmsto"
I/PackageManager(  741): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 3317): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3317):  
I/SELinux ( 3317):  
,I/SELinux ( 3317): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3317): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3317): >>>>> Normal User
,E/dalvikvm( 3317): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 3317): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 3317): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3317): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3317): Added TimaKesytore provider
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Launcher.HomeView( 1252): onStop
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  741): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector(  741): onPackageRemoved : com.example.hello
D/UsbSettingsManager(  741): clearDefaults: com.example.hello
,D/RCPManagerService(  741): exchangeData() failure , invalid userId
,D/RCPManagerService(  741): exchangeData() failure , invalid userId
,D/RCPManagerService(  741): exchangeData() failure , invalid userId
,E/SQLiteDatabase( 3317): Failed to open database '/data/data/com.android.email/databases/EmailProvider.db'.
E/SQLiteDatabase( 3317): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3317): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3317): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3317): 	at com.android.email.provider.EmailProvider.getDatabase(EmailProvider.java:921)
E/SQLiteDatabase( 3317): 	at com.android.email.provider.EmailProvider.query(EmailProvider.java:2062)
E/SQLiteDatabase( 3317): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase( 3317): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.provider.EmailContent$Account.restoreAccounts(EmailContent.java:5581)
E/SQLiteDatabase( 3317): 	at com.android.email.adapter.ProtocolAdapter.buildAccountInfoTable(ProtocolAdapter.java:283)
E/SQLiteDatabase( 3317): 	at com.android.email.adapter.ProtocolAdapter.initProtocolAdapter(ProtocolAdapter.java:588)
E/SQLiteDatabase( 3317): 	at com.android.email.Controller.<init>(Controller.java:322)
E/SQLiteDatabase( 3317): 	at com.android.email.Controller.getInstance(Controller.java:348)
E/SQLiteDatabase( 3317): 	at com.android.email.RefreshManager.getInstance(RefreshManager.java:358)
E/SQLiteDatabase( 3317): 	at com.android.email.Email.onCreate(Email.java:474)
E/SQLiteDatabase( 3317): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase( 3317): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase( 3317): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 3317): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 3317): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3317): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3317): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 3317): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3317): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3317): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 3317): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 3317): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 3317): Failed to open database '/data/data/com.android.email/databases/EmailProvider.db'.
E/SQLiteDatabase( 3317): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3317): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3317): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3317): 	at com.android.email.provider.EmailProvider.getDatabase(EmailProvider.java:921)
E/SQLiteDatabase( 3317): 	at com.android.email.provider.EmailProvider.query(EmailProvider.java:2062)
E/SQLiteDatabase( 3317): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase( 3317): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase( 3317): 	at com.android.email.Email.setServicesEnabledSync(Email.java:303)
E/SQLiteDatabase( 3317): 	at com.android.email.Email$1.run(Email.java:286)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.utility.Utility$2.doInBackground(Utility.java:1346)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.utility.Utility$2.doInBackground(Utility.java:1343)
E/SQLiteDatabase( 3317): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3317): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3317): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 3317): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3317): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
,W/System.err( 3317): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,W/System.err( 3317): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 3317): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 3317): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
,W/System.err( 3317): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 3317): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,W/System.err( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 3317): 	at com.android.email.provider.EmailProvider.getDatabase(EmailProvider.java:921)
W/System.err( 3317): 	at com.android.email.provider.EmailProvider.query(EmailProvider.java:2062)
W/System.err( 3317): 	at android.content.ContentProvider.query(ContentProvider.java:857)
W/System.err( 3317): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
W/System.err( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:470)
W/System.err( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:413)
W/System.err( 3317): 	at com.android.email.Email.setServicesEnabledSync(Email.java:303)
W/System.err( 3317): 	at com.android.email.Email$1.run(Email.java:286)
W/System.err( 3317): 	at com.android.emailcommon.utility.Utility$2.doInBackground(Utility.java:1346)
W/System.err( 3317): 	at com.android.emailcommon.utility.Utility$2.doInBackground(Utility.java:1343)
W/System.err( 3317): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 3317): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 3317): 	at java.lang.Thread.run(Thread.java:841)
,D/RCPManagerService(  741): exchangeData() failure , invalid userId
,D/InputReader(  741): Processing first event
,E/SQLiteDatabase( 3317): Failed to open database '/data/data/com.android.email/databases/EmailProvider.db'.
E/SQLiteDatabase( 3317): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3317): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3317): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3317): 	at com.android.email.provider.EmailProvider.getDatabase(EmailProvider.java:921)
E/SQLiteDatabase( 3317): 	at com.android.email.provider.EmailProvider.query(EmailProvider.java:2062)
E/SQLiteDatabase( 3317): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase( 3317): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.utility.Utility.getFirstRowColumn(Utility.java:1539)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.utility.Utility.getFirstRowLong(Utility.java:1572)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.provider.EmailContent$Message.getNewestServerTimestampMessage(EmailContent.java:2390)
E/SQLiteDatabase( 3317): 	at com.android.email.LegacyAutoRetryController.initializeLegacyAlarmReboot(LegacyAutoRetryController.java:141)
E/SQLiteDatabase( 3317): 	at com.android.email.Email$4.run(Email.java:1198)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.utility.EmailAsyncTask$1.doInBackground(EmailAsyncTask.java:289)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.utility.EmailAsyncTask$1.doInBackground(EmailAsyncTask.java:286)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.utility.EmailAsyncTask$InnerTask.doInBackground(EmailAsyncTask.java:122)
E/SQLiteDatabase( 3317): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3317): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteDatabase( 3317): Failed to open database '/data/data/com.android.email/databases/EmailProvider.db'.
E/SQLiteDatabase( 3317): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3317): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3317): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3317): 	at com.android.email.provider.EmailProvider.getDatabase(EmailProvider.java:921)
E/SQLiteDatabase( 3317): 	at com.android.email.provider.EmailProvider.query(EmailProvider.java:2062)
E/SQLiteDatabase( 3317): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase( 3317): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.provider.EmailContent$Account.restoreAccounts(EmailContent.java:5628)
E/SQLiteDatabase( 3317): 	at com.android.email.messagelist.AccountCache.validateAccounts(AccountCache.java:69)
E/SQLiteDatabase( 3317): 	at com.android.email.messagelist.AccountCache.access$000(AccountCache.java:12)
E/SQLiteDatabase( 3317): 	at com.android.email.messagelist.AccountCache$1.run(AccountCache.java:29)
E/SQLiteDatabase( 3317): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteDatabase( 3317): Failed to open database '/data/data/com.android.email/databases/EmailProvider.db'.
E/SQLiteDatabase( 3317): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3317): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3317): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3317): 	at com.android.email.provider.EmailProvider.getDatabase(EmailProvider.java:921)
E/SQLiteDatabase( 3317): 	at com.android.email.provider.EmailProvider.query(EmailProvider.java:2062)
E/SQLiteDatabase( 3317): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase( 3317): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase( 3317): 	at com.android.email.service.EmailBroadcastProcessorService.onNotificationSetting(EmailBroadcastProcessorService.java:1159)
E/SQLiteDatabase( 3317): 	at com.android.email.service.EmailBroadcastProcessorService$1.run(EmailBroadcastProcessorService.java:1139)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.utility.EmailAsyncTask$1.doInBackground(EmailAsyncTask.java:289)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.utility.EmailAsyncTask$1.doInBackground(EmailAsyncTask.java:286)
E/SQLiteDatabase( 3317): 	at com.android.emailcommon.utility.EmailAsyncTask$InnerTask.doInBackground(EmailAsyncTask.java:122)
E/SQLiteDatabase( 3317): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3317): 	at java.lang.Thread.run(Thread.java:841)
,W/dalvikvm( 3317): threadid=16: thread exiting with uncaught exception (group=0x41c41da0)
,E/AndroidRuntime( 3317): FATAL EXCEPTION: AsyncTask #3
E/AndroidRuntime( 3317): Process: com.android.email, PID: 3317
E/AndroidRuntime( 3317): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 3317): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 3317): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 3317): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 3317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3317): 	at java.lang.Thread.run(Thread.java:841)
E/AndroidRuntime( 3317): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3317): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 3317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 3317): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 3317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 3317): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 3317): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 3317): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 3317): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 3317): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3317): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3317): 	at com.android.email.provider.EmailProvider.getDatabase(EmailProvider.java:921)
E/AndroidRuntime( 3317): 	at com.android.email.provider.EmailProvider.query(EmailProvider.java:2062)
E/AndroidRuntime( 3317): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime( 3317): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime( 3317): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime( 3317): 	at com.android.email.service.EmailBroadcastProcessorService.onNotificationSetting(EmailBroadcastProcessorService.java:1159)
E/AndroidRuntime( 3317): 	at com.android.email.service.EmailBroadcastProcessorService$1.run(EmailBroadcastProcessorService.java:1139)
E/AndroidRuntime( 3317): 	at com.android.emailcommon.utility.EmailAsyncTask$1.doInBackground(EmailAsyncTask.java:289)
E/AndroidRuntime( 3317): 	at com.android.emailcommon.utility.EmailAsyncTask$1.doInBackground(EmailAsyncTask.java:286)
E/AndroidRuntime( 3317): 	at com.android.emailcommon.utility.EmailAsyncTask$InnerTask.doInBackground(EmailAsyncTask.java:122)
E/AndroidRuntime( 3317): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 3317): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 3317): 	... 3 more
,I/ActivityManager(  741): Killing 1194:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
,W/ApplicationsProvider( 1412): Could not fetch usage stats
W/ApplicationsProvider( 1412): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1412): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1412): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1412): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1412): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1412): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1412): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1412): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
