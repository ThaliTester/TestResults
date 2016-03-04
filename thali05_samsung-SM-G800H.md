#### Test 61703351a2a4153_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
W/System.err( 2383): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 2383): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 2383): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 2383): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 2383): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 2383): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 2383): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 2383): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:105)
W/System.err( 2383): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:89)
W/System.err( 2383): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 2383): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 2383): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 2383): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 2383): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2383): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 2383): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 2383): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2383): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2383): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 2383): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 2383): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 2383): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 2383): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2383): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2383): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2383): 	... 21 more
D/GalaxyFinderApplication( 2383): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 2383): [Slink platform] use state of slink location service is [false] to [true]
I/Process ( 1987): Sending signal. PID: 1987 SIG: 9
--------- beginning of /dev/log/system
I/ActivityManager(  746): Process com.sec.android.app.shealth (pid 1987) (adj 0) has died.
I/SELinux ( 2413): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2413):  
D/dalvikvm(  247): GC_EXPLICIT freed 43K, 50% free 9507K/19008K, paused 2ms+2ms, total 22ms
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/19008K, paused 2ms+3ms, total 18ms
I/TagReady( 2383): registerContentObserver() Support usertag? true
I/SELinux ( 2413): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2413):  
I/SELinux ( 2413):  
I/SELinux ( 2413): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2413): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2413): >>>>> Normal User
E/dalvikvm( 2413): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 2413): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/19008K, paused 1ms+3ms, total 18ms
D/TimaKeyStoreProvider( 2413): in addTimaSignatureService
D/TimaKeyStoreProvider( 2413): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2413): Added TimaKesytore provider
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=2413, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 2413): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences( 2413): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 2413): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 2413): ContentProvider is not null
V/MediaPlayer( 2413): decode(61, 33979084, 48105)
V/MediaPlayerService(  249): decode(33, 33979084, 48105)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 33979084, 48105)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3b8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3b8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3b8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3b8, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3b8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3b8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3b8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3b8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x20, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2413): decode(63, 33914984, 10421)
V/MediaPlayerService(  249): decode(33, 33914984, 10421)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 33914984, 10421)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71be228, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71be228, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71be228, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71be228, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71be228, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71be228, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71be228, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): addBatteryData
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71be228, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x21, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2413): decode(64, 37457308, 34198)
V/MediaPlayerService(  249): decode(33, 37457308, 34198)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 37457308, 34198)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): addBatteryData
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x22, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2413): decode(65, 33862452, 7405)
V/MediaPlayerService(  249): decode(33, 33862452, 7405)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 33862452, 7405)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3a0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3a0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3a0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3a0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3a0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3a0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3a0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ac3a0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x23, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2413): decode(66, 37547940, 5555)
V/MediaPlayerService(  249): decode(33, 37547940, 5555)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
I/ServiceManager(  289): Waiting for service AtCmdFwd...
V/AudioCache(  249): notify(0xb71a5920, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x24, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2413): decode(67, 30367732, 5085)
V/MediaPlayerService(  249): decode(33, 30367732, 5085)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ad4c0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71ad4c0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ad4c0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ad4c0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ad4c0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ad4c0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ad4c0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ad4c0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x25, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2413): decode(68, 30372876, 21552)
V/MediaPlayerService(  249): decode(33, 30372876, 21552)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 30372876, 21552)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71bbe40, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71bbe40, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71bbe40, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71bbe40, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71bbe40, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71bbe40, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71bbe40, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71bbe40, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x26, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2413): decode(69, 37543652, 4230)
V/MediaPlayerService(  249): decode(33, 37543652, 4230)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  249): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
I/AudioPlayer(  249): First fillBuffer call!!
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/MediaPlayerService(  249): wait for playback complete
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): addBatteryData
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x27, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2413): decode(70, 30337076, 9400)
V/MediaPlayerService(  249): decode(33, 30337076, 9400)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 30337076, 9400)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b81d8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71b81d8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b81d8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b81d8, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/Process ( 2413): Sending signal. PID: 2413 SIG: 9
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  249): open(44100, 1, 0x0, 1, 4)
E/IMemory (  249): binder=0xb71757e8 transaction failed fd=-2147483647, size=0, err=-32 (Broken pipe)
E/IMemory (  249): cannot dup fd=-2147483647, size=0, err=-32 (Bad file number)
E/IMemory (  249): cannot map BpMemoryHeap (binder=0xb71757e8), size=0, fd=-1 (Bad file number)
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b81d8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() stop AudioSource since AudioPlayer not exist
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x28, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/ActivityManager(  746): Process com.sec.android.app.shealth (pid 2413) (adj 0) has died.
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
I/SELinux ( 2491): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2491):  
I/SELinux ( 2491): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2491):  
I/SELinux ( 2491):  
I/SELinux ( 2491): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2491): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2491): >>>>> Normal User
E/dalvikvm( 2491): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 2491): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 2491): in addTimaSignatureService
D/TimaKeyStoreProvider( 2491): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2491): Added TimaKesytore provider
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=2491, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 2491): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences( 2491): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 2491): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 2491): ContentProvider is not null
V/MediaPlayer( 2491): decode(61, 33979084, 48105)
V/MediaPlayerService(  249): decode(33, 33979084, 48105)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 33979084, 48105)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b6e78, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71b6e78, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b6e78, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b6e78, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b6e78, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b6e78, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b6e78, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b6e78, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x29, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(62, 33914984, 10421)
V/MediaPlayerService(  249): decode(33, 33914984, 10421)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 33914984, 10421)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b26f0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71b26f0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b26f0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b26f0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b26f0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b26f0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b26f0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b26f0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x2a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(63, 37457308, 34198)
V/MediaPlayerService(  249): decode(33, 37457308, 34198)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 37457308, 34198)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b0e70, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71b0e70, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b0e70, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b0e70, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b0e70, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b0e70, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b0e70, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b0e70, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x2b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(64, 33862452, 7405)
V/MediaPlayerService(  249): decode(33, 33862452, 7405)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 33862452, 7405)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x2c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(65, 37547940, 5555)
V/MediaPlayerService(  249): decode(33, 37547940, 5555)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x2d, OMX_CommandStateSet, OMX_StateIdle)
D/SensorService(  746):   0.1 0.4 9.6
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(66, 30367732, 5085)
V/MediaPlayerService(  249): decode(33, 30367732, 5085)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x2e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(68, 30372876, 21552)
V/MediaPlayerService(  249): decode(33, 30372876, 21552)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 30372876, 21552)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba8d0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71ba8d0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba8d0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba8d0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba8d0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba8d0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba8d0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba8d0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x2f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(69, 37543652, 4230)
V/MediaPlayerService(  249): decode(33, 37543652, 4230)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba208, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71ba208, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba208, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba208, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  249): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba208, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba208, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba208, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ba208, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x30, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(70, 30337076, 9400)
V/MediaPlayerService(  249): decode(33, 30337076, 9400)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 30337076, 9400)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): Awe,somePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  249): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/SELinux ( 2560): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2560):  
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x31, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(71, 33925464, 44276)
V/MediaPlayerService(  249): decode(33, 33925464, 44276)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 33925464, 44276)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
I/SELinux ( 2560): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2560):  
I/SELinux ( 2560):  
I/SELinux ( 2560): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2560): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2560): >>>>> Normal User
E/dalvikvm( 2560): >>>>> com.sec.android.app.sns3 [ userId:0 | appId:10036 ]
E/SELinux ( 2560): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 2560): in addTimaSignatureService
D/TimaKeyStoreProvider( 2560): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2560): Added TimaKesytore provider
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71a5920, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x32, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(72, 33885672, 29256)
V/MediaPlayerService(  249): decode(33, 33885672, 29256)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 33885672, 29256)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ab638, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71ab638, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ab638, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ab638, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ab638, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
D/AndroidRuntime( 2522): 
D/AndroidRuntime( 2522): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2522): CheckJNI is OFF
D/AndroidRuntime( 2522): setted country_code = Poland
D/AndroidRuntime( 2522): setted countryiso_code = PL
D/AndroidRuntime( 2522): setted sales_code = XEO
D/AndroidRuntime( 2522): readGMSProperty: start
D/AndroidRuntime( 2522): readGMSProperty: already setted!!
D/AndroidRuntime( 2522): readGMSProperty: end
D/AndroidRuntime( 2522): addProductProperty: start
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
D/dalvikvm( 2522): Trying to load lib libjavacore.so 0x0
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ab638, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ab638, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
D/dalvikvm( 2522): Added shared lib libjavacore.so 0x0
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ab638, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x33, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
D/dalvikvm( 2522): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2522): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2522): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(73, 37491572, 52024)
V/MediaPlayerService(  249): decode(30, 37491572, 52024)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(30, 37491572, 52024)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ae1f8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71ae1f8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ae1f8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ae1f8, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ae1f8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
I/AudioPlayer(  249): First fillBuffer call!!
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ae1f8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ae1f8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71ae1f8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x34, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(74, 33969800, 9226)
V/MediaPlayerService(  249): decode(33, 33969800, 9226)
I/ServiceManager(  289): Waiting for service AtCmdFwd...
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 33969800, 9226)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
E/memtrack( 2522): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 2522): failed to load memtrack module: -2
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=2560, uid=10036 requires android.permission.INTERACT_ACROSS_USERS
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b50b8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x35, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 2491): decode(75, 30402580, 4509)
V/MediaPlayerService(  249): decode(33, 30402580, 4509)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(33, 30402580, 4509)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b86a0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/dalvikvm( 2522): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb71b86a0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b86a0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b86a0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b86a0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b86a0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b86a0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb71b86a0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x36, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
I/Process ( 2560): Sending signal. PID: 2560 SIG: 9
I/ActivityManager(  746): Process com.sec.android.app.sns3 (pid 2560) (adj 0) has died.
D/AndroidRuntime( 2522): Calling main entry com.android.commands.am.Am
I/SELinux ( 2614): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2614):  
V/ApplicationPolicy(  746): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService(  746): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 746  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  746): mDVFSHelper.acquire()
I/SELinux ( 2614): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2614):  
I/SELinux ( 2614):  
I/SELinux ( 2614): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2614): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2614): >>>>> Normal User
E/dalvikvm( 2614): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 2614): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SurfaceFlinger(  246): id=15 createSurf (1x1),1 flag=404, iello
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 2614): in addTimaSignatureService
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 2614): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2614): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4364, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
I/WindowManager(  746): Screenshot max retries 4 of Token{42c10910 ActivityRecord{426514f8 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42350228 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
W/WindowManager(  746): Screenshot failure taking screenshot for (720x1280) to layer 21005
D/LockPatternUtils( 1067): isPcwEnable = null
D/AndroidRuntime( 2522): Shutting down VM
D/dalvikvm( 2522): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 2ms
I/SELinux ( 2627): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2627):  
D/Launcher.HomeView( 1246): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1445): [237392/5] Surface widget pause on instance = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1445): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 1445): [KK AccuPhone]>>> SWW:224 [0:0] [SWW] onPause : instance = 1
D/accuweather( 1445): [KK AccuPhone]>>> SWW:239 [0:0] onPause : size = 0
D/accuweather( 1445): [KK AccuPhone]>>> SWW:517 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetView( 1246): destroyHardwareResources():1126551960
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/accuweather( 1445): [KK AccuPhone]>>> WR:149 [0:0] onPause
D/accuweather( 1445): [KK AccuPhone]>>> SM:526 [0:0] onPause
D/UiModeManager(  746): mCoverManager.getCoverState() : true
D/PowerManagerService(  746): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=1067
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/NotificationService(  746): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200dd contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/RCPManagerService(  746): NotificationReceiver onReceive()
D/RCPManagerService(  746):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService(  746): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967296746
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService(  746): sendNotification(1) - 5
W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/RCPManagerService(  746): getPolicy: policy value returned = false
D/RCPManagerService(  746): going to get the app label for pkg == com.android.systemui
D/RCPManagerService(  746): app label == com.android.systemui
D/RCPManagerService(  746): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967296746
D/Launcher( 1246): onTrimMemory. Level: 20
I/SELinux ( 2627): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2627):  
I/SELinux ( 2627):  
I/SELinux ( 2627): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2627): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2627): >>>>> Normal User
E/dalvikvm( 2627): >>>>> com.example.hello [ userId:0 | appId:10180 ]
D/RCPManagerService(  746): getPolicy: policy value returned = true
D/RCPManagerService(  746): Calling User is -1
D/RCPManagerService(  746): userid of SBN ==-1
D/UserManagerService(  746): User -1does not exists!!
E/PersonaManagerService(  746): returning null in  getPersonasForUser
E/SELinux ( 2627): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/ProgressBar( 1067): setProgressDrawable drawableHeight = 12
D/TimaKeyStoreProvider( 2627): in addTimaSignatureService
D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/PhoneStatusBar( 1067): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42351ad8
D/TimaKeyStoreProvider( 2627): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2627): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/LockPatternUtils( 1067): isPcwEnable = null
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/BatteryMeterView( 1067): onDraw batteryColor : -1
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=2627, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=2627, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 2627): Binding Chromium to the background looper Looper (main, tid 1) {4232f590}
I/chromium( 2627): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 2627): Initializing chromium process, renderers=0
I/Adreno-EGL( 2627): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2627): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2627): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2627): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2627): Remote Branch: 
I/Adreno-EGL( 2627): Local Patches: 
I/Adreno-EGL( 2627): Reconstruct Branch: 
W/chromium( 2627): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/SELinux ( 2657): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2657):  
I/SELinux ( 2657): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2657):  
I/SELinux ( 2657):  
I/SELinux ( 2657): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2657): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2657): >>>>> Normal User
E/dalvikvm( 2657): >>>>> com.sec.spp.push [ userId:0 | appId:10038 ]
E/SELinux ( 2657): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/dalvikvm( 2627): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2627): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2627): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2627): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2627): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2627): VFY: replacing opcode 0x6e at 0x0008
D/TimaKeyStoreProvider( 2657): in addTimaSignatureService
W/dalvikvm( 2627): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2627): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2627): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2627): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2627): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2627): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2627): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2627): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2627): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2627): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2627): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2627): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2627): CordovaWebView is running on device made by: samsung
D/TimaKeyStoreProvider( 2657): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2657): Added TimaKesytore provider
E/SMD     (  240): DCD ON
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
I/SurfaceFlinger(  246): id=16 createSurf (720x1280),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
I/HWUI    ( 2627): EGLImpl-HWUI Protected EGL context created
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
E/SPPClientService( 2657): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 2657): [PushClientApplication] Push log off : This is Ship build version
D/OpenGLRenderer( 2627): Enabling debug mode 0
D/SPPClientService( 2657): PushLog.txt file is not deleted.
D/SPPClientService( 2657): PushLog.txt file is not deleted.
D/SPPClientService( 2657): ============PushLog. stop!
W/AwContents( 2627): nativeOnDraw failed; clearing to background color.
E/SPPClientService( 2657): [SystemStateMoniter] ACTION_BOOT_COMPLETED
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
I/ServiceManager(  289): Waiting for service AtCmdFwd...
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/CustomFrequencyManagerService(  746): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 746  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  746): mDVFSHelper.release()
D/SurfaceWidgetView( 1246): destroyHardwareResources():1126551960
I/SurfaceFlinger(  246): id=15 Removed iello (10/13)
I/SurfaceFlinger(  246): id=15 Removed iello (-2/13)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  246): id=8 Removed Mauncher (8/12)
I/SurfaceFlinger(  246): id=8 Removed Mauncher (-2/12)
I/SurfaceFlinger(  246): id=14 Removed CatteryCove (8/11)
I/SurfaceFlinger(  246): id=14 Removed CatteryCove (-2/11)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  746): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 746  pkgName : ACTIVITY_RESUME_BOOSTER@9
E/ActivityThread( 1828): Performing stop of activity that is not resumed: {com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover}
E/ActivityThread( 1828): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover}
E/ActivityThread( 1828): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3536)
E/ActivityThread( 1828): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3623)
E/ActivityThread( 1828): 	at android.app.ActivityThread.access$1200(ActivityThread.java:172)
E/ActivityThread( 1828): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1335)
E/ActivityThread( 1828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1828): 	at android.os.Looper.loop(Looper.java:146)
E/ActivityThread( 1828): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/ActivityThread( 1828): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread( 1828): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread( 1828): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/ActivityThread( 1828): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/ActivityThread( 1828): 	at dalvik.system.NativeStart.main(Native Method)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/SELinux ( 2684): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2684):  
I/HarmonyEASService(  746): Updating for all 1
I/SELinux ( 2684): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2684):  
I/SELinux ( 2684):  
I/SELinux ( 2684): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2684): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2684): >>>>> Normal User
E/dalvikvm( 2684): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 2684): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 2684): in addTimaSignatureService
D/TimaKeyStoreProvider( 2684): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2684): Added TimaKesytore provider
I/chromium( 2627): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/SA      ( 2684): [SSP] onCreated
I/SA      ( 2684): [TPM] There is no property file
I/SA      ( 2684): [SCU] isHaveSA() - false
I/SA      ( 2684): [TPM] getModelProperty : null
I/SA      ( 2684): [TPM] getCSCProperty : null
I/SA      ( 2684): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED
I/SA      ( 2684): [DM] init START
I/SA      ( 2684): [DM] This device is not a Vodafone
I/SA      ( 2684): [DM] getCountryCodeFromCSC : PL
I/SA      ( 2684): support phone number id : false
I/SA      ( 2684): [DM] init END
I/chromium( 2627): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/SA      ( 2684): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 2684): [BDLM] already registered in spp
I/SA      ( 2684): [OR] onReceive Intent=[ action_BOOT_COMPLETED ]
I/SA      ( 2684): [OR] onReceive END
I/SA      ( 2684): [BDC] create
E/libGLESv2( 2627): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
E/libGLESv2( 2627): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
I/SELinux ( 2702): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2702):  
I/SA      ( 2684): [DBMV2] getEmailID
I/SA      ( 2684): [DBMV2] getDataV02ForItems
I/SA      ( 2684): [SSP] query invoked
I/SA      ( 2684): [SCU] get signed id from samsung account2.0 DB.
I/SA      ( 2684): [SCU] get signed id from samsung account1.0 DB.
I/SA      ( 2684): [BDC] destroy
E/AndroidProtocolHandler( 2627): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium( 2627): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
I/SELinux ( 2702): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2702):  
I/SELinux ( 2702):  
,I/SELinux ( 2702): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2702): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2702): >>>>> Normal User
,E/dalvikvm( 2702): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
,E/SELinux ( 2702): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 2702): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2702): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2702): Added TimaKesytore provider
,D/JsMessageQueue( 2627): Set native->JS mode to OnlineEventsBridgeMode
,E/libGLESv2( 2627): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,E/libGLESv2( 2627): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,D/dalvikvm( 2627): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x42656268
,D/dalvikvm( 2627): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x42656268
,D/jxcore_app_log( 2627): JniHelper::setJavaVM(0x4178e528), pthread_self() = 2009527192
,W/jxcore-log( 2627): Initializing JXcore engine
,W/jxcore-log( 2627): JXcore engine is ready
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=2702, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,W/jxcore-log( 2627): Starting JXcore engine
,W/jxcore-log( 2627): Platform android
W/jxcore-log( 2627): 
,W/jxcore-log( 2627): Process ARCH arm
W/jxcore-log( 2627): 
,D/dalvikvm(  746): GC_EXPLICIT freed 2993K, 19% free 22587K/27608K, paused 5ms+11ms, total 122ms
D/MediaScannerReceiver( 1207): action: android.intent.action.BOOT_COMPLETED
,I/jxcore-log( 2627): JXcore Cordova bridge is ready!
I/jxcore-log( 2627): 
,W/jxcore-log( 2627): JXcore engine is started
,E/jxcore  ( 2627): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 2627): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/Dialog  ( 2627):  checkMirrorLinkEnabled returns : false
,D/Dialog  ( 2627): showing allowed
,W/Atfwd_Sendcmd(  289): AtCmdFwd service not published, waiting... retryCnt : 3
,D/MediaScannerService( 1207): !@start scanning volume internal: [/system/media]
,D/TP/MmsProvider( 1240): Update uri=content://mms, match=0
D/TP/MmsProvider( 1240): update , handleReadChangedBroadcast
,D/TP/MmsSmsProvider( 1240): need read changed broadcast:false
I/Mms:transaction( 1665): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
,D/Mms/MessagingNotification( 1665): [start]    nonBlockingUpdateMessageIndicator()
,I/Mms/ReservationManager( 1665): resetAfterConnected()
,D/Mms/MessagingNotification( 1665): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1665): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 1665): isDefault true
,D/TP/MmsSmsProvider( 1240): match 7:Elapsed time : 3.408 ms
,I/Mms/ReservationManager( 1665): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1240): match 200:Elapsed time : 1.122 ms
,D/CustomFrequencyManagerService(  746): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 746  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 2726): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2726):  
,I/SurfaceFlinger(  246): id=17 createSurf (1x1),1 flag=4, NainActivit
,D/Mms/TelephonyPermission( 1665): isDefault true
D/Mms/SmsReceiverService( 1665): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
,D/Mms/SmsReceiverService( 1665): [start]    handleBootCompleted()
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/TP/MmsSmsProvider( 1240): deleteConversation threadId: 9223372036854775806
,D/TP/MmsSmsProvider( 1240): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,D/TP/MmsSmsProvider( 1240): delete threadId: 9223372036854775806
,D/TP/MmsSmsProvider( 1240): need read changed broadcast:false
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/Mms/Conversation( 1665): deleteTempConversation(),deleted=0
,D/BadgeProvider( 1321): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/SELinux ( 2726): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2726):  
I/SELinux ( 2726):  
,I/SELinux ( 2726): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2726): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2726): >>>>> Normal User
,E/dalvikvm( 2726): >>>>> com.sec.android.app.safetyassurance [ userId:0 | appId:10050 ]
,D/SmsProvider( 1240): Update uri=content://sms/outbox, match=8
E/SELinux ( 2726): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/Launcher.Model( 1246): reloadBadges entered.
D/BadgeProvider( 1321): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1321): sendNotify, [notify] : null
D/BadgeProvider( 1321): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1321): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1321): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 1665): setBadgeCount(), count=0
,D/MessagingNotification( 1665): remove alarm
,D/TP/MmsSmsProvider( 1240): need read changed broadcast:false
D/Mms/SmsReceiverService( 1665): sendFirstQueuedMessage()
,D/Mms/SmsReceiverService( 1665): [SIM-1]sendFirstQueuedMessage()
,D/Mms/MessagingNotification( 1665): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 1665): [end]    nonBlockingUpdateMessageIndicator()
,D/TimaKeyStoreProvider( 2726): in addTimaSignatureService
,D/Mms/MessagingNotification( 1665): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1665): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 1665): isDefault true
,D/TimaKeyStoreProvider( 2726): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2726): Added TimaKesytore provider
,D/MediaScanner( 1207): Prescan. DB items number : 156 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/TP/MmsSmsProvider( 1240): match 200:Elapsed time : 0.845 ms
,W/dalvikvm( 2726): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/BadgeProvider( 1321): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/SafetyAssuranceAppFeatures( 2726): init start
,I/SafetyAssuranceAppFeatures( 2726): mLoadBaiduMap:false
,I/SafetyAssuranceAppFeatures( 2726): mFeatureEnableMultiSim true
,D/SafetyAssuranceAppFeatures( 2726): init end
,V/MediaScanner( 1207): processDirectory :  /system/media
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/SafetyAssuranceReceiver( 2726): onReceive
,I/SafetyAssuranceApp( 2726): Acquire WL
,D/SafetyAssuranceConfig( 2726): getAppState : 1
D/SafetyAssuranceReceiver( 2726): onReceive - action:android.intent.action.BOOT_COMPLETED, currentAppState:1
,D/SafetyAssuranceReceiver( 2726): Init App state
,D/Launcher.Model( 1246): reloadBadges entered.
D/BadgeProvider( 1321): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1321): sendNotify, [notify] : null
D/BadgeProvider( 1321): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1321): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1321): update, [UpdateCount] : 1
,D/SafetyAssuranceConfig( 2726): setAppState : 1
,W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=10050
D/Mms/MessagingNotification( 1665): setBadgeCount(), count=0
D/SafetyAssuranceApp( 2726): topActivity's name is=.MainActivity
D/MessagingNotification( 1665): remove alarm
I/SafetyAssuranceApp( 2726): Release WL
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,D/Mms/MessagingNotification( 1665): updateAllHistoryAsRead()
,I/NetworkStatusReceiver( 1240): action: android.intent.action.BOOT_COMPLETED
,D/Mms/SmsReceiverService( 1665): [end]    handleBootCompleted()
,D/NearbySettings( 1353): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 1353): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 1353): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 1353): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,V/NearbySettings( 1353): MountReceiver.mPrefHandler - 7002
I/NearbySettings( 1353): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,I/NearbySettings( 1353): MountReceiver.onReceive - Internal Path
,I/AccessibilityManagerService(  746): setmDNIeNegative (false)
,V/MediaScanner( 1207):  prescan time: 208ms (DB items: 156)
,V/MediaScanner( 1207):     scan time: 157ms (Caching mode: true), (makeEntry time: 61ms ~38%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
,V/MediaScanner( 1207): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1207):    total time: 365ms
,V/MediaScanner( 1207): checked files: 149  directories : 5  (I: 0, U: 0)
,D/MediaScanner( 1207): checkDefaultSounds
,D/MediaScanner( 1207): system alarm_alert  : Vwiurug_etwofi5wgg
,D/MediaScanner( 1207): OK. alarm_alert is already exist in setting DB.
,D/MediaScanner( 1207): system notification_sound  : K_Oprkltf5wgg
,D/MediaScanner( 1207): OK. notification_sound is already exist in setting DB.
,D/MediaScanner( 1207): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/MediaScanner( 1207): OK. ringtone is already exist in setting DB.
,D/MediaScanner( 1207): system ringtone_2  : Wmfi_lpf_pwirywu5wgg
,D/MediaScanner( 1207): OK. ringtone_2 is already exist in setting DB.
,D/MediaScanner( 1207): system notification_sound_2  : K_Oprkltf5wgg
,D/MediaScanner( 1207): OK. notification_sound_2 is already exist in setting DB.
,D/MediaScannerService( 1207): !@done scanning volume internal
,D/MediaScannerService( 1207): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 1207): Prescan. DB items number : 20 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,V/MediaScanner( 1207): processDirectory :  /storage/emulated/0
,D/MediaScanner( 1207): Skipping:
,D/MediaScanner( 1207): 7klwibgf7fvntblfd7(75ebcf7
,I/iu.UploadsManager( 1782): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,D/MediaScanner( 1207): Skipping:
,D/MediaScanner( 1207): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1207): processDirectory :  /storage/extSdCard
W/MediaScanner( 1207): Error opening directory, reason : Permission denied.
,W/MediaScanner( 1207): 7klwibgf7fxlKdCbid7
,E/File    ( 1207): fail readDirectory() errno=2
,V/MediaScanner( 1207): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@4272a580
,V/MediaScanner( 1207): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@4272a580
V/MediaScanner( 1207):  prescan time: 50ms (DB items: 20)
V/MediaScanner( 1207):     scan time: 22ms (Caching mode: true), (makeEntry time: 12ms ~54%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1207): postscan time: 23ms (bulkDeleter : 0), (delete DeadThumbnail time : 21ms)
V/MediaScanner( 1207):    total time: 95ms
,V/MediaScanner( 1207): checked files: 3  directories : 17  (I: 0, U: 0)
,W/Settings( 1353): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MediaScannerService( 1207): !@done scanning volume external
D/MediaScannerService( 1207): send command to ssrm : REQ_DROP_CACHE
,I/iu.UploadsManager( 1782): End new media; added: 0, uploading: 0, time: 88 ms
,I/SettingSearch/SearchIntentReceiver( 1353): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1353): search setting db init!!
,I/SettingSearch/SearchIntentReceiver( 1353): BOOT_COMPLETED call InitSerachDBThread thread start!
W/ContextImpl( 1353): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:40 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:60 
,I/SELinux ( 2754): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2754):  
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
,I/BootupListener( 1240): mPendingNetworkManualSelection : false
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/ManualSelectionReceiver( 1240): onReceive : Intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.phone/.ManualSelectionReceiver (has extras) }
,I/SELinux ( 2754): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2754):  
I/SELinux ( 2754):  
,I/SELinux ( 2754): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2754): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2754): >>>>> Normal User
,E/dalvikvm( 2754): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10160 ]
,E/SELinux ( 2754): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 2764): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2764):  
,D/TimaKeyStoreProvider( 2754): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2754): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2754): Added TimaKesytore provider
,I/SELinux ( 2764): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2764):  
I/SELinux ( 2764):  
,I/SELinux ( 2764): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2764): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2764): >>>>> Normal User
,E/dalvikvm( 2764): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
,E/SELinux ( 2764): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2764): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2764): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2764): Added TimaKesytore provider
W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PowerManagerService(  746): [s] UserActivityState : 1 -> 0
,I/PowerManagerService(  746): [PWL] On : 0 (39856 ms ago)
I/PowerManagerService(  746): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  746): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1067, ws=null) (elapsedTime=2281)
,D/DisplayPowerController(  746): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService(  746): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/lights  (  746): lcd : 4 +
,D/lights  (  746): lcd : 4 -
,D/lights  (  746): lcd : 2 +
D/RampAnimator(  746): Light Animator Finished currentValue=2
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.ssrm.u.i:-1 com.android.server.ssrm.ai.run:-1 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 
,D/lights  (  746): lcd : 2 -
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=2754, uid=10160 requires android.permission.INTERACT_ACROSS_USERS
,D/SensorService(  746):   0.1 0.4 9.6
,I/DBG_DM  ( 2764): [][Line:95][onCreate] 
E/DBG_DM  ( 2764): BootingfileStream is null
,E/DBG_DM  ( 2764): xdmCreateBootingFilestream
,D/SSRMv2:SIOP(  746): SIOP:: AP = 340, Delta = 10
,I/DBG_DM  ( 2764): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DM  ( 2764): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
,I/DBG_DM  ( 2764): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
,I/DBG_DM  ( 2764): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
,I/DBG_DM  ( 2764): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
,I/DBG_DM  ( 2764): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
,I/DBG_DM  ( 2764): [3.19.140541][Line:36][onCreate] myUserId : 0
,I/DBG_DM  ( 2764): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 0
,I/DBG_DM  ( 2764): [3.19.140541][Line:2702][xdmdbsqlGetDownloadPostponeStatus] xdbsqlGetDownloadPostponeStatus : 0
,I/DBG_DM  ( 2764): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
,I/DBG_DM  ( 2764): [3.19.140541][Line:99][onCreate] DMApplication NOT Start !
,I/DBG_DM  ( 2764): [3.19.140541][Line:139][onReceive] android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1067): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1067): into the SAFE_MODE_ACTION
,D/OverheatReceiver( 1067): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1067): isSafeMode = false
,E/Tethering(  746): No numeric data
,E/Tethering(  746): No numeric data
E/Tethering(  746): No numeric data
,E/Tethering(  746): No numeric data
I/ConnectivityService(  746): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  746): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  746): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  746): defaultVal : 1, tetherEnabledInSettings : true
,E/Tethering(  746): No numeric data
,E/Tethering(  746): No numeric data
I/ConnectivityService(  746): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  746): defaultVal : 1, tetherEnabledInSettings : true
,D/LocationManagerService(  746): getProviders()=[passive]
,E/Tethering(  746): No numeric data
,E/Tethering(  746): No numeric data
,E/Tethering(  746): No numeric data
,E/Tethering(  746): No numeric data
I/ConnectivityService(  746): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  746): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  746): defaultVal : 1, tetherEnabledInSettings : true
,I/ConnectivityService(  746): defaultVal : 1, tetherEnabledInSettings : true
V/NFC     ( 1353): this device does not have NFC support
V/NFC     ( 1353): this device does not have NFC support
V/NFC     ( 1353): this device does not have NFC support
V/NFC     ( 1353): this device does not have NFC support
,I/ContactAccountLoggerTas( 2165): canRun() : Opted Out
V/VibratorService(  746): hasVibrator - useVibetonz: false
,W/dalvikvm( 2165): method Lcom/google/android/search/core/state/QueryState;.a incorrectly overrides package-private method with same name in Lcfl;
,D/WifiDisplayAdapter(  746): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/InputMethodInfo(  746): Duplicated subtype definition found: , voice
,I/AudioService(  746): getStreamVolume 3 index 0
,I/MediaRouter( 2165): Found default route: MediaRouter.RouteInfo{ uniqueId=android/kb:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  746): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/WifiDisplayAdapter(  746): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/SELinux ( 2806): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2806):  
,D/dalvikvm(  247): GC_EXPLICIT freed 44K, 50% free 9507K/19008K, paused 2ms+2ms, total 31ms
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/19008K, paused 2ms+3ms, total 19ms
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/19008K, paused 2ms+2ms, total 19ms
,I/LockPatternUtils( 1353): isSmartCardAuthenticationAvailable: false
I/SELinux ( 2806): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2806):  
I/SELinux ( 2806):  
,I/SELinux ( 2806): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2806): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2806): >>>>> Normal User
,E/dalvikvm( 2806): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 2806): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2806): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2806): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2806): Added TimaKesytore provider
,D/UserAnalysis.PlaceProvider( 2806): Create SecureDbHelper
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=2806, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 2806): Create SecureDbHelper
V/VibratorService(  746): hasVibrator - useVibetonz: false
,I/SQLiteSecureOpenHelper( 2806): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2806): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2806): Open Place.db in secure mode
,D/PackageManager(  746): [MSG] MCS_UNBIND
I/PackageManager(  746): calling disconnectService()
,D/PackageManager(  746): Trying to unbind to DefaultContainerService
,I/SQLiteSecureOpenHelper( 2806): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2806): ...getDatabaseLocked(b,b,pwd)
,I/SQLiteSecureOpenHelper( 2806): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2806): getDatabaseLocked(b,b,pwd)...
,D/UserAnalysis.CarAnalyzer( 2806): Create SecureDbHelper
,I/SQLiteSecureOpenHelper( 2806): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2806): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2806): Open Place.db in secure mode
,D/dalvikvm(  746): GC_EXPLICIT freed 1126K, 19% free 22569K/27608K, paused 5ms+10ms, total 130ms
,E/SMD     (  240): DCD ON
,I/LockPatternUtils( 1353): isSmartCardAuthenticationAvailable: false
,I/SQLiteSecureOpenHelper( 2806): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2806): ...getDatabaseLocked(b,b,pwd)
,I/SELinux ( 2823): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2823):  
,I/SELinux ( 2823): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2823):  
I/SELinux ( 2823):  
,I/SELinux ( 2823): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2823): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2823): >>>>> Normal User
,E/dalvikvm( 2823): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 2823): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2823): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2823): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2823): Added TimaKesytore provider
,I/sCloudBackupApp( 2823): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SELinux ( 2836): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2836):  
,I/SettingSearch/SearchIntentReceiver( 1353): InitSerachDBThread thread end!
W/ContextImpl( 1353): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:129 <bottom of call stack> 
,I/SELinux ( 2836): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2836):  
I/SELinux ( 2836):  
,I/SELinux ( 2836): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2836): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2836): >>>>> Normal User
,E/dalvikvm( 2836): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 2836): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2836): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2836): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2836): Added TimaKesytore provider
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=2836, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 2849): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2849):  
,W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/SELinux ( 2849): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2849):  
I/SELinux ( 2849):  
,I/SELinux ( 2849): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2849): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2849): >>>>> Normal User
,E/dalvikvm( 2849): >>>>> com.wssnps [ userId:0 | appId:1000 ]
,E/SELinux ( 2849): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2849): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2849): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2849): Added TimaKesytore provider
,D/NPS_WSSNPS( 2849): [] android.intent.action.BOOT_COMPLETED
,D/NPS_WSSNPS( 2849): [] Service onCreate!!
W/ContextImpl( 2849): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.wssnps.smlNpsReceiver.onReceive:380 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2862): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2862):  
,D/NPS_WSSNPS( 2849): [] NpsServiceTask Start
,I/NPS_WSSNPS( 2849): [44.140541] loadCryptionkeyLibrary
,I/NPS_WSSNPS( 2849): [44.140541] FirstLoad Or Not Exist
,D/dalvikvm( 2849): Trying to load lib /data/data/com.wssnps/files/libCryptionkey.so 0x426566c0
,D/dalvikvm( 2849): Added shared lib /data/data/com.wssnps/files/libCryptionkey.so 0x426566c0
,D/NPS_WSSNPS( 2849): [44.140541] smlDBHelper
,I/NPS_WSSNPS( 2849): [44.140541] AsyncBulkFlagCheck
,I/NPS_WSSNPS( 2849): [44.140541] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 2849): [44.140541] IsRemain_Asyncing nothing
,D/NPS_WSSNPS( 2849): [44.140541] Service onDestroy
,I/NPS_WSSNPS( 2849): [44.140541] smlBRConfigurationDelete
,I/NPS_WSSNPS( 2849): [44.140541] smlBRMessageDelete
,I/NPS_WSSNPS( 2849): [44.140541] smlBREmailDelete
,I/NPS_WSSNPS( 2849): [44.140541] smlBRNetworkDelete
,I/NPS_WSSNPS( 2849): [44.140541] smlBRCallLogDelete
D/AmoledAdjustTimer(  746): prevTemp = 299, currTemp = 301, prevStep = 4, currStep = 5
,W/ContextImpl( 2849): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 com.wssnps.smlNpsService$1.run:108 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/NPS_WSSNPS( 2849): [44.140541] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 2849): [44.140541] smlBRPenMemoMDelete
I/NPS_WSSNPS( 2849): [44.140541] smlBRSMemoDelete
I/NPS_WSSNPS( 2849): [44.140541] cpuBooster release : false
D/NPS_WSSNPS( 2849): [44.140541] dsServerSocket close
I/SELinux ( 2862): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2862):  
I/SELinux ( 2862):  
I/SELinux ( 2862): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2862): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2862): >>>>> Normal User
E/dalvikvm( 2862): >>>>> com.samsung.android.app.accesscontrol [ userId:0 | appId:10064 ]
E/SELinux ( 2862): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2862): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2862): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2862): Added TimaKesytore provider
,I/SELinux ( 2881): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2881):  
I/ActivityManager(  746): Killing 1290:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #43
,I/SELinux ( 2881): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2881):  
I/SELinux ( 2881):  
,I/SELinux ( 2881): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2881): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2881): >>>>> Normal User
,E/dalvikvm( 2881): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
,E/SELinux ( 2881): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2881): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2881): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2881): Added TimaKesytore provider
,D/FileShare-Server( 2881): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/SELinux ( 2895): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2895):  
I/ActivityManager(  746): Killing 1272:com.android.printspooler/u0a144 (adj 15): empty #43
,I/SELinux ( 2895): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2895):  
I/SELinux ( 2895):  
,I/SELinux ( 2895): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2895): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2895): >>>>> Normal User
,E/dalvikvm( 2895): >>>>> com.sec.android.nearby.mediaserver [ userId:0 | appId:10070 ]
,E/SELinux ( 2895): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2895): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2895): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2895): Added TimaKesytore provider
,I/AllShare(ASF-DMSLIB)( 2895): DMSReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=10070
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/SELinux ( 2907): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2907):  
I/ActivityManager(  746): Killing 1713:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #43
,I/SELinux ( 2907): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2907):  
I/SELinux ( 2907):  
,I/SELinux ( 2907): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2907): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2907): >>>>> Normal User
,E/dalvikvm( 2907): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 2907): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2907): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2907): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2907): Added TimaKesytore provider
,W/ContextImpl( 2907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:61 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2920): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2920):  
,I/SELinux ( 2920): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2920):  
I/SELinux ( 2920):  
,I/SELinux ( 2920): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2920): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2920): >>>>> Normal User
,E/dalvikvm( 2920): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
,E/SELinux ( 2920): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2920): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2920): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2920): Added TimaKesytore provider
,D/BluetoothBDAdrressReceiver( 2920): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2920): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
W/ContextImpl( 2920): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2932): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2932):  
,D/BluetoothBDTestService( 1240): onCreate()
,E/BluetoothBDTestService( 1240): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
,E/BluetoothBDTestService( 1240): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1240): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/ActivityManager(  746): Killing 1727:com.sec.modem.settings/1000 (adj 15): empty #43
,I/SELinux ( 2932): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2932):  
I/SELinux ( 2932):  
,I/SELinux ( 2932): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2932): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2932): >>>>> Normal User
,E/dalvikvm( 2932): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 2932): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 2932): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2932): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2932): Added TimaKesytore provider
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=2932, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 2948): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2948):  
,I/ActivityManager(  746): Killing 1739:com.sec.tcpdumpservice/1000 (adj 15): empty #43
,I/SELinux ( 2948): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2948):  
I/SELinux ( 2948):  
,I/SELinux ( 2948): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2948): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2948): >>>>> Normal User
,E/dalvikvm( 2948): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 2948): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2948): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2948): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2948): Added TimaKesytore provider
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2907): Resource data:2131165197
,I/AMMetaDataParserService( 2907): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131165194
I/AMMetaDataParserService( 2907): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,E/PersonaManagerService(  746): returning null in  getPersonasForUser
,I/AMMetaDataParserService( 2907): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,I/SELinux ( 2960): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2960):  
I/ActivityManager(  746): Killing 1768:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/dalvikvm(  247): GC_EXPLICIT freed 45K, 50% free 9507K/19008K, paused 2ms+3ms, total 26ms
,I/AMMetaDataParserService( 2907): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/19008K, paused 1ms+3ms, total 19ms
I/SELinux ( 2960): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2960):  
I/SELinux ( 2960):  
,I/SELinux ( 2960): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2960): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2960): >>>>> Normal User
,E/dalvikvm( 2960): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 2960): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/19008K, paused 2ms+3ms, total 19ms
,D/TimaKeyStoreProvider( 2960): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2960): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2960): Added TimaKesytore provider
,I/AMMetaDataParserService( 2907): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,I/AMMetaDataParserService( 2907): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131165194
I/AMMetaDataParserService( 2907): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,I/AMMetaDataParserService( 2907): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,I/AMMetaDataParserService( 2907): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,I/AMMetaDataParserService( 2907): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=10084
,I/AMMetaDataParserService( 2907): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,I/AMMetaDataParserService( 2907): Resource data:2131165195
,I/AMMetaDataParserService( 2907): getResourceName:com.sec.android.gallery3d:xml/device_filter
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2907): Resource data:2131165204
I/AMMetaDataParserService( 2907): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2907): Resource data:2131165204
I/AMMetaDataParserService( 2907): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2907): Resource data:2131165204
I/AMMetaDataParserService( 2907): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2907): Resource data:2131099676
,I/AMMetaDataParserService( 2907): getResourceName:com.android.mms:xml/spellscroll
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,I/AMMetaDataParserService( 2907): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131099648
I/AMMetaDataParserService( 2907): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,I/AMMetaDataParserService( 2907): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 2974): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2974):  
I/ActivityManager(  746): Killing 1321:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/AMMetaDataParserService( 2907): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2907): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/SELinux ( 2974): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2974):  
I/SELinux ( 2974):  
,I/SELinux ( 2974): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2974): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2974): >>>>> Normal User
,E/dalvikvm( 2974): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
,E/SELinux ( 2974): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2907): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/TimaKeyStoreProvider( 2974): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2974): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2974): Added TimaKesytore provider
,D/SensorService(  746):   0.1 0.4 9.6
,I/AMMetaDataParserService( 2907): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2907): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131099648
I/AMMetaDataParserService( 2907): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,I/AMMetaDataParserService( 2907): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 2987): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2987):  
I/ActivityManager(  746): Killing 1686:com.sec.android.app.mt/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2907): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2907): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/SELinux ( 2987): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2987):  
I/SELinux ( 2987):  
,I/SELinux ( 2987): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2987): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2987): >>>>> Normal User
,E/dalvikvm( 2987): >>>>> com.dropbox.android [ userId:0 | appId:10091 ]
,E/SELinux ( 2987): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/AMMetaDataParserService( 2907): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/TimaKeyStoreProvider( 2987): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2987): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2987): Added TimaKesytore provider
,I/AMMetaDataParserService( 2907): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2907): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131099648
I/AMMetaDataParserService( 2907): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,I/AMMetaDataParserService( 2907): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2907): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2907): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/com.dropbox.android.service.DropboxNetworkReceiver( 2987): Setting receiver enabled: false
,I/AMMetaDataParserService( 2907): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/com.dropbox.sync.android.a( 2987): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/AMMetaDataParserService( 2907): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/com.dropbox.sync.android.aa( 2987): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800H armeabi-v7a; en_US))
,I/AMMetaDataParserService( 2907): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/ActivityManager(  746): Waited long enough for: ServiceRecord{42feb428 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131099648
,I/AMMetaDataParserService( 2907): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=2987, uid=10091 requires android.permission.INTERACT_ACROSS_USERS
,I/AMMetaDataParserService( 2907): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 3008): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3008):  
I/ActivityManager(  746): Killing 1917:com.sec.phone/1001 (adj 15): empty #43
,I/AMMetaDataParserService( 2907): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
I/SELinux ( 3008): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3008):  
I/SELinux ( 3008):  
I/SELinux ( 3008): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3008): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3008): >>>>> Normal User
E/dalvikvm( 3008): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 3008): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2907): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/TimaKeyStoreProvider( 3008): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3008): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3008): Added TimaKesytore provider
,I/AMMetaDataParserService( 2907): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2907): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=3008, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 3008): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 3008): ELMEngine.ELMEngine( context ).
V/AlarmManager(  746): waitForAlarm result :4
,V/AlarmManager(  746): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
I/AMMetaDataParserService( 2907): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
D/elm:14132( 3008): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 3008): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 3008): ElmAgentService : onCreate()
,D/elm:14132( 3008): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14132( 3008): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:14132( 3008): BootCompletedState : startBootCompleted() call
,I/SELinux ( 3027): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3027):  
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131099648
,I/AMMetaDataParserService( 2907): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,D/elm:14132( 3008): ModuleBase.resetCalllogAPIAlarm()
,D/elm:14132( 3008): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:14132( 3008): Get License : 0
,D/elm:14132( 3008): ElmAgentService : onDestroy().
I/ActivityManager(  746): Killing 2017:com.google.android.configupdater/u0a3 (adj 15): empty #43
,I/AMMetaDataParserService( 2907): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 3027): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3027):  
I/SELinux ( 3027):  
,I/SELinux ( 3027): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3027): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3027): >>>>> Normal User
,E/dalvikvm( 3027): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,E/SELinux ( 3027): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3027): in addTimaSignatureService
,I/AMMetaDataParserService( 2907): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/TimaKeyStoreProvider( 3027): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3027): Added TimaKesytore provider
,I/AMMetaDataParserService( 2907): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,E/SMD     (  240): DCD ON
,I/System.out( 2987): Thread-257(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 2987): Thread-257(ApacheHTTPLog):isShipBuild true
I/System.out( 2987): Thread-257(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/AMMetaDataParserService( 2907): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/System.out( 2987): pool-4-thread-1 calls detatch()
,I/SELinux ( 3042): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3042):  
I/ActivityManager(  746): Killing 2061:com.sec.dsm.system/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2907): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2907): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/SELinux ( 3042): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3042):  
I/SELinux ( 3042):  
,I/SELinux ( 3042): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3042): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3042): >>>>> Normal User
,E/dalvikvm( 3042): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,E/SELinux ( 3042): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131099648
I/AMMetaDataParserService( 2907): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,I/AMMetaDataParserService( 2907): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/TimaKeyStoreProvider( 3042): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3042): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3042): Added TimaKesytore provider
,I/AMMetaDataParserService( 2907): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2907): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/CameraApp( 3042): CameraApp.onCreate()... mFeature : null
I/testFeature( 3042): Feature.Feature(context)
I/testFeature( 3042): Feature.readInternalDefaultXml()
,I/testFeature( 3042): ResetFeatureValue
I/CameraFirmware_broadcast( 3042): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 3042): CameraApp.getAppFeature()...
,I/AMMetaDataParserService( 2907): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 3054): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3054):  
,I/AMMetaDataParserService( 2907): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
I/ActivityManager(  746): Killing 2097:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2907): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2907): Resource data:2131099671
I/AMMetaDataParserService( 2907): getResourceName:com.android.mms:xml/searchable
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/SELinux ( 3054): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3054):  
I/SELinux ( 3054):  
I/SELinux ( 3054): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
,E/SELinux ( 3054): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3054): >>>>> Normal User
,E/dalvikvm( 3054): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 3054): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3054): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3054): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3054): Added TimaKesytore provider
,D/PackageIntentReceiver( 3054): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3054): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager(  746): Killing 2169:com.sec.factory/1000 (adj 15): empty #43
,D/dalvikvm( 2907): GC_CONCURRENT freed 4984K, 34% free 12703K/19008K, paused 3ms+3ms, total 40ms
,D/dalvikvm( 2907): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.GridSettings
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131165216
,I/SELinux ( 3070): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3070):  
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,I/AMMetaDataParserService( 2907): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,I/SELinux ( 3070): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3070):  
I/SELinux ( 3070):  
,I/SELinux ( 3070): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3070): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3070): >>>>> Normal User
,E/dalvikvm( 3070): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
,E/SELinux ( 3070): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/AMMetaDataParserService( 2907): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,D/TimaKeyStoreProvider( 3070): in addTimaSignatureService
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.TimDataConnectionDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.TetherHelp
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2907): Resource data:2131296695
D/TimaKeyStoreProvider( 3070): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429144
,D/ActivityThread( 3070): Added TimaKesytore provider
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429144
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429144
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2907): Resource data:2131297114
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ApnSettings
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ApnSettingsTabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429146
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429146
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429168
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/mirror_link_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2907): Resource data:2131296695
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2907): Resource data:2131296695
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429144
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131297114
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2907): Resource data:2131296695
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131296695
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring,
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE,
I/AMMetaDataParserService( 2907): Resource data:2131296695
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131296695
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog,
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131296695
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429219
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429191
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429191
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429191
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429191
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429191,
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429191
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2907): Resource data:2131298419,
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity,
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429191
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid,
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131298419
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429191
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131298419
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring,
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429176
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429176
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429173
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 2907): Resource data:2131429173
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429172
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429172
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429182
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429173
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/display_settings
,I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429186
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429186
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429173
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2907): Resource data:2131297804
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429173
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429228
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/about_settings
,I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.users.UserOptions
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429128
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429128
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429128
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429127
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/home_settings
,I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429127
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429128
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429128
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429127
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429127
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429128
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429153
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429224
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.CarrierMatchSetting
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429224
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2907): Resource data:2131296750
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429224
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429123
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/privacy_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429224
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2907): Resource data:2131296750
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429224
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2907): Resource data:2131296750
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429187
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/accessibility_settings
,I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429187
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131298587
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429187
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131298587
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429191
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429180
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/driving_mode
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429223
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429225
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131296695
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429165
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429225
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429223
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131297938
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/storage_settings_title
,I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429223
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=3070, uid=10105 requires android.permission.INTERACT_ACROSS_USERS,
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131297938
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429161
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429163
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429167
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131296695
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.RadioInfo
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429221
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429221
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429119
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429217
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429224
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429224
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429173
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429208
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/user_settings
,I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429286
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429224
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429201
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429185
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429185
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131299843
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/power_saving_mode_title
,I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429185
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429185
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429222
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/power_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429186
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 2907): Resource data:1
W/ResourceType( 2907): No package identifier when getting name for resource number 0x00000001
W/System.err( 2907): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
,W/System.err( 2907): 	at android.content.res.Resources.getResourceName(Resources.java:3017)
W/System.err( 2907): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 2907): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 2907): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 2907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2907): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 2907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429199
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131301070
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429173
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131297804
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429203
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429193
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429194
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429206
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131300118
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429196
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429260
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429197
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429291
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429228
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429199
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429199
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429199
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429199
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.NetworkManagement
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.MultiSimCardManagerPreference
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.NetworkManagementSetting
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.DualHelpActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.DualSoundRingtoneSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.RingtoneSettingTabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.IccLockTabSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429173
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429285
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429172
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131301505
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429203
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429203
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131302910
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429179
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2130838248
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2907): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429216
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429209
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429209
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAlertDialogActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429177
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429212
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429213
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429153
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131302078
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429153
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131302078
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429153
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131302107
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429159
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429117
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429122
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429195
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131297804
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429151
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429204
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429204
I/Babel   ( 3070): MmsConfig: mnc/mcc: 0/0
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429195
I/Babel   ( 3070): MmsConfig.loadMmsSettings
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2130838300
I/Babel   ( 3070): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
I/Babel   ( 3070): MmsConfig.loadFromDatabase
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2907): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2130838300
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:drawable/ic_settings_torchlight
,I/AMMetaDataParserService( 2907): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429202
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429202
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2907): Resource data:2131165381
,I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:xml/searchable
I/AMMetaDataParserService( 2907): getResourceTypeNamexml
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429124
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429187
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2907): Resource data:2131298587
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2907): getResourceTypeNamestring
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429198
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429258
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429220
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429220
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429276
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429276
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/safetycare_help
,I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429148
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 2907): getResourceTypeNameid
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429242
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.KnoxSettings
E/Babel   ( 3070): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3070): MmsConfig.loadFromResources
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2131429211
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2907): Resource data:2130838248
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2907): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2907): Resource data:2131429192
E/Babel   ( 3070): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3070): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
I/AMMetaDataParserService( 2907): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 2907): getResourceTypeNameid
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintOnehandGrip
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
,W/Settings( 3070): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 3070): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3070): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3070): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3070): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3070): VFY: unable to resolve instance field 36
D/dalvikvm( 3070): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3070): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3070): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3070): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3070): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3070): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 3070): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4275fa18
D/dalvikvm( 3070): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4275fa18
D/dalvikvm( 3070): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4275fa18, skipping init
D/dalvikvm( 3070): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4275fa18
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2907): Resource data:2131034120
,D/dalvikvm( 3070): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4275fa18
V/JNIHelp ( 3070): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AMMetaDataParserService( 2907): getResourceName:com.android.contacts:xml/searchable
I/AMMetaDataParserService( 2907): getResourceTypeNamexml
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
I/AMMetaDataParserService( 2907): Resource data:2131034113
I/AMMetaDataParserService( 2907): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 2907): getResourceTypeNamexml
V/Babel   ( 3070): babel boot account: thalitester@gmail.com
,V/Babel   ( 3070): babel boot account: SMS
,I/AMMetaDataParserService( 2907): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/SELinux ( 3095): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3095):  
I/ActivityManager(  746): Killing 2205:com.sec.kidsplat.installer/u0a158 (adj 15): empty #43
,I/AMMetaDataParserService( 2907): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/dalvikvm( 3070): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4275fa18
,D/dalvikvm( 3070): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x4275fa18
D/dalvikvm( 3070): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4275fa18
,D/dalvikvm( 3070): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4275fa18
,I/AMMetaDataParserService( 2907): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/SELinux ( 3095): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3095):  
I/SELinux ( 3095):  
,I/SELinux ( 3095): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3095): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3095): >>>>> Normal User
,E/dalvikvm( 3095): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 3095): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3095): in addTimaSignatureService
,I/AMMetaDataParserService( 2907): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,D/TimaKeyStoreProvider( 3095): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3095): Added TimaKesytore provider
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131034113
,I/AMMetaDataParserService( 2907): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,I/AMMetaDataParserService( 2907): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/ProviderInstaller( 3070): Installed default security provider GmsCore_OpenSSL
,V/AlarmManager(  746): waitForAlarm result :4
,V/AlarmManager(  746): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  746): waitForAlarm result :4
,V/AlarmManager(  746): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/AMMetaDataParserService( 2907): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/AMMetaDataParserService( 2907): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/SELinux ( 3111): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3111):  
,I/ActivityManager(  746): Killing 2226:com.sec.android.diagmonagent/1000 (adj 15): empty #43
I/AMMetaDataParserService( 2907): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 2907): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 2907): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 2907): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131034112
I/AMMetaDataParserService( 2907): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/PowerManagerService(  746): [PWL] On : 0 (44855 ms ago)
I/PowerManagerService(  746): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  746): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1067, ws=null) (elapsedTime=7279)
,I/AMMetaDataParserService( 2907): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
,I/SELinux ( 3111): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3111):  
I/SELinux ( 3111):  
,I/SELinux ( 3111): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3111): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3111): >>>>> Normal User
,E/dalvikvm( 3111): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
,E/SELinux ( 3111): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2907): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
,D/TimaKeyStoreProvider( 3111): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3111): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3111): Added TimaKesytore provider
,I/AMMetaDataParserService( 2907): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
,I/AMMetaDataParserService( 2907): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
I/AMMetaDataParserService( 2907): Resource data:2131034113
I/AMMetaDataParserService( 2907): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 2907): getResourceTypeNamexml
W/ContextImpl( 3111): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3111): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/AMMetaDataParserService( 2907): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/knox    ( 3111): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3111): KNOXAgentService : onCreate()
,W/ContextImpl( 3111): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
D/knox    ( 3111): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3111): KNOXAgentService. startJobThread() start
D/knox    ( 3111): KNOXAgentService. JobThread()
D/knox    ( 3111): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3111): KNOXAgentService. startJobThread() wait
,I/SELinux ( 3125): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3125):  
,D/knox    ( 3111): mKnoxAgentEngine.ELMEngine( context , reStart:true).
D/knox    ( 3111): ELMEngine.ServiceHandler.handleMessage( DEFAULT ).
D/knox    ( 3111): KNOXAgentService : onDestroy().
,D/knox    ( 3111): ModuleBase.cancelAllAlarmManageModule()
,I/AMMetaDataParserService( 2907): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/dalvikvm( 2907): GC_CONCURRENT freed 2269K, 35% free 12375K/19008K, paused 3ms+3ms, total 30ms
,I/AMMetaDataParserService( 2907): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
I/SELinux ( 3125): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3125):  
I/SELinux ( 3125):  
,I/SELinux ( 3125): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3125): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3125): >>>>> Normal User
,E/dalvikvm( 3125): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
,E/SELinux ( 3125): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3125): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3125): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3125): Added TimaKesytore provider
,I/AMMetaDataParserService( 2907): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2907): Resource data:2131034116
I/AMMetaDataParserService( 2907): getResourceName:com.android.contacts:xml/findo_searchable
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2907): Resource data:2131099668
,I/AMMetaDataParserService( 2907): getResourceName:com.sec.android.app.sbrowser:xml/searchable
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,I/AMMetaDataParserService( 2907): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 2907): Resource data:2131099650
I/AMMetaDataParserService( 2907): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,E/KnoxSetupWizardClient( 3125): isShipMode : 1
,I/KnoxSetupWizardClient( 3125): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 2907): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,W/System.err( 3125): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3125): 	at android.os.Parcel.readException(Parcel.java:1469)
,W/System.err( 3125): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 3125): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3125): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 3125): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
,W/System.err( 3125): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/System.err( 3125): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
D/ShortcutReceiver( 3125):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
W/System.err( 3125): 	at android.os.Parcel.readException(Parcel.java:1469)
,W/System.err( 3125): 	at android.os.Parcel.readException(Parcel.java:1419)
I/yash    ( 3125): setDisableWidget>size:0
W/System.err( 3125): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3125): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
,W/System.err( 3125): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
,W/System.err( 3125): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
,W/System.err( 3125): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/AMMetaDataParserService( 2907): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
,I/SELinux ( 3138): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3138):  
I/ActivityManager(  746): Killing 1638:com.fmm.dm/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2907): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
,D/dalvikvm(  247): GC_EXPLICIT freed 48K, 50% free 9507K/19008K, paused 2ms+3ms, total 28ms
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
,I/SELinux ( 3138): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3138):  
I/SELinux ( 3138):  
,I/SELinux ( 3138): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/19008K, paused 2ms+2ms, total 19ms
E/SELinux ( 3138): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3138): >>>>> Normal User
,E/dalvikvm( 3138): >>>>> com.LocalFota [ userId:0 | appId:10110 ]
E/SELinux ( 3138): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAutoDiscover
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131099667
,I/AMMetaDataParserService( 2907): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 3138): in addTimaSignatureService
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/19008K, paused 2ms+3ms, total 20ms
,D/TimaKeyStoreProvider( 3138): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3138): Added TimaKesytore provider
,I/AMMetaDataParserService( 2907): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559
,I/AMMetaDataParserService( 2907): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558
,I/DBG_WSS_LF( 3138): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
,I/DBG_WSS_LF( 3138): [20.0040.140326][Line:27][<init>] First call
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=3138, uid=10110 requires android.permission.INTERACT_ACROSS_USERS
,I/AMMetaDataParserService( 2907): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
,I/DBG_WSS_LF( 3138): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_WSS_LF( 3138): [20.0040.140326][Line:31][onReceive] *** boot complete ***
,I/DBG_WSS_LF( 3138): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
,I/DBG_WSS_LF( 3138): [20.0040.140326][Line:41][onReceive] nStatus : -1
,I/AMMetaDataParserService( 2907): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
,I/SELinux ( 3153): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3153):  
I/ActivityManager(  746): Killing 2240:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
,I/AMMetaDataParserService( 2907): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
,I/AMMetaDataParserService( 2907): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2907): Resource data:2131099689
,I/AMMetaDataParserService( 2907): getResourceName:com.android.email:xml/spellscroll
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/SELinux ( 3153): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3153):  
I/SELinux ( 3153):  
,I/SELinux ( 3153): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 2907): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2907): Resource data:2131099685
E/SELinux ( 3153): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2907): getResourceName:com.android.email:xml/searchable
E/dalvikvm( 3153): >>>>> Normal User
,E/dalvikvm( 3153): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,I/AMMetaDataParserService( 2907): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,E/SELinux ( 3153): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
,I/AMMetaDataParserService( 2907): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2907): getResourcePackageName:com.android.keyguard.layout
,I/AMMetaDataParserService( 2907): Resource data:2130903052
,I/AMMetaDataParserService( 2907): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
I/AMMetaDataParserService( 2907): getResourceTypeNamelayout
I/AMMetaDataParserService( 2907): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2907): Resource data:2131034112
,I/AMMetaDataParserService( 2907): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 2907): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 3153): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3153): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3153): Added TimaKesytore provider
,I/AMMetaDataParserService( 2907): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,I/AMMetaDataParserService( 2907): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
,D/StatusChecker( 3153): onReceive : android.intent.action.BOOT_COMPLETED
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 2907): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
I/ActivityManager(  746): Killing 2252:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #43
,I/SELinux ( 3167): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3167):  
I/ActivityManager(  746): Killing 2277:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,I/ActivityManager(  746): Waited long enough for: ServiceRecord{43188ff0 u0 com.samsung.android.providers.context/.ContextService}
,I/SELinux ( 3167): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3167):  
I/SELinux ( 3167):  
,I/SELinux ( 3167): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3167): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3167): >>>>> Normal User
,E/dalvikvm( 3167): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10133 ]
,E/SELinux ( 3167): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3167): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3167): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3167): Added TimaKesytore provider
,D/QuickConnect( 3167): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=10133
D/QuickConnect( 3167): Utils.setQCRunningSetting - set : 0
I/QuickConnect( 3167): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,V/QuickConnect( 3167): SconnectManager.getInstance - () return existing instance null
,W/ContextImpl( 3167): Implicit intents with startService are not safe: Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } android.content.ContextWrapper.startServiceAsUser:517 android.content.ContextWrapper.startServiceAsUser:517 com.samsung.android.sconnect.periph.PeriphStartReceiver.onReceive:30 
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/QuickConnect( 3167): PeriphService.onCreate - [START]
,I/SELinux ( 3183): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3183):  
,I/QuickConnect( 3167): PeriphService.onCreate - [START] USER_OWNER
,D/QuickConnect( 3167): PeriphService.setProcessForeground - Build.VERSION.SDK_INT = 19
,I/QuickConnect( 3167): PeriphService.setProcessForeground - true of JB_MR2 complete 
I/QuickConnect( 3167): PeriphService.setState - 0 >> 1
,V/QuickConnect( 3167): PeriphService.runService - 
,I/QuickConnect[1.1][2] ( 3167): SconnectManager.SconnectManager - initiate from com.samsung.android.sconnect.periph.PeriphService@4265e558
I/QuickConnect[1.1][2] ( 3167): SconnectManager.SconnectManager - set getApplicationContext android.app.Application@426564e0
,D/QuickConnect[1.1][2] ( 3167): SconnectManager.registerBroadcast - --
,D/QuickConnect[1.1][2] ( 3167): SconnectManager.SconnectManager - REQUEST_ID :  1
D/QuickConnect[1.1][2] ( 3167): ScanThread.ScanThread - created!
,V/QuickConnect[1.1][2] ( 3167): BluetoothHelper.BluetoothHelper - 
,D/QuickConnect[1.1][2] ( 3167): BluetoothHelper.registerBluetoothAdapterReceiver - mIsBluetoothAdapterReceiver = false
,I/SELinux ( 3183): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3183):  
I/SELinux ( 3183):  
,I/SELinux ( 3183): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3183): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3183): >>>>> Normal User
,E/dalvikvm( 3183): >>>>> com.sec.android.service.bezel [ userId:0 | appId:1000 ]
,E/SELinux ( 3183): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3183): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3183): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3183): Added TimaKesytore provider
,D/dalvikvm(  746): GC_EXPLICIT freed 1384K, 18% free 22689K/27608K, paused 5ms+10ms, total 116ms
,V/QuickConnect[1.1][2] ( 3167): BleHelper.BleHelper - Constructor
,D/BezelQuickConnect( 3183): BezelBroadcastReceiver - onReceive : android.intent.action.BOOT_COMPLETED
,D/BezelQuickConnect( 3183): BezelBroadcastReceiver - StartBezelInteractionService
,D/BezelQuickConnect( 3183): BezelManagerService - setProcessForeground, Build.VERSION.SDK_INT = 19
,I/BezelQuickConnect( 3183): BezelManagerService - setProcessForeground, true of JB_MR2 complete 
,D/BezelQuickConnect( 3183): BezelBroadcastReceiver - onReceive : Send to quickpanel - service.ENABLED
,V/PhoneStatusBar( 1067): onReceive: Intent { act=com.sec.android.sconnect.service.ENABLED flg=0x10 }mQconnectEnable = true
,E/QuickConnect[1.1][2] ( 3167): BleHelper.startScan - not isGattServiceReady. Try to BLE On calling addLeRadioReference()
D/BluetoothRadioManager( 3167): addLeRadioReference: Add CB  com.samsung.android.sconnect.common.net.BleHelper$GattServiceStateChangeCallback@42671988
D/BluetoothRadioManager( 3167):  addRadioReference enabled = false
,D/BluetoothRadioManager( 3167):  BLE Radio count is : 1
D/BluetoothManagerService(  746): foregroundUser: 0
D/BluetoothRadioManager( 3167): addLeRadioReference: isRadioEnabled() =  false
,V/QuickConnect[1.1][2] ( 3167): BleHelper.mSearchWearable - true
W/ContextImpl( 3183): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.android.service.bezel.BezelBroadcastReceiver.onReceive:40 android.app.ActivityThread.handleReceiver:2698 
D/STATUSBAR-PhoneStatusBar( 1067): showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
,E/NetworkSettingsReceiver( 1700): onReceive: android.intent.action.BOOT_COMPLETED
,E/BluetoothManagerService(  746): Package is exist.
,V/QuickConnect[1.1][2] ( 3167): UpnpHelper.UpnpHelper - 
,V/QuickConnect[1.1][2] ( 3167): JmdnsHelper.JmdnsHelper - Constructor
,V/QuickConnect[1.1][2] ( 3167): P2pHelper.P2pHelper - EXEC
,D/QuickConnect[1.1][2] ( 3167): p2pHelperWorkThread.p2pHelperWorkThread - created!
,I/SELinux ( 3200): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3200):  
,D/QuickConnect[1.1][2] ( 3167): WifiHelper.WifiHelper -  -- 
W/BroadcastQueue(  746): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.android.calendar/.magazine.CalendarUpdateRelatedDataReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/QuickConnect[1.1][2] ( 3167): CentralActionManager.CentralActionManager - EXEC
,V/QuickConnect[1.1][2] ( 3167): BluetoothOppActionHelper.BluetoothOppActionHelper - 
,V/QuickConnect[1.1][2] ( 3167): GroupVoiceTalkActionHelper.GroupVoiceTalkActionHelper -  --
,V/QuickConnect[1.1][2] ( 3167): SmartHomeActionHelper.SmartHomeActionHelper - --
,V/QuickConnect[1.1][2] ( 3167): ScreenMirrorActionHelper.ScreenMirrorActionHelper - 
,V/QuickConnect[1.1][2] ( 3167): BluetoothActionHelper.BluetoothActionHelper - 
,D/BluetoothAdapter( 3167): 1114037208: getState() :  mService = null. Returning STATE_OFF
D/WifiDisplayAdapter(  746): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/SELinux ( 3209): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3209):  
,E/BluetoothHeadset( 3167): BTStateChangeCB is registed
,E/BluetoothHeadset( 3167): BluetoothHeadset service is binded
,I/QuickConnect[1.1][2] ( 3167): SconnectManager.getInstance - make new instance com.samsung.android.sconnect.SconnectManager@42660190
,V/QuickConnect[1.1][2] ( 3167): SconnectManager.getInstance - return existing instance com.samsung.android.sconnect.SconnectManager@42660190
,V/QuickConnect[1.1][2] ( 3167): PreDiscoveryHelper.PreDiscoveryHelper -  -- 
,D/QuickConnect[1.1][2] ( 3167): PreDiscoveryHelper.setVisibilityFromSystemDb - --
,D/QuickConnect[1.1][2] ( 3167): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
I/SELinux ( 3200): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3200):  
I/SELinux ( 3200):  
,I/SELinux ( 3200): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/QuickConnect[1.1][2] ( 3167): Utils.getFromDb -  Key[quick_connect_contact_only], isEnabled [1] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 3167): PreDiscoveryHelper.setVisibilityFromSystemDb - isAllowToConnect : false, isContactOnly : true, visibilitySetting : 2
,D/QuickConnect[1.1][2] ( 3167): PreDiscoveryHelper.changeResponseSetting - changed: 2
E/SELinux ( 3200): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/QuickConnect[1.1][2] ( 3167): PreDiscoveryHelper.updateAdvData - 
E/dalvikvm( 3200): >>>>> Normal User
E/dalvikvm( 3200): >>>>> com.android.bluetooth [ userId:0 | appId:1002 ]
,V/QuickConnect[1.1][2] ( 3167): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42660190
,V/QuickConnect[1.1][2] ( 3167): PreDiscoveryHelper.updateRespTarget - 
,E/SELinux ( 3200): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/QuickConnect[1.1][2] ( 3167): PreDiscoveryHelper.initializeAdvData - 
V/QuickConnect[1.1][2] ( 3167): PreDiscoveryHelper.initializeAdvData - name: Galaxy S5-2(11)
D/QuickConnect[1.1][2] ( 3167): PreDiscoveryHelper.initializeAdvData - name selected: Galaxy S5-2(11)
,V/QuickConnect[1.1][2] ( 3167): CONTACT_Info.getMyMobileNumber - 
,D/TimaKeyStoreProvider( 3200): in addTimaSignatureService
I/SELinux ( 3209): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3209):  
I/SELinux ( 3209):  
,I/SELinux ( 3209): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3209): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3209): >>>>> Normal User
,E/dalvikvm( 3209): >>>>> com.sec.android.app.camera [ userId:0 | appId:10147 ]
D/QuickConnect[1.1][2] ( 3167): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3167): CONTACT_Info.getMyMobileNumber - null 
,E/SELinux ( 3209): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3200): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3200): Added TimaKesytore provider
,D/QuickConnect[1.1][2] ( 3167): NetUtil.getP2pMacFromWifiMac - ($)
,V/QuickConnect[1.1][2] ( 3167): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42660190
W/QuickConnect[1.1][2] ( 3167): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.emeeting.b2c.hancom
,D/QuickConnect[1.1][2] ( 3167): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.emeeting
D/QuickConnect[1.1][2] ( 3167): AppPackageUtil.isStubApk - but Stub version[2.7.025] of com.samsung.groupcast
W/QuickConnect[1.1][2] ( 3167): AppPackageUtil.isAppInstalled - this is Stub - com.samsung.groupcast
,D/QuickConnect[1.1][2] ( 3167): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.samsung.groupcast
W/QuickConnect[1.1][2] ( 3167): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3167): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3167): PeriphService.registerUserReceiver - mIsUserReceiver == false
,I/QuickConnect[1.1][2] ( 3167): PeriphService.onStartCommand - USER_OWNER
I/QuickConnect[1.1][2] ( 3167): PeriphService.onStartCommand - Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } flags[0] startId[1]
,I/QuickConnect[1.1][2] ( 3167): PeriphService.onStartCommand - Action: com.samsung.android.sconnect.periph.START_SERVICE
,D/TimaKeyStoreProvider( 3209): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3209): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3209): Added TimaKesytore provider
,W/dalvikvm( 3209): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,D/BtSettings.ProfileConfig( 3200): Adding GattService
D/BtSettings.ProfileConfig( 3200): Adding HeadsetService
,D/BtSettings.ProfileConfig( 3200): Adding A2dpService
D/BtSettings.ProfileConfig( 3200): Adding HidService
D/BtSettings.ProfileConfig( 3200): Adding HealthService
D/BtSettings.ProfileConfig( 3200): Adding PanService
,D/BtSettings.ProfileConfig( 3200): Adding BluetoothMapService
,I/SELinux ( 3232): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3232):  
I/ActivityManager(  746): Killing 2297:com.sec.android.app.mss/u0a21 (adj 15): empty #43
,D/BluetoothAdapterService( 3200): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterState( 3200): make
I/bluedroid( 3200): init
,I/BluetoothAdapterState( 3200): Entering OffState
,I/bte_conf( 3200): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bluedroid( 3200): get_profile_interface socket
,I/GKI_LINUX( 3200): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterService( 3200):  checkAddrForIOP: Loading from conf
E/BluetoothServiceJni( 3200): populateRssiValuesNative
I/bluedroid( 3200): getModelRssiValues
,E/BluetoothServiceJni( 3200): model_rssi_values_callback: low = -70, mid = -60, high = 127
I/SELinux ( 3232): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3232):  
I/SELinux ( 3232):  
,I/SELinux ( 3232): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3232): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3232): >>>>> Normal User
,E/dalvikvm( 3232): >>>>> com.sec.android.inputmethod [ userId:0 | appId:1000 ]
,E/SELinux ( 3232): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3232): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3232): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3232): Added TimaKesytore provider
,I/bluedroid( 3200): config_hci_snoop_log
,D/BluetoothManagerService(  746): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothRadioManager( 3167): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@426c8f48
,D/BluetoothRadioManager( 3167): onBluetoothServiceUp()  registerRadioClient mUUID = 9c489183-fdf1-4f47-ac72-0f3f57fe6a00
,I/bluedroid( 3200): update_radio_count
,D/BluetoothAdapterState( 3200): CURRENT_STATE=OFF, MSG = USER_TURN_ON_RADIO
I/BluetoothAdapterState( 3200): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=false
D/BluetoothAdapterState( 3200): CURRENT_STATE=PENDING, MSG = BEGIN_ENABLE_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
,I/bluedroid( 3200): enable
,I/bt_hci_bdroid( 3200): init
,I/bt_vendor( 3200): bt-vendor : init
I/bt_vendor( 3200): bt-vendor : get_bt_soc_type
E/bt_vendor( 3200): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 3200): init: Local BD Address : dc:06:b5:96:94:38
D/bt_userial_mct( 3200): userial_init
I/bt_vendor( 3200): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3200): Starting hciattach daemon
I/bt_vendor( 3200): try to set false
,I/bt_hci_bdroid( 3200): bt_hc_worker_thread started
,I/bt_vendor( 3200): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 3200): Starting hciattach daemon
,I/bt_vendor( 3200): try to set true
,I/qcom-bluetooth( 3256): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/SELinux ( 3259): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3259):  
,I/ActivityManager(  746): Killing 2311:com.sec.android.app.msa/u0a23 (adj 15): empty #43
,I/qcom-bluetooth( 3266): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/SELinux ( 3259): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3259):  
I/SELinux ( 3259):  
,I/SELinux ( 3259): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3259): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3259): >>>>> Normal User
E/dalvikvm( 3259): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 3259): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/qcom-bluetooth( 3267): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/TimaKeyStoreProvider( 3259): in addTimaSignatureService
D/TimaKeyStoreProvider( 3259): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3259): Added TimaKesytore provider
,I/qcom-bluetooth( 3277): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3282): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,D/SensorService(  746):   0.1 0.4 9.6
,I/qcom-bluetooth( 3283): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3284): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,I/SELinux ( 3296): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3296):  
W/ActivityManager(  746): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 3305): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3305):  
,I/ActivityManager(  746): Killing 1188:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
I/SELinux ( 3296): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3296):  
I/SELinux ( 3296):  
I/SELinux ( 3296): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3296): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 3296): >>>>> Normal User
E/dalvikvm( 3296): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
E/SELinux ( 3296): [DEBUG] seapp_context_lookup: seinfoCategory = release
,W/ActivityManager(  746): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 3296): in addTimaSignatureService
I/SELinux ( 3305): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3305):  
I/SELinux ( 3305):  
,I/SELinux ( 3305): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/TimaKeyStoreProvider( 3296): Cannot add TimaSignature Service, License check Failed
E/SELinux ( 3305): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3305): >>>>> Normal User
,E/dalvikvm( 3305): >>>>> com.android.exchange [ userId:0 | appId:10156 ]
,D/ActivityThread( 3296): Added TimaKesytore provider
,E/SELinux ( 3305): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3305): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3305): Cannot add TimaSignature Service, License check Failed
,I/ActivityManager(  746): Killing 2330:com.sec.pcw.device/1000 (adj 15): empty #43
D/ActivityThread( 3305): Added TimaKesytore provider
,I/Process ( 3259): Sending signal. PID: 3259 SIG: 9
,D/BadgeProvider( 3296): onCreate
,D/BadgeProvider( 3296): DatabaseHelper
I/ActivityManager(  746): Process com.android.email (pid 3259) (adj 9) has died.
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=3296, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,E/SMD     (  240): DCD ON
,I/SELinux ( 3331): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3331):  
,I/SELinux ( 3335): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3335):  
,I/SELinux ( 3331): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3331):  
I/SELinux ( 3331):  
,I/SELinux ( 3331): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3331): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3331): >>>>> Normal User
,E/dalvikvm( 3331): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 3331): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  247): GC_EXPLICIT freed 45K, 50% free 9507K/19008K, paused 2ms+3ms, total 27ms
,D/TimaKeyStoreProvider( 3331): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3331): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3331): Added TimaKesytore provider
I/SELinux ( 3335): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3335):  
I/SELinux ( 3335):  
,I/SELinux ( 3335): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3335): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3335): >>>>> Normal User
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/19008K, paused 2ms+4ms, total 21ms
,E/dalvikvm( 3335): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 3335): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3335): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3335): Cannot add TimaSignature Service, License check Failed
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/19008K, paused 2ms+3ms, total 22ms
,D/ActivityThread( 3335): Added TimaKesytore provider
,I/ActivityManager(  746): Killing 2364:com.vlingo.midas/u0a33 (adj 15): empty #43
,I/SELinux ( 3358): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3358):  
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
I/ActivityManager(  746): Killing 2491:com.sec.android.app.shealth/u0a35 (adj 15): empty #43
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,I/SELinux ( 3358): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3358):  
I/SELinux ( 3358):  
,I/SELinux ( 3358): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3358): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3358): >>>>> Normal User
,E/dalvikvm( 3358): >>>>> com.sec.modem.settings [ userId:0 | appId:1000 ]
E/SELinux ( 3358): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/Process ( 3305): Sending signal. PID: 3305 SIG: 9
,D/TimaKeyStoreProvider( 3358): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3358): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3358): Added TimaKesytore provider
,D/BadgeProvider( 3296): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/ActivityManager(  746): Process com.android.exchange (pid 3305) (adj 9) has died.
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
D/BadgeProvider( 3296): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1246): reloadBadges entered.
D/BadgeProvider( 3296): sendNotify, [notify] : null
D/BadgeProvider( 3296): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3296): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 3296): update, [UpdateCount] : 1
,W/ActivityManager(  746): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 3377): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3377):  
,I/SELinux ( 3377): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3377):  
I/SELinux ( 3377):  
,I/SELinux ( 3377): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3377): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3377): >>>>> Normal User
,E/dalvikvm( 3377): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 3377): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3377): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3377): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3377): Added TimaKesytore provider
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=3377, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
,D/NotiRemoteService( 3377): action com.peel.widget.notification.SETUP_SERVICE_CONNECTION
,D/NotiRemoteService( 3377): connectToPeelService 0
,W/ContextImpl( 3377): Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:529 tv.peel.samsung.widget.a.c.<init>:-1 tv.peel.samsung.widget.NotiRemoteService.a:-1 
,I/SELinux ( 3401): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3401):  
,D/NotiRemoteService( 3377): onServiceOn() mServiceState = 1
,D/NotiRemoteService( 3377): Send action to self com.peel.widget.notification.SERVICE_BINDED
,D/NotiRemoteService( 3377): action com.peel.widget.notification.SERVICE_BINDED
,D/NotiRemoteService( 3377): feature is Off. Stop service
,D/NotiRemoteService( 3377): Send action to self com.peel.widget.notification.STOP_PROCESS
,D/NotiRemoteService( 3377): action com.peel.widget.notification.STOP_PROCESS
,D/NotiRemoteService( 3377): onDestroy()
,D/NotiRemoteService( 3377): mOrientationChangeReceier was not registered
I/ActivityManager(  746): Killing 2080:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/SELinux ( 3401): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3401):  
I/SELinux ( 3401):  
,I/SELinux ( 3401): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3401): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3401): >>>>> Normal User
,E/dalvikvm( 3401): >>>>> org.simalliance.openmobileapi.service [ userId:0 | appId:1101 ]
,E/SELinux ( 3401): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3401): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3401): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3401): Added TimaKesytore provider
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=3401, uid=1101 requires android.permission.INTERACT_ACROSS_USERS
V/SmartcardService( 3401): main Received broadcast
V/SmartcardService( 3401): Starting smartcard service after boot completed
,I/SELinux ( 3421): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3421):  
I/ActivityManager(  746): Killing 2614:com.policydm/1000 (adj 15): empty #43
,E/STK2    ( 1240): onReceive android.intent.action.BOOT_COMPLETED
,I/SELinux ( 3421): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3421):  
I/SELinux ( 3421):  
,I/SELinux ( 3421): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3421): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3421): >>>>> Normal User
,E/dalvikvm( 3421): >>>>> org.simalliance.openmobileapi.service:remote [ userId:0 | appId:1101 ]
,E/SELinux ( 3421): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 3434): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3434):  
,D/TimaKeyStoreProvider( 3421): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3421): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3421): Added TimaKesytore provider
,I/SELinux ( 3434): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3434):  
I/SELinux ( 3434):  
,I/SELinux ( 3434): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3434): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3434): >>>>> Normal User
,E/dalvikvm( 3434): >>>>> com.sec.android.app.sysscope [ userId:0 | appId:1000 ]
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=3421, uid=1101 requires android.permission.INTERACT_ACROSS_USERS
E/SELinux ( 3434): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3434): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3434): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3434): Added TimaKesytore provider
,W/ContextImpl( 3434): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 3452): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3452):  
,I/SELinux ( 3452): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3452):  
I/SELinux ( 3452):  
,I/SELinux ( 3452): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3452): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/qcom-bluetooth( 3459): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 38:94:96:b5:06:dc 
E/dalvikvm( 3452): >>>>> Normal User
,E/dalvikvm( 3452): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
,E/SELinux ( 3452): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/qcom-bluetooth( 3460): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/TimaKeyStoreProvider( 3452): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3452): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3452): Added TimaKesytore provider
,I/bt_vendor( 3200): bluetooth satus is on
,I/GKI_LINUX( 3200): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
D/bt_userial_mct( 3200): userial_open(port:0)
,I/bt_vendor( 3200): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 3200): Done intiailizing UART
I/bt_vendor( 3200): Done intiailizing UART
I/bt_userial_mct( 3200): CMD=61, EVT=61, ACL_Out=62, ACL_In=62
I/bt_vendor( 3200): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 3200): Entering userial_read_thread()
D/GKI_LINUX( 3200): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
I/        ( 3200): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3200): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3200): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3200): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3200): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3200): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3200): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3200): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3200): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3200): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3200): BTE_InitTraceLevels -- TRC_SAP
I/        ( 3200): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3200): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3200): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3200): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3200): BTE_InitTraceLevels -- TRC_BTIF
,I/        ( 3200): BTE_InitTraceLevels -- TRC_PROTOCOL
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=3452, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 3478): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3478):  
I/ActivityManager(  746): Killing 2657:com.sec.spp.push/u0a38 (adj 15): empty #43
,E/bt-btm  ( 3200): BTM_SecRegister:p_cb_info->p_le_callback == 0x77ebbca1 
,E/bt-btm  ( 3200): BTM_SecRegister: btm_cb.api.p_le_callback = 0x77ebbca1 
,E/bt-btif ( 3200): btif_storage_get_adapter_property service_mask:0x0
,E/BluetoothServiceJni( 3200): populateRssiValuesNative
I/bluedroid( 3200): getModelRssiValues
,E/BluetoothServiceJni( 3200): model_rssi_values_callback: low = -70, mid = -60, high = 127
,I/SELinux ( 3478): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3478):  
I/SELinux ( 3478):  
,I/SELinux ( 3478): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3478): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 3478): >>>>> Normal User
,E/dalvikvm( 3478): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 3478): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,E/BluetoothAdapterProperties( 3200): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3200): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3200): 	at dalvik.system.NativeStart.run(Native Method)
,E/BluetoothAdapterProperties( 3200): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3200): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3200): 	at dalvik.system.NativeStart.run(Native Method)
,E/BluetoothAdapterProperties( 3200): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3200): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 3200): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3200): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 3200): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3200): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 3200): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3200): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 3200): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3200): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 3200): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3200): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 3200): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3200): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3200): 	at dalvik.system.NativeStart.run(Native Method)
D/TimaKeyStoreProvider( 3478): in addTimaSignatureService
E/BluetoothAdapterProperties( 3200): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3200): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 3200): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3200): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3200): 	at dalvik.system.NativeStart.run(Native Method)
D/TimaKeyStoreProvider( 3478): Cannot add TimaSignature Service, License check Failed
E/BluetoothAdapterProperties( 3200): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3200): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3200): java.lang.NullPointerException
E/BluetoothServiceJni( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): An exception was thrown by callback 'remote_device_properties_callback'.
D/ActivityThread( 3478): Added TimaKesytore provider
E/BluetoothServiceJni( 3200): java.lang.NullPointerException
E/BluetoothServiceJni( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3200): java.lang.NullPointerException
E/BluetoothServiceJni( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3200): java.lang.NullPointerException
E/BluetoothServiceJni( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3200): java.lang.NullPointerException
E/BluetoothServiceJni( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3200): java.lang.NullPointerException
E/BluetoothServiceJni( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3200): java.lang.NullPointerException
E/BluetoothServiceJni( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3200): java.lang.NullPointerException
E/BluetoothServiceJni( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3200): java.lang.NullPointerException
E/BluetoothServiceJni( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3200): java.lang.NullPointerException
E/BluetoothServiceJni( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): An exception was thrown by callback 'remote_device_properties_callback'.
,E/BluetoothServiceJni( 3200): java.lang.NullPointerException
E/BluetoothServiceJni( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3200): java.lang.NullPointerException
E/BluetoothServiceJni( 3200): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3200): 	at dalvik.system.NativeStart.run(Native Method)
E/bt-btif ( 3200): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 3200): btif_sock_init, radio_req:1, rfc_init:0, vhci_init:0
E/bt-btif ( 3200): btif_sock_init: !vhci_init
D/BluetoothAdapterState( 3200): CURRENT_STATE=PENDING, MSG = ENABLED_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
D/BluetoothAdapterService(1114026032)( 3200): startQuietModeServices:bStart =true QModeRCnt=1
D/BluetoothBondStateMachine( 3200): make
E/bt_mct  ( 3200): hci lib postload completed
W/BluetoothAdapterService( 3200): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(1114026032)( 3200): startQuietModeServices:Starting  com.android.bluetooth.gatt.GattService
D/BluetoothSecureManager( 3200): getInstant: null
D/BluetoothSecureManager( 3200): calling getMethod for getService
I/BluetoothBondStateMachine( 3200): StableState(): Entering Off State
D/BluetoothSecureManager( 3200): calling getService
D/BluetoothSecureManager( 3200): getService return binder: android.os.BinderProxy@426bbf40
D/BluetoothSecureManagerService(  746): isSecureModeEnabled
D/BluetoothSecureManagerService(  746): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 3200): isSecureModeOn:false
D/BluetoothAdapterService( 3200): setProfileState(): setting profile com.android.bluetooth.gatt.GattService to state = 10
W/BluetoothAdapterService( 3200): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 3200): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3200): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 3200): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 3200): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 3200): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
I/BluetoothAdapterState( 3200): Bluetooth adapter radio state changed: 14
D/BluetoothAdapterService( 3200): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3200): updateAdapterState state is 14
D/BluetoothAdapterService( 3200): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3200): Autoconnection is available 
D/BluetoothAdapterService( 3200): updateAdapterState prevState = 10newState = 14
I/BluetoothAdapterState( 3200): Entering OffState
D/BluetoothManagerService(  746): Broadcasting Radio() to 1 Radio Mgr receivers.
D/BluetoothRadioManager( 3167): onBTRadioStateChange:  up = true
I/BtGatt.JNI( 3200): classInitNative(L703): classInitNative: Success!
I/BluetoothManagerService(  746): enableGatt, doBind called
D/BtGatt.GattService( 3200): BluetoothAdapter state is = 10
D/BtGatt.DebugUtils( 3200): handleDebugAction() action=null
D/BtGatt.GattService( 3200): Received start request. Starting profile...
D/BtGatt.GattService( 3200): start()
I/bluedroid( 3200): get_profile_interface gatt
,D/BluetoothManagerService(  746): Broadcasting onBluetoothServiceUp() to 1 receivers.
D/BluetoothRadioManager( 3167): onGattServiceStateChange: up = truemBleCount = 1
,E/QuickConnect[1.1][2] ( 3167): BleHelper.onGattServiceStateChange - up = true, BluetoothGatt is android.bluetooth.IBluetoothGatt$Stub$Proxy@426c9cd0
,E/QuickConnect[1.1][2] ( 3167): BleHelper.onGattServiceStateChange - Radio turned on
,I/Intent to TravelDirActivity( 3478): inside TravelBroadcastReceiver
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=3478, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  746): Killing 2684:com.osp.app.signin/u0a43 (adj 15): empty #43
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1465): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1465): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:87 [0:0] ABOOTCOPLD
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=10172
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,D/dalvikvm(  746): GC_EXPLICIT freed 1064K, 18% free 22715K/27608K, paused 4ms+10ms, total 113ms
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1761 [0:0] [boot]now           :1457094148839
D/daemonapp( 1465): [MSC_Daemon]>>> WU:1762 [0:0] [boot]NUT :1457115720000
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1763 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1764 [0:0] [boot]NUT - now :true
V/AlarmManager(  746): waitForAlarm result :4
,D/daemonapp( 1465): [MSC_Daemon]>>> WDBH:2157 [0:0] ud NT1457115720000
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1212 [0:0] cp update : count : 1, pt : 3
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1774 [0:0] Boot set AR_nexttime :1457115720000
V/AlarmManager(  746): waitForAlarm result :4
,D/comdaemonstockapp( 1465): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 1465): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/SELinux ( 3499): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3499):  
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  746): mCoverManager.getCoverState() : true
,I/SELinux ( 3499): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3499):  
I/SELinux ( 3499):  
,I/SELinux ( 3499): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3499): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 3499): >>>>> Normal User
,E/dalvikvm( 3499): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 3499): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/QuickConnect[1.1][2] ( 3167): BleAdvertiser.BleAdvertiser - Constructor
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,D/BluetoothGattServer( 3167): registerCallback()
,D/BluetoothGattServer( 3167): registerCallback() - UUID=fd68a4c3-63fd-48ab-8d69-48ef91d78040
,D/BtGatt.GattService( 3200): registerServer() - UUID=fd68a4c3-63fd-48ab-8d69-48ef91d78040
D/BtGatt.btif( 3200): btif_gatts_register_app
D/BtGatt.btif( 3200): btgatts_handle_event: Event 2000
E/bt-btif ( 3200): register application first_unuse rcb_idx = 0
,D/BtGatt.btif( 3200): btapp_gatts_handle_cback: Event 0
,D/BtGatt.GattService( 3200): onServerRegistered() - UUID=fd68a4c3-63fd-48ab-8d69-48ef91d78040, serverIf=4
,D/BluetoothGattServer( 3167): onServerRegistered() - status=0 serverIf=4
,V/QuickConnect[1.1][2] ( 3167): BleHelper.shouldScanBleBg - 
D/TimaKeyStoreProvider( 3499): in addTimaSignatureService
,D/QuickConnect[1.1][2] ( 3167): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 3167): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42660190
V/QuickConnect[1.1][2] ( 3167): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42660190
V/QuickConnect[1.1][2] ( 3167): BleHelper.shouldScanBleFg - 
,V/QuickConnect[1.1][2] ( 3167): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42660190
V/QuickConnect[1.1][2] ( 3167): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42660190
,V/QuickConnect[1.1][2] ( 3167): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42660190
D/QuickConnect[1.1][2] ( 3167): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 3167): BleHelper.startScan - bluetoothActionState = 0
,D/QuickConnect[1.1][2] ( 3167): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 3167): BleHelper.startScan - shouldScanBleFg = false
,D/TimaKeyStoreProvider( 3499): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3499): Added TimaKesytore provider
,W/ProcessCpuTracker(  746): Skipping unknown process pid 3494
,W/ProcessCpuTracker(  746): Skipping unknown process pid 3495
,W/ProcessCpuTracker(  746): Skipping unknown process pid 3497
,W/ProcessCpuTracker(  746): Skipping unknown process pid 3503
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=3499, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,E/YouTube ( 3499): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/YouTube ( 3499): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 3499): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 3499): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
,D/YouTube ( 3499): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
,D/YouTube ( 3499): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/YouTube ( 3499): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  746): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  746): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService(  746): getStreamVolume 3 index 0
,I/MediaRouter( 3499): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/YouTube ( 3499): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 3499): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=pCM2fjXErR9Rqcj2Pcnofw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.2&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1457094149&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 3499): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
I/System.out( 3499): Thread-355(HTTPLog):isShipBuild true
,I/System.out( 3499): Thread-355(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/YouTube ( 3499): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,E/Watchdog(  746): !@Sync 1
,D/WifiDisplayAdapter(  746): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/YouTube ( 3499): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3499): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,E/GoogleConversionPing( 3499): Error sending ping
,D/YouTube ( 3499): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3499): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,I/SELinux ( 3550): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3550):  
,I/ActivityManager(  746): Killing 2702:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/YouTube ( 3499): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,V/AlarmManager(  746): waitForAlarm result :4
,V/AlarmManager(  746): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  746): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 3550): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3550):  
I/SELinux ( 3550):  
,I/SELinux ( 3550): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3550): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3550): >>>>> Normal User
,E/dalvikvm( 3550): >>>>> com.qualcomm.atfwd [ userId:0 | appId:1000 ]
,V/AlarmManager(  746): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
E/SELinux ( 3550): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3550): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3550): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3550): Added TimaKesytore provider
,I/iu.UploadsManager( 1782): End new media; added: 0, uploading: 0, time: 44 ms
,W/ContextImpl( 3550): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2698 
E/AtFwd AutoBoot( 3550): AtFwd Auto Boot Started Successfully
D/AtFwdService( 3550): onCreate method
,I/AtFwdService( 3550): Instantiate AtCmdFwd Service
,D/AtCkpdCmdHandler( 3550): De-queing command
W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.location.LocationServiceReceiver.onReceive:41 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 3577): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3577):  
,I/SELinux ( 3577): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3577):  
I/SELinux ( 3577):  
,I/SELinux ( 3577): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3577): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3577): >>>>> Normal User
,E/dalvikvm( 3577): >>>>> com.android.vending [ userId:0 | appId:10030 ]
,E/SELinux ( 3577): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3577): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3577): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3577): Added TimaKesytore provider
,I/ActivityManager(  746): Waited long enough for: ServiceRecord{4335d8e8 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,D/SensorService(  746):   0.1 0.4 9.6
,I/dalvikvm( 3577): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 3577): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3577): VFY: replacing opcode 0x6e at 0x000e
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/Finsky  ( 3577): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 3577): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 3577): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 3577): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 3577): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 3577): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 3577): VFY: replacing opcode 0x6e at 0x000a
,D/SSRMv2:SIOP(  746): SIOP:: AP = 340, Delta = 0
,D/Finsky  ( 3577): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/dalvikvm( 3577): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 3577): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 3577): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 3577): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3577): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 3577): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 3577): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 3577): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 3577): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 3577): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3577): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 3577): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3577): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 3577): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 3577): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 3577): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 3577): VFY: replacing opcode 0x6e at 0x0019
,I/dalvikvm( 1306): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 1306): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1306): VFY: replacing opcode 0x6e at 0x001c
,V/GLSActivity( 1306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Volley  ( 3577): [344] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3577): [351] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 3577): Skipping gmscore version check
,D/Finsky  ( 3577): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3577): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3577): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3577): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1306): GC_EXPLICIT freed 625K, 42% free 11113K/19008K, paused 2ms+7ms, total 34ms
,I/dalvikvm( 1306): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 1306): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 1306): VFY: replacing opcode 0x6e at 0x001f
,V/GLSActivity( 1306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1306): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1306): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1306): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1306): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1306): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1306): VFY: replacing opcode 0x6e at 0x00bb
I/dalvikvm( 1306): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 1306): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 1306): VFY: replacing opcode 0x6e at 0x0041
,I/dalvikvm( 1306): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
,W/dalvikvm( 1306): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1306): VFY: replacing opcode 0x6e at 0x0046
,D/dalvikvm( 1782): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1782): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1782): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 1782): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
,W/dalvikvm( 1782): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1782): VFY: replacing opcode 0x62 at 0x0021
,D/dalvikvm( 1782): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1782): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1782): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1782): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1782): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1782): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1782): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1782): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1782): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
I/dalvikvm( 1782): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1782): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 1782): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,I/System.out( 3577): Thread-356(HTTPLog):isShipBuild true
,I/System.out( 3577): Thread-356(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/InstanceID/Rpc( 1782): Found 10011
,D/FileApkUtils( 1782): Spent 62ms computing apk sha1.
,D/FileApkUtils( 1782): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1782): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1782): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 1782): Reading stored module config
,D/GmsModuleFndr( 1782): Beginning GMS chimera module scan
,D/ChimeraCfgMgr( 1782): Beginning module configuration check
,D/ChimeraCfgMgr( 1782): Module APKs unchanged, check complete
,E/dalvikvm( 1782): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 1782): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1782): VFY: replacing opcode 0x22 at 0x00af
,W/dalvikvm( 1782): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1782): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1782): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1782): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,I/dalvikvm( 1782): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1782): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 1782): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,W/dalvikvm( 1782): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1782): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1782): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1219): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1219): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1219): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1219): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1219): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1219): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1219): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1219): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1219): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1219): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 1219): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 1219): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1219): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,I/ActivityManager(  746): Waited long enough for: ServiceRecord{43062dc8 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
D/dalvikvm( 1219): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
E/dalvikvm( 1782): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1782): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/dalvikvm( 1782): VFY: replacing opcode 0x1f at 0x000e
,D/dalvikvm( 1782): GC_CONCURRENT freed 6240K, 40% free 11443K/19008K, paused 4ms+6ms, total 51ms
,E/dalvikvm( 1782): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1782): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 1782): VFY: replacing opcode 0x1f at 0x00f6
,W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1782): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1782): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1782): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1782): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1782): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 1782): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 1782): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
,I/CheckinService( 1782): Checkin interval check for package: unspecified last checkin: 1456597269343 min interval config: 0 actual interval: 496881755
,I/CheckinService( 1782): Disabling old GoogleServicesFramework version
,D/dalvikvm( 1782): GC_EXPLICIT freed 997K, 44% free 10656K/19008K, paused 4ms+9ms, total 51ms
,W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/GCM     ( 1782): COMPAT: Multi user not supported
,D/GCM     ( 1306): COMPAT: Multi user not supported
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 1782): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1782): Got an BootCompleted event.
,D/BootCompletedReceiver( 1782): Will NOT schedule AdAttestation signal task because it's disabled.
I/dalvikvm( 1306): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.nts.a.c.b
W/dalvikvm( 1306): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1306): VFY: replacing opcode 0x6e at 0x000f
,D/SystemUpdateService( 1782): onCreate
,I/GCoreUlr( 1782): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1219): DispatchingService.onCreate()
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/CheckinService( 1782): Checking schedule, now: 1457094151170 next: 1457184795286
,I/CheckinService( 1782): active receiver: disabled
,I/dalvikvm( 1306): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
,W/dalvikvm( 1306): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 1306): VFY: replacing opcode 0x6e at 0x0010
I/dalvikvm( 1782): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1782): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x0409
,V/AuthZen ( 1782): Handling intent: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 1782): cancelUpdate (empty URL)
,I/SystemUpdateService( 1782): active receiver: disabled
,I/dalvikvm( 1782): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 1782): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x002b
,D/EnterpriseDeviceManagerService(  746): Creating context as user 0
,W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1306): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
,W/dalvikvm( 1306): VFY: unable to resolve instance field 161
,D/dalvikvm( 1306): VFY: replacing opcode 0x52 at 0x0006
,D/dalvikvm( 1782): Trying to load lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42669c58
,I/GCoreUlr( 1219): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/SystemUpdateService( 1782): onDestroy
D/dalvikvm( 1782): Added shared lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42669c58
,D/dalvikvm( 1782): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42669c58, skipping init
,D/EnterpriseDeviceManagerService(  746): Creating context as user 0
,D/AuthZenEventHandler( 1782): Handling event: android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1219): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/dalvikvm( 1306): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1306): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1306): VFY: replacing opcode 0x6e at 0x0059
,I/GCoreUlr( 1219): Unbound from all location providers
,I/GCoreUlr( 1219): Place inference reporting - stopped
,I/dalvikvm( 1306): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1306): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1306): VFY: replacing opcode 0x6e at 0x0022
I/GCoreUlr( 1219): DispatchingService.onDestroy()
,I/GCoreUlr( 1219): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1219): Unbound from all location providers
,I/GCoreUlr( 1219): Place inference reporting - stopped
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1782): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1782): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x00bb
,D/GCM     ( 1306): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,V/GLSActivity( 1306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1306): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
,E/BaseAppContext( 1782): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/dalvikvm( 1306): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1306): VFY: replacing opcode 0x6e at 0x0053
D/ConnectivityService(  746): handleInetConditionChange: no active default network - ignore
,I/dalvikvm( 1782): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
,W/dalvikvm( 1782): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x002f
,W/Auth    ( 1306): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtils( 1067): isPcwEnable = null
,I/AuthZen ( 1782): Fetching signing key...
,I/AuthZen ( 1782): Signing key fetched successfully!
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,I/AuthZen ( 1782): Starting Enrollment...
,D/PersistentNotificationBroadcastReceiver( 1219): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/AuthZen ( 1782): getting auth token. Attempt 0
,W/dalvikvm( 1306): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1306): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1306): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1306): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1306): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1306): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1306): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1306): Thread-50(HTTPLog):isShipBuild true
,I/System.out( 1306): Thread-50(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/Auth    ( 1306): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/cryptauth
,W/AuthZen ( 1782): Retryable error when getting auth token
W/AuthZen ( 1782): java.io.IOException: NetworkError
W/AuthZen ( 1782): 	at com.google.android.gms.auth.t.a(SourceFile:498)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.s.a(SourceFile:908)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.s.e(SourceFile:528)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.s.d(SourceFile:450)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.s.b(SourceFile:442)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.q.a(SourceFile:541)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:395)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:135)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:258)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:209)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:202)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:148)
W/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
W/AuthZen ( 1782): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/AuthZen ( 1782): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/AuthZen ( 1782): 	at android.os.Looper.loop(Looper.java:146)
W/AuthZen ( 1782): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AuthZen ( 1782): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 1782): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:142)
E/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1782): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:258)
E/AuthZen ( 1782): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:209)
E/AuthZen ( 1782): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:202)
E/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:148)
E/AuthZen ( 1782): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1782): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1782): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1782): 	at android.os.Looper.loop(Looper.java:146)
E/AuthZen ( 1782): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/dalvikvm( 1782): GC_CONCURRENT freed 1573K, 42% free 11025K/19008K, paused 3ms+3ms, total 28ms
,D/dalvikvm( 1306): GC_EXPLICIT freed 1582K, 44% free 10809K/19008K, paused 2ms+4ms, total 32ms
,D/AuthZenTransactionCache( 1782): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1782): Clearing transaction cache
,D/WearableService( 1219): callingUid 10011, callindPid: 1219
,D/LocationInitializer( 1782): Restart initialization of location
,E/MDM     ( 1219): [88] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1306): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1306): Proximity feature is not enabled.
,V/GLSActivity( 1306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
,E/MDM     ( 1219): [90] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1782): Restart initialization of location
,D/AuthorizationBluetoothService( 1306): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1306): Proximity feature is not enabled.
,V/GLSActivity( 1306): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  746): GC_EXPLICIT freed 2149K, 18% free 22882K/27608K, paused 4ms+12ms, total 137ms
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
D/Mms/Contact( 1665): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 1665): performUpdate:widgetCount=0
D/QuickConnect[1.1][2] ( 3167): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3167): CONTACT_Info.getMyMobileNumber - 
,I/SELinux ( 3697): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3697):  
,D/QuickConnect[1.1][2] ( 3167): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3167): CONTACT_Info.getMyMobileNumber - null 
D/QuickConnect[1.1][2] ( 3167): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3167): CONTACT_Info.getMyMobileNumber - 
,D/Mms/Contact( 1665): sContactsObserver.onChange(),selfUpdate=false
,D/dalvikvm(  247): GC_EXPLICIT freed 44K, 50% free 9507K/19008K, paused 2ms+2ms, total 26ms
,D/QuickConnect[1.1][2] ( 3167): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3167): CONTACT_Info.getMyMobileNumber - null 
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/19008K, paused 1ms+2ms, total 19ms
I/SELinux ( 3697): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3697):  
I/SELinux ( 3697):  
,I/SELinux ( 3697): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3697): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3697): >>>>> Normal User
,E/dalvikvm( 3697): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
,E/SELinux ( 3697): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3697): in addTimaSignatureService
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/19008K, paused 2ms+2ms, total 19ms
,D/TimaKeyStoreProvider( 3697): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3697): Added TimaKesytore provider
,V/TaskCloserActivity( 3697): TaskCloserActivity enter()
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=3697, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 3709): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3709):  
D/AmoledAdjustTimer(  746): prevTemp = 301, currTemp = 304, prevStep = 5, currStep = 5
,I/SELinux ( 3709): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3709):  
I/SELinux ( 3709):  
,I/SELinux ( 3709): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3709): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3709): >>>>> Normal User
,E/dalvikvm( 3709): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,E/SELinux ( 3709): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3709): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3709): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3709): Added TimaKesytore provider
,D/FactoryTestApp( 3709): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
,I/FactoryTestApp( 3709): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
,D/FactoryTest( 3709): User mode
,I/SELinux ( 3721): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3721):  
I/ActivityManager(  746): Killing 1665:com.android.mms/u0a48 (adj 15): empty #43
,D/CountryDetector(  746): No listener is left
,I/SELinux ( 3721): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3721):  
I/SELinux ( 3721):  
,I/SELinux ( 3721): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3721): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3721): >>>>> Normal User
,E/dalvikvm( 3721): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 3721): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3721): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3721): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3721): Added TimaKesytore provider
,E/MTPRx   ( 3721): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 3721): check value of boot_completed is1
,E/MTPRx   ( 3721): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3721): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3721): Status for mount/Unmount :removed
,E/MTPRx   ( 3721): SDcard is not available
,W/MTPRx   ( 3721): value of connected istrue
W/MTPRx   ( 3721): value of configured istrue
W/MTPRx   ( 3721): value of mtpEnabled istrue
,W/MTPRx   ( 3721): value of ptpEnabled isfalse
E/MTPRx   ( 3721): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3721): mFirstTime: false
,D/        ( 3721): MTP: reading debug level property
,E/MTPRx   ( 3721):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 3721): Getting CryptionKey from JAVA
,E/MTPRx   ( 3721): currentUserId is 0
,E/MTPRx   ( 3721): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3721): usbMode is 0200
,E/MTPRx   ( 3721): is_secretmode is NOT 1
,W/MTPRx   ( 3721): Phone is lockedtrue
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/MTPRx   ( 3721):  inside checkKnoxStatus
,D/MTPRx   ( 3721):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 3721): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3721): noti = 17
,E/MTPRx   ( 3721): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 3721): else part ... so first time!!!
,E/MTPPlaObsrvr( 3721): inside setContext()
,E/MTPPlaObsrvr( 3721):  inside createplafiles
,E/MTPPlaObsrvr( 3721): playlist count is0
,E/MTPPlaObsrvr( 3721):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3721):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 3721): Inside registerContentObserver
E/MtpAdbObserver( 3721): inside setContext()
,E/MtpAdbObserver( 3721): Inside registerContentObserver
,W/Settings( 3721): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 3721): onCreate.
,E/MtpService( 3721): < MTP > Registering BroadCast receiver :::::
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,E/MtpService( 3721): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3721): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3721): onStartCommand.
,E/MtpService( 3721): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 3721): calling native method
,E/MTPJNIInterface( 3721): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 3721): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 3721): noti = 10
,E/MtpService( 3721): onStartCommand.
,E/MtpService( 3721): handleMessage. msg= { when=-2ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 3721): calling native method
E/MTPRx   ( 3721): Checking the driver time out
E/MTPJNIInterface( 3721): noti = 2
,D/        ( 3721): deleting sockets before message queue initialization
,D/        ( 3721): event handler thread is created, so set the flag
,E/MTPRx   ( 3721): called native method
,E/MTPJNIInterface( 3721): Getting media scanner status0
,E/MTPJNIInterface( 3721): DeviceName is Galaxy S5-2
E/MTPJNIInterface( 3721): setting Media scanner status0
E/MTPJNIInterface( 3721): After setting Media scanner status0
,W/MTPRx   ( 3721): notification from stack 1
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1465): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1465): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
,D/dalvikvm( 1465): GC_CONCURRENT freed 7271K, 46% free 10416K/19008K, paused 8ms+9ms, total 54ms
,D/dalvikvm( 1465): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1457115720000
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1457094152470
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/SamsungIME( 3232): InputManagerImpl.getInstance() == null
,I/SELinux ( 3750): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3750):  
,I/SELinux ( 3750): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3750):  
I/SELinux ( 3750):  
,I/SELinux ( 3750): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3750): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 3750): >>>>> Normal User
,E/dalvikvm( 3750): >>>>> com.samsung.groupcast [ userId:0 | appId:10015 ]
,E/SELinux ( 3750): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 3750): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3750): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3750): Added TimaKesytore provider
,D/GKI_LINUX( 3200): release_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,D/GroupCast_FileTools( 3750): [getDirectoryForImageResized : 295] cleaning!!
,W/System.err( 3750): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.mv.player
,W/System.err( 3750): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 3750): 	at com.samsung.groupcast.application.App.preLoadShareVideoCheck(App.java:325)
W/System.err( 3750): 	at com.samsung.groupcast.application.App.onCreate(App.java:145)
W/System.err( 3750): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
,W/System.err( 3750): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 3750): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 3750): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 3750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3750): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 3750): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 3750): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 3750): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 3750): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 3750): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 3750): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 3750): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
W/System.err( 3750): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
,W/System.err( 3750): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 3750): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 3750): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 3750): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
,W/System.err( 3750): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 3750): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 3750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3750): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 3750): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 3750): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 3750): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 3750): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 3750): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 3750): 	at dalvik.system.NativeStart.main(Native Method)
,I/SELinux ( 3763): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3763):  
I/ActivityManager(  746): Killing 2726:com.sec.android.app.safetyassurance/u0a50 (adj 15): empty #43
,I/SELinux ( 3763): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3763):  
I/SELinux ( 3763):  
,I/SELinux ( 3763): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3763): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 3763): >>>>> Normal User
,E/dalvikvm( 3763): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
,E/SELinux ( 3763): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 3763): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3763): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3763): Added TimaKesytore provider
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=3763, uid=10024 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 3778): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3778):  
,I/ActivityManager(  746): Killing 2754:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,I/SELinux ( 3778): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3778):  
I/SELinux ( 3778):  
,I/SELinux ( 3778): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3778): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3778): >>>>> Normal User
,E/dalvikvm( 3778): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
,E/SELinux ( 3778): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/dalvikvm( 3778): Enabling JNI app bug workarounds for target SDK version 8...
,D/TimaKeyStoreProvider( 3778): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3778): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3778): Added TimaKesytore provider
,I/PCWCLIENTTRACE_PushUtil( 3778): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3778): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 3778): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_LOG( 3778): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3778): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_SYSTEMReceiver( 3778): [onReceive] - android.intent.action.PACKAGE_ADDED
,I/SELinux ( 3795): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3795):  
I/ActivityManager(  746): Killing 2764:com.wssyncmldm/1000 (adj 15): empty #43
,I/SELinux ( 3795): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3795):  
I/SELinux ( 3795):  
,I/SELinux ( 3795): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3795): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3795): >>>>> Normal User
,E/dalvikvm( 3795): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10034 ]
,E/SELinux ( 3795): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3795): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3795): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3795): Added TimaKesytore provider
,E/MTPJNIInterface( 3721): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3721): SDcard is not available
,E/MTPJNIInterface( 3721): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3721): SDcard is not available
E/SQLiteLog( 3721): (21) API call with NULL database connection pointer
E/SQLiteLog( 3721): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3721): (21) API call with NULL database connection pointer
E/SQLiteLog( 3721): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3721): (21) API call with NULL database connection pointer
E/SQLiteLog( 3721): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3721): (21) API call with NULL database connection pointer
,E/SQLiteLog( 3721): (21) misuse at line 96833 of [00bb9c9ce4]
,W/MTPRx   ( 3721): notification from stack 2
D/        ( 3721): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3721): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3721): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,D/        ( 3721): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
