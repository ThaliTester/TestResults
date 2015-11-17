#### Test 50388019c82294c_thali05_HTC-HTC One_M8 Logs


```
--------- beginning of system
I/ActivityManager(  906): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3876 uid=10096 gids={50096, 9997, 1028} abi=armeabi-v7a
--------- beginning of main
D/MediaScanner( 3605):  prescan time: 107ms
D/MediaScanner( 3605):     scan time: 414ms
D/MediaScanner( 3605): postscan time: 1ms
D/MediaScanner( 3605):    total time: 522ms
D/MediaScanner( 3605): -----------------------------------------------------------------
D/MediaScanner( 3605): firstscan(media) time: 309ms
D/MediaScanner( 3605): secondscan(non-media) time: 105ms
D/MediaScanner( 3605):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3605):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3605):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3605):  [Total]    File(Image+Video+Audio+Others) in database : 1533
W/System.err( 3854): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 3854): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 3854): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
W/Atfwd_Sendcmd(  480): AtCmdFwd service not published, waiting... retryCnt : 3
,D/MediaProvider( 3605): [delete][42]
D/MediaProvider( 3605): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 3605): [recoverParentNodes] - 0
D/MediaProvider( 3605): [update][5]
D/MediaScannerServiceEx( 3605): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3605): [updateImage]+
V/SmsReceiverService( 3680): updateNotificationAndShortcutStatus: 
D/MessagingNotification( 3680): New incoming message, can't cancel notification now
D/MessagingNotification( 3680): newMsgCnt: 0, false
D/MediaScannerServiceEx( 3605): [updateImage]-0
D/Process (  906): killProcessQuiet, pid=3373
I/ActivityManager(  906): Start proc com.htc.tiber2 for service com.htc.videohub.ui/com.htc.htcircontrol.HtcIrService: pid=3896 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/Process (  906): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  906): Killing 3373:com.htc.home.personalize/1000 (adj 15): empty #17
D/PMS     (  906): releaseWL(777df1b): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3605): [3] scan finished
D/MediaProviderUtils( 3605): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3605): calcVolumeId: /storage/ext_sd
I/ActivityManager(  906): Recipient 3373
D/MediaProviderUtils( 3605): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3605): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3605): Process mounted intent for unmounted storage: /storage/ext_sd
E/Vold    (  364): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.videohub.ui/cache/
W/Vold    (  364): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3854): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.videohub.ui/cache
E/Vold    (  364): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.videohub.ui/cache/
W/Vold    (  364): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3854): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.videohub.ui/cache
D/Process (  906): killProcessQuiet, pid=3373
W/libprocessgroup(  906): failed to open /acct/uid_1000/pid_3373/cgroup.procs: No such file or directory
D/Process (  906): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/MediaScannerServiceEx( 3605): [disAliveExtStorageRows]+131073
D/PMS     (  906): releaseWL(3aaa6031): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
D/MediaProvider( 3605): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/MediaProvider( 3605): [update][10]#1#
I/WorldClock.Global( 3876): isHEPDevice = true
W/ResourceType( 3896): ResTable_typeSpec entry count inconsistent: given 1, previously 1426
D/PMS     (  906): acquireWL(d5a18e1): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 3876 10096 null
W/ResourcesManager( 3896): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Tiber/HtcIrService( 3896): Created by Thread:1
I/WorldClock.Global( 3876): isHEPDevice = true
I/Tiber/PeelUtils( 3896): Create new PeelUtils
W/ContextImpl(  906): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
I/Tiber/PeelUtils( 3896): loadDB: load data from database
I/HtcStatusBarManagerWrapper( 3896): glow:20
D/MediaProvider( 3605): [update][33]#0#
W/WorldClock.AlarmService( 3876): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
I/WorldClock.AlarmUtils( 3876): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
D/MediaProvider( 3605): [update][32]#0#
I/ActivityManager(  906): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3923 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
D/AntHalService(  906): onCreate() entered
I/IntentController( 1122): receive(com.htc.intent.action.STATUS_BAR_GLOW,1,false)
D/JAntJava(  906): Calling nativeJAnt_Create
D/JAntJava(  906): create: nativeJAnt_Create returned success
D/AntHalService(  906): JAntJava create success
D/AntHalService(  906): onStartCommand() entered
I/Tiber/PeelUtils( 3896): loadDB(), room count : 0
I/Tiber/PeelUtils( 3896): loadDB: load updated data from database finished
I/Tiber/HtcIrService( 3896): Created by Thread:1 finished
I/WorldClock.AlarmUtils( 3876): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 3876): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1122): receive(android.intent.action.ALARM_CHANGED,1,false)
D/MediaScannerServiceEx( 3605): [disAliveExtStorageRows]--1, 0, 0
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33474cb6:true
D/MediaProviderUtils( 3605): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3605): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3605): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3605): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3605): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3605): [disAliveExtStorageRows]+196609
D/BluetoothAdapter( 3854): 444457932: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  906): releaseWL(d5a18e1): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
I/ActivityManager(  906): Killing 3070:com.htc.contacts/u0a40 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3070
D/Process (  906): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  906): Recipient 3070
D/MediaProvider( 3605): [sendStorageAddedIfNeed]: /storage/usb : unmounted
D/MediaProvider( 3605): [update][12]#1#
D/MediaProvider( 3605): [update][3]#0#
I/PhoneStatusBar( 1122): glow(20,0,0)
D/MediaProvider( 3605): [update][30]#0#
D/MediaScannerServiceEx( 3605): [disAliveExtStorageRows]--1, 0, 0
E/cutils-trace( 3913): Error opening trace file: No such file or directory (2)
D/Process (  906): killProcessQuiet, pid=3070
W/libprocessgroup(  906): failed to open /acct/uid_10040/pid_3070/cgroup.procs: No such file or directory
D/Process (  906): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/CIRControlWrapper( 3854): hasIrEmitter = true
D/PMS     (  906): acquireWL(197f4db7): PARTIAL_WAKE_LOCK  TvReminderManager_60 0x1 3854 10091 null
D/PMS     (  906): releaseWL(197f4db7): PARTIAL_WAKE_LOCK  TvReminderManager_60 0x1 null
I/Tiber/HtcIrService( 3896): onDestroy called
I/Tiber/PeelUtils( 3896): Stop CIR service...
D/Tiber/HtcIrService( 3896): If IR had killed, to remove temp data in videocenter_had_killed
D/Process (  906): killProcessQuiet, pid=3390
I/ActivityManager(  906): Killing 3390:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
D/Process (  906): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  906): Recipient 3390
E/UpdateRequestReceiver( 3923): ignoring update request
D/CustomizationManager( 3913): ====startRecUseTime====
D/htc.customization.log.level( 3913):  is 
W/CustomizationLogLevel( 3913): Level value is invalid, use default level 2
I/ActivityManager(  906): Killing 3408:com.htc.mobiledata:remote/u0a48 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3408
D/Process (  906): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  906): Recipient 3408
I/Prism.ItemManager( 1489): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1489): loadItems() com.htc.launcher.pageview.WidgetManager@5014774 +
I/Prism.WidgetManager( 1489): onLoadItems() +
D/CustomizationManager( 3913):  Read ACC file spent 0.042 (s)
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__203
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__405
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__304
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 3913): Parsing tag item name = HTC__002
V/CustomizationCIDLoader( 3913): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3913): Parsing tag category name = system
I/CustomizationCIDLoader( 3913): Parsing tag category name = application
I/CustomizationCIDLoader( 3913): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3913): Parsing tag category name = Settings
I/CustomizationCIDLoader( 3913): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3913): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3913): Parsing tag category name = ACC
D/CustomizationManager( 3913):  Read CID file spent 0.083 (s)
D/CustomizationManager( 3913):  All configurations done spent 0.083 (s)
W/ResourcesManager( 1489): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/ActTriggerJNI( 3913): open library fail.
I/HtcModeClient( 3198): handler message = 4009
I/HtcModeClient( 3198): start to setup the connection
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
E/MP-Decision( 2230): Update arg 2
D/PMS     (  906): acquireHCC(376c0924): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 906 1000 null
E/MP-Decision( 2230): Update arg 4
D/PMS     (  906): acquireHCC(39a10c8d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 906 1000 null
W/asset   (  906): Copying FileAsset 0xb92b1258 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
E/MP-Decision( 2230): Update arg "0 190 240 240".
E/MP-Decision( 2230): Update arg "0 75 400 400".
D/PMS     (  906): acquireWL(bf29390): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
D/Process (  906): killProcessQuiet, pid=3408
W/libprocessgroup(  906): failed to open /acct/uid_10048/pid_3408/cgroup.procs: No such file or directory
I/AnimationUtil(  906): isHTCRecent(HelloWorld/Recent screens.)/5
D/Process (  906): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/Process (  906): killProcessQuiet, pid=3390
W/libprocessgroup(  906): failed to open /acct/uid_10042/pid_3390/cgroup.procs: No such file or directory
D/Process (  906): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
I/FeedHostManager( 1489): [onPause]
I/FeedProviderManager( 1489): onPause
I/FeedHostManager( 1489): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@33e8f45
I/SocialFeedProvider( 1489): +onPause
I/SocialFeedProvider( 1489): -onPause
D/HtcSystemUPManager(  906): HtcSystemUPolicy [canLog (default)] category: launch, enable: true
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3963 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/UpdateRequestReceiver( 3923): ignoring update request
E/UpdateRequestReceiver( 3923): ignoring update request
D/StatusBarManagerService(  906): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  906): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  906): hiding MENU key
E/UpdateRequestReceiver( 3923): ignoring update request
E/UpdateRequestReceiver( 3923): ignoring update request
W/asset   ( 3963): Copying FileAsset 0xb8fc8ca0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
E/UpdateRequestReceiver( 3923): ignoring update request
I/TrimMemoryManager( 1489): [trimMemory] 20
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=3989 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
D/Process (  906): killProcessQuiet, pid=3428
I/ActivityManager(  906): Killing 3428:com.htc.music:mediaplaybackservice/u0a50 (adj 15): empty #17
D/Process (  906): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/art     (  472): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 141us total 10.826ms
I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 136us total 10.610ms
I/ActivityManager(  906): Recipient 3428
I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 135us total 8.961ms
W/ResourcesManager( 1489): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Process (  906): killProcessQuiet, pid=3428
D/Process (  906): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  906): failed to open /acct/uid_10050/pid_3428/cgroup.procs: No such file or directory
I/DeviceManagement( 3989): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=3989 dbg=false s=true
I/DeviceManagement( 3989): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
I/DeviceManagement( 3989): WorkflowService: Starting workflow service
,I/GoogleHttpClient( 1710): GMS http client unavailable, use old client
I/WebViewFactory( 3963): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/DeviceManagement( 3989): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@10141935] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 3989): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3989): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 3989): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3989): ModelRegistry: Loading model meta data from resources...
I/Prism.WidgetManager( 1489): onLoadItems() -
I/Prism.ItemManager( 1489): loadItems() com.htc.launcher.pageview.WidgetManager@5014774 -
I/ActivityManager(  906): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=4010 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DeviceManagement( 3989): BackgroundController: *** Update after boot...
I/DeviceManagement( 3989): SessionStateController: Checking invariants...
I/LibraryLoader( 3963): Time to load native libraries: 8 ms (timestamps 1302-1310)
I/LibraryLoader( 3963): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3963): Binding Chromium to main looper Looper (main, tid 1) {2a4737be}
I/LibraryLoader( 3963): Expected native library version number "",actual native library version number ""
I/chromium( 3963): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3963): Initializing chromium process, singleProcess=true
W/art     ( 3963): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3963): ApplicationContext is null in ApplicationStatus
W/chromium( 3963): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3963): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3963): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3963): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3963): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 3963): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3963): Build Date: 12/11/14 Thu
I/Adreno-EGL( 3963): Local Branch: 
I/Adreno-EGL( 3963): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 3963): Local Patches: NONE
I/Adreno-EGL( 3963): Reconstruct Branch: NOTHING
I/htcbackup-core( 4010): ModelRegistry: Loading model meta data from resources...
D/AutoSetting( 1332): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1332): Util - check NLP state, Allowned:true, Enabled:true
D/AutoSetting( 1332): Util - no network available!
D/AutoSetting( 1332): service - requestNLP() network is not available
I/DeviceManagement( 3989): BackgroundController: Invariants are unchanged.
I/DeviceManagement( 3989): SessionStateController: Checking invariants...
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10f7f731:true
D/BluetoothAdapter( 3963): 1031410609: getState() :  mService = null. Returning STATE_OFF
D/PhoneApp( 1445): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1445): -- N1 =0
D/PhoneApp( 1445): -- N2 =0
D/PhoneApp( 1445): -- N3 =0
I/DeviceManagement( 3989): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm
I/DeviceManagement( 3989): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3989): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 3989): Perf: *** Cache update - start...
I/DeviceManagement( 3989): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 3989): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 3989): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 3989): Perf: Scan enabled apps - start...
W/art     ( 3963): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3963): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3963): CordovaWebView is running on device made by: HTC
W/art     ( 3963): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3963): Attempt to remove local handle scope entry from IRT, ignoring
I/DeviceManagement( 3989): EnabledAppBuilder: Examining 267 installed apps for DM enabled apps...
I/DeviceManagement( 3989): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500050, versionName=6.5.838445
D/Atlas   ( 3963): Validating map...
W/chromium( 3963): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/ResourcesManager( 3989): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/DeviceManagement( 3989): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031392, versionName=6.3.851500
W/ResourcesManager( 3989): Asset path '/system/framework/com.android.future.usb.accessory.jar' does not exist or contains no resources.
I/DeviceManagement( 3989): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444606881, versionName=4.2.848011
I/InputMethodManager( 3963): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@96d7d2b, mServedView=org.apache.cordova.engine.SystemWebView{1a039588 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1a464b21
I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +701ms
I/InputMethodManagerService(  906): Disable input method client, pid=1489
D/StatusBarManagerService(  906): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  906): Enable input method client, pid=3963
D/PMS     (  906): releaseWL(bf29390): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/ResourcesManager( 3989): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/XT9_C   ( 1263): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1263): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1263): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1263): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/DeviceManagement( 3989): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001301, versionName=6.0.847523
W/BindingManager( 3963): Cannot call determinedVisibility() - never saw a connection for the pid: 3963
I/chromium( 3963): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/ResourcesManager( 3989): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/JsMessageQueue( 3963): Set native->JS mode to OnlineEventsBridgeMode
W/ResourcesManager( 3989): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3989): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 3989): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/AndroidProtocolHandler( 3963): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/DeviceManagement( 3989): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001280, versionName=6.5.847469
W/ResourceType( 3989): ResTable_typeSpec entry count inconsistent: given 1, previously 1426
W/ResourcesManager( 3989): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/DeviceManagement( 3989): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.videohub.ui, versionKey=747235e1-123a-48e6-af18-c5967cf0b131, versionCode=250081396, versionName=2.7.845092
W/ResourceType( 3989): ResTable_typeSpec entry count inconsistent: given 2, previously 1426
I/DeviceManagement( 3989): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001212, versionName=1.2.848061
D/jxcore_app_log( 3963): JniHelper::setJavaVM(0xb7f1db98), pthread_self() = -1189593680
D/JX-Cordova( 3963): jxcore cordova android initializing
W/ResourcesManager( 3989): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3989): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/DeviceManagement( 3989): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715
W/ResourcesManager( 3989): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
W/ResourcesManager( 3989): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/jxcore-log( 3963): Initializing JXcore engine
W/jxcore-log( 3963): JXcore engine is ready
W/jxcore-log( 3963): Starting JXcore engine
W/ResourcesManager( 3989): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 3989): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
I/DeviceManagement( 3989): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001186, versionName=2.2.821083
I/DeviceManagement( 3989): EnabledAppBuilder: Found 9 DM enabled apps.
I/DeviceManagement( 3989): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 3989): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/DeviceManagement( 3989): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/art     (  906): Explicit concurrent mark sweep GC freed 27558(1349KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 912us total 64.893ms
I/DeviceManagement( 3989): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 3989): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity
I/DeviceManagement( 3989): EnabledAppController: Nothing appears to have changed for appID=com.htc.videohub.ui
I/DeviceManagement( 3989): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns
I/DeviceManagement( 3989): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
I/DeviceManagement( 3989): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
I/DeviceManagement( 3989): Perf: Scan enabled apps - complete: 663 ms
I/DeviceManagement( 3989): Perf: *** Enabled app cache update - complete: 664 ms
I/DeviceManagement( 3989): Perf: *** Config cache update - start...
I/DeviceManagement( 3989): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 3989): ConfigCacheController: *** Device manifest update is pending...
I/DeviceManagement( 3989): ConfigCacheController: *** Sending device manifest...
W/jxcore-log( 3963): Platform android
W/jxcore-log( 3963): 
W/jxcore-log( 3963): Process ARCH arm
W/jxcore-log( 3963): 
I/jxcore-log( 3963): JXcore Cordova bridge is ready!
I/jxcore-log( 3963): 
W/jxcore-log( 3963): JXcore engine is started
E/jxcore-log( 3963): >> HTC-HTC One_M8
E/jxcore-log( 3963): 
I/jxcore-log( 3963): Total memory 1912020992
I/jxcore-log( 3963): 
I/jxcore-log( 3963): Free memory 175271936
I/jxcore-log( 3963): 
I/jxcore-log( 3963): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3963): 
I/jxcore-log( 3963): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3963): 
I/jxcore-log( 3963): userPath [ 'www' ]
I/jxcore-log( 3963): 
I/jxcore-log( 3963): Size 1080 1776
I/jxcore-log( 3963): 
I/jxcore-log( 3963): Screen Brightness 142
I/jxcore-log( 3963): 
E/jxcore-log( 3963): Dummy Error Log.
E/jxcore-log( 3963): 
I/art     ( 3989): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
I/art     ( 3989): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
W/System.err( 3989): Starting the internal HTTP client
I/DeviceManagement( 3989): DeviceClientResource: Active network...
I/DeviceManagement( 3989):   No active network
I/DeviceManagement( 3989): DeviceClientResourceController: Network is unavailable: code=1010 description=There is no active network.
I/DeviceManagement( 3989): BackgroundController: *** Network unavailable!
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=1, flag=1, pid=3989, uid=10105, userID:0
I/DeviceManagement( 3989): Perf: *** Config cache update - complete: 262 ms
I/DeviceManagement( 3989): Perf: *** Cache update - complete: 927 ms
I/DeviceManagement( 3989): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@10141935]
I/DeviceManagement( 3989): WorkflowService: Stopping workflow service
,I/jxcore-log( 3963): getBuffer is called!!!!
I/jxcore-log( 3963): 
,D/PMS     (  906): releaseHCC(376c0924): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  906): releaseHCC(39a10c8d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
E/MP-Decision( 2230): Update arg 1,
,I/HtcModeClient( 3198): handler message = 4011,
,E/HtcModeClient( 3198): Check connection and retry 2 times.,
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{14a747bf u0 com.google.android.gms/.gcm.GcmService},
,D/PMS     (  906): releaseWL(18d85bcf): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,V/AlarmManager(  906): sending alarm PendingIntent{74002aa: PendingIntentRecord{108d1e9b com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1447782160339, Int=0,
,I/iu.UploadsManager( 1929): End new media; added: 0, uploading: 0, time: 74 ms,
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  906): disable(): mBluetooth = null mBinding = false
D/WifiService(  906): New client listening to asynchronous messages
W/Settings:Agent(  906): MONITOR_LOG
W/Settings:Agent(  906): name: bluetooth_on
W/Settings:Agent(  906): value: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1533
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  906): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  906): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
D/WifiService(  906): setWifiEnabled: false pid=3963, uid=10380
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:7403)
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
I/WifiService(  906): isSprintWifiRestricted(): false
W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:379)
I/WifiService(  906): isMdmWifiRestricted(): false
W/System.err(  906): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:625)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 5(ms)
D/BluetoothManagerService(  906): Message: MESSAGE_DISABLE
E/WifiTrafficPoller(  906): ADD_CLIENT: 6
D/WifiManager( 3963): setWifiEnabled: Base Package Name=com.example.hello, uid=10380
W/Settings:Agent(  906): MONITOR_LOG
W/Settings:Agent(  906): name: wifi_on
W/Settings:Agent(  906): value: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
,W/Settings:Agent(  906): Process.myTid(): 1492
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  906): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  906): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:7503),
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  906): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1134)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:454),
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 6(ms)
I/jxcore-log( 3963): ****TEST TOOK:  5056  ms ****
I/jxcore-log( 3963): 
I/jxcore-log( 3963): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3963): 
,E/cutils-trace( 4085): Error opening trace file: No such file or directory (2),
,D/CustomizationManager( 4085): ====startRecUseTime====
,D/htc.customization.log.level( 4085):  is 
W/CustomizationLogLevel( 4085): Level value is invalid, use default level 2
,D/CustomizationManager( 4085):  Read ACC file spent 0.042 (s)
,D/CIDMapFileReader( 4085): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 4085): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 4085): Parsing tag item name = HTC__102
,D/CIDMapFileReader( 4085): Parsing tag item name = HTC__203
D/CIDMapFileReader( 4085): Parsing tag item name = HTC__405
D/CIDMapFileReader( 4085): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4085): Parsing tag item name = HTC__304,
D/CIDMapFileReader( 4085): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4085): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4085): Parsing tag item name = HTC__J15,
D/CIDMapFileReader( 4085): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4085): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4085): Parsing tag item name = HTC__A48
,D/CIDMapFileReader( 4085): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 4085): Parsing tag item name = HTC__002
,V/CustomizationCIDLoader( 4085): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4085): Parsing tag category name = system
,I/CustomizationCIDLoader( 4085): Parsing tag category name = application,
,I/CustomizationCIDLoader( 4085): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4085): Parsing tag category name = Settings,
I/CustomizationCIDLoader( 4085): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4085): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4085): Parsing tag category name = ACC,
,D/CustomizationManager( 4085):  Read CID file spent 0.087 (s)
D/CustomizationManager( 4085):  All configurations done spent 0.087 (s)
,E/ActTriggerJNI( 4085): open library fail.,
,D/PackageManager(  906): deletePackageAsUser: pkg=com.example.hello, pid=4085, uid=2000 userid=0,
,D/Process (  906): killProcessQuiet, pid=3963
I/ActivityManager(  906): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg,
I/ActivityManager(  906): Killing 3963:com.example.hello/u0a380 (adj 0): stop com.example.hello
,D/Process (  906): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 ,
,I/ActivityManager(  906): Recipient 3963,
,I/WindowState(  906): WIN DEATH: Window{20fdbbb4 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  906): Client connection lost with reason: 4
,W/PackageSettings(  906): Skipping PackageSetting{287e614b com.test.thalitest/10373} due to missing metadata,
,W/ActivityManager(  906): Force removing ActivityRecord{1d737e42 u0 com.example.hello/.MainActivity t27}: app died, no saved state
,E/MP-Decision( 2230): Update arg "0 380 380 380".,
E/MP-Decision( 2230): Update arg "0 400 400 400".
,W/ActivityManager(  906): Spurious death for ProcessRecord{124b7238 3963:com.example.hello/u0a380}, curProc for 3963: null
,I/ActivityManager(  906): Force stopping com.example.hello appid=10380 user=0: pkg removed
,D/DotMatrix( 1193): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1193): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1193): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,D/PMS     (  906): acquireWL(163ce211): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1688 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  906): releaseWL(163ce211): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
I/FeedHostManager( 1489): [onResume]
I/FeedProviderManager( 1489): onResume
D/StatusBarManagerService(  906): setSystemUiVisibility(0x700)
I/SocialFeedProvider( 1489): +onResume
D/StatusBarManagerService(  906): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SocialFeedProvider( 1489): updateAccounts - Accounts is no change
D/StatusBarManagerService(  906): hiding MENU key
I/SocialFeedProvider( 1489): -onResume
I/ConnectivityHelper( 1489): [getCurrentConnectionType] no network connection
I/Prism.ItemManager( 1489): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1489): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PhoneApp( 1445): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/AccTypeManager( 1591): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1591): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/art     (  906): Explicit concurrent mark sweep GC freed 11833(989KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 16MB/24MB, paused 932us total 110.180ms
I/art     (  906): WaitForGcToComplete blocked for 96.841ms for cause Explicit
,E/ExternalAccountType( 1591): Unsupported attribute readOnly
,I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 3963 uid 10380,
D/StatusBarManagerService(  906): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  906): Enable input method client, pid=1489
,D/StatusBarManagerService(  906): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  906): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  906): hiding MENU key
,W/PackageManager(  906): Unable to load service info ResolveInfo{3490bcf1 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  906): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,I/art     (  906): Explicit concurrent mark sweep GC freed 4209(228KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.434ms total 102.255ms
,W/asset   (  906): Copying FileAsset 0xb9296e40 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,W/ResourcesManager(  906): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  906): Killing 3445:com.htc.musicenhancer/u0a51 (adj 15): empty #17,
D/Process (  906): killProcessQuiet, pid=3445
D/Process (  906): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,D/JobSchedulerService(  906): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  906): Recipient 3445,
,D/Process (  906): killProcessQuiet, pid=3445
,D/Process (  906): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  906): failed to open /acct/uid_10051/pid_3445/cgroup.procs: No such file or directory
,D/TaskPersister(  906): removeObsoleteFile: deleting file=27_task.xml
,W/OpenGLRenderer( 1489): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{1b0e196e u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/HtcModeClient( 3198): handler message = 4011,
E/HtcModeClient( 3198): Check connection and retry 3 times.,
,I/Prism.ItemManager( 1489): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1489): loadItems() com.htc.launcher.pageview.WidgetManager@5014774 +
I/Prism.WidgetManager( 1489): onLoadItems() +
,W/ResourcesManager( 1489): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 1489): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Prism.WidgetManager( 1489): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1489): onLoadItems() -
I/Prism.ItemManager( 1489): loadItems() com.htc.launcher.pageview.WidgetManager@5014774 -

```
