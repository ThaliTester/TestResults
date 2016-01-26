#### Test 5667282762e056f_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
W/System.err( 4392): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 4392): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 4392): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 4392): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 4392): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 4392): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 4392): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 4392): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 4392): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 4392): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:105)
W/System.err( 4392): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:89)
W/System.err( 4392): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 4392): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 4392): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 4392): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 4392): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4392): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4392): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 4392): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4392): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4392): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 4392): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 4392): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 4392): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 4392): 	at libcore.io.Posix.open(Native Method)
W/System.err( 4392): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 4392): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 4392): 	... 21 more
D/GalaxyFinderApplication( 4392): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 4392): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 4413): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4413):  
--------- beginning of /dev/log/system
I/ActivityManager(  802): Killing 3073:com.LocalFota/u0a110 (adj 15): empty #43
,I/SELinux ( 4413): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4413):  
I/SELinux ( 4413):  
I/SELinux ( 4413): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4413): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4413): >>>>> Normal User
E/dalvikvm( 4413): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 4413): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4413): in addTimaSignatureService
D/TimaKeyStoreProvider( 4413): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4413): Added TimaKesytore provider
W/ActivityManager(  802): Permission Denial: getCurrentUser() from pid=4413, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 4413): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/SELinux ( 4439): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4439):  
E/Device Type Shared Preferences( 4413): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 4413): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 4413): ContentProvider is not null
I/SELinux ( 4439): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4439):  
I/SELinux ( 4439):  
I/SELinux ( 4439): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4439): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4439): >>>>> Normal User
E/dalvikvm( 4439): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 4439): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4439): in addTimaSignatureService
D/TimaKeyStoreProvider( 4439): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4439): Added TimaKesytore provider
V/MediaPlayer( 4413): decode(61, 33979084, 48105)
V/MediaPlayerService(  252): decode(33, 33979084, 48105)
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
V/StagefrightPlayer(  252): setDataSource(33, 33979084, 48105)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac480, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb7bac480, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac480, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac480, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7bac480, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/AudioPlayer(  252): First fillBuffer call!!
W/ActivityManager(  802): Permission Denial: getCurrentUser() from pid=4439, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
D/AndroidRuntime( 4430): 
D/AndroidRuntime( 4430): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
D/AndroidRuntime( 4430): CheckJNI is OFF
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac480, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac480, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
D/AndroidRuntime( 4430): setted country_code = Poland
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac480, 8, 0, 0)
V/AudioCache(  252): ignored
D/AndroidRuntime( 4430): setted countryiso_code = PL
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/AndroidRuntime( 4430): setted sales_code = XEO
D/AndroidRuntime( 4430): readGMSProperty: start
D/AndroidRuntime( 4430): readGMSProperty: already setted!!
D/AndroidRuntime( 4430): readGMSProperty: end
D/AndroidRuntime( 4430): addProductProperty: start
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
V/MediaPlayer( 4413): decode(63, 33914984, 10421)
V/MediaPlayerService(  252): decode(33, 33914984, 10421)
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
V/StagefrightPlayer(  252): setDataSource(33, 33914984, 10421)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac0e0, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
D/dalvikvm( 4439): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4263bdf8, skipping init
I/SecureStorage( 4439): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4439): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
I/SecureStorage(  402): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4439
I/SecureStorage(  402): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4439): [INFO]: SPID(0x00000000)SS Daemon is running
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
D/dalvikvm( 4430): Trying to load lib libjavacore.so 0x0
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb7bac0e0, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac0e0, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac0e0, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
D/dalvikvm( 4430): Added shared lib libjavacore.so 0x0
D/AmoledAdjustTimer(  802): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
D/dalvikvm( 4430): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4430): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4430): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac0e0, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb7bac0e0, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac0e0, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac0e0, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/SecureStorage( 4439): [INFO]: SPID(0x00000000)Processing data
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/SecureStorage(  402): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4439
I/SecureStorage(  402): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
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
V/MediaPlayer( 4413): decode(64, 37457308, 34198)
V/MediaPlayerService(  252): decode(34, 37457308, 34198)
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
V/StagefrightPlayer(  252): setDataSource(34, 37457308, 34198)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb78a0, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb78a0, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb78a0, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb78a0, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb78a0, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb78a0, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb78a0, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb78a0, 8, 0, 0)
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
V/MediaPlayer( 4413): decode(65, 33862452, 7405)
V/MediaPlayerService(  252): decode(33, 33862452, 7405)
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
V/StagefrightPlayer(  252): setDataSource(33, 33862452, 7405)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb14b8, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb14b8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb14b8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb14b8, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb14b8, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb14b8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb14b8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb14b8, 8, 0, 0)
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
V/MediaPlayer( 4413): decode(66, 37547940, 5555)
V/MediaPlayerService(  252): decode(33, 37547940, 5555)
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
V/StagefrightPlayer(  252): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac4c8, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb7bac4c8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac4c8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac4c8, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7bac4c8, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb7bac4c8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac4c8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bac4c8, 8, 0, 0)
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
V/MediaPlayer( 4413): decode(67, 30367732, 5085)
V/MediaPlayerService(  252): decode(33, 30367732, 5085)
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
V/StagefrightPlayer(  252): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bbccf8, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb7bbccf8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bbccf8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bbccf8, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7bbccf8, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb7bbccf8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bbccf8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bbccf8, 8, 0, 0)
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
V/MediaPlayer( 4413): decode(68, 30372876, 21552)
V/MediaPlayerService(  252): decode(33, 30372876, 21552)
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
V/StagefrightPlayer(  252): setDataSource(33, 30372876, 21552)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bc0648, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
E/memtrack( 4430): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4430): failed to load memtrack module: -2
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
V/AudioCache(  252): notify(0xb7bc0648, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bc0648, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bc0648, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7bc0648, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
D/dalvikvm( 4430): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bc0648, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bc0648, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bc0648, 8, 0, 0)
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
V/MediaPlayer( 4413): decode(69, 37543652, 4230)
V/MediaPlayerService(  252): decode(33, 37543652, 4230)
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
V/StagefrightPlayer(  252): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb4ac8, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb4ac8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb4ac8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb4ac8, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb4ac8, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb4ac8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb4ac8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb4ac8, 8, 0, 0)
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
V/MediaPlayer( 4413): decode(70, 30337076, 9400)
V/MediaPlayerService(  252): decode(33, 30337076, 9400)
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
V/StagefrightPlayer(  252): setDataSource(33, 30337076, 9400)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bbbe88, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
D/AndroidRuntime( 4430): Calling main entry com.android.commands.am.Am
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
V/AudioCache(  252): notify(0xb7bbbe88, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bbbe88, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bbbe88, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7bbbe88, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/SELinux ( 4509): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4509):  
I/ActivityManager(  802): Killing 3097:com.sec.android.app.mt/1000 (adj 15): empty #43
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bbbe88, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bbbe88, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bbbe88, 8, 0, 0)
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
V/MediaPlayer( 4413): decode(71, 33925464, 44276)
V/MediaPlayerService(  252): decode(33, 33925464, 44276)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/ApplicationPolicy(  802): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
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
V/StagefrightPlayer(  252): setDataSource(33, 33925464, 44276)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/Aud,ioCache(  252): notify(0xb7bb78b8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
I/SELinux ( 4509): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4509):  
I/SELinux ( 4509):  
I/SELinux ( 4509): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
E/SELinux ( 4509): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4509): >>>>> Normal User
E/dalvikvm( 4509): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 4509): [DEBUG] seapp_context_lookup: seinfoCategory = platform
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
V/AudioCache(  252): notify(0xb7bb78b8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb78b8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb78b8, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
D/CustomFrequencyManagerService(  802): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 802  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  802): mDVFSHelper.acquire()
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
V/AudioCache(  252): notify(0xb7bb78b8, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/SELinux ( 4524): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4524):  
D/TimaKeyStoreProvider( 4509): in addTimaSignatureService
D/dalvikvm(  250): GC_EXPLICIT freed 45K, 51% free 9507K/19220K, paused 2ms+2ms, total 34ms
D/LockPatternUtils( 1068): isPcwEnable = null
D/TimaKeyStoreProvider( 4509): Cannot add TimaSignature Service, License check Failed
I/SELinux ( 4524): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4524):  
I/SELinux ( 4524):  
D/ActivityThread( 4509): Added TimaKesytore provider
I/SELinux ( 4524): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4524): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4524): >>>>> Normal User
E/dalvikvm( 4524): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 4524): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9507K/19220K, paused 2ms+3ms, total 23ms
D/AndroidRuntime( 4430): Shutting down VM
D/dalvikvm( 4430): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
D/TimaKeyStoreProvider( 4524): in addTimaSignatureService
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9507K/19220K, paused 1ms+3ms, total 22ms
D/TimaKeyStoreProvider( 4524): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4524): Added TimaKesytore provider
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb78b8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb78b8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb78b8, 8, 0, 0)
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
V/MediaPlayer( 4413): decode(72, 33885672, 29256)
V/MediaPlayerService(  252): decode(33, 33885672, 29256)
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
V/StagefrightPlayer(  252): setDataSource(33, 33885672, 29256)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb71c0, 8, 0, 0)
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
D/LockPatternUtils( 1068): isPcwEnable = null
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
I/SQLiteSecureOpenHelper( 2017): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2017): getDatabaseLocked(b,b,pwd)...
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/SurfaceFlinger(  249): id=14 Removed CatteryCove (8/12)
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb7bb71c0, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb71c0, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb71c0, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/SurfaceFlinger(  249): id=14 Removed CatteryCove (-2/12)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb71c0, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
D/SurfaceWidgetView( 1252): destroyHardwareResources():1126422672
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb71c0, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb71c0, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb71c0, 8, 0, 0)
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
V/MediaPlayer( 4413): decode(73, 37491572, 52024)
V/MediaPlayerService(  252): decode(33, 37491572, 52024)
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
V/StagefrightPlayer(  252): setDataSource(33, 37491572, 52024)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7baf4b0, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb7baf4b0, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7baf4b0, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7baf4b0, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7baf4b0, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
W/ActivityManager(  802): Permission Denial: getCurrentUser() from pid=4524, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  802): Permission Denial: getCurrentUser() from pid=4524, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 4524): Binding Chromium to the background looper Looper (main, tid 1) {42316950}
I/chromium( 4524): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4524): Initializing chromium process, renderers=0
,W/chromium( 4524): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7baf4b0, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7baf4b0, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7baf4b0, 8, 0, 0)
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
V/MediaPlayer( 4413): decode(74, 33969800, 9226)
V/MediaPlayerService(  252): decode(33, 33969800, 9226)
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
V/StagefrightPlayer(  252): setDataSource(33, 33969800, 9226)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb2fe0, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb2fe0, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb2fe0, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb2fe0, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb2fe0, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb2fe0, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb2fe0, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb2fe0, 8, 0, 0)
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
V/MediaPlayer( 4413): decode(75, 30402580, 4509)
V/MediaPlayerService(  252): decode(33, 30402580, 4509)
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
V/StagefrightPlayer(  252): setDataSource(33, 30402580, 4509)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb1858, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb1858, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb1858, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb1858, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7bb1858, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb1858, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb1858, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7bb1858, 8, 0, 0)
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
I/SELinux ( 4569): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4569):  
I/ActivityManager(  802): Killing 3155:com.sec.android.app.camera/u0a147 (adj 15): empty #43
I/SELinux ( 4569): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4569):  
I/SELinux ( 4569):  
I/SELinux ( 4569): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4569): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4569): >>>>> Normal User
E/dalvikvm( 4569): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 4569): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 4569): in addTimaSignatureService
D/TimaKeyStoreProvider( 4569): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4569): Added TimaKesytore provider
I/SA      ( 4569): [SSP] onCreated
I/SA      ( 4569): [TPM] There is no property file
I/SA      ( 4569): [SCU] isHaveSA() - false
I/SA      ( 4569): [TPM] getModelProperty : null
I/SA      ( 4569): [TPM] getCSCProperty : null
I/SA      ( 4569): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4569): [DM] init START
I/SA      ( 4569): [DM] This device is not a Vodafone
I/SA      ( 4569): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4569): support phone number id : false
I/SA      ( 4569): [DM] init END
I/SA      ( 4569): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4569): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  802): Killing 3255:com.android.email/u0a155 (adj 15): empty #43
D/Mms/PackageInstallReceiver( 3759): loadAuthorityPref(): sEnableAuthority = true
I/PowerManagerService(  802): [PWL] Off : 30s ago
I/IcingCorporaProvider( 2122): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 2812): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
E/SMD     (  243): DCD ON
I/SELinux ( 4587): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4587):  
I/SELinux ( 4587): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4587):  
I/SELinux ( 4587):  
I/SELinux ( 4587): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4587): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4587): >>>>> Normal User
E/dalvikvm( 4587): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 4587): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm( 2122): GC_CONCURRENT freed 6430K, 42% free 11257K/19220K, paused 4ms+5ms, total 39ms
D/dalvikvm( 2122): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/TimaKeyStoreProvider( 4587): in addTimaSignatureService
D/TimaKeyStoreProvider( 4587): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4587): Added TimaKesytore provider
V/AlarmManager(  802): waitForAlarm result :4
V/AlarmManager(  802): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/CapabilityManagerService New( 4587): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  802): Permission Denial: getCurrentUser() from pid=4587, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 4599): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4599):  
I/ActivityManager(  802): Killing 3251:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
D/BatteryService(  802): stay LED for fully charged
D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  802): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/SELinux ( 4599): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4599):  
I/SELinux ( 4599):  
I/SELinux ( 4599): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4599): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4599): >>>>> Normal User
E/dalvikvm( 4599): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 4599): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
D/SSRMv2:SIOP(  802): SIOP:: AP = 310, Delta = 0
D/TimaKeyStoreProvider( 4599): in addTimaSignatureService
D/TimaKeyStoreProvider( 4599): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4599): Added TimaKesytore provider
I/IcingCorporaProvider( 2122): UpdateCorporaTask done [took 255 ms] updated apps [took 255 ms] 
I/Adreno-EGL( 4524): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4524): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4524): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4524): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4524): Remote Branch: 
I/Adreno-EGL( 4524): Local Patches: 
I/Adreno-EGL( 4524): Reconstruct Branch: 
I/SurfaceFlinger(  249): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  249): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SecureStorage(  402): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  402): [INFO]: SPID(0x00000003)PID: 4439, TID: 4439
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1446): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1252): onTrimMemory. Level: 20
,I/SecureStorage( 4439): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4439): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4439): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4439): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4439): Open platform.db in secure mode
,I/dalvikvm( 4524): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4524): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4524): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4524): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4524): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4524): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4524): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4524): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4524): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4524): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4524): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4524): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4524): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4524): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4524): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4524): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4524): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4524): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4524): CordovaWebView is running on device made by: samsung
,W/ActivityManager(  802): Permission Denial: getCurrentUser() from pid=4599, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=404, NainActivit
I/SQLiteSecureOpenHelper( 4439): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4439): ...getDatabaseLocked(b,b,pwd)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 4524): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4524): Enabling debug mode 0
I/ActivityManager(  802): Killing 3277:com.sec.modem.settings/1000 (adj 15): empty #43
,D/OpenGLRenderer( 4524): GL error from OpenGLRenderer: 0x502
,E/OpenGLRenderer( 4524):   GL_INVALID_OPERATION
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  802): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 802  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  802): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  802): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 802  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/JsMessageQueue( 4524): Set native->JS mode to OnlineEventsBridgeMode
,W/GAV2    ( 4599): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 4637): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4637):  
,I/SELinux ( 4637): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4637):  
I/SELinux ( 4637):  
,I/SELinux ( 4637): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4637): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4637): >>>>> Normal User
,E/dalvikvm( 4637): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 4637): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4637): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4637): Cannot add TimaSignature Service, License check Failed
,D/dalvikvm( 4524): Trying to load lib /data/app-lib/com.test.thalitest-3/libjxcore.so 0x4263d700
,D/ActivityThread( 4637): Added TimaKesytore provider
,D/dalvikvm( 4524): Added shared lib /data/app-lib/com.test.thalitest-3/libjxcore.so 0x4263d700
,D/jxcore_app_log( 4524): JniHelper::setJavaVM(0x41739528), pthread_self() = 2033672992
,I/chromium( 4524): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PackageIntentReceiver( 4637): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4637): Not GearManger package! 
,I/SELinux ( 4652): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4652):  
,I/ActivityManager(  802): Killing 1334:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/SELinux ( 4652): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4652):  
I/SELinux ( 4652):  
,I/SELinux ( 4652): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4652): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4652): >>>>> Normal User
,E/dalvikvm( 4652): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 4652): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4652): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4652): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4652): Added TimaKesytore provider
,D/MagazineService Version( 4652): Magazine-Channel: 13
,W/GAV2    ( 4599): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  802): Killing 3295:tv.peel.smartremote/u0a163 (adj 15): empty #43
,D/MagazineService Version( 4652): Magazine-Provider: 13
,D/MagazineService Version( 4652): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 4652): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 4652): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  802): Permission Denial: getCurrentUser() from pid=4652, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,I/Icing   ( 1785): Indexing 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B from com.google.android.googlequicksearchbox
,I/MagazineService::MagazineService( 4652): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/SELinux ( 4666): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4666):  
,D/MagazineService::MagazineService( 4652): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  802): Killing 3320:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,I/SELinux ( 4666): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4666):  
I/SELinux ( 4666):  
,I/SELinux ( 4666): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4666): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4666): >>>>> Normal User
,E/dalvikvm( 4666): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 4666): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4666): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4666): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4666): Added TimaKesytore provider
D/dalvikvm( 4524): GC_CONCURRENT freed 4953K, 34% free 12734K/19220K, paused 2ms+3ms, total 32ms
D/dalvikvm( 4524): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 4524): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Icing   ( 1785): Indexing done 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B
,I/SELinux ( 4679): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4679):  
I/ActivityManager(  802): Killing 3383:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 4679): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4679):  
I/SELinux ( 4679):  
,I/SELinux ( 4679): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4679): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4679): >>>>> Normal User
,E/dalvikvm( 4679): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 4679): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4679): in addTimaSignatureService
,D/CustomFrequencyManagerService(  802): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 802  tag : ACTIVITY_RESUME_BOOSTER@9
D/TimaKeyStoreProvider( 4679): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4679): Added TimaKesytore provider
,W/ActivityManager(  802): Permission Denial: getCurrentUser() from pid=4679, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4679): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4691): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4691):  
I/ActivityManager(  802): Killing 3396:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,I/SELinux ( 4691): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4691):  
I/SELinux ( 4691):  
,I/SELinux ( 4691): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4691): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4691): >>>>> Normal User
,E/dalvikvm( 4691): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4691): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4691): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4691): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4691): Added TimaKesytore provider
,I/SELinux ( 4703): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4703):  
,I/ActivityManager(  802): Killing 3414:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4703): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4703):  
I/SELinux ( 4703):  
,I/SELinux ( 4703): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4703): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4703): >>>>> Normal User
,E/dalvikvm( 4703): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4703): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4703): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4703): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4703): Added TimaKesytore provider
,I/ActivityManager(  802): Killing 3604:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
D/dalvikvm( 4524): GC_CONCURRENT freed 4683K, 28% free 16226K/22460K, paused 2ms+4ms, total 45ms
D/dalvikvm( 4524): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm( 4524): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/Finsky  ( 3491): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1785): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1785): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/dalvikvm( 1785): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
,W/dalvikvm( 1785): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1785): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1785): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1785): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1785): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1785): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1785): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1785): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1785): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1785): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1785): Submit a task: k
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1785): Processing package: com.test.thalitest
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,D/GassUtils( 1785): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1785): Found info for package com.test.thalitest in db.
,D/dalvikvm( 1312): GC_EXPLICIT freed 837K, 45% free 10751K/19220K, paused 3ms+4ms, total 52ms
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/dalvikvm( 1785): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1785): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1785): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1785): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1785): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1785): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1785): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1785): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1785): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1785): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1785): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1785): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0006
,D/dalvikvm( 4524): GC_FOR_ALLOC freed 5114K, 32% free 17218K/25132K, paused 41ms, total 41ms
,I/dalvikvm-heap( 4524): Grow heap (frag case) to 22.655MB for 2459024-byte allocation
,I/PeopleDatabaseHelper( 1785): cleanUpNonGplusAccounts done.
,D/dalvikvm(  802): GC_EXPLICIT freed 2531K, 59% free 23405K/56996K, paused 7ms+16ms, total 155ms
,W/dalvikvm( 1785): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1785): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 4524): GC_FOR_ALLOC freed 3737K, 35% free 17930K/27536K, paused 35ms, total 35ms
,E/SMD     (  243): DCD ON
,D/dalvikvm( 4524): GC_FOR_ALLOC freed 1188K, 36% free 17840K/27536K, paused 30ms, total 30ms
,D/dalvikvm( 4524): GC_FOR_ALLOC freed 4470K, 39% free 19151K/31140K, paused 32ms, total 32ms
,W/jxcore-log( 4524): Initializing JXcore engine
,W/jxcore-log( 4524): JXcore engine is ready
,I/Icing   ( 1785): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1785): GC_CONCURRENT freed 1398K, 38% free 11938K/19220K, paused 4ms+5ms, total 52ms
,D/dalvikvm( 1785): WAIT_FOR_CONCURRENT_GC blocked 32ms
,W/jxcore-log( 4524): Starting JXcore engine
,I/Icing   ( 1785): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,W/jxcore-log( 4524): Platform android
W/jxcore-log( 4524): 
,W/jxcore-log( 4524): Process ARCH arm
W/jxcore-log( 4524): 
,I/jxcore-log( 4524): JXcore Cordova bridge is ready!
I/jxcore-log( 4524): 
,W/jxcore-log( 4524): JXcore engine is started
,E/jxcore  ( 4524): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4524): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4524): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtils( 1068): isPcwEnable = null
I/ActivityManager(  802): Killing 3648:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/SurfaceFlinger(  249): id=17 Removed NainActivit (7/11)
,I/SurfaceFlinger(  249): id=17 Removed NainActivit (-2/11)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  802): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 802  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  802): mDVFSHelper.acquire()
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/SurfaceWidgetView( 1252): destroyHardwareResources():1126422672
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/Launcher( 1252): onRestart, Launcher: 1114486832
D/Launcher( 1252): onStart, Launcher: 1114486832
,D/Launcher.HomeView( 1252): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1446): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1446): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  249): id=18 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  249): id=19 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/Launcher.HomeView( 1252): onStop
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  802): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 802  tag : ACTIVITY_RESUME_BOOSTER@5
,D/CustomFrequencyManagerService(  802): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 802  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  802): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  802): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 802  tag : ACTIVITY_RESUME_BOOSTER@9
,I/GAV2    ( 4599): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  802): stay LED for fully charged
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  802): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/HarmonyEASService(  802): Updating for all 1
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 310, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 3
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 284, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService(  802): [PWL] Off : 50s ago
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = -10
,E/SMD     (  243): DCD ON
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,V/AlarmManager(  802): waitForAlarm result :4
,V/AlarmManager(  802): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  802): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/FactoryTest( 4058): Not factory mode
,D/FactoryTest( 4058): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4058): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4058): still no open session command from host, so toast
W/ContextImpl( 4058): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4058): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  802): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  802): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 802  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  802): mDVFSHelper.acquire()
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/LockPatternUtils( 1068): isPcwEnable = null
,E/MTPRx   ( 4058): started activity for popup
,I/SQLiteSecureOpenHelper( 2017): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2017): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4058): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/SettingsReceiverActivity( 4058): dev.kiessupport is : TRUE
,D/dalvikvm( 3491): GC_CONCURRENT freed 6682K, 43% free 11006K/19220K, paused 4ms+4ms, total 58ms
,D/dalvikvm( 3491): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/Finsky  ( 3491): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3491): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/WindowManager(  802): Screenshot max retries 4 of Token{42c55080 ActivityRecord{42c54f00 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42bf6738 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
,D/LockPatternUtils( 1068): isPcwEnable = null
W/WindowManager(  802): Screenshot failure taking screenshot for (720x1280) to layer 21005
,E/SMD     (  243): DCD ON
,D/CustomFrequencyManagerService(  802): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 802  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  802): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  802): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 802  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  802): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 802  tag : ACTIVITY_RESUME_BOOSTER@9
,D/AmoledAdjustTimer(  802): prevTemp = 286, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  802): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  802): <AppSync3 Whitelist>
,V/AlarmManager(  802): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,I/PowerManagerService(  802): [PWL] Off : 75s ago
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 4
,V/AlarmManager(  802): waitForAlarm result :8
,D/NtpTrustedTime(  802): forceRefresh() from cache miss
,D/NtpTrustedTime(  802): forceRefresh Fail.
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 283, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,I/PowerManagerService(  802): [PWL] Off : 105s ago
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 5
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 6
,V/AlarmManager(  802): waitForAlarm result :4
,V/AlarmManager(  802): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  802): forceRefresh() from cache miss
,D/NtpTrustedTime(  802): forceRefresh Fail.
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,I/VacuumService( 1219): Vacuum at: now=1453831084049 tag=VacuumService
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService(  802): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 7
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService(  802): [PWL] Off : 180s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 8
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  802): [PWL] Off : 225s ago
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 9
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  802): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  802): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,D/TimaService(  802): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  802): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  802): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  802): initializing...
,I/TLC_TIMA_PKM_initialize(  802): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  802): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  802): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  802): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  802): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  802): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  802): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  802): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  802): App is not loaded in QSEE
,D/QSEECOMAPI: (  802): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  802): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  802): Trustlet response is completed
,E/SMD     (  243): DCD ON
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  802): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  802): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  802): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  802): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  802): !@Sync 10
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,E/SMD     (  243): DCD ON
D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  802): [PWL] Off : 275s ago
,E/SMD     (  243): DCD ON
,V/AlarmManager(  802): waitForAlarm result :4
,V/AlarmManager(  802): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
I/SELinux ( 4845): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4845):  
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,I/SELinux ( 4845): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4845):  
I/SELinux ( 4845):  
,I/SELinux ( 4845): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4845): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 4845): >>>>> Normal User
,E/dalvikvm( 4845): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 4845): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4845): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4845): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4845): Added TimaKesytore provider
,W/ActivityManager(  802): Permission Denial: getCurrentUser() from pid=4845, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  802): Killing 3688:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43,
,D/AmoledAdjustTimer(  802): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 11
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  240): write error (Broken pipe)
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 12
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,I/PowerManagerService(  802): [PWL] Off : 330s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 13
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/dalvikvm(  802): GC_CONCURRENT freed 3414K, 59% free 23373K/56996K, paused 21ms+42ms, total 466ms
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 14
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  802): [PWL] Off : 390s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 15
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 16
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  802): mCoverManager.getCoverState() : true
D/BatteryService(  802): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  802): [PWL] Off : 455s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 17
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 18
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  802): [PWL] Off : 525s ago
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 19
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/TimaService(  802): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  802): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  802): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  802): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  802): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  802): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  802): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 20
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  802): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 21
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  240): write error (Broken pipe)
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,V/AlarmManager(  802): waitForAlarm result :8
,I/SensorManagerA(  802): getReportingMode :: sensor.mType = 5
,D/Sensors (  802): LightSensor setDelay = 200000000
,D/Sensors (  802): LightSensor setSensorDelay = 200000000
,D/LightsService(  802): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  802): Light sensor flush: not enabled 0
D/Sensors (  802): LightSensor enable = 1
D/Sensors (  802): LightSensor enableSensor = 1
D/SensorManager(  802): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/PowerManagerService(  802): [PWL] Off : 600s ago
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/LightsService(  802): [SvcLED]  onSensorChanged::light value = 0
D/Sensors (  802): LightSensor enable = 0
D/Sensors (  802): LightSensor enableSensor = 0
,D/SensorManager(  802): unregisterListener ::   
D/LightsService(  802): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 269, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 22
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 23
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  802): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  802): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
V/AlarmManager(  802): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 24
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,I/PowerManagerService(  802): [PWL] Off : 680s ago
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 25
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 26
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  802): [PWL] Off : 765s ago
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 27
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 28
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/dalvikvm(  802): GC_CONCURRENT freed 3401K, 59% free 23342K/56920K, paused 20ms+38ms, total 412ms
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 29
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/TimaService(  802): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  802): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  802): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,I/PowerManagerService(  802): [PWL] Off : 855s ago
,I/PowerManagerService(  802): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  802): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  802): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=802, ws=null) (elapsedTime=3666)
,I/TLC_TIMA_PKM_measure_kernel(  802): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  802): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  802): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  802): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 30
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/SMD     (  243): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 31
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 268, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 32
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 33
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,I/PowerManagerService(  802): [PWL] Off : 950s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 34
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 35
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 36
,E/SMD     (  243): DCD ON
,W/ProcessCpuTracker(  802): Skipping unknown process pid 5025
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,I/PowerManagerService(  802): [PWL] Off : 1050s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/SMD     (  243): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 37
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 38
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 39
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/TimaService(  802): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  802): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  802): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  802): [PWL] Off : 1155s ago
,I/PowerManagerService(  802): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  802): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  802): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=802, ws=null) (elapsedTime=3674)
,I/TLC_TIMA_PKM_measure_kernel(  802): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  802): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  802): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  802): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 40
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 41
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  802): waitForAlarm result :8
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,I/SensorManagerA(  802): getReportingMode :: sensor.mType = 5
,D/Sensors (  802): LightSensor setDelay = 200000000
,D/Sensors (  802): LightSensor setSensorDelay = 200000000
,D/Sensors (  802): Light sensor flush: not enabled 0
,D/LightsService(  802): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  802): LightSensor enable = 1
D/Sensors (  802): LightSensor enableSensor = 1
D/SensorManager(  802): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  802): LightSensor enable = 0
,D/Sensors (  802): LightSensor enableSensor = 0
,D/SensorManager(  802): unregisterListener ::   
D/LightsService(  802): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  802): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  802): waitForAlarm result :8
,V/AlarmManager(  802): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  802): !@Sync 42
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/BatteryService(  802): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/SMD     (  243): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  802): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  802): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  802): stay LED for fully charged
,D/UiModeManager(  802): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  802): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  802): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5070): 
D/AndroidRuntime( 5070): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5070): CheckJNI is OFF
D/AndroidRuntime( 5070): setted country_code = Poland
D/AndroidRuntime( 5070): setted countryiso_code = PL
D/AndroidRuntime( 5070): setted sales_code = XEO
D/AndroidRuntime( 5070): readGMSProperty: start
D/AndroidRuntime( 5070): readGMSProperty: already setted!!
D/AndroidRuntime( 5070): readGMSProperty: end
D/AndroidRuntime( 5070): addProductProperty: start
D/dalvikvm( 5070): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5070): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5070): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5070): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5070): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5070): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5070): failed to load memtrack module: -2
D/dalvikvm( 5070): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5070): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  802): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  802): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  802): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  802): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  802): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  802): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  802): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  802): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  802): getApplicationUninstallationEnabled
D/ApplicationPolicy(  802): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  802): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  802): START PACKAGE DELETE: observer{1124004272}
D/PackageManager(  802): pkg{<packageName>}
D/PackageManager(  802): user{0}
D/PackageManager(  802): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  802): [MSG] DELETE_PACKAGE_AS_USER
D/dalvikvm(  802): GC_CONCURRENT freed 3361K, 59% free 23362K/56920K, paused 6ms+13ms, total 146ms
D/PackageManager(  802): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  802): Killing 4524:com.test.thalitest/u0a179 (adj 9): stop com.test.thalitest
D/PackageManager(  802): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1785): GC_EXPLICIT freed 561K, 40% free 11694K/19220K, paused 3ms+4ms, total 38ms
D/dalvikvm( 2122): GC_EXPLICIT freed 676K, 43% free 10993K/19220K, paused 2ms+4ms, total 37ms
D/PackageManager(  802): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 1087): onReceive: android.intent.action.PACKAGE_REMOVED
D/AdaptiveEventManager( 1068): action=android.intent.action.PACKAGE_REMOVED
I/InputReader(  802): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  802):   Action: "android.intent.action.SENDTO"
I/PackageManager(  802):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  802):   Scheme: "sms"
I/PackageManager(  802): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/QuickConnect[1.1][2] ( 3113): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/RCPManagerService(  802): PackageReceiver onReceive()
D/dalvikvm( 1405): GC_EXPLICIT freed 4289K, 48% free 10019K/19220K, paused 3ms+4ms, total 73ms
W/GeofencerStateMachine( 1219): Ignoring removeGeofence because network location is disabled.
I/HarmonyEASService(  802): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SELinux ( 5091): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5091):  
I/PackageManager(  802):   Action: "android.intent.action.SENDTO"
I/PackageManager(  802):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  802):   Scheme: "smsto"
I/PackageManager(  802): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/InputMethodInfo(  802): Duplicated subtype definition found: , voice
I/PackageManager(  802):   Action: "android.intent.action.SENDTO"
I/PackageManager(  802):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  802):   Scheme: "mms"
D/dalvikvm(  250): GC_EXPLICIT freed 43K, 51% free 9507K/19220K, paused 2ms+3ms, total 33ms
I/PackageManager(  802): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5091): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5091):  
I/SELinux ( 5091):  
I/SELinux ( 5091): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5091): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5091): >>>>> Normal User
E/dalvikvm( 5091): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 5091): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9507K/19220K, paused 2ms+3ms, total 21ms
I/PackageManager(  802):   Action: "android.intent.action.SENDTO"
I/PackageManager(  802):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  802):   Scheme: "mmsto"
D/TimaKeyStoreProvider( 5091): in addTimaSignatureService
I/PackageManager(  802): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 5091): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5091): Added TimaKesytore provider
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9507K/19220K, paused 2ms+3ms, total 22ms
I/PackageManager(  802):   Action: "android.intent.action.SENDTO"
I/PackageManager(  802):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  802):   Scheme: "sms"
I/PackageManager(  802): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  802):   Action: "android.intent.action.SENDTO"
I/PackageManager(  802):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  802):   Scheme: "smsto"
I/PackageManager(  802): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  802):   Action: "android.intent.action.SENDTO"
I/PackageManager(  802):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  802):   Scheme: "mms"
I/PackageManager(  802): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  802): Package has changed for user 0
D/EnterpriseDeviceManagerService(  802): Admin package name: com.google.android.gms
I/PackageManager(  802):   Action: "android.intent.action.SENDTO"
I/PackageManager(  802):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  802):   Scheme: "mmsto"
I/PackageManager(  802): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  802): Permission Denial: getCurrentUser() from pid=5091, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 5091): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5091): ELMEngine.ELMEngine( context ).
D/elm:14132( 5091): MDMBridge.setEnterpriseBridge()
D/elm:14132( 5091): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5091): ElmAgentService : onCreate()
D/elm:14132( 5091): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5091): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5091): MDMBridge.getInstance()
D/elm:14132( 5091): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 5091): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService(  802): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/SELinux ( 5110): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5110):  
D/elm:14132( 5091): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
V/BackupManagerService(  802): removePackageParticipantsLocked: uid=10179 #1
D/elm:14132( 5091): ElmAgentService : onDestroy().
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SMD     (  243): DCD ON
I/SELinux ( 5110): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5110):  
I/SELinux ( 5110):  
I/SELinux ( 5110): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/dalvikvm(  802): GC_EXPLICIT freed 1769K, 59% free 23570K/56920K, paused 6ms+17ms, total 342ms
E/SELinux ( 5110): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5110): >>>>> Normal User
E/dalvikvm( 5110): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux ( 5110): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager(  802): delete sourFile : 
D/PackageManager(  802): delete native library directory: 
D/PackageManager(  802): return delete result to caller: 1124004272
D/AndroidRuntime( 5070): Shutting down VM
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  802): returnCode: 1
D/TimaKeyStoreProvider( 5110): in addTimaSignatureService
D/dalvikvm( 5070): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 5110): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5110): Added TimaKesytore provider
I/PackageManager(  802):   Action: "android.intent.action.SENDTO"
I/PackageManager(  802):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  802):   Scheme: "sms"
I/PackageManager(  802): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  802):   Action: "android.intent.action.SENDTO"
I/PackageManager(  802):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  802):   Scheme: "smsto"
I/PackageManager(  802): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  802):   Action: "android.intent.action.SENDTO"
I/PackageManager(  802):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  802):   Scheme: "mms"
I/PackageManager(  802): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  802): Permission Denial: getCurrentUser() from pid=5110, uid=10021 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  802):   Action: "android.intent.action.SENDTO"
I/PackageManager(  802):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  802):   Scheme: "mmsto"
I/PackageManager(  802): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PCWCLIENTTRACE_PushUtil( 4380): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4380): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4380): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4380): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SA      ( 4569): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4569): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
I/ActivityManager(  802): Killing 3958:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/IcingCorporaProvider( 2122): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  802): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 5133): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5133):  
I/CrashAnrDetector(  802): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  802): clearDefaults: com.test.thalitest
E/SQLiteLog( 2122): (10) unixWrite() File Descriptor : 64 gets errno : 9
E/SQLiteLog( 2122): (778) statement aborts at 33: [DELETE FROM applications WHERE uri=?] 
E/SQLiteLog( 2122): (10) unixWrite() File Descriptor : 64 gets errno : 9
W/AppWidgetServiceImpl(  802): Failed to write state: java.io.IOException: write failed: EBADF (Bad file number)
E/SQLiteLog( 2122): (1) statement aborts at 2: [ROLLBACK;] cannot rollback - no transaction is active
W/dalvikvm( 2122): threadid=15: thread exiting with uncaught exception (group=0x41848da0)
W/AppWidgetServiceImpl(  802): Failed to save state, restoring backup.
E/AndroidRuntime( 2122): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2122): Process: com.google.android.googlequicksearchbox:search, PID: 2122
E/AndroidRuntime( 2122): android.database.sqlite.SQLiteException: cannot rollback - no transaction is active (code 1)
E/AndroidRuntime( 2122): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2122): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 2122): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:439)
E/AndroidRuntime( 2122): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 2122): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:524)
E/AndroidRuntime( 2122): 	at cid.d(PG:192)
E/AndroidRuntime( 2122): 	at clo.g(PG:594)
E/AndroidRuntime( 2122): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2122): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 2122): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 2122): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2122): 	at clr.tL(PG:827)
E/AndroidRuntime( 2122): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2122): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2122): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2122): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2122): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2122): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 2122): Sending signal. PID: 2122 SIG: 9
I/SELinux ( 5133): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5133):  
I/SELinux ( 5133):  
I/SELinux ( 5133): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5133): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5133): >>>>> Normal User
E/dalvikvm( 5133): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 5133): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/DropBoxManagerService(  802): Can't write: system_app_crash
E/DropBoxManagerService(  802): java.io.FileNotFoundException: /data/system/dropbox/drop211.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  802): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  802): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  802): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  802): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService(  802): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  802): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12552)
E/DropBoxManagerService(  802): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  802): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  802): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  802): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  802): 	... 5 more
I/ActivityManager(  802): Process com.google.android.googlequicksearchbox:search (pid 2122) (adj 5) has died.
D/TimaKeyStoreProvider( 5133): in addTimaSignatureService
D/TimaKeyStoreProvider( 5133): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5133): Added TimaKesytore provider
D/InputReader(  802): Processing first event

```
