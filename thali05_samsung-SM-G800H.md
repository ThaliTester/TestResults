#### Test 50650278ec2c976_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
W/System.err( 4506): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 4506): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 4506): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 4506): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 4506): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 4506): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 4506): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 4506): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 4506): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 4506): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:105)
W/System.err( 4506): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:89)
W/System.err( 4506): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 4506): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 4506): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 4506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 4506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4506): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4506): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 4506): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4506): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 4506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 4506): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 4506): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 4506): 	at libcore.io.Posix.open(Native Method)
W/System.err( 4506): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 4506): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 4506): 	... 21 more
D/GalaxyFinderApplication( 4506): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 4506): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 4527): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4527):  
--------- beginning of /dev/log/system
I/ActivityManager(  738): Killing 3106:com.LocalFota/u0a110 (adj 15): empty #43
I/SELinux ( 4527): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4527):  
I/SELinux ( 4527):  
I/SELinux ( 4527): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4527): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4527): >>>>> Normal User
E/dalvikvm( 4527): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 4527): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4527): in addTimaSignatureService
D/TimaKeyStoreProvider( 4527): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4527): Added TimaKesytore provider
D/CustomFrequencyManagerService(  738): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  tag : ACTIVITY_RESUME_BOOSTER@9
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=4527, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 4527): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/SELinux ( 4551): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4551):  
E/Device Type Shared Preferences( 4527): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 4527): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 4527): ContentProvider is not null
I/SELinux ( 4551): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4551):  
I/SELinux ( 4551):  
I/SELinux ( 4551): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4551): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4551): >>>>> Normal User
E/dalvikvm( 4551): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 4551): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4551): in addTimaSignatureService
D/TimaKeyStoreProvider( 4551): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4551): Added TimaKesytore provider
V/MediaPlayer( 4527): decode(61, 33979084, 48105)
V/MediaPlayerService(  243): decode(33, 33979084, 48105)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 33979084, 48105)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d8c58, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
D/AndroidRuntime( 4531): 
D/AndroidRuntime( 4531): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/AndroidRuntime( 4531): CheckJNI is OFF
D/AndroidRuntime( 4531): setted country_code = Poland
D/AndroidRuntime( 4531): setted countryiso_code = PL
D/AndroidRuntime( 4531): setted sales_code = XEO
D/AndroidRuntime( 4531): readGMSProperty: start
D/AndroidRuntime( 4531): readGMSProperty: already setted!!
D/AndroidRuntime( 4531): readGMSProperty: end
D/AndroidRuntime( 4531): addProductProperty: start
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70d8c58, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d8c58, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d8c58, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  243): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d8c58, 6, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
I/AudioPlayer(  243): First fillBuffer call!!
D/dalvikvm( 4531): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4531): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4531): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4531): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4531): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=4551, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d8c58, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d8c58, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d8c58, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( 4527): decode(63, 33914984, 10421)
V/MediaPlayerService(  243): decode(33, 33914984, 10421)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 33914984, 10421)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cd870, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
D/dalvikvm( 4551): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42610ad0, skipping init
I/SecureStorage( 4551): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4551): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/SecureStorage(  285): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4551
I/SecureStorage(  285): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4551): [INFO]: SPID(0x00000000)SS Daemon is running
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70cd870, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cd870, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cd870, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  243): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cd870, 6, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
I/SecureStorage( 4551): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  285): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4551
I/SecureStorage(  285): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cd870, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cd870, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cd870, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( 4527): decode(64, 37457308, 34198)
V/MediaPlayerService(  243): decode(33, 37457308, 34198)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 37457308, 34198)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cfd10, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70cfd10, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cfd10, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cfd10, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  243): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cfd10, 6, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cfd10, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cfd10, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70cfd10, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( 4527): decode(65, 33862452, 7405)
V/MediaPlayerService(  243): decode(33, 33862452, 7405)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 33862452, 7405)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e8438, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
E/memtrack( 4531): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4531): failed to load memtrack module: -2
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70e8438, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e8438, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e8438, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  243): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e8438, 6, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
I/AudioPlayer(  243): First fillBuffer call!!
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e8438, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e8438, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e8438, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( 4527): decode(66, 37547940, 5555)
V/MediaPlayerService(  243): decode(33, 37547940, 5555)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
D/dalvikvm( 4531): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  243): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 6, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( 4527): decode(67, 30367732, 5085)
V/MediaPlayerService(  243): decode(33, 30367732, 5085)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d37c8, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70d37c8, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d37c8, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d37c8, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  243): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d37c8, 6, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
I/AudioPlayer(  243): First fillBuffer call!!
V/MediaPlayerService(  243): wait for playback complete
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d37c8, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d37c8, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d37c8, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( 4527): decode(68, 30372876, 21552)
V/MediaPlayerService(  243): decode(33, 30372876, 21552)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 30372876, 21552)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d2878, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70d2878, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d2878, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d2878, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
D/AndroidRuntime( 4531): Calling main entry com.android.commands.am.Am
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  243): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d2878, 6, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d2878, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d2878, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70d2878, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( 4527): decode(69, 37543652, 4230)
V/MediaPlayerService(  243): decode(33, 37543652, 4230)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70da178, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70da178, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70da178, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70da178, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
V/ApplicationPolicy(  738): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  243): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70da178, 6, 0, 0)
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70da178, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70da178, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70da178, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( 4527): decode(70, 30337076, 9400)
V/MediaPlayerService(  243): decode(33, 30337076, 9400)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 30337076, 9400)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
D/CustomFrequencyManagerService(  738): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  738): mDVFSHelper.acquire()
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  243): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 6, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
I/SELinux ( 4619): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4619):  
D/LockPatternUtils( 1067): isPcwEnable = null
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
D/AndroidRuntime( 4531): Shutting down VM
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ccd10, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
D/dalvikvm( 4531): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( ,4527): decode(71, 33925464, 44276)
V/MediaPlayerService(  243): decode(33, 33925464, 44276)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 33925464, 44276)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ce4f8, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
I/SELinux ( 4623): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4623):  
I/ActivityManager(  738): Killing 3181:com.sec.android.app.camera/u0a147 (adj 15): empty #43
I/SELinux ( 4619): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4619):  
I/SELinux ( 4619):  
I/SELinux ( 4619): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4619): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4619): >>>>> Normal User
E/dalvikvm( 4619): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 4619): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/FileSource(  243): [Read time] time (15190) us > 10000 us, request_size (27), read_size (27)
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/dalvikvm(  240): GC_EXPLICIT freed 44K, 51% free 9506K/19040K, paused 2ms+3ms, total 35ms
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70ce4f8, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ce4f8, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ce4f8, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
D/dalvikvm(  240): GC_EXPLICIT freed <1K, 51% free 9506K/19040K, paused 2ms+2ms, total 22ms
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/SELinux ( 4623): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4623):  
I/SELinux ( 4623):  
I/SELinux ( 4623): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  243): open(44100, 2, 0x0, 1, 4)
E/SELinux ( 4623): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ce4f8, 6, 0, 0)
V/AudioCache(  243): ignored
E/dalvikvm( 4623): >>>>> Normal User
E/dalvikvm( 4623): >>>>> com.policydm [ userId:0 | appId:1000 ]
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
E/SELinux ( 4623): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AudioPlayer(  243): First fillBuffer call!!
D/dalvikvm(  240): GC_EXPLICIT freed <1K, 51% free 9506K/19040K, paused 2ms+3ms, total 22ms
D/TimaKeyStoreProvider( 4623): in addTimaSignatureService
D/TimaKeyStoreProvider( 4619): in addTimaSignatureService
D/TimaKeyStoreProvider( 4623): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4623): Added TimaKesytore provider
D/TimaKeyStoreProvider( 4619): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4619): Added TimaKesytore provider
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget visibility changed visibility = false on instance = 1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ce4f8, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ce4f8, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): addBatteryData
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70ce4f8, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
D/LockPatternUtils( 1067): isPcwEnable = null
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( 4527): decode(72, 33885672, 29256)
V/MediaPlayerService(  243): decode(33, 33885672, 29256)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 33885672, 29256)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70db8f8, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
I/SurfaceFlinger(  239): id=14 Removed CatteryCove (8/13)
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
I/SurfaceFlinger(  239): id=14 Removed CatteryCove (-2/13)
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
I/SecMediaClock(  243): SecMediaClock constructor
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/SQLiteSecureOpenHelper( 2025): getWritableDatabase(pwd)
D/SurfaceWidgetView( 1262): destroyHardwareResources():1126244200
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70db8f8, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70db8f8, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70db8f8, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  243): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70db8f8, 6, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70db8f8, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70db8f8, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70db8f8, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
,I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( 4527): decode(73, 37491572, 52024)
V/MediaPlayerService(  243): decode(33, 37491572, 52024)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 37491572, 52024)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e0c90, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
I/SQLiteSecureOpenHelper( 2025): getDatabaseLocked(b,b,pwd)...
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70e0c90, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e0c90, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e0c90, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  243): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e0c90, 6, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
I/AudioPlayer(  243): First fillBuffer call!!
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=4619, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=4619, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 4619): Binding Chromium to the background looper Looper (main, tid 1) {422ea3e8}
I/chromium( 4619): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4619): Initializing chromium process, renderers=0
W/chromium( 4619): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e0c90, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e0c90, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e0c90, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( 4527): decode(74, 33969800, 9226)
V/MediaPlayerService(  243): decode(33, 33969800, 9226)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 33969800, 9226)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e5fd8, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70e5fd8, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e5fd8, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e5fd8, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  243): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e5fd8, 6, 0, 0)
I/AudioPlayer(  243): First fillBuffer call!!
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e5fd8, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e5fd8, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e5fd8, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/MediaPlayer( 4527): decode(75, 30402580, 4509)
V/MediaPlayerService(  243): decode(33, 30402580, 4509)
V/MediaPlayerService(  243): player type = 3
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): constructor
V/AwesomePlayer(  243): setDefault
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): StagefrightPlayer
V/AwesomePlayer(  243): setListener
V/StagefrightPlayer(  243): initCheck
V/AwesomePlayer(  243): setAudioSink
V/StagefrightPlayer(  243): setDataSource(33, 30402580, 4509)
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e6098, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  243): mBitrate = -1 bits/sec
V/AwesomePlayer(  243): current audio track index (0) is added to vector
V/AwesomePlayer(  243): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  243): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  243): prepare
V/AwesomePlayer(  243): prepareAsync
V/MediaPlayerService(  243): wait for prepare
V/AwesomePlayer(  243): onPrepareAsyncEvent
I/SecMediaClock(  243): SecMediaClock constructor
I/SecMediaClock(  243): reset
V/AwesomePlayer(  243): initAudioDecoder
V/AwesomePlayer(  243): checkOffloadExceptions is true
I/OMXCodec(  243): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  243): mDispatchers.add
I/OMXCodec(  243): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  243): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  243): finishAsyncPrepare_l
V/AwesomePlayer(  243): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  243): notify(0xb70e6098, 200, 973, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e6098, 5, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e6098, 1, 0, 0)
V/AudioCache(  243): prepared
V/AudioCache(  243): wait - success
V/MediaPlayerService(  243): start
V/StagefrightPlayer(  243): start
V/AwesomePlayer(  243): play
V/AwesomePlayer(  243): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  243): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  243): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  243): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  243):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  243): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  243): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e6098, 6, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): addBatteryData
V/MediaPlayerService(  243): wait for playback complete
I/AudioPlayer(  243): First fillBuffer call!!
V/AwesomePlayer(  243): postAudioEOS delayUs (0)
V/AwesomePlayer(  243): onCheckAudioStatus
V/AwesomePlayer(  243): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  243): onStreamDone
V/AwesomePlayer(  243): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  243): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e6098, 2, 0, 0)
V/AudioCache(  243): playback complete - thread will wake up later
V/AwesomePlayer(  243): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e6098, 7, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  243): addBatteryData
V/AudioCache(  243): wait - success
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  243): notify(0xb70e6098, 8, 0, 0)
V/AudioCache(  243): ignored
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  243): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  243): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  243): instance freeNode
I/AudioPlayer(  243): reset out
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  243): SecMediaClock destructor
V/AwesomePlayer(  243): mSecMediaClock clear
V/StagefrightPlayer(  243): ~StagefrightPlayer
V/StagefrightPlayer(  243): reset
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
V/AwesomePlayer(  243): destructor
V/AwesomePlayer(  243): reset_l()
V/AwesomePlayer(  243): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  243): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  243): mAudioTrackVector clear
V/AwesomePlayer(  243): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  243): mSecMediaClock clear
D/CustomFrequencyManagerService(  738): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  738): mDVFSHelper.release()
D/CustomFrequencyManagerService(  738): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SELinux ( 4679): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4679):  
I/ActivityManager(  738): Killing 3290:com.android.email/u0a155 (adj 15): empty #43
I/SELinux ( 4679): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4679):  
I/SELinux ( 4679):  
I/SELinux ( 4679): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4679): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4679): >>>>> Normal User
E/dalvikvm( 4679): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 4679): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 4679): in addTimaSignatureService
D/TimaKeyStoreProvider( 4679): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4679): Added TimaKesytore provider
I/SA      ( 4679): [SSP] onCreated
I/SA      ( 4679): [TPM] There is no property file
I/SA      ( 4679): [SCU] isHaveSA() - false
I/SA      ( 4679): [TPM] getModelProperty : null
I/SA      ( 4679): [TPM] getCSCProperty : null
I/SA      ( 4679): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4679): [DM] init START
I/SA      ( 4679): [DM] This device is not a Vodafone
I/SA      ( 4679): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4679): support phone number id : false
I/SA      ( 4679): [DM] init END
I/SA      ( 4679): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4679): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  738): Killing 3286:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
D/Mms/PackageInstallReceiver( 3788): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2118): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 2834): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 4698): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4698):  
I/SELinux ( 4698): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4698):  
I/SELinux ( 4698):  
I/SELinux ( 4698): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4698): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4698): >>>>> Normal User
E/dalvikvm( 4698): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 4698): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 4698): in addTimaSignatureService
I/IcingCorporaProvider( 2118): UpdateCorporaTask done [took 103 ms] updated apps [took 103 ms] 
D/TimaKeyStoreProvider( 4698): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4698): Added TimaKesytore provider
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=4698, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CapabilityManagerService New( 4698): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 4710): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4710):  
I/ActivityManager(  738): Killing 1338:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
D/AmoledAdjustTimer(  738): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
I/SELinux ( 4710): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4710):  
I/SELinux ( 4710):  
I/SELinux ( 4710): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4710): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4710): >>>>> Normal User
E/dalvikvm( 4710): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 4710): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 4710): in addTimaSignatureService
D/TimaKeyStoreProvider( 4710): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4710): Added TimaKesytore provider
I/Adreno-EGL( 4619): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4619): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4619): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4619): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4619): Remote Branch: 
I/Adreno-EGL( 4619): Local Patches: 
I/Adreno-EGL( 4619): Reconstruct Branch: 
I/SurfaceFlinger(  239): id=17 Removed TettingsRec (8/12)
I/SurfaceFlinger(  239): id=17 Removed TettingsRec (-2/12)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/SecureStorage(  285): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  285): [INFO]: SPID(0x00000003)PID: 4551, TID: 4551
I/SurfaceFlinger(  239): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  239): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/Launcher( 1262): onTrimMemory. Level: 20
,I/SecureStorage( 4551): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4551): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SQLiteSecureOpenHelper( 4551): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4551): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4551): Open platform.db in secure mode
,I/dalvikvm( 4619): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4619): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4619): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4619): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4619): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4619): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4619): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4619): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4619): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4619): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4619): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4619): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4619): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4619): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4619): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4619): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4619): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4619): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4619): CordovaWebView is running on device made by: samsung
,I/SQLiteSecureOpenHelper( 4551): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4551): ...getDatabaseLocked(b,b,pwd)
,I/SurfaceFlinger(  239): id=18 createSurf (1x1),1 flag=404, NainActivit
I/ActivityManager(  738): Killing 3314:com.sec.modem.settings/1000 (adj 15): empty #43
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 4619): EGLImpl-HWUI Protected EGL context created
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=4710, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
D/OpenGLRenderer( 4619): Enabling debug mode 0
D/OpenGLRenderer( 4619): GL error from OpenGLRenderer: 0x502
,E/OpenGLRenderer( 4619):   GL_INVALID_OPERATION
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  738): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  tag : ACTIVITY_RESUME_BOOSTER@9
,D/JsMessageQueue( 4619): Set native->JS mode to OnlineEventsBridgeMode
,I/SELinux ( 4744): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4744):  
,D/dalvikvm( 4619): Trying to load lib /data/app-lib/com.test.thalitest-39/libjxcore.so 0x42611158
,W/GAV2    ( 4710): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 4619): Added shared lib /data/app-lib/com.test.thalitest-39/libjxcore.so 0x42611158
,D/jxcore_app_log( 4619): JniHelper::setJavaVM(0x4173b528), pthread_self() = 2033042528
,D/JX-Cordova( 4619): jxcore cordova android initializing
,I/dalvikvm( 4619): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4619): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4619): VFY: replacing opcode 0x6e at 0x0045
,I/SELinux ( 4744): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4744):  
I/SELinux ( 4744):  
,I/SELinux ( 4744): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4744): >>>>> Normal User
,E/dalvikvm( 4744): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 4744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4744): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4744): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4744): Added TimaKesytore provider
,E/SMD     (  233): DCD ON
,D/PackageIntentReceiver( 4744): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4744): Not GearManger package! 
,I/SELinux ( 4760): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4760):  
I/ActivityManager(  738): Killing 3335:tv.peel.smartremote/u0a163 (adj 15): empty #43
,I/SELinux ( 4760): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4760):  
I/SELinux ( 4760):  
I/SELinux ( 4760): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4760): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4760): >>>>> Normal User
E/dalvikvm( 4760): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 4760): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4760): in addTimaSignatureService
D/TimaKeyStoreProvider( 4760): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4760): Added TimaKesytore provider
D/MagazineService Version( 4760): Magazine-Channel: 13
D/MagazineService Version( 4760): Magazine-Provider: 13
D/MagazineService Version( 4760): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 4760): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 4760): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=4760, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 4760): [onHandleIntent] ACTION_PACKAGE_INSTALLED
D/MagazineService::MagazineService( 4760): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/SELinux ( 4773): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4773):  
I/ActivityManager(  738): Killing 3360:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
I/SELinux ( 4773): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4773):  
I/SELinux ( 4773):  
I/SELinux ( 4773): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4773): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4773): >>>>> Normal User
E/dalvikvm( 4773): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 4773): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/GAV2    ( 4710): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  738): Killing 3412:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
D/dalvikvm( 4619): GC_CONCURRENT freed 4934K, 34% free 12752K/19040K, paused 3ms+3ms, total 47ms
D/dalvikvm( 4619): WAIT_FOR_CONCURRENT_GC blocked 32ms
D/TimaKeyStoreProvider( 4773): in addTimaSignatureService
D/TimaKeyStoreProvider( 4773): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4773): Added TimaKesytore provider
I/SELinux ( 4787): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4787):  
I/ActivityManager(  738): Killing 3428:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
I/SELinux ( 4787): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4787):  
I/SELinux ( 4787):  
I/SELinux ( 4787): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4787): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4787): >>>>> Normal User
E/dalvikvm( 4787): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 4787): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4787): in addTimaSignatureService
D/TimaKeyStoreProvider( 4787): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4787): Added TimaKesytore provider
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=4787, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
D/KidsPlatformStub( 4787): Package not found : com.sec.android.app.kidshome
I/SELinux ( 4799): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4799):  
I/ActivityManager(  738): Killing 3449:com.google.android.youtube/u0a175 (adj 15): empty #43
I/SELinux ( 4799): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4799):  
I/SELinux ( 4799):  
I/SELinux ( 4799): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4799): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4799): >>>>> Normal User
E/dalvikvm( 4799): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
E/SELinux ( 4799): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4799): in addTimaSignatureService
D/TimaKeyStoreProvider( 4799): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4799): Added TimaKesytore provider
,I/SELinux ( 4811): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4811):  
I/ActivityManager(  738): Killing 3123:com.sec.android.app.mt/1000 (adj 15): empty #43
,I/SELinux ( 4811): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4811):  
I/SELinux ( 4811):  
,I/SELinux ( 4811): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4811): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4811): >>>>> Normal User
,E/dalvikvm( 4811): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4811): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4811): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4811): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4811): Added TimaKesytore provider
,D/dalvikvm( 4619): GC_FOR_ALLOC freed 4698K, 28% free 15769K/21844K, paused 35ms, total 36ms
,I/ActivityManager(  738): Killing 3646:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/Finsky  ( 3527): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/PackageBroadcastService( 1759): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraModuleLdr( 1759): Loading module APK com.google.android.play.games
,I/dalvikvm( 1759): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1759): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1759): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1759): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1759): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1759): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1759): VFY: replacing opcode 0x22 at 0x001a
,I/dalvikvm( 1759): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1759): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1759): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/SSRMv2:SIOP(  738): SIOP:: AP = 310, Delta = 10
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1759): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1759): Submit a task: k
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  738): mCoverManager.getCoverState() : true
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/dalvikvm( 4619): GC_FOR_ALLOC freed 5056K, 32% free 16782K/24532K, paused 41ms, total 47ms
,I/dalvikvm-heap( 4619): Grow heap (frag case) to 22.070MB for 2475476-byte allocation
,D/k       ( 1759): Processing package: com.test.thalitest
,D/GassUtils( 1759): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1759): Found info for package com.test.thalitest in db.
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
,D/dalvikvm(  738): GC_EXPLICIT freed 24557K, 61% free 23312K/59020K, paused 10ms+16ms, total 211ms
,I/PeopleDatabaseHelper( 1759): cleanUpNonGplusAccounts done.
,D/dalvikvm( 1306): GC_EXPLICIT freed 979K, 44% free 10744K/19040K, paused 4ms+5ms, total 41ms
,D/dalvikvm( 4619): GC_FOR_ALLOC freed 3777K, 36% free 17470K/26952K, paused 39ms, total 39ms
,D/dalvikvm( 4619): GC_FOR_ALLOC freed 1222K, 36% free 17370K/26952K, paused 29ms, total 29ms
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1759): Module APK com.google.android.play.games already loaded
,W/jxcore-log( 4619): Initializing JXcore engine
,W/jxcore-log( 4619): JXcore engine is ready
,W/jxcore-log( 4619): Starting JXcore engine
,W/jxcore-log( 4619): Platform android
W/jxcore-log( 4619): 
,W/jxcore-log( 4619): Process ARCH arm
W/jxcore-log( 4619): 
,I/Icing   ( 1759): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1759): GC_CONCURRENT freed 1853K, 38% free 11931K/19040K, paused 5ms+5ms, total 86ms
,I/Icing   ( 1759): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,E/SMD     (  233): DCD ON
,I/jxcore-log( 4619): JXcore Cordova bridge is ready!
I/jxcore-log( 4619): 
,W/jxcore-log( 4619): JXcore engine is started
,I/chromium( 4619): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/GAV2    ( 4710): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4619): Toggling radios to true
I/jxcore-log( 4619): 
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=4619, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  738): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  738): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4619, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  738): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/BluetoothManagerService(  738): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService(  738): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  738): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService(  738): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService(  738): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService(  738): foregroundUser: 0
,E/BluetoothManagerService(  738): Package is exist.
,I/WifiManager( 4619): packageName : com.test.thalitest
,I/WifiManager( 4619): setWifiEnabled : true
D/BluetoothAdapterState( 3167): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,I/BluetoothAdapterState( 3167): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3167): Bluetooth PBAP supproted is true
I/WifiService(  738): setWifiEnabled: true pid=4619, uid=10179
D/BluetoothAdapterService( 3167): updateAdapterState state is 11
D/BluetoothAdapterService( 3167): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService( 3167): Autoconnection is available 
D/BluetoothAdapterService( 3167): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 3167): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/WifiService(  738): Failed getting userId using ActivityManagerNative
W/WifiService(  738): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4619, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  738): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  738): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  738): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  738): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  738): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  738): 	at dalvik.system.NativeStart.run(Native Method)
W/BluetoothAdapterService( 3167): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=4619, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/InputMethodManagerService(  738): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  738): [BT Setting State] State =11
W/BluetoothAdapterService( 3167): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3167): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 3167): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 3167): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/PhoneApp( 1241): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
I/QuickConnect[1.1][2] ( 3137): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/BluetoothAdapterService( 3167): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3167): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3167): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 3167): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 3167): Not skipping com.android.bluetooth.hfp.HeadsetService
I/WifiService(  738): disconnect: pid=4619, uid=10179
E/WifiHW  (  738): ##################### set firmware type 0 #####################
I/jxcore-log( 4619): Radios toggled
I/jxcore-log( 4619): 
W/BluetoothAdapterService( 3167): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3167): Not skipping com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3167): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 3167): Not skipping com.android.bluetooth.hid.HidService
I/jxcore-log( 4619): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 4619): 
D/QuickConnect[1.1][2] ( 3137): HeadsetProfile.onServiceConnected - Bluetooth service connected
D/HeadsetService( 3167): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3167): classInitNative: succeeds
D/HeadsetStateMachine( 3167): Version 1.6
D/HeadsetStateMachine( 3167): make
I/jxcore-log( 4619): Perf Test app loaded loaded
I/jxcore-log( 4619): 
D/BluetoothNotiBroadcastReceiver( 1311): onReceive
E/HeadsetStateMachine( 3167): # of Max HF connection is 2
I/jxcore-log( 4619): check test folder
I/jxcore-log( 4619): 
W/BluetoothAdapterService( 3167): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 3167): Not skipping com.android.bluetooth.hdp.HealthService
I/jxcore-log( 4619): found test : ./testFindPeers.js
I/jxcore-log( 4619): 
,W/BluetoothAdapterService( 3167): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3167): Not skipping com.android.bluetooth.pan.PanService
,I/bluedroid( 3167): get_profile_interface handsfree
,W/BluetoothAdapterService( 3167): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3167): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3167): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAtMessage( 3167): createCMTIContentObservers
,I/BluetoothAdapterState( 3167): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3167): Enter Disconnected: -2
,E/HeadsetStateMachine( 3167): set to mRemoteBrsf = 0
D/HeadsetStateMachine( 3167): map size, before remove : 0
D/HeadsetStateMachine( 3167): map size, after remove: 0
,D/HeadsetStateMachine( 3167): mNextConnectingDevice : null
,D/BluetoothA2dp( 3137): Proxy object connected
,D/BluetoothA2dp(  738): Proxy object connected
,D/BluetoothA2dp( 2025): Proxy object connected
,D/QuickConnect[1.1][2] ( 3137): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/A2dpService( 3167): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 3167): classInitNative: succeeds
,D/A2dpStateMachine( 3167): make
,I/bluedroid( 3167): get_profile_interface a2dp
,I/GKI_LINUX( 3167): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothAvrcpServiceJni( 3167): classInitNative: succeeds
,I/bluedroid( 3167): get_profile_interface avrcp
,D/A2dpStateMachine( 3167): Enter Disconnected: -2
,D/MediaFocusControl(  738): >>> registerRemoteControlDisplay
,E/MediaFocusControl(  738): Error updating focussed RCC to RCD 
E/MediaFocusControl(  738): java.util.EmptyStackException
E/MediaFocusControl(  738): 	at java.util.Stack.peek(Stack.java:57)
E/MediaFocusControl(  738): 	at android.media.MediaFocusControl.registerRemoteControlDisplay_int(MediaFocusControl.java:2308)
E/MediaFocusControl(  738): 	at android.media.MediaFocusControl.registerRemoteControlDisplay(MediaFocusControl.java:250)
E/MediaFocusControl(  738): 	at android.media.AudioService.registerRemoteControlDisplay(AudioService.java:6425)
E/MediaFocusControl(  738): 	at android.media.IAudioService$Stub.onTransact(IAudioService.java:593)
E/MediaFocusControl(  738): 	at android.os.Binder.execTransact(Binder.java:404)
E/MediaFocusControl(  738): 	at dalvik.system.NativeStart.run(Native Method)
,I/jxcore-log( 4619): found test : ./testSendData.js
I/jxcore-log( 4619): 
,I/BluetoothHidServiceJni( 3167): classInitNative: succeeds
,D/BluetoothInputDevice( 3137): Proxy object connected
,D/QuickConnect[1.1][2] ( 3137): HidProfile.onServiceConnected - Bluetooth service connected
,D/HidService( 3167): Received start request. Starting profile...
I/bluedroid( 3167): get_profile_interface hidhost
,D/HidService( 3167): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 3167): classInitNative: succeeds
,D/HealthService( 3167): Received start request. Starting profile...
,I/bluedroid( 3167): get_profile_interface health
,D/HeadsetStateMachine( 3167): Try to query the phonestate on bind
,D/BluetoothPhoneService( 1241): handleMessage: 4
,V/BluetoothPhoneService( 1241): Call state Converted2: IDLE/IDLE -> 6
,W/BluetoothHeadset( 1241): Proxy not attached to service
,D/HeadsetStateMachine( 3167): Proxy object connected
,I/BluetoothPanServiceJni( 3167): classInitNative(L105): succeeds
,D/BluetoothPan(  738): BluetoothPAN Proxy object connected
,D/PanService( 3167): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3167): initializeNative(L110): pan
,I/bluedroid( 3167): get_profile_interface pan
,D/BluetoothTethering(  738): got CMD_CHANNEL_HALF_CONNECTED
,D/AuthorizationBluetoothService( 1306): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/HeadsetPhoneState( 3167): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 3167): Disconnected process message: 11
,D/HeadsetPhoneState( 3167): sendDeviceDataStateChanged
,D/HeadsetStateMachine( 3167): Disconnected process message: 20
,D/BluetoothMapService( 3167): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 3167): mAccount : null
,D/HeadsetPhoneState( 3167): Signal level : previous=0 curr=0
V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
D/HeadsetPhoneState( 3167): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3167): Disconnected process message: 11
,D/BluetoothAdapterService( 3167): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3167): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3167): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3167): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3167): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterState( 3167): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3167): enable
,D/GKI_LINUX( 3167): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 3167): Calling BTA_HhEnable
,E/bt-btif ( 3167): btif_storage_get_adapter_property service_mask:0x140040
E/BluetoothServiceJni( 3167): populateRssiValuesNative
I/bluedroid( 3167): getModelRssiValues
,E/BluetoothServiceJni( 3167): model_rssi_values_callback: low = -70, mid = -60, high = 127
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 241
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 241
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 241
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 241
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 241
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/GKI_LINUX( 3167): release_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 241
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 10
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 241
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 10
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 241
,E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
E/BluetoothRemoteDevices( 3167): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 241
E/bt-btif ( 3167): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 3167): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 3167): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 3167): db_open: file /etc/bluetooth/iop_bt.db
,I/chromium( 4619): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/IOP_DB_BT( 3167): db_open: db_open : handle 2012853016l, read 9734 bytes onto local cache
,D/IOP_DB_BT( 3167): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 3167): db_query: result 1
I/        ( 3167): iop_db_open: iop_db_open status 0
D/GKI_LINUX( 3167): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,I/bte_conf( 3167): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3167): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 3167): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3167): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothAdapterState( 3167): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3167): ScanMode =  20
,D/BluetoothAdapterProperties( 3167): State =  11
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
D/BtConfig.SecureMode( 3167): isSecureModeOn:false
D/BtConfig.SecureMode( 3167): isSecureModeOn:false
D/BtConfig.SecureMode( 3167): isSecureModeOn:false
D/BtConfig.SecureMode( 3167): isSecureModeOn:false
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
D/BtConfig.SecureMode( 3167): isSecureModeOn:false
D/BtConfig.SecureMode( 3167): isSecureModeOn:false
D/BtConfig.SecureMode( 3167): isSecureModeOn:false
,D/BtConfig.SecureMode( 3167): isSecureModeOn:false
,I/BluetoothAdapterState( 3167): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3167): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3167): updateAdapterState state is 12
,D/BluetoothAdapterService( 3167): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService(1113710032)( 3167): Register RemoteMessageListener
,D/BluetoothInputDevice( 3137): onBluetoothStateChange: up=true
D/HeadsetService( 3167): registerMessageListener
,D/HeadsetStateMachine( 3167): Disconnected process message: 70
,D/BluetoothA2dp( 2025): onBluetoothStateChange: up=true
D/HeadsetStateMachine( 3167): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@42660930
D/BluetoothAdapterService( 3167): Autoconnection is available 
D/BluetoothAdapterService( 3167): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 3167): starting service from this receiver
,D/BluetoothA2dp( 3137): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  738): onBluetoothStateChange: up=true
,D/BluetoothAdapterService( 3167): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[91]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[92]}
,D/bluedroid( 3167): init_wake_lock lock_fd:91, unlock_fd:92
,I/WifiTrafficPoller(  738): mBoosterFLAG : 2
,I/WifiTrafficPoller(  738): current booster mode : BTCoexMode
,D/PhoneApp( 1241): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
,W/ContextImpl( 3167): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
W/InputMethodManagerService(  738): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  738): [BT Setting State] State =12
,I/InputMethodManagerService(  738): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/BluetoothAdapterService(1113710032)( 3167): Get Bonded Devices being called
D/BluetoothHeadset( 1241): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@427c2e38, true
I/QuickConnect[1.1][2] ( 3137): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
D/BluetoothHeadset( 1241): registerMessageListener
I/BluetoothPbapService( 3167): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
I/BluetoothPbapService( 3167): Handler(): got msg=1
,I/BluetoothAdapterState( 3167): Entering On State from state = 11
,D/HeadsetService( 3167): registerMessageListener
,D/HeadsetService( 3167): registerMessageListener
D/HeadsetStateMachine( 3167): Disconnected process message: 70
D/HeadsetStateMachine( 3167): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@426e7448
,D/PhoneApp( 1241): registerMessageListener
,V/BluetoothPbapService( 3167): PBAP Service initSocket try: 0
,D/BluetoothPanServiceJni( 3167): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,W/BluetoothAdapter( 3167): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3167): SOCK FLAG = 1 ***********************
D/BluetoothPbapService( 3167): PBAP Socket is BluetoothServerSocket
,D/BluetoothMapMasInstance( 3167): set MAP SDP message type : 1
,W/BluetoothAdapter( 3167): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3167): SOCK FLAG = 3 ***********************
W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/STATUSBAR-IconMerger( 1067): checkOverflow(336), More:false, Req:false Child:2
,D/LocalBluetoothProfileManager( 1311): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1311): Adding local HEADSET profile
W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1311): BTStateChangeCB is registed
,E/BluetoothHeadset( 1311): BluetoothHeadset service is binded
W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,D/Bluetoothsap( 1311): bindService called to Bluetooth SAP Service
W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/GKI_LINUX( 3167): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,D/LocalBluetoothProfileManager( 1311): PANU : true
,D/LocalBluetoothProfileManager( 1311): Adding local MAP profile
,D/BluetoothMap( 1311): Create BluetoothMap proxy object
W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1311): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1311): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1311): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1311): onReceive
,D/BluetoothA2dp( 1311): Proxy object connected
,W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/BtConfig.SecureMode( 3167): isSecureModeOn:false
D/A2dpProfile( 1311): Bluetooth service connected
,D/AuthorizationBluetoothService( 1306): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1306): Proximity feature is not enabled.
,D/HeadsetProfile( 1311): Bluetooth service connected
,D/BluetoothInputDevice( 1311): Proxy object connected
,D/HidProfile( 1311): Bluetooth service connected
,D/BluetoothPan( 1311): BluetoothPAN Proxy object connected
,D/PanProfile( 1311): Bluetooth service connected
,D/BluetoothMap( 1311): Proxy object connected
,D/MapProfile( 1311): Bluetooth service connected
,D/BluetoothPbap( 1311): Proxy object connected
,D/PbapServerProfile( 1311): Bluetooth service connected
,W/BluetoothAdapter( 3167): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3167): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 3167): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 3167): Accept thread started.
,D/Tethering(  738): interfaceAdded wlan0
,E/Tethering(  738): No numeric data
,I/ConnectivityService(  738): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  738): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  738): interfaceLinkStateChanged wlan0, false
D/Tethering(  738): interfaceStatusChanged wlan0, false
D/NtpTrustedTime(  738): forceRefresh() from cache miss
,D/Tethering(  738): InitialState.processMessage what=4
,E/Tethering(  738): No numeric data
,D/NtpTrustedTime(  738): forceRefresh Fail.
,D/Tethering(  738): interfaceAdded p2p0
,D/Tethering(  738): sendTetherStateChangedBroadcast 0, 0, 0
I/ConnectivityService(  738): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  738): performPollLocked(flags=0x1)
D/Tethering(  738): p2p0 is not a tetherable iface, ignoring
,D/Tethering(  738): interfaceLinkStateChanged p2p0, false
,D/Tethering(  738): interfaceStatusChanged p2p0, false
,I/WifiHW  (  230): wifi_change_fw_path(): fwpath = sta
,D/SoftapController(  230): Softap fwReload - Ok
,D/NtpTrustedTime(  738): forceRefresh() from cache miss
,D/NtpTrustedTime(  738): forceRefresh Fail.
,D/NtpTrustedTime(  738): forceRefresh() from cache miss
D/NtpTrustedTime(  738): forceRefresh Fail.
D/CommandListener(  230): Setting iface cfg
,D/CommandListener(  230): Trying to bring down wlan0
V/NetworkStats(  738): performPollLocked() took 26ms
V/NetworkStats(  738): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  738): forceRefresh() from cache miss
,D/NtpTrustedTime(  738): forceRefresh Fail.
,D/GKI_LINUX( 3167): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
V/NetworkStats(  738): performPollLocked() took 17ms
,D/WifiHW  (  738): Skip the update_ctrl_interface
,D/WifiHW  (  738): Skip the update_ctrl_interface
,E/WifiHW  (  738): supplicant_name : p2p_supplicant
,E/SMD     (  233): DCD ON
,I/wpa_supplicant( 4907): wpa_supplicant v2.1-devel-4.4.22014-11-04/18:06:52
I/wpa_supplicant( 4907): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 4907): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4907): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4907): getIMSI cannot open file
,E/wpa_supplicant( 4907): Interworking config: - SIM READ ERROR
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/WifiMonitor(  738): startMonitoring(wlan0) with mConnected = false
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/knox    ( 3071): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3071): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 3071): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3071): KNOXAgentService : onCreate()
D/knox    ( 3071): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3071): KNOXAgentService. startJobThread() start
D/knox    ( 3071): KNOXAgentService. JobThread()
D/knox    ( 3071): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3071): KNOXAgentService. startJobThread() wait
,I/SELinux ( 4912): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4912):  
D/knox    ( 3071): KNOXAgentService : onDestroy().
,D/knox    ( 3071): ModuleBase.cancelAllAlarmManageModule()
,I/wpa_supplicant( 4907): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4907): getIMSI cannot open file
,E/wpa_supplicant( 4907): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 4907): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4907): rfkill: Cannot open RFKILL control device
,D/Tethering(  738): interfaceLinkStateChanged wlan0, false
,D/Tethering(  738): interfaceStatusChanged wlan0, false
,I/SELinux ( 4912): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4912):  
I/SELinux ( 4912):  
,I/SELinux ( 4912): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4912): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4912): >>>>> Normal User
,E/dalvikvm( 4912): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 4912): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4912): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4912): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4912): Added TimaKesytore provider
,I/wpa_supplicant( 4907): wlan0: Setting scan request: 0 sec 100000 usec
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=4912, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
,I/wpa_supplicant( 4907): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4907): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4907): rfkill: Cannot open RFKILL control device
D/Tethering(  738): interfaceLinkStateChanged p2p0, false
,D/Tethering(  738): interfaceStatusChanged p2p0, false
D/Tethering(  738): interfaceLinkStateChanged p2p0, false
,D/Tethering(  738): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4907): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4907): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
I/wpa_supplicant( 4907): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4907): Skip scan - bUseNetwork false
,D/WifiStateMachine(  738): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/SignalClusterView_dual( 1067): wifi: GONE sig=0 act=0
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
,D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=0
,D/WifiNative(  738): callSECApiString - ID [21]
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=0
I/wpa_supplicant( 4907): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 4907): wlan0: HS20_DISABLED_COMPLETE normal
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/WifiNative(  738): callSECApiInt - ID [65]
,E/WifiConfigStore(  738): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative(  738): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 4907): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 4907): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 4907): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 4907): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 4907): First Scan Start
,I/wpa_supplicant( 4907): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 3030): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine(  738): Set the Nv default ccode
,D/WifiStateMachine(  738): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,D/WifiP2pService(  738): P2pDisabledState{ what=131203 }
,E/WifiStateMachine(  738): HS20_DISABLED_COMPLETEnormal
W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.enterprise.wifi.WifiPolicy.asyncEnableNetwork:3065 com.android.server.enterprise.wifi.WifiPolicy.edmUpdateConfiguredNetworks:2530 com.android.server.enterprise.wifi.WifiPolicy$2$2.run:3022 java.lang.Thread.run:841 
,I/wpa_supplicant( 4907): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/CommandListener(  230): Setting iface cfg
,D/CommandListener(  230): Trying to bring up p2p0
,D/WifiMonitor(  738): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  738): P2pEnablingState
D/WifiP2pService(  738): P2pEnablingState{ what=147457 }
D/WifiP2pService(  738): P2p socket connection successful
D/WifiP2pService(  738): P2pEnabledState
,D/QuickConnect[1.1][2] ( 3137): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,D/QuickConnect[1.1][2] ( 3137): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiP2pService(  738): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController(  738): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  738): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  738): disconnect
D/WifiDisplayController(  738): updateConnection
D/WifiDisplayController(  738): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  738): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter(  738): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 3137): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/WifiDisplayController(  738): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/QuickConnect[1.1][2] ( 3137): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,I/ActivityManager(  738): Killing 3691:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,D/WifiDisplayController(  738): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy S5-2
D/WifiDisplayController(  738):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiDisplayController(  738):  primary type: 10-0050F204-5
D/WifiDisplayController(  738):  secondary type: null
D/WifiDisplayController(  738):  wps: 0
D/WifiDisplayController(  738):  grpcapab: 0
D/WifiDisplayController(  738):  devcapab: 0
D/WifiDisplayController(  738):  status: 3
D/WifiDisplayController(  738):  wfdInfo: null
D/WifiDisplayController(  738):  groupownerAddress: null
D/WifiDisplayController(  738):  GOdeviceName: null
D/WifiDisplayController(  738):  interfaceAddress: 
D/WifiDisplayController(  738):  SConnectInfo : null
,D/WifiP2pService(  738): DeviceAddress: 3a:06:dd
,E/WifiStateMachine(  738): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService(  738): sending p2p persistent groups changed broadcast
,D/QuickConnect[1.1][2] ( 3137): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,I/knox    ( 3071): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/WifiP2pService(  738): InactiveState
W/WifiP2pStateTracker(  738): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiP2pService(  738): InactiveState{ what=139287 }
D/WifiP2pService(  738): P2pEnabledState{ what=139287 }
D/WifiP2pService(  738): DefaultState{ what=139287 }
,W/ContextImpl( 3071): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 3071): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3071): KNOXAgentService : onCreate()
,D/knox    ( 3071): KNOXAgentService : set alarms for deniallog and usage data upload
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/knox    ( 3071): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
D/knox    ( 3071): KNOXAgentService. startJobThread() start
D/knox    ( 3071): KNOXAgentService. JobThread()
,D/knox    ( 3071): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3071): KNOXAgentService. startJobThread() wait
D/knox    ( 3071): KNOXAgentService : onDestroy().
,D/knox    ( 3071): ModuleBase.cancelAllAlarmManageModule()
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 4173): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 4173): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,D/Tethering(  738): interfaceLinkStateChanged p2p0, false
,D/Tethering(  738): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4907): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4907): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4907): nl80211: Received scan results (12 BSSes)
I/wpa_supplicant( 4907): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 4907): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 4907): Trying to associate with  'G700'
,I/wpa_supplicant( 4907): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 4907): Cmd 35609 not handled
D/Tethering(  738): interfaceLinkStateChanged wlan0, false
,D/Tethering(  738): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  738): Error! unhandled message{ when=0 what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4907): Cmd 35605 not handled
I/wpa_supplicant( 4907): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 4907): Associated with C0.AA.48
,I/wpa_supplicant( 4907): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 4907): Cmd 35847 not handled
E/wpa_supplicant( 4907): Cmd 35848 not handled
,E/wpa_supplicant( 4907): Cmd 35605 not handled
,I/wpa_supplicant( 4907): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 4907): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4907): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 4907): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative(  738): callSECApiVoid - ID [50]
,D/Tethering(  738): interfaceLinkStateChanged wlan0, false
,D/Tethering(  738): interfaceStatusChanged wlan0, false
,D/Tethering(  738): interfaceLinkStateChanged wlan0, false
,D/Tethering(  738): interfaceStatusChanged wlan0, false
,D/Tethering(  738): interfaceLinkStateChanged wlan0, false
,D/Tethering(  738): interfaceStatusChanged wlan0, false
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/Tethering(  738): interfaceLinkStateChanged wlan0, true
,D/Tethering(  738): interfaceStatusChanged wlan0, true
,E/Tethering(  738): No numeric data
I/ConnectivityService(  738): defaultVal : 1, tetherEnabledInSettings : true
,I/SELinux ( 4945): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4945):  
,D/Tethering(  738): interfaceLinkStateChanged wlan0, true
,D/Tethering(  738): interfaceStatusChanged wlan0, true
,D/Tethering(  738): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering(  738): interfaceLinkStateChanged wlan0, true
,D/Tethering(  738): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime(  738): forceRefresh() from cache miss
,D/NtpTrustedTime(  738): forceRefresh Fail.
,D/Tethering(  738): interfaceLinkStateChanged wlan0, true
,D/Tethering(  738): interfaceStatusChanged wlan0, true
D/Tethering(  738): interfaceLinkStateChanged wlan0, true
,D/Tethering(  738): interfaceStatusChanged wlan0, true
,D/dalvikvm(  240): GC_EXPLICIT freed 43K, 51% free 9506K/19040K, paused 3ms+15ms, total 46ms
V/NetworkStats(  738): performPollLocked(flags=0x1)
,V/NetworkStats(  738): performPollLocked() took 19ms
D/NtpTrustedTime(  738): forceRefresh() from cache miss
D/NtpTrustedTime(  738): forceRefresh Fail.
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 51% free 9506K/19040K, paused 2ms+3ms, total 22ms
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
I/SELinux ( 4945): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4945):  
I/SELinux ( 4945):  
,I/SELinux ( 4945): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4945): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4945): >>>>> Normal User
,E/dalvikvm( 4945): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 4945): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/WifiP2pService(  738): InactiveState{ what=143375 }
,D/WifiP2pService(  738): P2pEnabledState{ what=143375 }
D/dalvikvm(  240): GC_EXPLICIT freed <1K, 51% free 9506K/19040K, paused 2ms+3ms, total 22ms
,D/TimaKeyStoreProvider( 4945): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4945): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4945): Added TimaKesytore provider
,I/System.out( 4945): Inside WakeupProvider
,I/System.out( 4945): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 4945): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 4945): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 4945): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 4974): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 4974): bssid match
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  738): Killing 3730:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/DialogFlow( 4945): initQueue()
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
,D/WifiP2pService(  738): InactiveState{ what=143375 }
,D/WifiP2pService(  738): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  738): VerifyingLinkState enter
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
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  738): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  738): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  738): evaluateTrafficStatsPolling
D/ConnectivityService(  738): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  738): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  738): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
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
,I/WifiTrafficPoller(  738): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  738): mBoosterFLAG : 2
,I/WifiTrafficPoller(  738): current booster mode : BTCoexMode
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
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
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  738): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  738): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  738): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService(  738): handleConnectivityChange: setting default proxy info 
,V/RouteController(  230): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  230): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  230): RTNETLINK answers: No such file or directory
,V/RouteController(  230): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,V/RouteController(  230): /system/bin/ip route flush cached 2>&1
,D/Toast   ( 1311):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1311): showing allowed
,V/RouteController(  230): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  230): RTNETLINK answers: No such process
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,V/RouteController(  230): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController(  230): /system/bin/ip route flush cached 2>&1
,I/SurfaceFlinger(  239): id=19 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,V/NetworkStats(  738): updateIfacesLocked()
,D/NtpTrustedTime(  738): forceRefresh() from cache miss
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
V/NetworkStats(  738): performPollLocked(flags=0x1)
D/PowerManagerService(  738): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=738
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
V/NetworkStats(  738): performPollLocked() took 18ms
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  738): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1450109416326 mCachedNtpElapsedRealtime : 132256 mCachedNtpCertainty : 17
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
D/NtpTrustedTime(  738): currentTimeMillis() cache hit
D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
V/NetworkStats(  738): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/jxcore-log( 4619): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4619): 
,D/Tethering(  738): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  738): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  738): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
D/        (  738): Setting time of day to sec=1450109416
D/        (  738): Trying to open a file
D/        (  738): File Open Success
D/        (  738): File Close Success
I/        (  738): DRM_TIME_PATH CHMOD 660 for resetState done 
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,W/        (  738): Unable to set rtc to 1450109416: Invalid argument
V/AlarmManager(  738): waitForAlarm result :65536
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,I/AudioService(  738): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 1067): Received intent with android.intent.action.TIME_SET action
D/StatusBar-DoNotDistrub( 1067): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/StatusBar-DoNotDistrub( 1067): sendBroadcast android.intent.action.DORMANT_MODE_OFF
D/StatusBar-DoNotDistrub( 1067): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService(  738): manageDisableList what=0x0 pkg=com.android.systemui
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 4490): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 4490): sales region : global
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
I/PCWCLIENTTRACE_PushUtil( 4490): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4490): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/HarmonyEASService(  738): Updating for all 1
,I/NetworkMonitor( 3764): type=WIFI subType= reason=null isConnected=true
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:452 [0:0] doChangeDayOrNight : 1
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
,W/Settings(  738): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AlarmManager(  738): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager(  738): waitForAlarm result :4
,W/SEC_DRM_PLUGIN_Playready(  241): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1450109416 after conversion: 1450109416
,W/SEC_DRM_PLUGIN_Playready(  241): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1450109416 after conversion: 1450109416
,I/SensorManagerA(  738): getReportingMode :: sensor.mType = 5
D/Sensors (  738): LightSensor setDelay = 200000000
,D/Sensors (  738): LightSensor setSensorDelay = 200000000
D/Sensors (  738): Light sensor flush: not enabled 0
D/Sensors (  738): LightSensor enable = 1
D/Sensors (  738): LightSensor enableSensor = 1
,D/SensorManager(  738): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/STATUSBAR-NotificationService(  738): received android.intent.action.DORMANT_MODE_OFF
D/LightsService(  738): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 738) 
D/LightsService(  738): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LocSvc_java(  738): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  738): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  738): ignore wifi update if we are not in OPENING or CLOSING
,I/SELinux ( 5058): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5058):  
,I/SELinux ( 5058): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5058):  
I/SELinux ( 5058):  
,I/SELinux ( 5058): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/SELinux ( 5068): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5068):  
,E/SELinux ( 5058): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5058): >>>>> Normal User
,E/dalvikvm( 5058): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5058): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5058): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5058): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5058): Added TimaKesytore provider
,I/dalvikvm( 1759): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1759): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x003d
,I/SELinux ( 5068): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5068):  
I/SELinux ( 5068):  
,I/SELinux ( 5068): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5068): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5068): >>>>> Normal User
,E/dalvikvm( 5068): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5068): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5068): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5068): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5068): Added TimaKesytore provider
E/ActivityThread( 1759): Failed to find provider info for com.android.contacts.metadata
,D/Sensors (  738): LightSensor enable = 0
,D/Sensors (  738): LightSensor enableSensor = 0
,D/SensorManager(  738): unregisterListener ::   
D/LightsService(  738): [SvcLED]  onSensorChanged::light value = 2
D/LightsService(  738): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SyncManager(  738): failed sync operation 
,D/SyncManager(  738): not retrying sync operation because the error is a hard error: 
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5058, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5068, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,D/PicasaService( 3850): start picasa sync
,D/PicasaService( 3850): end picasa sync
,W/WifiP2pStateTracker(  738): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  738): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  738):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  738): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  738): updateSourceRoutes : no source routing conditions
,D/dalvikvm(  738): GC_EXPLICIT freed 2740K, 61% free 23508K/59020K, paused 7ms+13ms, total 146ms
,I/SELinux ( 5099): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5099):  
,D/DelayedSyncController( 5068): Delaying sync.
,D/DelayedSyncController( 5068): Delaying sync.
,I/SELinux ( 5099): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5099):  
I/SELinux ( 5099):  
,I/SELinux ( 5099): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5099): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5099): >>>>> Normal User
,E/dalvikvm( 5099): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5099): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5099): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5099): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5099): Added TimaKesytore provider
,D/SSRMv2:SIOP(  738): SIOP:: AP = 320, Delta = 10
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5099, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  738): Killing 3748:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/ActivityManager(  738): Killing 3965:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,I/SELinux ( 5116): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5116):  
,W/DriveInitializer( 1759): Awaiting to be initialized
,W/DriveInitializer( 1759): Background init thread started
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 1759): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,W/Vold    (  220): Returning OperationFailed - no handler for errno 30
I/SELinux ( 5116): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5116):  
I/SELinux ( 5116):  
I/SELinux ( 5116): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5116): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5116): >>>>> Normal User
E/dalvikvm( 5116): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
E/SELinux ( 5116): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5116): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5116): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5116): Added TimaKesytore provider
,W/DriveInitializer( 1759): Background init thread ended
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5116, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5116): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5116): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450109417801
,I/KLMS-2.3.201 : ( 5116): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/dalvikvm( 1759): GC_CONCURRENT freed 1611K, 36% free 12330K/19040K, paused 6ms+4ms, total 51ms
,I/ActivityManager(  738): Killing 3984:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 5145): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5145):  
,I/LocationTagReadyService( 2359): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2359): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2359): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2359): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3850): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/btif_config_util( 3167): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/SELinux ( 5145): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5145):  
I/SELinux ( 5145):  
,I/SELinux ( 5145): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5145): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5145): >>>>> Normal User
,E/dalvikvm( 5145): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5145): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 5151): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5151):  
,D/TimaKeyStoreProvider( 5145): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5145): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5145): Added TimaKesytore provider
,I/SELinux ( 5163): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5163):  
,I/SELinux ( 5151): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5151):  
I/SELinux ( 5151):  
,I/SELinux ( 5151): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5151): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5151): >>>>> Normal User
,E/dalvikvm( 5151): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5151): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5151): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5151): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5151): Added TimaKesytore provider
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5145, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
D/SO_AGENT( 5145): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5145): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 5163): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5163):  
I/SELinux ( 5163):  
,I/SELinux ( 5163): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5163): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5163): >>>>> Normal User
,E/dalvikvm( 5163): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5163): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5163): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5163): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5163): Added TimaKesytore provider
,I/ActivityManager(  738): Killing 3972:com.android.calendar/u0a142 (adj 15): empty #43
,I/SA      ( 4679): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,V/KVNProvider( 5163): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5163): getFindoCursor query string : 
,I/SA      ( 4679): [BDLM] already registered in spp
,V/KVNProvider( 5163): getTagSearchCursor() tagSearchCursor count : 0
I/SA      ( 4679): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4679): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/ActivityManager(  738): Killing 4017:com.android.providers.calendar/u0a44 (adj 15): empty #43
,I/SA      ( 4679): [SLFUCHKMGR] constructor called
,I/SA      ( 4679): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4679): [OR] == isSIMCardReady false ==
I/SA      ( 4679): [SCU] == networkStateCheck == true
I/SA      ( 4679): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4679): isChinaCountryCode : false
,I/SA      ( 4679): [OR] == networkStateCheck true ==
,I/dalvikvm( 4623): Total arena pages for JIT: 11
,I/dalvikvm( 4623): Total arena pages for JIT: 12
I/dalvikvm( 4623): Total arena pages for JIT: 13
,I/dalvikvm( 4623): Total arena pages for JIT: 14
,I/SA      ( 4679): [OR] GetMyCountryZoneTask
,I/SA      ( 4679): [OR] onReceive END
,I/SA      ( 4679): [SRS] prepareGetMyCountryZone
,I/SA      ( 4679): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/ActivityManager(  738): Killing 4021:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
I/SA      ( 4679): [SSP] query invoked
,I/SA      ( 4679): [TPMU] GetMccFromDB : null
I/SA      ( 4679): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4679): [TPM] isNoProxy(default) : true
,I/SA      ( 4679): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,I/Scheduler( 1220): Use legacy PeriodicScheduler
,I/SELinux ( 5192): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5192):  
,W/InstanceID/Rpc( 1220): Found 10011
,I/SELinux ( 5192): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5192):  
I/SELinux ( 5192):  
,I/SELinux ( 5192): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5192): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5192): >>>>> Normal User
,E/dalvikvm( 5192): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5192): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5192): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5192): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5192): Added TimaKesytore provider
,E/SMD     (  233): DCD ON
,I/System.out( 4679): Thread-449(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4679): Thread-449(ApacheHTTPLog):isShipBuild true
,I/System.out( 4679): Thread-449(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/sCloudBackupApp( 5192): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5192): Other Intent
I/ActivityManager(  738): Killing 3947:com.sec.phone/1001 (adj 15): empty #43
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:37 [0:0] oR : create UI manager : start
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:89 [0:0] getInstance
D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1449): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 1449): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1486): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1449): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1486): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1449): [KK AccuPhone]>>> DBH:3047 [0:0] gADWI : count = 0
,D/daemonapp( 1486): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5206): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5206):  
,I/SELinux ( 5206): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5206):  
I/SELinux ( 5206):  
,I/SELinux ( 5206): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5206): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5206): >>>>> Normal User
,E/dalvikvm( 5206): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10106 ]
,E/SELinux ( 5206): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5206): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5206): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5206): Added TimaKesytore provider
,D/HeadlinesChannelApplication( 5206): [onCreate]
,D/Headlines( 5206): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5206, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,D/HeadlinesChannelUtil( 5206): getCountryCode(): countryCode = PL
,D/Headlines( 5206): Breath.onCreate
,D/HeadlinesCardManager( 5206): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 5206): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 5206): CardProvider Library : 13
W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 5221): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5221):  
,D/MagazineService::CardProviderContentProvider( 4760): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 4760): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5206): registerCardProvider: provider already exists.
,I/Headlines( 5206): HeadlinesDataCenter ctor
I/Headlines( 5206): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 5206): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 5206): HeadlinesCardManager : constructor welcome :YES
,D/Headlines( 5206): Breath timer started. interval : 30000
,D/Headlines( 5206): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5206): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5206): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5206): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5206): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5206): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5206): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5221): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5221):  
I/SELinux ( 5221):  
,I/SELinux ( 5221): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5221): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5221): >>>>> Normal User
,E/dalvikvm( 5221): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5221): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5221): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5221): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5221): Added TimaKesytore provider
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5221): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5221): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 5221): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5221): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5221): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/WebViewChromium( 5221): Binding Chromium to the main looper Looper (main, tid 1) {422ea1c0}
,I/chromium( 5221): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5221): Initializing chromium process, renderers=0
,I/SA      ( 4679): [RC New] [v2liruge] api execute + 850
,I/SA      ( 4679): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4679): AsyncTask #1 calls detatch()
,I/SA      ( 4679): [TPMU] getNetworkMcc : 
,W/chromium( 5221): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/SA      ( 4679): [SCU] saveMccToPreferece Start
I/SA      ( 4679): [SCU] RegionMCC : 260
,I/SA      ( 4679): [SSP] query invoked
,I/SA      ( 4679): [TPMU] GetMccFromDB : null
I/SA      ( 4679): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4679): [SCU] saveMccToPreferece End
I/SA      ( 4679): [RC New] executeRequest [v2liruge] end. 868
,I/SA      ( 4679): [RC New] Execute end
,I/SA      ( 4679): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 4679): [OR] GetMyCountryZoneTask Success
,I/Adreno-EGL( 5221): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5221): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5221): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5221): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5221): Remote Branch: 
I/Adreno-EGL( 5221): Local Patches: 
I/Adreno-EGL( 5221): Reconstruct Branch: 
,I/NSApplication( 5221): Starting up...
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5221, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3137): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3137): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3137): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4261ede8
I/ActivityManager(  738): Killing 3892:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
,I/SELinux ( 5258): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5258):  
,D/dalvikvm(  240): GC_EXPLICIT freed 43K, 51% free 9506K/19040K, paused 2ms+2ms, total 27ms
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 51% free 9506K/19040K, paused 2ms+2ms, total 19ms
I/SELinux ( 5258): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5258):  
I/SELinux ( 5258):  
,I/SELinux ( 5258): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5258): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5258): >>>>> Normal User
,E/dalvikvm( 5258): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5258): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5258): in addTimaSignatureService
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 51% free 9506K/19040K, paused 2ms+3ms, total 19ms
,D/TimaKeyStoreProvider( 5258): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5258): Added TimaKesytore provider
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,I/SELinux ( 5277): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5277):  
I/ActivityManager(  738): Killing 3030:com.google.android.talk/u0a105 (adj 15): empty #43
,I/SELinux ( 5281): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5281):  
,I/SELinux ( 5277): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5277):  
I/SELinux ( 5277):  
I/SELinux ( 5277): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/WifiStateMachine(  738): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
E/SELinux ( 5277): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5277): >>>>> Normal User
,E/dalvikvm( 5277): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5277): [DEBUG] seapp_context_lookup: seinfoCategory = shared
W/ActivityManager(  738): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 5277): in addTimaSignatureService
I/SELinux ( 5281): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5281):  
I/SELinux ( 5281):  
,I/SELinux ( 5281): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5281): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5281): >>>>> Normal User
,E/dalvikvm( 5281): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,D/TimaKeyStoreProvider( 5277): Cannot add TimaSignature Service, License check Failed
,E/SELinux ( 5281): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/ActivityThread( 5277): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 5281): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5281): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5281): Added TimaKesytore provider
,I/ActivityManager(  738): Killing 4042:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5277, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5281): onCreate
,D/BadgeProvider( 5281): DatabaseHelper
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5281, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5281): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5281): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5281): sendNotify, [notify] : null
D/BadgeProvider( 5281): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5281): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5281): update, [UpdateCount] : 1
,D/Launcher.Model( 1262): reloadBadges entered.
,D/dalvikvm(  738): GC_EXPLICIT freed 1430K, 61% free 23359K/59020K, paused 6ms+12ms, total 141ms
,D/WaitQueueForNetworkActivate( 4811): notifyNetworkActivated
,W/ContextImpl( 4811): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager(  738): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/ActivityManager(  738): Killing 2896:com.sec.knox.bridge/1000 (adj 15): empty #43
I/SurfaceFlinger(  239): id=19 Removed Uoast (11/12)
I/SurfaceFlinger(  239): id=19 Removed Uoast (-2/12)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  738): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=738 (0x0)
D/PowerManagerService(  738): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=738, ws=WorkSource{1000}) (elapsedTime=3454)
,D/hcjo    ( 4811): AutoUpdateManager:IDLE:execute
I/dalvikvm( 4811): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 4811): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 4811): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 4811): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4811): exit::IDLE
,D/InitializeManagerStateMachine( 4811): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4811): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 4811): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4811): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4811): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4811): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4811): entry::SUCCESS
,D/hcjo    ( 4811): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4811): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 4811): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4811): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4811): exit::SUCCESS
,D/InitializeManagerStateMachine( 4811): entry::IDLE
I/ActivityManager(  738): Killing 4243:com.wssyncmldm/1000 (adj 15): empty #43
,I/iu.SyncManager( 1759): SYNC; picasa accounts
,D/NetworkLogImpl( 1759): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1759): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1759): num queued entries: 0
,I/iu.UploadsManager( 1759): num updated entries: 0
,I/iu.SyncManager( 1759): NEXT; no task
,I/SELinux ( 5323): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5323):  
,I/SELinux ( 5323): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5323):  
I/SELinux ( 5323):  
,I/SELinux ( 5323): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5323): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5323): >>>>> Normal User
,E/dalvikvm( 5323): >>>>> com.android.calendar [ userId:0 | appId:10142 ]
,E/SELinux ( 5323): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5323): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5323): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5323): Added TimaKesytore provider
,I/GCM     ( 1306): GCM config loaded
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/ActivityManager(  738): Killing 4398:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/BootCompletedReceiver(  738): onReceive
,I/KLMS-2.3.201 : ( 5116): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5116): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1450109420260
,I/KLMS-2.3.201 : ( 5116): StateImplV2() : dateTimeChanged() : Mon Dec 14 17:10:20 CET 2015
,D/SO_AGENT( 5145): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 5145): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 4679): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/Mms/MessagingNotification( 3788): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 3788): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 3788): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 3788): isDefault true
,I/SELinux ( 5348): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5348):  
,D/TP/MmsSmsProvider( 1241): match 200:Elapsed time : 1.873 ms
,I/SELinux ( 5348): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5348):  
I/SELinux ( 5348):  
,D/BadgeProvider( 5281): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/SELinux ( 5348): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5348): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5348): >>>>> Normal User
,E/dalvikvm( 5348): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 5348): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TP/MmsSmsProvider( 1241): match 8:Elapsed time : 26.709 ms
,D/BadgeProvider( 5281): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/Launcher.Model( 1262): reloadBadges entered.
D/BadgeProvider( 5281): sendNotify, [notify] : null
D/BadgeProvider( 5281): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5281): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5281): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 3788): setBadgeCount(), count=0
,D/TimaKeyStoreProvider( 5348): in addTimaSignatureService
,D/MessagingNotification( 3788): remove alarm
,D/TimaKeyStoreProvider( 5348): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5348): Added TimaKesytore provider
,D/Mms/MessagingNotification( 3788): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 3788): [end]    nonBlockingUpdateMessageIndicator()
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5348, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 5348): Time Difference not stored. TIME_DIFFERENCE
I/ActivityManager(  738): Killing 3199:com.sec.android.inputmethod/1000 (adj 15): empty #43
,I/SELinux ( 5373): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5373):  
,I/SELinux ( 5373): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5373):  
I/SELinux ( 5373):  
,I/SELinux ( 5373): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5373): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5373): >>>>> Normal User
,E/dalvikvm( 5373): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 5373): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5373): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5373): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5373): Added TimaKesytore provider
,D/ConnectivityService(  738): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5392): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5392):  
I/ActivityManager(  738): Killing 4443:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 5392): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5392):  
I/SELinux ( 5392):  
,I/SELinux ( 5392): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5392): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 5392): >>>>> Normal User
,E/dalvikvm( 5392): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 5392): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5392): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5392): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5392): Added TimaKesytore provider
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5392, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 5392): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 5392): ELMEngine.ELMEngine( context ).
,D/elm:14132( 5392): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 5392): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,I/knox    ( 3071): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,W/ContextImpl( 3071): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/elm:14132( 5392): ElmAgentService : onCreate()
D/elm:14132( 5392): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/elm:14132( 5392): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 5392): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14132( 5392): ModuleBase.resetCalllogAPIAlarm()
D/knox    ( 3071): MainReceiver.listeningToTimeDateChanges( context, intent ).
I/knox    ( 3071): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/knox    ( 3071): KNOXAgentService : onCreate()
D/knox    ( 3071): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3071): KNOXAgentService. startJobThread() start
D/knox    ( 3071): KNOXAgentService. JobThread()
D/knox    ( 3071): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3071): KNOXAgentService. startJobThread() wait
,D/elm:14132( 5392): ModuleBase.ModifySetAlarm()
,D/elm:14132( 5392): MDMBridge.getInstance()
,D/elm:14132( 5392): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 5392): ElmAgentService : onDestroy().
,I/SELinux ( 5407): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5407):  
I/ActivityManager(  738): Killing 4460:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/knox    ( 3071): KNOXAgentService : onDestroy().
,D/knox    ( 3071): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 5407): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5407):  
I/SELinux ( 5407):  
,I/SELinux ( 5407): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5407): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5407): >>>>> Normal User
,E/dalvikvm( 5407): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10143 ]
,E/SELinux ( 5407): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5407): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5407): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5407): Added TimaKesytore provider
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5407, uid=10143 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5419): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5419):  
I/ActivityManager(  738): Killing 4473:com.android.musicfx/u0a24 (adj 15): empty #43
,E/SMD     (  233): DCD ON
,I/SELinux ( 5419): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5419):  
I/SELinux ( 5419):  
,I/SELinux ( 5419): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5419): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5419): >>>>> Normal User
,E/dalvikvm( 5419): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
,E/SELinux ( 5419): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5419): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5419): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5419): Added TimaKesytore provider
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5419, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5431): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5431):  
I/ActivityManager(  738): Killing 4506:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty #43
,I/SELinux ( 5431): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5431):  
I/SELinux ( 5431):  
,I/SELinux ( 5431): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5431): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5431): >>>>> Normal User
,E/dalvikvm( 5431): >>>>> com.qualcomm.timeservice [ userId:0 | appId:10168 ]
,E/SELinux ( 5431): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5431): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5431): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5431): Added TimaKesytore provider
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5431, uid=10168 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm( 5431): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x4260f798, skipping init
D/TimeService( 5431): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450109421559
D/        ( 5431): TimeServiceNative: User Time to be set is 1450109421559
D/QC-time-services( 5431): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5431): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 5431): Lib:time_genoff_operation: pargs->ts_val = 1450109421559
D/QC-time-services( 5431): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  278): Daemon: Connection accepted:time_genoff
D/QC-time-services(  278): Daemon: genoff_handler: Process name is omm.timeservice
D/QC-time-services(  278): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450109421559
D/QC-time-services(  278): Daemon:genoff_opr: Base = 2, val = 1450109421559, operation = 0
,D/QC-time-services(  278): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/18/70 8:7:27
D/QC-time-services(  278): Daemon:Value read from RTC seconds = 1498047000
D/QC-time-services(  278): Daemon:new time 1450109421559 
D/QC-time-services(  278): Daemon: delta 1448611374559 genoff 1448611374559 
D/QC-time-services(  278): Daemon:genoff_persistent_update: Writing genoff = 1448611374559 to memory
D/QC-time-services(  278): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  278): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  278): Updating the TOD offset
,D/QC-time-services(  278): Daemon:genoff_persistent_update: Writing genoff = 1448611374559 to memory
D/QC-time-services(  278): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  278): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  278): Daemon:Update to modem bit set
,E/QC-time-services( 5431): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  278): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  278): Daemon: Base = 2, Value being sent to MODEM = 1134144621559
,I/ActivityManager(  738): Killing 4551:com.sec.android.service.health/u0a16 (adj 15): empty #43
E/QC-time-services(  278): Daemon: Time-services: Waiting to acceptconnection
E/QC-time-services(  278): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/daemonapp( 1486): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1486): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1486): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1486): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1486): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1486): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1486): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1486): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1486): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1486): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1486): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1486): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,I/PowerManagerService(  738): [PWL] Off : 75s ago
I/PowerManagerService(  738): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  738): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  738): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=738, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=4788)
,I/PowerManagerService(  738): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10084, pid=5373, ws=null) (elapsedTime=804)
,D/dalvikvm( 1486): GC_CONCURRENT freed 7495K, 47% free 10191K/19040K, paused 10ms+4ms, total 77ms
,D/dalvikvm( 1486): WAIT_FOR_CONCURRENT_GC blocked 39ms
,D/daemonapp( 1486): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1486): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1486): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1486): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/rmt_storage(  284): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7bf3178
I/rmt_storage(  284): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  284): wakelock acquired: 1, error no: 42
I/rmt_storage(  284): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1212207384)
,D/comdaemonstockapp( 1486): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1486): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 1759): Checkin interval check for package: unspecified last checkin: 1449576543959 min interval config: 0 actual interval: 532877781
,I/rmt_storage(  284): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  284): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  284): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1212207384) wakelock released: 1, error no: 0
I/rmt_storage(  284): 
,I/rmt_storage(  284): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7bf3178
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4490): mConnectivityHandler : connected
V/AlarmManager(  738): waitForAlarm result :4
,V/AlarmManager(  738): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
W/PCWCLIENTTRACE_AccountUtil( 4490): [hasSamungAccount] - No Samsung Account
,W/linker  ( 4490): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
I/CSTORAGE( 4490): ================================================
I/CSTORAGE( 4490):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 4490): ================================================
D/dalvikvm( 4490): No JNI_OnLoad found in /system/lib/libterrier.so 0x4260f090, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4490): [GetString-S]
,I/terrier ( 4490): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 4490): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 4490): App is not loaded in QSEE
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  738): stay LED for fully charged
D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/QSEECOMAPI: ( 4490): Loaded image: APP id = 3
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/QSEECOMAPI: ( 4490): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 4490): QSEECom_shutdown_app, app_id = 3
E/terrier ( 4490): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 4490): [GetString-E]
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/PCWCLIENTTRACE_PushUtil( 4490): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4490): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4490): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 4490): [ensureRegistration] - No Samsung account
,D/ContextualEventManager( 1067): removeContextualEvent(): requestClass=com.android.mms
,D/Mms/MessagesLockscreen( 3788): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,D/ContextualEventManager( 1067): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1067): updateContainer()
D/ContextualEventContainer( 1067): update()
D/ContextualEventContainer( 1067): handleUpdate()
D/ContextualEventManager( 1067): getTopEventView()
,D/ContextualEventManager( 1067): getTopContextualEvent()
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 5454): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5454):  
,D/ContextualEventManager( 1067): top view = flightmode
I/KeyguardEffectViewMain( 1067): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1067): getTopEventClass()
,D/ContextualEventManager( 1067): getTopContextualEvent()
D/ContextualEventManager( 1067): !isClockTop
D/ContextualEventManager( 1067): getTopEventClass()
,D/ContextualEventManager( 1067): getTopContextualEvent()
D/ContextualEventManager( 1067): !isClockTop
D/ContextualEventManager( 1067): getTopEventClass()
,D/ContextualEventManager( 1067): getTopContextualEvent()
,D/UsbManager( 1067):  :::: isUsb30Available :: return = false from pid = 1067
,V/AlarmManager(  738): waitForAlarm result :4
,V/AlarmManager(  738): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SecContextualClockFlightMode( 1067): handleUpdateClock()
,D/KeyguardProperties( 1067): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SELinux ( 5454): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5454):  
I/SELinux ( 5454):  
,I/SELinux ( 5454): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5454): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5454): >>>>> Normal User
,E/dalvikvm( 5454): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
,E/SELinux ( 5454): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5454): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5454): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5454): Added TimaKesytore provider
,I/VacuumService( 1220): Vacuum at: now=1450109422121 tag=VacuumService
,D/Finsky  ( 3527): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3527): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5454, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,D/Headlines( 5206): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5206): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5206): Breath 3791 latestRequest time : 1450109418682 current time : 1450109422473
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,E/Watchdog(  738): !@Sync 4
,I/GAV2    ( 5221): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm(  738): GC_EXPLICIT freed 1402K, 61% free 23396K/59020K, paused 32ms+20ms, total 458ms
,I/ActivityManager(  738): Killing 3863:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty #43
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 289, currTemp = 294, prevStep = 4, currStep = 4
,D/CaptivePortalTracker(  738): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  738): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  738): Checking http://216.58.209.78/generate_204
,W/ActivityThread(  738): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/SMD     (  233): DCD ON
,I/System.out(  738): Thread-163(HTTPLog):isShipBuild true
,I/System.out(  738): Thread-163(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker(  738): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  738): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  738): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  738): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  738): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/SSRMv2:SIOP(  738): SIOP:: AP = 310, Delta = -10
,D/PreloadUpdateManagerStateMachine( 4811): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4811): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4811): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4811): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 4811): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4811): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4811): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4811): entry::IDLE
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,I/ActivityManager(  738): Waited long enough for: ServiceRecord{44635ed8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/AmoledAdjustTimer(  738): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = -10
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,V/AlarmManager(  738): waitForAlarm result :4
,V/AlarmManager(  738): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5206): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5206): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5206): Breath 30999 latestRequest time : 1450109418682 current time : 1450109449681
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  233): DCD ON
,D/SyncManager(  738): failed sync operation 
,D/SyncManager(  738): not retrying sync operation because the error is a hard error: 
E/ActivityThread( 1759): Failed to find provider info for com.android.contacts.metadata
,I/PowerManagerService(  738): [PWL] Off : 105s ago
,E/Watchdog(  738): !@Sync 5
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 293, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  738): waitForAlarm result :8
,V/AlarmManager(  738): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  738): waitForAlarm result :4
,V/AlarmManager(  738): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  738): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5206): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/Headlines( 5206): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Headlines( 5206): Breath 61472 latestRequest time : 1450109418682 current time : 1450109480154
,E/SMD     (  233): DCD ON
,E/Watchdog(  738): !@Sync 6
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService(  738): [PWL] Off : 140s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  738): waitForAlarm result :8
,D/Headlines( 5206): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5206): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5206): Breath 90050 latestRequest time : 1450109418682 current time : 1450109508732
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  738): !@Sync 7
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  738): waitForAlarm result :8
,V/AlarmManager(  738): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,E/SMD     (  233): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  738): waitForAlarm result :8
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,D/Headlines( 5206): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5206): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5206): Breath 120040 latestRequest time : 1450109418682 current time : 1450109538722
,D/Headlines( 5206): stop 
,D/Headlines( 5206): Breath.onDestroy : 
,I/ActivityManager(  738): Killing 2834:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/Watchdog(  738): !@Sync 8
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 225s ago
,E/Watchdog(  738): !@Sync 9
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  738): waitForAlarm result :8
,V/AlarmManager(  738): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON

```
