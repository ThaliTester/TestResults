#### Test 57132760f6ec045_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
W/System.err( 4415): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 4415): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 4415): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 4415): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 4415): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 4415): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 4415): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 4415): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 4415): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 4415): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:105)
W/System.err( 4415): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:89)
W/System.err( 4415): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 4415): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 4415): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 4415): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 4415): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4415): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4415): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 4415): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4415): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4415): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 4415): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 4415): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 4415): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 4415): 	at libcore.io.Posix.open(Native Method)
W/System.err( 4415): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 4415): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 4415): 	... 21 more
D/GalaxyFinderApplication( 4415): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 4415): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 4434): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4434):  
--------- beginning of /dev/log/system
I/ActivityManager(  740): Killing 3092:com.sec.android.app.mt/1000 (adj 15): empty #43
,I/SELinux ( 4434): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4434):  
I/SELinux ( 4434):  
I/SELinux ( 4434): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4434): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4434): >>>>> Normal User
E/dalvikvm( 4434): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 4434): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4434): in addTimaSignatureService
D/TimaKeyStoreProvider( 4434): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4434): Added TimaKesytore provider
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4434, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 4434): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/SELinux ( 4461): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4461):  
E/Device Type Shared Preferences( 4434): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 4434): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 4434): ContentProvider is not null
I/SELinux ( 4461): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4461):  
I/SELinux ( 4461):  
I/SELinux ( 4461): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4461): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4461): >>>>> Normal User
E/dalvikvm( 4461): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 4461): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4461): in addTimaSignatureService
D/TimaKeyStoreProvider( 4461): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4461): Added TimaKesytore provider
V/MediaPlayer( 4434): decode(61, 33979084, 48105)
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
V/AudioCache(  250): notify(0xb7e856c8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb7e856c8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e856c8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e856c8, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb7e856c8, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4461, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e856c8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e856c8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e856c8, 8, 0, 0)
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
V/MediaPlayer( 4434): decode(63, 33914984, 10421)
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
V/AudioCache(  250): notify(0xb7e80560, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb7e80560, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e80560, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e80560, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb7e80560, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
D/dalvikvm( 4461): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42a92f00, skipping init
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
I/SecureStorage( 4461): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4461): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
I/SecureStorage(  325): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4461
I/SecureStorage(  325): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4461): [INFO]: SPID(0x00000000)SS Daemon is running
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e80560, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e80560, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e80560, 8, 0, 0)
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
V/MediaPlayer( 4434): decode(64, 37457308, 34198)
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
V/AudioCache(  250): notify(0xb7e761c8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb7e761c8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e761c8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e761c8, 1, 0, 0)
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
D/AndroidRuntime( 4452): 
D/AndroidRuntime( 4452): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e761c8, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/AudioPlayer(  250): First fillBuffer call!!
D/AndroidRuntime( 4452): CheckJNI is OFF
D/AndroidRuntime( 4452): setted country_code = Poland
D/AndroidRuntime( 4452): setted countryiso_code = PL
D/AndroidRuntime( 4452): setted sales_code = XEO
D/AndroidRuntime( 4452): readGMSProperty: start
D/AndroidRuntime( 4452): readGMSProperty: already setted!!
D/AndroidRuntime( 4452): readGMSProperty: end
D/AndroidRuntime( 4452): addProductProperty: start
I/SecureStorage( 4461): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  325): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4461
I/SecureStorage(  325): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
D/dalvikvm( 4452): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4452): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4452): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4452): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4452): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e761c8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e761c8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e761c8, 8, 0, 0)
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
V/MediaPlayer( 4434): decode(65, 33862452, 7405)
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
V/AudioCache(  250): notify(0xb7e78978, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb7e78978, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78978, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78978, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb7e78978, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb7e78978, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78978, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78978, 8, 0, 0)
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
V/MediaPlayer( 4434): decode(66, 37547940, 5555)
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
V/AudioCache(  250): notify(0xb7e7d500, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb7e7d500, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7d500, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7d500, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb7e7d500, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb7e7d500, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7d500, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7d500, 8, 0, 0)
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
V/MediaPlayer( 4434): decode(67, 30367732, 5085)
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
V/AudioCache(  250): notify(0xb7e7e998, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb7e7e998, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7e998, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7e998, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb7e7e998, 6, 0, 0)
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
V/AudioCache(  250): notify(0xb7e7e998, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7e998, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): addBatteryData
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7e998, 8, 0, 0)
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
V/MediaPlayer( 4434): decode(68, 30372876, 21552)
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
V/AudioCache(  250): notify(0xb7e70440, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb7e70440, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e70440, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e70440, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb7e70440, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/AudioPlayer(  250): First fillBuffer call!!
E/memtrack( 4452): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4452): failed to load memtrack module: -2
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e70440, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e70440, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e70440, 8, 0, 0)
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
,V/AwesomePlayer(  250): mSecMediaClock clear
V/MediaPlayer( 4434): decode(69, 37543652, 4230)
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
V/AudioCache(  250): notify(0xb7e7c9a0, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
D/dalvikvm( 4452): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
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
V/AudioCache(  250): notify(0xb7e7c9a0, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7c9a0, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7c9a0, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb7e7c9a0, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7c9a0, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7c9a0, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7c9a0, 8, 0, 0)
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
V/MediaPlayer( 4434): decode(70, 30337076, 9400)
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
V/AudioCache(  250): notify(0xb7e799c8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb7e799c8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e799c8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e799c8, 1, 0, 0)
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
W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e799c8, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
D/AndroidRuntime( 4452): Calling main entry com.android.commands.am.Am
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e799c8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e799c8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e799c8, 8, 0, 0)
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
V/MediaPlayer( 4434): decode(71, 33925464, 44276)
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
V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(35, 33925464, 44276)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e81dd8, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb7e81dd8, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e81dd8, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e81dd8, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
I/SELinux ( 4532): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4532):  
I/ActivityManager(  740): Killing 3164:com.sec.android.app.camera/u0a147 (adj 15): empty #43
D/dalvikvm(  248): GC_EXPLICIT freed 46K, 50% free 9513K/18936K, paused 2ms+3ms, total 31ms
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/ApplicationPolicy(  740): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e81dd8, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9513K/18936K, paused 2ms+3ms, total 20ms
I/SELinux ( 4532): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4532):  
I/SELinux ( 4532):  
I/SELinux ( 4532): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4532): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4532): >>>>> Normal User
E/dalvikvm( 4532): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 4532): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9513K/18936K, paused 1ms+2ms, total 19ms
D/TimaKeyStoreProvider( 4532): in addTimaSignatureService
D/TimaKeyStoreProvider( 4532): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4532): Added TimaKesytore provider
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e81dd8, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e81dd8, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
D/CustomFrequencyManagerService(  740): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  pkgName : ACTIVITY_RESUME_BOOSTER@5
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e81dd8, 8, 0, 0)
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
V/MediaPlayer( 4434): decode(72, 33885672, 29256)
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
V/AudioCache(  250): notify(0xb7e78d68, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
W/ActivityManager(  740): mDVFSHelper.acquire()
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
V/AudioCache(  250): notify(0xb7e78d68, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78d68, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78d68, 1, 0, 0)
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
V/AudioCache(  250): notify(0xb7e78d68, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/SELinux ( 4549): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4549):  
D/LockPatternUtils( 1065): isPcwEnable = null
D/AndroidRuntime( 4452): Shutting down VM
D/dalvikvm( 4452): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+1ms, total 2ms
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
I/SELinux ( 4549): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4549):  
I/SELinux ( 4549):  
I/SELinux ( 4549): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4549): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4549): >>>>> Normal User
E/dalvikvm( 4549): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 4549): [DEBUG] seapp_context_lookup: seinfoCategory = default
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78d68, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78d68, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
D/SurfaceWidgetView( 1248): destroyHardwareResources():1130968048
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
D/TimaKeyStoreProvider( 4549): in addTimaSignatureService
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78d68, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  250): instance freeNode
I/AudioPlayer(  250): reset out
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (-2/12)
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
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
V/MediaPlayer( 4434): decode(73, 37491572, 52024)
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
V/AudioCache(  250): notify(0xb7e78a88, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
D/TimaKeyStoreProvider( 4549): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4549): Added TimaKesytore provider
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
V/AudioCache(  250): notify(0xb7e78a88, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78a88, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78a88, 1, 0, 0)
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
D/LockPatternUtils( 1065): isPcwEnable = null
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78a88, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/SQLiteSecureOpenHelper( 2021): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2021): getDatabaseLocked(b,b,pwd)...
I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78a88, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78a88, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e78a88, 8, 0, 0)
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
V/MediaPlayer( 4434): decode(74, 33969800, 9226)
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
V/AudioCache(  250): notify(0xb7e7a850, 8, 0, 0)
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
V/AudioCache(  250): notify(0xb7e7a850, 200, 973, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7a850, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7a850, 1, 0, 0)
V/AudioCache(  250): prepared
V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4549, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7a850, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
V/MediaPlayerService(  250): wait for playback complete
I/AudioPlayer(  250): First fillBuffer call!!
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4549, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
,V/WebViewChromium( 4549): Binding Chromium to the background looper Looper (main, tid 1) {42761e48}
,I/chromium( 4549): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4549): Initializing chromium process, renderers=0
V/AwesomePlayer(  250): postAudioEOS delayUs (0)
V/AwesomePlayer(  250): onCheckAudioStatus
V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7a850, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7a850, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
V/AudioCache(  250): wait - success
,V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
,V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e7a850, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  250): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  250): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  250): instance freeNode
,I/AudioPlayer(  250): reset out
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  250): SecMediaClock destructor
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): ~StagefrightPlayer
V/StagefrightPlayer(  250): reset
,V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
,V/AwesomePlayer(  250): destructor
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
,V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
,V/MediaPlayer( 4434): decode(75, 30402580, 4509)
,V/MediaPlayerService(  250): decode(35, 30402580, 4509)
V/MediaPlayerService(  250): player type = 3
V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): constructor
,V/AwesomePlayer(  250): setDefault
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
,V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  250): mSecMediaClock clear
V/StagefrightPlayer(  250): StagefrightPlayer
V/AwesomePlayer(  250): setListener
V/StagefrightPlayer(  250): initCheck
,V/AwesomePlayer(  250): setAudioSink
V/StagefrightPlayer(  250): setDataSource(35, 30402580, 4509)
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  250): notify(0xb7e87188, 8, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  250): mAudioTrackVector clear
V/AwesomePlayer(  250): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  250): mSecMediaClock clear
,V/AwesomePlayer(  250): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  250): mBitrate = -1 bits/sec
V/AwesomePlayer(  250): current audio track index (0) is added to vector
V/AwesomePlayer(  250): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  250): AwesomePlayer::setDataSource_l():: This is not a DRM content
,V/MediaPlayerService(  250): prepare
V/AwesomePlayer(  250): prepareAsync
V/MediaPlayerService(  250): wait for prepare
V/AwesomePlayer(  250): onPrepareAsyncEvent
I/SecMediaClock(  250): SecMediaClock constructor
I/SecMediaClock(  250): reset
V/AwesomePlayer(  250): initAudioDecoder
V/AwesomePlayer(  250): checkOffloadExceptions is true
,I/OMXCodec(  250): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,W/chromium( 4549): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/OMX     (  250): mDispatchers.add
I/OMXCodec(  250): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  250): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  250): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  250): finishAsyncPrepare_l
V/AwesomePlayer(  250): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  250): notify(0xb7e87188, 200, 973, 0)
V/AudioCache(  250): ignored
,V/AwesomePlayer(  250): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e87188, 5, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e87188, 1, 0, 0)
V/AudioCache(  250): prepared
,V/AudioCache(  250): wait - success
V/MediaPlayerService(  250): start
V/StagefrightPlayer(  250): start
V/AwesomePlayer(  250): play
V/AwesomePlayer(  250): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  250): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec(  250): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  250): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  250): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  250): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  250):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  250): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  250): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e87188, 6, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): addBatteryData
,V/MediaPlayerService(  250): wait for playback complete
I/AudioPlayer(  250): First fillBuffer call!!
,V/AwesomePlayer(  250): postAudioEOS delayUs (0)
,V/AwesomePlayer(  250): onCheckAudioStatus
,V/AwesomePlayer(  250): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  250): onStreamDone
V/AwesomePlayer(  250): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  250): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e87188, 2, 0, 0)
V/AudioCache(  250): playback complete - thread will wake up later
,V/AwesomePlayer(  250): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e87188, 7, 0, 0)
V/AudioCache(  250): ignored
V/AwesomePlayer(  250): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  250): addBatteryData
,V/AudioCache(  250): wait - success
V/StagefrightPlayer(  250): reset
V/AwesomePlayer(  250): reset_l()
V/AwesomePlayer(  250): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  250): notify(0xb7e87188, 8, 0, 0)
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
,I/SA      ( 4082): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4082): [DM] init START
,I/SA      ( 4082): [DM] This device is not a Vodafone
,I/SA      ( 4082): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4082): support phone number id : false
,I/SA      ( 4082): [DM] init END
,I/SA      ( 4082): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
V/AlarmManager(  740): waitForAlarm result :4
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SA      ( 4082): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  740): Killing 3259:com.android.email/u0a155 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,D/Mms/PackageInstallReceiver( 3782): loadAuthorityPref(): sEnableAuthority = true
,I/IcingCorporaProvider( 2122): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/ContextImpl( 2815): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 4593): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4593):  
,I/SELinux ( 4593): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4593):  
I/SELinux ( 4593):  
,I/SELinux ( 4593): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4593): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4593): >>>>> Normal User
,E/dalvikvm( 4593): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
,E/SELinux ( 4593): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4593): in addTimaSignatureService
,D/dalvikvm( 3500): GC_CONCURRENT freed 6596K, 42% free 11074K/18936K, paused 8ms+4ms, total 105ms
,D/TimaKeyStoreProvider( 4593): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4593): Added TimaKesytore provider
,D/CapabilityManagerService New( 4593): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4593, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 4605): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4605):  
I/ActivityManager(  740): Killing 3255:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
,I/SELinux ( 4605): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4605):  
I/SELinux ( 4605):  
,I/SELinux ( 4605): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4605): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4605): >>>>> Normal User
,E/dalvikvm( 4605): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
,E/SELinux ( 4605): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4605): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4605): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4605): Added TimaKesytore provider
,I/IcingCorporaProvider( 2122): UpdateCorporaTask done [took 299 ms] updated apps [took 299 ms] 
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4605, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,D/Finsky  ( 3500): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3500): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/Adreno-EGL( 4549): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4549): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4549): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4549): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4549): Remote Branch: 
I/Adreno-EGL( 4549): Local Patches: 
I/Adreno-EGL( 4549): Reconstruct Branch: 
,I/SurfaceFlinger(  247): id=7 Removed Mauncher (7/11)
,I/SurfaceFlinger(  247): id=7 Removed Mauncher (-2/11)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/SecureStorage(  325): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  325): [INFO]: SPID(0x00000003)PID: 4461, TID: 4461
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1442): [237392/5] Surface widget visibility changed visibility = false on instance = 1
,D/Launcher( 1248): onTrimMemory. Level: 20
,I/dalvikvm( 4549): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 4549): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4549): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4549): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4549): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4549): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4549): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4549): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4549): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4549): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4549): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4549): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4549): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4549): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4549): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4549): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4549): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4549): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4549): CordovaWebView is running on device made by: samsung
,I/SecureStorage( 4461): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 4461): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4461): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4461): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4461): Open platform.db in secure mode
,I/SurfaceFlinger(  247): id=17 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 4549): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4549): Enabling debug mode 0
,D/OpenGLRenderer( 4549): GL error from OpenGLRenderer: 0x502
,E/OpenGLRenderer( 4549):   GL_INVALID_OPERATION
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SQLiteSecureOpenHelper( 4461): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 4461): ...getDatabaseLocked(b,b,pwd)
,D/CustomFrequencyManagerService(  740): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  740): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  740): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/ActivityManager(  740): Killing 3281:com.sec.modem.settings/1000 (adj 15): empty #43
,W/GAV2    ( 4605): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 4641): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4641):  
,I/SELinux ( 4641): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4641):  
I/SELinux ( 4641):  
,I/SELinux ( 4641): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4641): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4641): >>>>> Normal User
E/dalvikvm( 4641): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
D/JsMessageQueue( 4549): Set native->JS mode to OnlineEventsBridgeMode
,E/SELinux ( 4641): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4641): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4641): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4641): Added TimaKesytore provider
,D/PackageIntentReceiver( 4641): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4641): Not GearManger package! 
,I/SELinux ( 4656): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4656):  
,D/dalvikvm( 4549): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42a89178
I/ActivityManager(  740): Killing 1340:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,D/dalvikvm( 4549): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42a89178
,D/jxcore_app_log( 4549): JniHelper::setJavaVM(0x41cd24f8), pthread_self() = 1943350736
,I/SELinux ( 4656): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4656):  
I/SELinux ( 4656):  
,I/SELinux ( 4656): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4656): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4656): >>>>> Normal User
,E/dalvikvm( 4656): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 4656): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4656): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4656): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4656): Added TimaKesytore provider
,I/chromium( 4549): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/MagazineService Version( 4656): Magazine-Channel: 13
,D/MagazineService Version( 4656): Magazine-Provider: 13
,D/MagazineService Version( 4656): Magazine-Administrator: 11
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4656, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/HeadlinesChannelApplication( 4656): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 4656): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,I/SELinux ( 4671): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4671):  
,I/Icing   ( 1785): Indexing 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B from com.google.android.googlequicksearchbox
,I/SELinux ( 4671): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4671):  
I/SELinux ( 4671):  
,I/SELinux ( 4671): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4671): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4671): >>>>> Normal User
,E/dalvikvm( 4671): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 4671): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/MagazineService::MagazineService( 4656): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,D/MagazineService::MagazineService( 4656): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  740): Killing 3301:tv.peel.smartremote/u0a163 (adj 15): empty #43
,D/TimaKeyStoreProvider( 4671): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4671): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4671): Added TimaKesytore provider
,W/GAV2    ( 4605): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  740): Killing 3327:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,D/dalvikvm( 4549): GC_CONCURRENT freed 4926K, 33% free 12767K/18936K, paused 3ms+2ms, total 33ms
,D/dalvikvm( 4549): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 4549): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/Icing   ( 1785): Indexing done 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B
,I/SELinux ( 4686): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4686):  
I/ActivityManager(  740): Killing 3385:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 4686): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4686):  
I/SELinux ( 4686):  
,I/SELinux ( 4686): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4686): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4686): >>>>> Normal User
,E/dalvikvm( 4686): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 4686): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4686): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4686): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4686): Added TimaKesytore provider
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4686, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4686): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4698): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4698):  
I/ActivityManager(  740): Killing 3401:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,D/CustomFrequencyManagerService(  740): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 4698): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4698):  
I/SELinux ( 4698):  
,I/SELinux ( 4698): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4698): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4698): >>>>> Normal User
,E/dalvikvm( 4698): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4698): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4698): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4698): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4698): Added TimaKesytore provider
,I/SELinux ( 4710): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4710):  
,I/ActivityManager(  740): Killing 3419:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4710): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4710):  
I/SELinux ( 4710):  
,I/SELinux ( 4710): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4710): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4710): >>>>> Normal User
,E/dalvikvm( 4710): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4710): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4710): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4710): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4710): Added TimaKesytore provider
,I/ActivityManager(  740): Killing 3616:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/Finsky  ( 3500): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1785): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1785): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/dalvikvm( 4549): GC_CONCURRENT freed 4705K, 27% free 16240K/22204K, paused 1ms+5ms, total 46ms
,D/dalvikvm( 4549): WAIT_FOR_CONCURRENT_GC blocked 26ms
I/dalvikvm( 1785): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1785): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1785): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1785): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1785): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1785): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1785): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1785): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1785): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1785): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1785): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1785): Submit a task: k
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1785): Processing package: com.test.thalitest
,D/GassUtils( 1785): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1785): Found info for package com.test.thalitest in db.
,D/dalvikvm( 1295): GC_EXPLICIT freed 962K, 44% free 10764K/18936K, paused 2ms+4ms, total 38ms
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,D/dalvikvm(  740): GC_EXPLICIT freed 2387K, 59% free 23446K/56696K, paused 7ms+17ms, total 166ms
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
W/dalvikvm( 1785): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1785): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1785): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x000e
,W/dalvikvm( 1785): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1785): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1785): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1785): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1785): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 1785): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1785): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1785): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1785): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1785): cleanUpNonGplusAccounts done.
,D/dalvikvm( 4549): GC_FOR_ALLOC freed 5085K, 31% free 17225K/24876K, paused 36ms, total 38ms
,I/dalvikvm-heap( 4549): Grow heap (frag case) to 22.377MB for 2459024-byte allocation
,W/dalvikvm( 1785): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1785): Module APK com.google.android.play.games already loaded
,E/SMD     (  241): DCD ON
,D/dalvikvm( 1785): GC_CONCURRENT freed 1465K, 38% free 11759K/18936K, paused 5ms+4ms, total 36ms
,D/dalvikvm( 4549): GC_FOR_ALLOC freed 3734K, 35% free 17940K/27280K, paused 34ms, total 37ms
,D/dalvikvm( 4549): GC_FOR_ALLOC freed 1184K, 35% free 17849K/27280K, paused 30ms, total 30ms
,D/dalvikvm( 4549): GC_FOR_ALLOC freed 4477K, 38% free 19161K/30884K, paused 36ms, total 40ms
,I/Icing   ( 1785): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
W/jxcore-log( 4549): Initializing JXcore engine
,W/jxcore-log( 4549): JXcore engine is ready
,I/Icing   ( 1785): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,W/jxcore-log( 4549): Starting JXcore engine
,W/jxcore-log( 4549): Platform android
W/jxcore-log( 4549): 
,W/jxcore-log( 4549): Process ARCH arm
W/jxcore-log( 4549): 
,I/jxcore-log( 4549): JXcore Cordova bridge is ready!
I/jxcore-log( 4549): 
,W/jxcore-log( 4549): JXcore engine is started
,E/jxcore  ( 4549): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4549): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4549): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtils( 1065): isPcwEnable = null
I/ActivityManager(  740): Killing 3669:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,W/PluginManager( 4549): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  247): id=17 Removed NainActivit (7/11)
,I/SurfaceFlinger(  247): id=17 Removed NainActivit (-2/11)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  740): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  740): mDVFSHelper.acquire()
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1065): isPcwEnable = null
,D/SurfaceWidgetView( 1248): destroyHardwareResources():1130968048
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1248): onRestart, Launcher: 1119033064
D/Launcher( 1248): onStart, Launcher: 1119033064
,D/Launcher.HomeView( 1248): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1442): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1442): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  247): id=18 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=19 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/Launcher.HomeView( 1248): onStop
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  740): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  740): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  740): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  740): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  tag : ACTIVITY_RESUME_BOOSTER@9
,I/GAV2    ( 4605): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 320, Delta = 10
,E/SMD     (  241): DCD ON
,D/PackageManager(  740): [MSG] WRITE_PACKAGE_RESTRICTIONS
,V/AlarmManager(  740): waitForAlarm result :8
V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager(  740): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager(  740): <AppSync3 Whitelist>
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  740): (AppSync) ### 0 added ###
D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,I/HarmonyEASService(  740): Updating for all 1
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 3
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager(  740): waitForAlarm result :4
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:81, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,I/PowerManagerService(  740): [PWL] Off : 50s ago
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/dalvikvm( 3500): GC_CONCURRENT freed 1807K, 41% free 11203K/18936K, paused 3ms+4ms, total 42ms
,D/Finsky  ( 3500): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3500): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = -20
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/FactoryTest( 4098): Not factory mode
,D/FactoryTest( 4098): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4098): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4098): still no open session command from host, so toast
W/ContextImpl( 4098): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4098): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  740): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  740): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  740): mDVFSHelper.acquire()
,D/LockPatternUtils( 1065): isPcwEnable = null
,D/LockPatternUtils( 1065): isPcwEnable = null
,E/MTPRx   ( 4098): started activity for popup
,E/SettingsReceiverActivity( 4098): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtils( 1065): isPcwEnable = null
,I/SQLiteSecureOpenHelper( 2021): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2021): getDatabaseLocked(b,b,pwd)...
,D/SettingsReceiverActivity( 4098): dev.kiessupport is : TRUE
,E/SMD     (  241): DCD ON
,I/WindowManager(  740): Screenshot max retries 4 of Token{42f39c60 ActivityRecord{4330e238 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{43357500 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
,W/WindowManager(  740): Screenshot failure taking screenshot for (720x1280) to layer 21005
D/LockPatternUtils( 1065): isPcwEnable = null
,D/AmoledAdjustTimer(  740): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService(  740): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  740): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  740): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  pkgName : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:77, charge type:1, power sharing:false
,D/BatteryService(  740): stay LED for fully charged
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/CustomFrequencyManagerService(  740): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  tag : ACTIVITY_RESUME_BOOSTER@9
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 75s ago
,E/Watchdog(  740): !@Sync 4
,V/AlarmManager(  740): waitForAlarm result :4
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  740): forceRefresh() from cache miss
,D/NtpTrustedTime(  740): forceRefresh Fail.
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:71, charge type:1, power sharing:false
,D/BatteryService(  740): stay LED for fully charged
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 287, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:70, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:69, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 105s ago
,E/Watchdog(  740): !@Sync 5
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:68, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:71, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 6
,V/AlarmManager(  740): waitForAlarm result :4
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  740): forceRefresh() from cache miss
,D/NtpTrustedTime(  740): forceRefresh Fail.
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:69, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/VacuumService( 1217): Vacuum at: now=1453758275584 tag=VacuumService
,D/AmoledAdjustTimer(  740): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService(  740): [PWL] Off : 140s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:66, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:65, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 7
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:63, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:61, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:63, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 8
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:63, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:62, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:59, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 225s ago
,E/Watchdog(  740): !@Sync 9
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:60, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:57, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:61, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/TimaService(  740): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  740): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  740): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  740): initializing...
,I/TLC_TIMA_PKM_initialize(  740): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  740): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  740): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  740): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  740): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  740): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  740): max_message_size = 524416 = 0x80080,
,D/QSEECOMAPI: (  740): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  740): App is not loaded in QSEE
,D/QSEECOMAPI: (  740): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  740): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  740): Trustlet response is completed
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  740): !@Sync 10
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:57, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 275s ago
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :4
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 4849): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4849):  
D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:58, charge type:1, power sharing:false
D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 4849): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4849):  
I/SELinux ( 4849):  
,I/SELinux ( 4849): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4849): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 4849): >>>>> Normal User
,E/dalvikvm( 4849): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 4849): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4849): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4849): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4849): Added TimaKesytore provider
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4849, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  740): Killing 3737:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 11
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:55, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:56, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:55, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 12
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:56, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:52, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 330s ago
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  740): GC_CONCURRENT freed 3405K, 59% free 23440K/56664K, paused 19ms+41ms, total 430ms
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:51, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 13
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:52, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 14
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:52, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:48, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 390s ago
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:50, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 15
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:48, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:47, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  740): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:46, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  241): DCD ON
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 16
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:44, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:47, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 455s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:48, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 17
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:44, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:48, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 18
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:45, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:46, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:43, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  740): [PWL] Off : 525s ago
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 19
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:45, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:45, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:44, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  740): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  740): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  740): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 20
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:46, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:45, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:45, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 21
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:43, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:46, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  740): [PWL] Off : 600s ago
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:40, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 22
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:40, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:34, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:33, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  740): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  740): <AppSync3 Whitelist>
,V/AlarmManager(  740): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 23
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:35, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:41, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :4
,I/SensorManagerA(  740): getReportingMode :: sensor.mType = 5
D/LightsService(  740): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors (  740): LightSensor setDelay = 200000000
,D/Sensors (  740): LightSensor setSensorDelay = 200000000
,D/Sensors (  740): Light sensor flush: not enabled 0
,D/Sensors (  740): LightSensor enable = 1
,D/Sensors (  740): LightSensor enableSensor = 1
,D/SensorManager(  740): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:42, charge type:1, power sharing:false
,D/BatteryService(  740): stay LED for fully charged
,D/Finsky  ( 3500): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/Sensors (  740): LightSensor enable = 0
,D/Sensors (  740): LightSensor enableSensor = 0
,D/SensorManager(  740): unregisterListener ::   
D/LightsService(  740): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  740): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1785): Aggregate from 1453756645548 (log), 1453756645548 (data)
,I/System.out( 3500): Thread-336 calls detatch()
,W/Finsky  ( 3500): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3500): Thread-337 calls detatch()
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3500): Thread-336 calls detatch()
,W/Finsky  ( 3500): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,E/Watchdog(  740): !@Sync 24
,D/dalvikvm( 3500): GC_CONCURRENT freed 1910K, 41% free 11266K/18936K, paused 3ms+5ms, total 43ms
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3500): Thread-337 calls detatch()
,W/Finsky  ( 3500): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3500): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  740): waitForAlarm result :4
,D/Finsky  ( 3500): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WearableService( 1217): callingUid 10011, callindPid: 1217
,D/DeviceConnectionService( 1217): client connected with version: 8296000
,D/Finsky  ( 3500): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3500): [365] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3500): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3500): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  740): [PWL] Off : 680s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :4
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:39, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm(  740): GC_CONCURRENT freed 3521K, 59% free 23414K/56620K, paused 82ms+40ms, total 543ms
,D/Finsky  ( 3500): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3500): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:40, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 25
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:37, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:35, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 26
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:35, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:36, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:37, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  740): [PWL] Off : 765s ago
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 27
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:36, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:37, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,I/ClearcutLoggerApiImpl( 1295): disconnect managed GoogleApiClient
,E/Watchdog(  740): !@Sync 28
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:36, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:37, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:36, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 29
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:37, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:33, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  740): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  740): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  740): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:34, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  740): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  740): [PWL] Off : 855s ago
,I/PowerManagerService(  740): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  740): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  740): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=740, ws=null) (elapsedTime=3733)
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 30
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:35, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:32, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:34, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 31
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  241): DCD ON
,D/dalvikvm( 3500): GC_CONCURRENT freed 2691K, 45% free 10513K/18936K, paused 9ms+12ms, total 109ms
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:32, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:34, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:31, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 32
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:29, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:32, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  740): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 33
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  740): [PWL] Off : 950s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:31, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:30, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 34
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:31, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:30, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:31, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 35
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:28, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 36
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,I/PowerManagerService(  740): [PWL] Off : 1050s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:27, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:26, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 37
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:31, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:32, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:28, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 38
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:27, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:27, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:26, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 39
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:25, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:27, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/dalvikvm(  740): GC_CONCURRENT freed 3396K, 59% free 23393K/56396K, paused 21ms+39ms, total 406ms
,D/TimaService(  740): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  740): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  740): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService(  740): [PWL] Off : 1155s ago
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:25, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  740): !@Sync 40
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:28, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:29, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 41
,E/SMD     (  241): DCD ON
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1295): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:25, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:27, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:24, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  740): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 42
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:25, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:24, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  740): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  740): <AppSync3 Whitelist>
,V/AlarmManager(  740): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 43
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5115): 
D/AndroidRuntime( 5115): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5115): CheckJNI is OFF
D/AndroidRuntime( 5115): setted country_code = Poland
D/AndroidRuntime( 5115): setted countryiso_code = PL
D/AndroidRuntime( 5115): setted sales_code = XEO
D/AndroidRuntime( 5115): readGMSProperty: start
D/AndroidRuntime( 5115): readGMSProperty: already setted!!
D/AndroidRuntime( 5115): readGMSProperty: end
D/AndroidRuntime( 5115): addProductProperty: start
D/dalvikvm( 5115): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5115): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5115): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5115): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5115): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5115): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5115): failed to load memtrack module: -2
D/dalvikvm( 5115): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
E/SMD     (  241): DCD ON
D/AndroidRuntime( 5115): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  740): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  740): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  740): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  740): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  740): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  740): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  740): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  740): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  740): getApplicationUninstallationEnabled
D/ApplicationPolicy(  740): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  740): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  740): START PACKAGE DELETE: observer{1117964320}
D/PackageManager(  740): pkg{<packageName>}
D/PackageManager(  740): user{0}
D/PackageManager(  740): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  740): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  740): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  740): Killing 4549:com.test.thalitest/u0a179 (adj 9): stop com.test.thalitest
D/PackageManager(  740): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1785): GC_EXPLICIT freed 737K, 38% free 11872K/18936K, paused 3ms+5ms, total 48ms
D/dalvikvm( 2122): GC_EXPLICIT freed 1199K, 42% free 11063K/18936K, paused 4ms+5ms, total 45ms
D/AdaptiveEventManager( 1065): action=android.intent.action.PACKAGE_REMOVED
I/FPMS_FingerprintManagerService( 1084): onReceive: android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 1406): GC_EXPLICIT freed 4290K, 48% free 10027K/18936K, paused 2ms+4ms, total 53ms
W/GeofencerStateMachine( 1217): Ignoring removeGeofence because network location is disabled.
D/QuickConnect[1.1][2] ( 3111): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/PackageManager(  740): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "sms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5141): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5141):  
W/InputMethodInfo(  740): Duplicated subtype definition found: , voice
I/InputReader(  740): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm(  248): GC_EXPLICIT freed 43K, 50% free 9513K/18936K, paused 2ms+3ms, total 28ms
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "smsto"
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9513K/18936K, paused 2ms+3ms, total 20ms
I/SELinux ( 5141): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5141):  
I/SELinux ( 5141):  
I/SELinux ( 5141): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5141): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5141): >>>>> Normal User
E/dalvikvm( 5141): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "mms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SELinux ( 5141): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9513K/18936K, paused 2ms+3ms, total 19ms
D/TimaKeyStoreProvider( 5141): in addTimaSignatureService
D/TimaKeyStoreProvider( 5141): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5141): Added TimaKesytore provider
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "mmsto"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "sms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  740): Package has changed for user 0
D/EnterpriseDeviceManagerService(  740): Admin package name: com.google.android.gms
D/dalvikvm(  740): GC_EXPLICIT freed 2039K, 59% free 23428K/56396K, paused 6ms+14ms, total 233ms
D/dalvikvm(  740): WAIT_FOR_CONCURRENT_GC blocked 46ms
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "smsto"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "mms"
D/RCPManagerService(  740): PackageReceiver onReceive()
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "mmsto"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService(  740): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5141, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 5141): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5141): ELMEngine.ELMEngine( context ).
D/elm:14132( 5141): MDMBridge.setEnterpriseBridge()
D/elm:14132( 5141): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5141): ElmAgentService : onCreate()
D/elm:14132( 5141): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5141): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5141): MDMBridge.getInstance()
D/elm:14132( 5141): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 5141): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 5163): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5163):  
D/elm:14132( 5141): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 5141): ElmAgentService : onDestroy().
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5163): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5163):  
I/SELinux ( 5163):  
I/SELinux ( 5163): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5163): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5163): >>>>> Normal User
E/dalvikvm( 5163): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 5163): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5163): in addTimaSignatureService
D/TimaKeyStoreProvider( 5163): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5163): Added TimaKesytore provider
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(  740): GC_EXPLICIT freed 758K, 59% free 23432K/56396K, paused 6ms+21ms, total 234ms
D/PackageManager(  740): delete sourFile : 
D/BackupManagerService(  740): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  740): removePackageParticipantsLocked: uid=10179 #1
D/PackageManager(  740): delete native library directory: 
D/PackageManager(  740): return delete result to caller: 1117964320
D/PackageManager(  740): returnCode: 1
D/AndroidRuntime( 5115): Shutting down VM
D/dalvikvm( 5115): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+0ms, total 3ms
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "sms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "smsto"
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5163, uid=10021 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "mms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "mmsto"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PCWCLIENTTRACE_PushUtil( 4401): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4401): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4401): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4401): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5178): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5178):  
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/ActivityManager(  740): Killing 3714:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
I/CrashAnrDetector(  740): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  740): clearDefaults: com.test.thalitest
I/SELinux ( 5178): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5178):  
I/SELinux ( 5178):  
I/SELinux ( 5178): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5178): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5178): >>>>> Normal User
E/dalvikvm( 5178): >>>>> com.sec.spp.push:RemoteNotiProcess [ userId:0 | appId:10038 ]
E/SELinux ( 5178): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5178): in addTimaSignatureService
D/TimaKeyStoreProvider( 5178): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5178): Added TimaKesytore provider
E/SPPClientService( 5178): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5178): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 5178): PushLog.txt file is not deleted.
D/SPPClientService( 5178): PushLog.txt file is not deleted.
D/SPPClientService( 5178): ============PushLog. stop!
I/SA      ( 4082): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4082): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
I/ActivityManager(  740): Killing 3967:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
E/SharedPreferencesImpl( 3849): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
I/IcingCorporaProvider( 2122): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:22, charge type:1, power sharing:false
I/SELinux ( 5198): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5198):  
D/BatteryService(  740): stay LED for fully charged
D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  740): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/InputReader(  740): Processing first event
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/SELinux ( 5198): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5198):  
I/SELinux ( 5198):  
I/SELinux ( 5198): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
W/ApplicationsProvider( 1406): Could not fetch usage stats
W/ApplicationsProvider( 1406): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1406): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1406): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1406): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1406): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1406): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1406): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1406): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1406): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1406): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1406): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1406): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
