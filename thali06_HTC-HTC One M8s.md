#### Test 6170335106d974e_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
I/[FDDMI]BootCompletedReceiver( 3119): BootCompletedReceiver :android.intent.action.BOOT_COMPLETED
D/OtaStartupReceiver( 1493): onReceive: android.intent.action.BOOT_COMPLETED
W/HtcActiveEngineManager(  974): Can't find out the target sensor
E/WifiStateMachine(  974): handleMessage: E msg.what=131206
E/WifiStateMachine(  974): processMsg: InitialState
E/WifiStateMachine(  974):  InitialState CMD_BOOT_COMPLETED 0 0
E/WifiStateMachine(  974): processMsg: DefaultState
E/WifiStateMachine(  974):  DefaultState CMD_BOOT_COMPLETED 0 0
E/WifiStateMachine(  974): handleMessage: X
D/UsbnetService(  974): BroadcastReceiver::onReceive+
D/UsbnetService(  974): onReceive ACTION_BOOT_COMPLETED
D/UsbnetService(  974): BroadcastReceiver::onReceive-
D/UsbnetService(  974): UsbnetHandler::handleMessage+:4
D/UsbnetService(  974): MESSAGE_BOOT_COMPLETED+
D/WIFI    (  974): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI    (  974):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  974): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
--------- beginning of system
D/ConnectivityService(  974): Got NetworkFactory Messenger for WIFI
D/ConnectivityService(  974): NetworkFactory connected
W/ContextImpl(  974): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
E/WifiStateMachine(  974): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/Process (  974): killProcessQuiet, pid=2446
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ContextImpl(  974): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1473 com.android.server.backup.BackupManagerService.notifyBackupEnabled:10562 com.android.server.backup.BackupManagerService.access$3400:164 com.android.server.backup.BackupManagerService$BootCompleteReceiver.onReceive:10549 android.app.LoadedApk$ReceiverDispatcher$Args.run:950 
I/ActivityManager(  974): Killing 2446:com.htc.sense.news/u0a74 (adj 15): empty #17
D/UsbnetService(  974): systemReady+
,I/ActivityManager(  974): Recipient 2446
D/WifiService(  974): updateDevicePolicy Exchange policy allowWifiStatus = 1
D/WifiService(  974): updateDevicePolicy Exchange policy allowInternetSharingStatus = 1
D/UsbnetService(  974): systemReady-
D/ConnectivityService(  974): Got NetworkFactory Messenger for usbnet
D/UsbnetService(  974): UsbnetHandler::handleMessage-
D/ConnectivityService(  974): NetworkFactory connected
D/usbnet  (  974): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/usbnet  (  974):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  974): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
I/ActivityManager(  974): Start proc com.htc.autobot for broadcast com.htc.autobot/.UsbReceiver: pid=3171 uid=10047 gids={50047, 9997, 3003, 3002, 3001, 5003, 1024} abi=arm64-v8a
D/MediaProvider( 3142): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
D/MediaProvider( 3142): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 3142): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 3142): [MP][DEBUG] Storage State: removed
D/MediaProvider( 3142): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/MediaProvider( 3142): [MP][DEBUG] Storage State: removed
D/UsbReceiver( 3171): onReceiver android.intent.action.BOOT_COMPLETED
D/HtcModeClient( 3171): power connected, start service
E/SQLiteLog( 3142): (283) recovered 69 frames from WAL file /data/data/com.android.providers.media/databases/external.db-wal
I/ActivityManager(  974): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=3196 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/DotMatrix( 2125): [CoverService] onDestroy, version: 1.3
D/Utils   ( 3171): CMD:getprop ro.htc.htcmode.socket.type
I/System  ( 3171): exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.util.Utils.systemCmd:34)
I/SensorManager( 2125): unregisterListenerImpl++: listener = com.htc.dotmatrix.CoverService$7@62657e9
W/SensorService(  974): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  974): disable: get sensor name = CM36686 Proximity sensor
W/SensorService(  974): pid=2125, uid=10041
W/SensorService(  974): Active sensors: size = 3
W/SensorService(  974): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  974): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  974): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  974): SensorService::listenerSensor++: mName = com.htc.dotmatrix.CoverService$7@62657e9, eanble = 0, strlen(mName) = 40
W/SensorService(  974): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  974): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@136b7597
W/SensorService(  974): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3c669aae
W/SensorService(  974): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 2125): [CoverService] unregisterCallContentObserver()
D/Process (  974): killProcessQuiet, pid=2125
I/ActivityManager(  974): Killing 2125:com.htc.dotmatrix/u0a41 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/HtcModeClient( 3171): sSocketMode = LocalSocket
D/HtcModeClient( 3171): start the htcmodeservice thread
D/HtcModeClient( 3171): initCanAgent
I/CANMesgAgentLocalSocket( 3171): CANAgent Id = 0
E/cutils-trace( 3169): Error opening trace file: Permission denied (13)
D/HtcModeClient( 3171): sense info: version = none, id = 2
D/HtcModeClient( 3171): display info: width = 1080, height = 1776
D/HtcModeClient( 3171): display info: mode = 10
D/CustomizationManager( 3169): ====startRecUseTime====
D/htc.customization.log.level( 3169):  is 
W/CustomizationLogLevel( 3169): Level value is invalid, use default level 2
D/CustomizationManager( 3169):  Read ACC file spent 0.030 (s)
D/CIDMapFileReader( 3169): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3169): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3169): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3169): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3169): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3169): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3169): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3169): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 3169): Parsing tag category name = system
I/CustomizationCIDLoader( 3169): Parsing tag category name = application
I/CustomizationCIDLoader( 3169): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3169): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3169): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3169): Parsing tag category name = Settings
I/CustomizationCIDLoader( 3169): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3169): add string-array item, value = 42507
I/CustomizationCIDLoader( 3169): add string-array item, value = 21902
I/CustomizationCIDLoader( 3169): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 3169): add string-array item, value = 23420
I/CustomizationCIDLoader( 3169): add string-array item, value = 22299
I/CustomizationCIDLoader( 3169): add string-array item, value = 24002
I/CustomizationCIDLoader( 3169): add string-array item, value = 23210
I/CustomizationCIDLoader( 3169): add string-array item, value = 23205
I/CustomizationCIDLoader( 3169): add string-array item, value = 23806
I/CustomizationCIDLoader( 3169): add string-array item, value = 23430
I/CustomizationCIDLoader( 3169): add string-array item, value = 23408
I/CustomizationCIDLoader( 3169): add string-array item, value = 27205
I/CustomizationCIDLoader( 3169): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 3169): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 3169): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 3169): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 3169): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 3169): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 3169): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 3169): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 3169): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 3169): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 3169): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 3169): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 3169):  Read CID file spent 0.065 (s)
D/CustomizationManager( 3169):  All configurations done spent 0.065 (s)
I/Prism.ItemManager( 1538): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1538): loadItems() com.htc.launcher.pageview.WidgetManager@3fbb9d3b +
I/Prism.WidgetManager( 1538): onLoadItems() +
E/libprocessgroup(  974): failed to kill 1 processes for processgroup 2125
I/ActivityManager(  974): Recipient 2125
D/PMS     (  974): acquireWL(231ad9a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 974 1000 WorkSource{1000}
V/AlarmManager(  974): sending alarm PendingIntent{efdec10: PendingIntentRecord{246a9309 android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=38838, Int=0
D/PMS     (  974): acquireHCC(30a056c5): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 974 1000 null
D/PMS     (  974): acquireHCC(3013281a): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 974 1000 null
I/ActivityManager(  974): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 3169 on display 0
D/HtcModeClient( 3171): onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
W/asset   (  974): Copying FileAsset 0x555d76dfa0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/HtcModeClient( 3171): connectState: BT_TURNON_BYME = false
D/HtcModeClient( 3171): connectState: CONNECTION_READY = false
D/HtcModeClient( 3171): connectState: ENABLE_PROJECTBYAPP = false
D/HtcModeClient( 3171): connectState: ENTER_PROJECTMODE = false
D/HtcModeClient( 3171): connectState: PHONE_PULGIN = false
D/HtcModeClient( 3171): connectState: Force_AWAKE = false
D/HtcModeClient( 3171): connectState: PHONE_PULGIN = true
D/HtcModeClient( 3171): connectState: POWERCONNECTED_READY = true
D/PMS     (  974): acquireWL(ab49a41): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 974 1000 null
W/ResourcesManager( 1538): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/FeedHostManager( 1538): [onPause]
I/FeedProviderManager( 1538): onPause
I/AnimationUtil(  974): isHTCRecent(HelloWorld/Recent screens.)/12
I/FeedHostManager( 1538): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@11169787
I/SocialFeedProvider( 1538): +onPause
I/SocialFeedProvider( 1538): -onPause
D/Process (  974): killProcessQuiet, pid=2601
I/ActivityManager(  974): Killing 2601:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  974): Recipient 2601
W/ContextImpl( 3196): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.powersaver.PowerSaverNotificationReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
W/HtcSystemUPManager(  974): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  974): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3243 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  974): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=3263 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/PowerSaverNotificationService( 3196): updateNotification, mToggle = false
D/StatusBarManagerService(  974): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  974): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  974): hiding MENU key
D/Process (  974): killProcessQuiet, pid=2914
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  974): Killing 2914:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
W/asset   ( 3243): Copying FileAsset 0xac0e3ba8 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/ResourcesManager( 1538): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/TrimMemoryManager( 1538): [trimMemory] 20
I/ActivityManager(  974): Recipient 2914
W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 3
W/asset   ( 1538): Copying FileAsset 0x555d6ff770 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
D/PhoneApp( 1493): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1493): -- N1 =0
D/PhoneApp( 1493): -- N2 =0
D/PhoneApp( 1493): -- N3 =0
I/Prism.WidgetManager( 1538): onLoadItems() -
I/Prism.ItemManager( 1538): loadItems() com.htc.launcher.pageview.WidgetManager@3fbb9d3b -
W/ResourcesManager( 3263): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/WebViewFactory( 3243): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/CalendarApplication( 3263): onCreate
D/AlertReceiver( 3263): beginStartingService
D/PMS     (  974): acquireWL(161d7b35): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3263 10010 null
D/PMS     (  974): acquireWL(2615cbca): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 2049 10011 null
D/PMS     (  974): releaseWL(2615cbca): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 null
D/DFPI.PIReciver( 2983): onReceiver action:android.intent.action.BOOT_COMPLETED
D/DFPI    ( 2983): getInstance = com.htc.demoflopackageinstaller.ApkInstallHelper@62657e9
W/CustomizationIntentService( 1652): failed at default contact creation!
W/CustomizationIntentService( 1652): java.lang.SecurityException: Requesting code from com.htc.contacts (with uid 10038) to be run in process android.process.acore (with uid 10013)
W/CustomizationIntentService( 1652): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1793)
W/CustomizationIntentService( 1652): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1768)
W/CustomizationIntentService( 1652): 	at android.app.ContextImpl.createPackageContextAsUser(ContextImpl.java:2266)
W/CustomizationIntentService( 1652): 	at android.app.ContextImpl.createPackageContext(ContextImpl.java:2253)
W/CustomizationIntentService( 1652): 	at android.content.ContextWrapper.createPackageContext(ContextWrapper.java:658)
W/CustomizationIntentService( 1652): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.handleIntentInternal(CustomizationIntentService.java:143)
W/CustomizationIntentService( 1652): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.onHandleIntent(CustomizationIntentService.java:104)
W/CustomizationIntentService( 1652): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/CustomizationIntentService( 1652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/CustomizationIntentService( 1652): 	at android.os.Looper.loop(Looper.java:155)
W/CustomizationIntentService( 1652): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/CustomizationIntentService( 1652): handleIntentInternal(): action = com.htc.intent.action.PRELOAD_CONTACTS, original action = android.intent.action.BOOT_COMPLETED, launched by: null
W/CustomizationIntentService( 1652): AFH Enable: false, LEONCHAME: false
W/CustomizationIntentService( 1652): hasBeenInit true
W/CustomizationIntentService( 1652): isNewChameleonHFASupported false
W/CustomizationIntentService( 1652): isHFA true
W/CustomizationIntentService( 1652): setupWizRun 1
D/HtcAlertService( 3263): start to updateAlertNotification!
D/DFPI    ( 2983): set install APK prefrence is false
I/LibraryLoader( 3243): Time to load native libraries: 14 ms (timestamps 9678-9692)
I/LibraryLoader( 3243): Expected native library version number "",actual native library version number ""
D/HtcAlertService( 3263): No fired or scheduled alerts
D/HtcAlertUtils( 3263): -- cancelReminderNotification --
D/HtcAlertUtils( 3263): broadcastExistReminder!
D/DotMatrix( 1319): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  974): releaseWL(161d7b35): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
W/AlertReceiver( 3263): stopSelfResult true
I/ActivityManager(  974): Killing 2936:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=2936
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
V/WebViewChromiumFactoryProvider( 3243): Binding Chromium to main looper Looper (main, tid 1) {1dea4f0f}
I/LibraryLoader( 3243): Expected native library version number "",actual native library version number ""
I/chromium( 3243): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3243): Initializing chromium process, singleProcess=true
W/art     ( 3243): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3243): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  974): Recipient 2936
W/chromium( 3243): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3243): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3243): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3243): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3243): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 3243): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 3243): Build Date: 03/09/15 Mon
I/Adreno-EGL( 3243): Local Branch: 
I/Adreno-EGL( 3243): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 3243): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 3243):                  d74aa161a12b9c6fc6332151
I/ActivityManager(  974): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=3302 uid=10020 gids={50020, 9997, 1028, 1015} abi=arm64-v8a
W/System.err(  974): java.lang.Throwable: stack dump
W/System.err(  974): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  974): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  974): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  974): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  974): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  974): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a458a3:true
D/BluetoothAdapter( 3243): 304784776: getState() :  mService = null. Returning STATE_OFF
D/FlexNetS( 2049): setNetMode:0, false
D/FlexNetS( 2049): set2gLowSignalEnablePref: false
V/FlexNetS( 2049): [DRX] setHigherPowerIn2GPref to: true
D/FlexNetS( 2049): setSimCardisWhiteList: false
V/FlexNetS( 2049): setSimCardCamp3GNetworkSignalPref to: false
D/FlexNetS( 2049): setCampNetworkisBlackList: false
V/FlexNetS( 2049): [DRX] setHigherPowerIn2GPref to: true
W/art     ( 3243): Attempt to remove local handle scope entry from IRT, ignoring
D/FlexNetS( 2049): updateSvcAllowedInSettings:false
V/FlexNetS( 2049): setRilHandOverW2GEnable: 0
W/AwContents( 3243): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3243): CordovaWebView is running on device made by: HTC
D/Process (  974): killProcessQuiet, pid=2957
I/ActivityManager(  974): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3341 uid=10026 gids={50026, 9997} abi=arm64-v8a
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  974): Killing 2957:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
I/ActivityManager(  974): Recipient 2957
,W/art     ( 3243): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3243): Attempt to remove local handle scope entry from IRT, ignoring
,V/OneTimeInitializerReceiver( 3341): OneTimeInitializerReceiver.onReceive,
,V/OneTimeService( 3341): OneTimeService.onHandleIntent
,W/chromium( 3243): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.partnersetup, clsName=com.google.android.partnersetup.PhoneStateReceiver, state=1, flag=1, pid=2763, uid=10027, userID:0,
,D/FindExtension( 3243): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ActivityManager(  974): Start proc com.htc.video for broadcast com.htc.video/.videowidget.videoDMC.DLNAReceiver: pid=3376 uid=10029 gids={50029, 9997, 3002, 3003, 1028, 1015, 1023, 2001} abi=arm64-v8a,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=2763, uid=10027, userID:0,
,I/InputMethodManager( 3243): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@239680b8, mServedView=org.apache.cordova.engine.SystemWebView{89d0e91 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1a7591f6,
I/InputMethodManagerService(  974): Disable input method client, pid=1538
I/PhoneStatusBar( 1233): setImeWindowStatus(false,false)
D/StatusBarManagerService(  974): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  974): Enable input method client, pid=3243,
,W/XT9_C   ( 1367): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,I/XT9_C   ( 1367): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1367): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1367): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/PMS     (  974): releaseWL(ab49a41): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  974): Displayed com.example.hello/.MainActivity: +1s71ms
,D/PMS     (  974): acquireWL(3b1f20e7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(3b1f20e7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,W/BindingManager( 3243): Cannot call determinedVisibility() - never saw a connection for the pid: 3243,
,D/PMS     (  974): acquireWL(2d998b3d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(2d998b3d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): acquireWL(20fb0f32): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
I/chromium( 3243): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/PMS     (  974): releaseWL(20fb0f32): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/Process (  974): killProcessQuiet, pid=1735
I/ActivityManager(  974): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=3407 uid=10031 gids={50031, 9997, 3003} abi=arm64-v8a
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  974): Killing 1735:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/JsMessageQueue( 3243): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  974): Recipient 1735
,E/AndroidProtocolHandler( 3243): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/RlzPingService( 2763): Setting next ping for 1457962900404
,D/PMS     (  974): acquireWL(2ac6ec7e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(2ac6ec7e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/jxcore_app_log( 3243): JniHelper::setJavaVM(0xaaf768f8), pthread_self() = -1406615648
,D/PMS     (  974): acquireWL(3a3545df): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
,D/Process (  974): killProcessQuiet, pid=3007
I/ActivityManager(  974): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=3430 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  974): Killing 3007:com.htc.task/u0a69 (adj 15): empty #17
D/PMS     (  974): releaseWL(3a3545df): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,W/jxcore-log( 3243): Initializing JXcore engine
W/jxcore-log( 3243): JXcore engine is ready
,I/ActivityManager(  974): Recipient 3007
,W/jxcore-log( 3243): Starting JXcore engine,
,W/jxcore-log( 3243): Platform android
W/jxcore-log( 3243): 
,W/jxcore-log( 3243): Process ARCH arm
W/jxcore-log( 3243): 
,I/jxcore-log( 3243): JXcore Cordova bridge is ready!,
I/jxcore-log( 3243): 
W/jxcore-log( 3243): JXcore engine is started
,E/jxcore  ( 3243): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js,
E/jxcore  ( 3243): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,E/Personalize.BootComple_( 3430): onReceive() + Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.home.personalize/.receiver.BootCompleteInitializer (has extras) }
E/Personalize.BootComple_( 3430): action android.intent.action.BOOT_COMPLETED
,D/PMS     (  974): acquireWL(be1528a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
E/Personalize.Utilities( 3430): SimpleLauncher not found: com.htc.simplelauncher
D/PMS     (  974): releaseWL(be1528a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.htc.home.personalize, clsName=com.htc.home.personalize.SimpleModeEntryActivity, state=2, flag=1, pid=3430, uid=1000, userID:0
,E/Personalize.BootComple_( 3430): initialize: false
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.htc.simplelauncher, clsName=null, state=2, flag=0, pid=3430, uid=1000, userID:0
,D/FindExtension( 3243): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
E/Personalize.Utilities( 3430): setApplicationEnabled IllegalArgumentException com.htc.simplelauncher
,V/BootCompletedReceiver( 2785): ensureAndExecuteUserProfiling: ensureAndExecuteUserProfiling 
,D/PeopleYouKnow( 2785): receive intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.contacts/.peopleyouknow.PeopleYouKnowReceiver (has extras) }
,I/ActivityManager(  974): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=3453 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
I/ActivityManager(  974): Killing 3033:com.android.settings/1000 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=3033
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  974): Explicit concurrent mark sweep GC freed 28179(1890KB) AllocSpace objects, 53(3MB) LOS objects, 33% free, 15MB/23MB, paused 1.337ms total 144.783ms,
,I/ActivityManager(  974): Recipient 3033
,D/PMS     (  974): acquireWL(16d260fb): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1818 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  974): releaseWL(16d260fb): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseHCC(30a056c5): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  974): releaseHCC(3013281a): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null,
,D/Process (  974): killProcessQuiet, pid=2647
I/ActivityManager(  974): Killing 2647:com.htc.showme/u0a81 (adj 15): empty #17
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,V/HtcDataRoamingWidget.DisableWidgetReceiver( 3453): ACTION_BOOT_COMPLETED
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.dataroaming, clsName=com.htc.rosiewidgets.dataroaming.HtcSettingWidgetProvider, state=1, flag=1, pid=3453, uid=10040, userID:0
,I/ActivityManager(  974): Recipient 2647
,D/Process (  974): killProcessQuiet, pid=2714
I/ActivityManager(  974): Killing 2714:com.htc.sense.browser/u0a9 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,V/HtcDataStripWidget.DisableWidgetReceiver( 3453): ACTION_BOOT_COMPLETED,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.datastrip, clsName=com.htc.rosiewidgets.datastrip.HtcSettingWidgetProvider, state=1, flag=1, pid=3453, uid=10040, userID:0
,I/ActivityManager(  974): Recipient 2714
,D/Process (  974): killProcessQuiet, pid=2812,
I/ActivityManager(  974): Killing 2812:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 2812
,D/Process (  974): killProcessQuiet, pid=3119
I/ActivityManager(  974): Killing 3119:com.futuredial/u0a82 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  974): Recipient 3119,
,D/DotMatrix( 1319): [EventReceiver] onReceive, version:1.3,
,I/ActivityManager(  974): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3474 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager(  974): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=3497 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 3002, 3001, 2001, 1023} abi=armeabi-v7a,
,W/ResourcesManager( 3497): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.,
,D/Process (  974): killProcessQuiet, pid=3095,
I/ActivityManager(  974): Killing 3095:com.android.keychain/1000 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 3095
,D/MediaSessionHelper( 3497): Attempting to get helper with context android.app.ReceiverRestrictedContext@346a022,
V/AlarmManager(  974): sending alarm PendingIntent{fed4ac4: PendingIntentRecord{2c68bdad com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=42224, Int=0
V/AlarmManager(  974): sending alarm PendingIntent{3331a8e2: PendingIntentRecord{2e65f473 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1457348400000, Int=86400000
,D/MediaSessionService(  974): Created session for package com.htc.music with tag MediaSessionHelper-com.htc.music,
,D/MediaSessionHelper( 3497): addMediaButtonListener added PendingIntent{1ac3870: android.os.BinderProxy@2628bab3}
,I/ActivityManager(  974): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=3521 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
I/ActivityManager(  974): Killing 3196:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=3196
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  974): Recipient 3196
,D/Process (  974): killProcessQuiet, pid=3263,
,I/ActivityManager(  974): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3543 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  974): Killing 3263:com.htc.calendar/u0a10 (adj 15): empty #17
,I/art     (  407): Explicit concurrent mark sweep GC freed 8676(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 289us total 31.925ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 227us total 26.796ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 346us total 26.100ms,
,I/ActivityManager(  974): Recipient 3263,
,W/ContextImpl( 3543): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 3543): MY_DEBUG = false,
,W/ContextImpl( 3543): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncServiceReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 3543): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,V/AlarmManager(  974): sending alarm PendingIntent{242164cf: PendingIntentRecord{16092e5c com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457358102642, Int=0,
,W/ContextImpl( 3543): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 3543): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.startService:208 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.onHandleIntent:71 android.app.IntentService$ServiceHandler.handleMessage:65 ,
D/HtcAppUPService( 1456): CustomizationReceiver  receieve: android.intent.action.BOOT_COMPLETED
,I/[PluginManager]RegisterService( 1456): onHandleIntent, action: android.intent.action.BOOT_COMPLETED, data: null
D/HtcAppUPService( 1456): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.BOOT_COMPLETED cmp=com.htc.sense.hsp/.upservice.HtcUPService }, this = com.htc.sense.hsp.upservice.HtcUPService@19549cc7
,D/AutoSetting( 1456): receiver - intent: android.intent.action.BOOT_COMPLETED
,I/WSP     ( 1456): [Receiver] EVENT - BOOT COMPLETED, is settings existed? true
,D/HtcAppUPService( 1456): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.BOOT_COMPLETED,
I/ActivityManager(  974): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=3575 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a
D/WeatherUtility( 1233): Weather sync is On
W/WeatherTimeKeeper( 1233): [refreshWeatherData] no weather data
,D/AutoSetting( 1456): service - onStartCommand() action: com.htc.app.autosetting.bootcomplete
D/AutoSetting( 1456): service - onStartCommand() boot completed, remove cache
,D/AutoSetting( 1456): service - onStartCommand() REMOVE current location bundle
,D/Process (  974): killProcessQuiet, pid=2983
I/ActivityManager(  974): Killing 2983:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/AutoSetting( 1456): service - handleMessage() setting current location null
D/AutoSetting( 1456): service - handleMessage() removing cache
,D/AutoSetting( 1456): service - AddressCache: clean up all cache
,D/HtcAppUPService( 1456): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
,W/Bundle  ( 1456): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
,W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/FeatureList( 1456): feature
D/FeatureList( 1456): type
D/FeatureList( 1456): description
,W/Bundle  ( 1456): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1456): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1456): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102),
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
,W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1456): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1456): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source),
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1456): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1456): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1456): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
,W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1456): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
,I/ActivityManager(  974): Recipient 2983
,W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1456): Attempt to cast generated internal exception:
,W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1456): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
,W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1456): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1456): Attempt to cast generated internal exception:
W/Bundle  ( 1456): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1456): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1456): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1456): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/HtcAppUPService( 1456): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
,V/BootReceiver( 3575): onReceive: android.intent.action.BOOT_COMPLETED,
D/BootReceiver( 3575): boot completed:
,D/BootReceiver( 3575): isValid:  isEnabledEasyAccess = true, isEnabledQuickDial = true
,D/BootReceiver( 3575): Valid,
D/BootReceiver( 3575): startService:
,I/ActivityManager(  974): Start proc com.htc.HTCSpeaker:ngfservice for service com.htc.HTCSpeaker/.NGFService: pid=3596 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  974): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=3615 uid=10058 gids={50058, 9997, 1028, 1015, 1023} abi=arm64-v8a,
D/Process (  974): killProcessQuiet, pid=3142
I/ActivityManager(  974): Killing 3142:android.process.media/u0a17 (adj 15): empty #17,
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/PluginProvider( 1456): Begin Apply Batch
,E/PluginProvider( 1456): conflict when insert feature, ignored
,I/ActivityManager(  974): Recipient 3142,
,D/NGFService( 3596): onCreate +++
,D/SettingUtils( 3596): getProcessNormalFlag: true
,D/NGFService( 3596): onCreate last time crash or 1st run=false
D/SettingUtils( 3596): setProcessNormalFlag: false
,D/NGFService( 3596): getAudioStreamType: ScoOn =false
,D/SoundEffects( 3596): init +++ 3
,W/LMW     ( 3615): [3645][ActionDeviceStorageHandler] onActionBootComplete++
I/ActivityManager(  974): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3646 uid=10063 gids={50063, 9997, 1028, 3003} abi=arm64-v8a
,W/LMW     ( 3615): [3645][ActionDeviceStorageHandler] onActionBootComplete--
,I/ActivityManager(  974): Killing 3302:com.htc.fm/u0a20 (adj 15): empty #17
,D/Process (  974): killProcessQuiet, pid=3302
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/AudioCache(  400): Heap size overflow! req size: 1058400, max size: 1048576,
,W/NuPlayerRenderer(  400): AudioSink write short frame count 0 < 9824
,I/ActivityManager(  974): Recipient 3302,
,D/PluginProvider( 1456): apply Batch success
,I/ActivityManager(  974): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=3711 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 5001, 1024} abi=arm64-v8a
,I/ActivityManager(  974): Killing 2049:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=2049
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/[PluginManager]RegisterService( 1456): Notify Carousel that a new TabPlugin has been installed!
,D/NGFLanguageMgr( 3596): LanguageFromSystem: language:en  country:gb
D/NGFLanguageMgr( 3596): language package name = preload_package
,I/NMT     ( 3596): NMT version: 1.6.1-B006 REL,
D/NGFService( 3596): Audio Dump Folder: Elvis = /data/data/com.htc.HTCSpeaker/files/htcspeak_elvis, PCM = /data/data/com.htc.HTCSpeaker/files/htcspeak_pcm,
,I/ActivityManager(  974): Recipient 2049
,D/NGFService( 3596): applyCurrentSystemLanguage +++,
D/NGFService( 3596): grammar support language:[United States English, Taiwanese Mandarin, Chinese Mandarin, German, Latin American Spanish, European Spanish, European French, Italian, British English, Japanese, Canadian French, Chinese Cantonese, Danish, Greek, Finnish, Dutch, Norwegian, Polish, Brazilian Portuguese, European Portuguese, Russian, Swedish, Australian English, Turkish]
D/NGFLanguageMgr( 3596): LanguageFromSystem: language:en  country:gb
D/NGFService( 3596): Elvis language uses the language: 2
D/NGFService( 3596): setCurrentNGFLanguageMgr: Language = 2, CurrentLanguage = 0
D/NGFService( 3596): setCurrentNGFLanguageMgr: set language = British English
D/NGFService( 3596): bluetoothInitialize +++
,W/System.err(  974): java.lang.Throwable: stack dump
D/BluetoothManagerService(  974): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  974): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/BluetoothManagerService(  974): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3673e460:true
W/System.err(  974): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  974): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  974): 	at android.os.Binder.execTransact(Binder.java:454)
,D/NGFService( 3596): cloud_init +++
D/NGFLanguageMgr( 3596): getCloudServerDNSName: language = 2, DNS name = cc.nvc.engb.nuancemobility.net
,D/MediaProvider( 3711): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
,D/MediaProvider( 3711): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 3711): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 3711): [MP][DEBUG] Storage State: removed
D/MediaProvider( 3711): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/MediaProvider( 3711): [MP][DEBUG] Storage State: removed,
,D/NGFService( 3596): elvisInitalize +++,
,E/SQLiteLog( 3711): (283) recovered 69 frames from WAL file /data/user/0/com.android.providers.media/databases/external.db-wal,
,D/MediaScannerReceiver( 3711): onReceive Intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.media/.MediaScannerReceiver (has extras) },
,D/MediaProviderUtils( 3711): [startScan]volume:internal, action:android.intent.action.MEDIA_MOUNTED
,D/MediaProviderUtils( 3711): [startScan]volume:external, action:android.intent.action.MEDIA_MOUNTED
,D/NGFService( 3596): elvisInitalize lang = British English
D/NGFService( 3596): elvisInitalize: Freq Type:16000
,D/NGFService( 3596): tts_init +++,
D/NGFLanguageMgr( 3596): getVocalizerFolderName: language = 2, folder name = vocalizer_eng
,D/NGFLanguageMgr( 3596): LanguageFromSystem: language:en  country:gb,
D/NGFLanguageMgr( 3596): language package name = preload_package
,D/NGFService( 3596): load vocalizer language = British English,
,E/NGFService( 3596): registerObserver
,D/NGFService( 3596): onCreate: Battery Level Remaining: 100%
,D/NGFService( 3596): onStartCommand(): service start
D/NGFService( 3596): onStartCommand() action = com.htc.HTCSpeaker.NGFService.QuickCall
D/NGFService( 3596): QuickCall
,W/NMT-OemFile( 3596): fopen(): Failed to open file sysdct.dat
,W/NMT-OemFile( 3596): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
,W/NMT     ( 3596): Fail to open read-stream for file generic.lst,
,D/MediaScannerServiceEx( 3711): Action not in map, volume = internal, action = android.intent.action.MEDIA_MOUNTED
W/NMT-OemFile( 3596): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
D/MediaScannerServiceEx( 3711): Action not in map, volume = external, action = android.intent.action.MEDIA_MOUNTED
D/PMS     (  974): acquireWL(235ee651): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3711 10017 null
,W/NMT-OemFile( 3596): fopen(): Failed to open file sysdct.dat
,W/NMT-OemFile( 3596): fopen(): Failed to open file sysdct.dat
,W/NMT-OemFile( 3596): fopen(): Failed to open file clm.dat
,D/NGFService( 3596): Elvis is initialization Success
,D/NGFService( 3596): bElvisInitializeCompleted = true
D/NGFService( 3596): GrammarState = 0
D/NGFService( 3596): loadGrammar +++
D/NGFService( 3596): loadGrammar asr_grammar
,D/MtpReceiver( 3711): [MTP][handleUsbStateAsync]+
,I/NGFService( 3596): GrammarDepot contains a valid Elvis Grammar0
D/NGFService( 3596): loadGrammar from cache
D/MtpReceiver( 3711): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3711): [MTP][handleUsbState]+
,W/NMT     ( 3596): Fail to open read-stream for file elvisBritish Englishname.lst
,W/NMT     ( 3596): Fail to open read-stream for file elvisBritish Englishartist.lst,
,W/NMT     ( 3596): Fail to open read-stream for file elvisBritish Englishplaylist.lst,
I/ActivityManager(  974): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=3757 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
W/NMT     ( 3596): Fail to open read-stream for file elvisBritish Englishsong.lst
W/NMT     ( 3596): Fail to open read-stream for file elvisBritish Englishalbum.lst
W/NMT     ( 3596): Fail to open read-stream for file elvisBritish Englishgeneric.lst,
D/MediaScanner( 3711): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
D/MediaProvider( 3711): bindService() MTP Service Connection.
,D/MtpReceiver( 3711): [MTP][scanExternalVolumeIfNeed] scan external volume
,D/MtpReceiver( 3711): [MTP][handleUsbState]-
D/MtpReceiver( 3711): [MTP][handleMessage]-
,W/NMT-OemFile( 3596): fopen(): Failed to open file daniel_userdct_eng.dat
,D/MtpService( 3711): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpService( 3711): addStorageInternal without MtpServer
,D/MtpService( 3711): [MTP][onCreate]-
,E/SQLiteLog( 3711): (283) recovered 67 frames from WAL file /data/user/0/com.android.providers.media/databases/internal.db-wal
,I/ActionCombine( 3711): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/MtpService( 3711): [MTP] startForeground,
I/HtcModeClient( 3171): handler message = 4011
E/HtcModeClient( 3171): Check connection and retry 1 times.,
D/MtpService( 3711): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 3711): TotalSize=1886532,MediaCacheLimit=6000
D/DotMatrix( 1319): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/PMS     (  974): acquireWL(2ba7166): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2151 10024 null
,D/MtpService( 3711): starting MTP server in MTP mode
,D/MtpService( 3711): addStorageInternal 65537 /storage/emulated/0
,D/SettingUtils( 3596): setProcessNormalFlag: true
D/NGFService( 3596): RebuildListener constraintList size 17
,D/NGFService( 3596): RebuildListener: onComplete0
D/NGFService( 3596): onComplete GRAMMAR_STATE_DEFAULT
D/NGFService( 3596): switchScenario: htc_screen_140_19
D/NGFService( 3596): Activated grammar scenario [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3596): Activated grammar constraintNames [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3596): Loading grammar completed.
D/NGFService( 3596): update contact cache completed
D/SettingUtils( 3596): set Updatge Contact Cache: false
,D/MtpService( 3711): [checkStorageState] Storage state - mounted,
I/RemoteViews( 1233): apply : com.android.providers.media 0 13 2 36
D/MtpDatabase( 3711): [MTP][addStorage] iHostType =2,
D/MtpService( 3711): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
,W/HtcWrapAdjustableCursorFactory( 3757): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 3757): onCreate
,I/RemoteViews( 1233): apply : com.android.providers.media 0 13 1 51,
V/GetPrviateResource( 3757): GetPrviateResource
,V/GetPrviateResource( 3757): GetPrviateResource
,D/MessageCustFlag( 3757): sense_version=6.0,
D/BTAccessoryUtil( 3757): createReceiver
,D/BTAccessoryUtil( 3757): registerReceiver return intent = null
,D/MessageCustFlag( 3757): sku_id=118
,D/HtcBuildUtils( 3757): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3757): Cannot find qct_8960_interface, use default value instead
,V/MmsSystemEventReceiver( 3757): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) }
,I/iu.UploadsManager( 2151): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400,
,D/ExchangePolicystatus( 3757): onReceive()
D/ExchangePolicystatus( 3757): onReceive(): ACTION_BOOT_COMPLETED
,D/MessageUtils( 3757): Text messaging allow status = allow
D/Messaging( 3757): EAS allow SMS !!!
D/ExchangePolicystatus( 3757): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
D/Messaging( 3757): EAS allow SMS !!!
,W/MediaScanner( 3711): Error opening directory '/oem/media/', skipping: No such file or directory.
,W/MediaScanner( 3711): Error opening directory '/oem/media/', skipping: No such file or directory.,
I/ActivityManager(  974): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=3794 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/MediaScanner( 3711):  prescan time: 128ms
D/MediaScanner( 3711):     scan time: 34ms
,D/MediaScanner( 3711): postscan time: 0ms
D/MediaScanner( 3711):    total time: 162ms
D/MediaScanner( 3711): -----------------------------------------------------------------
D/MediaScanner( 3711): firstscan(media) time: 19ms
D/MediaScanner( 3711): secondscan(non-media) time: 10ms
D/MediaScanner( 3711):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3711):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3711):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3711):  [Total]    File(Image+Video+Audio+Others) in database : 339
D/PMS     (  974): acquireWL(3b33abf9): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 3757 10064 null
,I/art     (  408): Explicit concurrent mark sweep GC freed 8694(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 248us total 18.820ms
,V/SmsReceiverService( 3757): onStart: #1, @304784776,
I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 226us total 14.351ms
,E/MediaScannerService( 3711): [handleMessage] --- Should not be here, ignore request. ----
E/MediaScannerService( 3711): [onStartCommand] --- Should not be here, redirect request. ----
V/SmsReceiverService( 3757): action: android.intent.action.BOOT_COMPLETED
D/SmsReceiverService( 3757): isCbm: false
D/SmsReceiverService( 3757): isDiscard: false
,D/SettingsManager( 3757): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@15746b9c
,V/SmsReceiverService( 3757): handleBootCompleted
I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 235us total 14.653ms
,W/ResourcesManager( 3757): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/AccFlag ( 1493): sku_id=118
I/iu.UploadsManager( 2151): End new media; added: 0, uploading: 0, time: 97 ms
D/PMS     (  974): releaseWL(2ba7166): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,D/SmsReceiverService( 3757): OutBoxSize = 0
,D/SmsReceiverService( 3757): sendFirstQueuedMessage start: 0
,D/MessageCustFlag( 3757): sku_id=118
D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1493): sku_id=118
,D/MessageCustFlag( 3757): sku_id=118
,D/MediaProvider( 3711): [delete][81],
D/MediaProvider( 3711): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/SmsReceiverService( 3757): sendFirstQueuedMessage end cnt> 0
D/SpaceBufferUtil( 3757): > createBufferFile()
D/SpaceBufferUtil( 3757): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
D/SpaceBufferUtil( 3757): < createBufferFile()
D/MediaProvider( 3711): [recoverParentNodes] - 0
D/MediaProvider( 3711): [update][19]
D/MediaScannerServiceEx( 3711): [scan] Recover Parent Node is finished!
D/PMS     (  974): releaseWL(235ee651): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
E/MediaScannerServiceEx( 3711): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3711): [ServiceHandler][handleMessage] , action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3711): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3711): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3711): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3711): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3711): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3711): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 3711): [update][8]#0#
D/MediaProvider( 3711): [update][3]#0#
,D/MediaProvider( 3711): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3711): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3711): [update][13]#1#
,D/MediaScannerServiceEx( 3711): [AliveExtStorageRows]-0, 0
,E/cutils-trace( 3819): Error opening trace file: Permission denied (13)
I/dex2oat ( 3819): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 3819): dex2oat: override thread count:4
,I/art     (  974): Explicit concurrent mark sweep GC freed 11182(590KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 15MB/23MB, paused 2.072ms total 145.389ms,
D/PMS     (  974): acquireWL(3713699f): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3711 10017 null,
D/MediaScanner( 3711): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,V/AlarmManager(  974): sending alarm PendingIntent{2d6c9aec: PendingIntentRecord{2cfa0eb5 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=44666, Int=0
,I/dex2oat ( 3819): dex2oat took 671.612ms (threads: 4),
,I/PushClient( 3794): ApplicationMonitor {9c81b21}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 3794): ApplicationMonitor {9c81b21}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 3794): ApplicationMonitor {9c81b21}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 3794): ApplicationMonitor {9c81b21}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 3794): ApplicationMonitor {9c81b21}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 3794): ApplicationMonitor {9c81b21}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 3794): ApplicationMonitor {9c81b21}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 3794): ApplicationMonitor {9c81b21}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 3794): ApplicationMonitor {9c81b21}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/ActivityManager(  974): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3826 uid=10076 gids={50076, 9997} abi=arm64-v8a
,I/PushClient( 3794): String {2b182068}: handleBroadcast(): Schedule update on boot completed.
,D/Process (  974): killProcessQuiet, pid=3341,
,I/ActivityManager(  974): Killing 3341:com.google.android.onetimeinitializer/u0a26 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 3341,
,D/SMSBackup( 3826): Got ACTION_BOOT_COMPLETED event
,D/SMSBackup( 3826): setCheckAlarm
,D/SMSBackup( 3826): Next check is scheduled at 60s from now
,D/Process (  974): killProcessQuiet, pid=3376
I/ActivityManager(  974): Killing 3376:com.htc.video/u0a29 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  974): Recipient 3376,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1493, uid=1001, userID:0,
,I/ActivityManager(  974): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=3849 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/[AppShowMeDebug]BootCompletedReceiver( 3849): received boot complete
,I/[AppShowMeDebug]BootCompletedReceiver( 3849): push flag is false, skip check,
I/ActivityManager(  974): Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=3872 uid=10083 gids={50083, 9997, 1007, 3003, 1028} abi=arm64-v8a
,D/Process (  974): killProcessQuiet, pid=2763
,I/ActivityManager(  974): Killing 2763:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/MediaScanner( 3711):  prescan time: 546ms,
D/MediaScanner( 3711):     scan time: 585ms,
D/MediaScanner( 3711): postscan time: 2ms
D/MediaScanner( 3711):    total time: 1133ms
D/MediaScanner( 3711): -----------------------------------------------------------------,
D/MediaScanner( 3711): firstscan(media) time: 259ms
D/MediaScanner( 3711): secondscan(non-media) time: 326ms
D/MediaScanner( 3711):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3711):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0,
D/MediaScanner( 3711):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3711):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,D/MediaProvider( 3711): [delete][12],
D/MediaProvider( 3711): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3711): [recoverParentNodes] - 0,
D/MediaProvider( 3711): [update][5]
D/MediaScannerServiceEx( 3711): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3711): [updateImage]+
,D/MediaScannerServiceEx( 3711): [updateImage]-0,
,I/ActivityManager(  974): Recipient 2763
,I/HtcModeClient( 3171): handler message = 4009
I/HtcModeClient( 3171): start to setup the connection
,D/PMS     (  974): releaseWL(3713699f): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 3711): [2] scan finished
D/MediaProviderUtils( 3711): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3711): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3711): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3711): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1,
,W/MediaScannerServiceEx( 3711): Process mounted intent for unmounted storage: /storage/ext_sd
,D/MediaScannerServiceEx( 3711): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3711): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3711): [update][9]#1#
,D/Process (  974): killProcessQuiet, pid=3407
,I/ActivityManager(  974): Killing 3407:com.htc.csrecommend/u0a31 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 3407
,D/MediaProvider( 3711): [update][33]#0#,
D/MediaScannerServiceEx( 3711): [disAliveExtStorageRows]--1, 0
,D/MediaProviderUtils( 3711): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3711): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3711): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3711): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3711): Process mounted intent for unmounted storage: /storage/usb
,D/MediaScannerServiceEx( 3711): [disAliveExtStorageRows]+196609
,D/MyReportAgent( 3872): PolicyReceiver  receieve: android.intent.action.BOOT_COMPLETED
,D/MediaProvider( 3711): [sendStorageAddedIfNeed]: /storage/usb : unmounted,
,D/MediaProvider( 3711): [update][8]#1#,
,D/MyReportAgent( 3872): DatabaseHelper [DatabaseHelper constructor],
,D/MyReportAgent( 3872): PolicyStore [Init] Get cached policy bundle
,D/MyReportAgent( 3872): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE
,I/ActivityManager(  974): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3894 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a,
D/MediaProvider( 3711): [update][33]#0#
D/MediaScannerServiceEx( 3711): [disAliveExtStorageRows]--1, 0
,E/MediaScannerServiceEx( 3711): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3711): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3711): [handleExternalVolume] ext storage
,D/MediaProviderUtils( 3711): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3711): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3711): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3711): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3711): [AliveExtStorageRows]+65537, 11223344
,D/MyReportAgent( 3872): ReportServiceHandler on boot complete event 
,D/MediaProvider( 3711): [update][6]#0#,
,D/MediaProvider( 3711): [update][2]#0#
,D/MediaProvider( 3711): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3711): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3711): [update][4]#1#
,D/MediaScannerServiceEx( 3711): [AliveExtStorageRows]-0, 0
,D/PMS     (  974): acquireWL(14cd5b84): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3711 10017 null
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.htc.feedback, clsName=com.htc.feedback.reportagent.receiver.PowerConnectedReceiver, state=2, flag=1, pid=3872, uid=10083, userID:0
V/MyReportAgent( 3872): ReportServiceHandler unregister the PowerConnected Listener
,D/MediaScanner( 3711): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
I/ActivityManager(  974): Killing 3430:com.htc.home.personalize/1000 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=3430
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 3430,
,D/Messaging( 3757): supportCMAS(SIE)/init? false/true
,D/MmsConfig( 3757): networkCode: 
,D/MmsConfig( 3757): SIE smsPri: null
D/MmsConfig( 3757): networkCode: 
,D/MmsConfig( 3757): packageName: com.htc.vvm.att does not exist
,D/Messaging( 3757): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 3757): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 3757): ,
D/MmsAsyncWorkHandler( 3757): HM tk = 20001
D/ReportIndicatorCache( 3757): MSG_QUERY_REPORTS >>,
,D/DraftCache( 3757): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 3757): [DraftCache/1] refresh
,D/MmsConfig( 3757): networkCode: 
,I/Messaging( 3757): mccmnc> 
,D/Messaging( 3757): ViewCache CreatePreloadOnlyConversationList,
,D/MessageCustFlag( 3757): sense_version=6.0,
,D/Jerry   ( 3757): start to preload cursor >>>>>>>,
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1493): sku_id=118
,D/DraftCache( 3757): [DraftCache/91] rebuildCache
,D/UpdaterAPK | UpdaterBootCompleteReceiver( 3894): onReceive() - start htcCheckinService
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/MmsSmsV2Provider( 1493):  slotId = -1000
D/MmsSmsV2Provider( 1493): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 3757): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3757): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 3757): createReceiver
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/MmsSmsV2Provider( 1493):  slotId = -1000
D/MmsSmsV2Provider( 1493): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/MmsSmsV2Provider( 1493):  slotId = -1000
,I/htcCheckinService(  974): htcCheckinProvider V2.1,
D/htcCheckinService(  974): htcCheckinService() the mIsServiceRunning = true
I/htcCheckinService(  974): Checkin service onCreate()!
,D/Messaging( 3757): ViewCache CreatePreload
,I/ActivityManager(  974): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3927 uid=10090 gids={50090, 9997, 1028} abi=arm64-v8a
D/Messaging( 3757): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/Jerry   ( 1493): URI_DRAFT
,D/htcCheckinService(  974): onStartCommand()
,D/htcCheckinService(  974): onStartCommand() the action name = null
D/htcCheckinService(  974): InitThread start
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49,
D/DraftCache( 3757): hasDraft() = false mNeedNotifyChange = true
D/MmsSmsV2Provider( 1493):  slotId = -1000
D/Cust_MMSMS( 3757): _has_set_default_values_2=true
D/MmsSmsV2Provider( 1493): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/DraftCache( 3757): [DraftCache/91] rebuildCache time: 9
D/MmsAsyncWorkHandler( 3757): 
D/MmsAsyncWorkHandler( 3757): HM tk = 20002
D/Messaging( 3757): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MsgPreferenceUtils( 3757): def_index: 0
D/MsgPreferenceUtils( 3757): globalIndex = 1
,D/TelephUtils( 1493): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 64,
I/ActivityManager(  974): Killing 2785:com.htc.contacts/u0a38 (adj 15): empty #17
V/MmsProvider( 1493): Update uri=content://mms, match=0
,V/MmsProvider( 1493): selection=st=129 AND m_type!=134
D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1493):  slotId = -1000
D/MmsSmsV2Provider( 1493): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 3757): Reset downloading state: 0
V/MmsSystemEventReceiver( 3757): TransactionService is going to be woken up.
D/Process (  974): killProcessQuiet, pid=2785
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/Messaging( 3757): mNeedToUpdateDate2: false
,D/MsgPreferenceUtils( 3757): phone state: true
D/MsgPreferenceUtils( 3757): sd state: false
,D/MsgPreferenceUtils( 3757): vIndex = 0
,I/ActivityManager(  974): Recipient 2785,
,V/TransactionService( 3757): 1-Creating TransactionService
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/PMS     (  974): acquireWL(158b8957): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 3927 10090 null
D/AccFlag ( 1493): sku_id=118
,V/TransactionService( 3757): onStartCommand: 1
D/MmsSystemEventReceiver( 3757): unRegisterForConnectionStateChanges
V/TransactionService( 3757): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 3757): Loading previous transactions.
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49,
D/AccFlag ( 1493): sku_id=118
D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1493): device_type: 1
W/ContextImpl(  974): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
I/WorldClock.Global( 3927): isHEPDevice = true
W/ContextImpl(  974): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
,D/TransactionService( 3757): Force clearing mTransactionList
D/TransactionService( 3757): Force set service start id to 1
V/TransactionService( 3757): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 3757): unRegisterForConnectionStateChanges
,I/ActivityManager(  974): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3968 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a
,D/TransactionService( 3757): stopSelfResult: true, mLastHandledServiceId: 1,
V/TransactionService( 3757): Destroying TransactionService
,V/TransactionService( 3757): 4-Handling incoming message: { when=0 what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,W/SystemReader( 3927): Cannot find support_china_sense_feature, use default value instead
,W/WorldClock.AlarmService( 3927): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
,I/WorldClock.AlarmUtils( 3927): saveSupportOffAlarmInPreference: isSupport = false
,I/WorldClock.AlarmUtils( 3927): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 3927): Cancel any alarm from alarm manager,
,I/WorldClock.AlarmUtils( 3927): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1233): receive(android.intent.action.ALARM_CHANGED,1,false)
,I/WorldClock.AlarmService( 3927): isDeviceEncryptionEnabled = false,
,D/PMS     (  974): releaseWL(158b8957): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null,
,I/ActivityManager(  974): Killing 2209:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=2209
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  974): Recipient 2209,
,I/WorldClock.AlarmUtils( 3927): isDeviceEncryptionEnabled = false,
,I/WorldClock.AlarmUtils( 3927): Calculate next off alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmService( 3927): resetStopwatchToDefault,
,I/WorldClock.DmdCmd( 3927): This version is general off mode alarm function
,W/WorldClock.DmdCmd( 3927): Conn: fail e = java.io.IOException: No such file or directory
,E/UpdateRequestReceiver( 3968): ignoring update request,
,E/UpdateRequestReceiver( 3968): ignoring update request
,E/UpdateRequestReceiver( 3968): ignoring update request,
,E/UpdateRequestReceiver( 3968): ignoring update request,
,I/WorldClock.AlarmService( 3927): resetTimerToDefault
,E/UpdateRequestReceiver( 3968): ignoring update request
,E/UpdateRequestReceiver( 3968): ignoring update request
,I/ActivityManager(  974): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=4007 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
D/Process (  974): killProcessQuiet, pid=3453
I/ActivityManager(  974): Killing 3453:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 ,
,I/ActivityManager(  974): Recipient 3453,
,D/AutoSetting( 1456): service - mRequestRunnable: screen on delay 10s, request NLP now,
D/AutoSetting( 1456): Util - check NLP state, Allowned:false, Enabled:false,
D/AutoSetting( 1456): service - requestNLP() NetworkLocationProvider not enabled
,D/MediaScanner( 3711):  prescan time: 104ms,
D/MediaScanner( 3711):     scan time: 837ms
D/MediaScanner( 3711): postscan time: 3ms
D/MediaScanner( 3711):    total time: 944ms
D/MediaScanner( 3711): -----------------------------------------------------------------
D/MediaScanner( 3711): firstscan(media) time: 467ms,
D/MediaScanner( 3711): secondscan(non-media) time: 370ms
D/MediaScanner( 3711):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
,D/MediaScanner( 3711):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3711):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3711):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,D/MediaProvider( 3711): [delete][6],
D/MediaProvider( 3711): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3711): [recoverParentNodes] - 0,
D/MediaProvider( 3711): [update][5]
D/MediaScannerServiceEx( 3711): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3711): [updateImage]+
I/DeviceManagement( 4007): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4007 dbg=false s=true
,I/DeviceManagement( 4007): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
,D/MediaScannerServiceEx( 3711): [updateImage]-0,
,I/DeviceManagement( 4007): WorkflowService: Starting workflow service
,D/PMS     (  974): releaseWL(14cd5b84): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 3711): [3] scan finished
I/DeviceManagement( 4007): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@1c86cd2b] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 4007): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 4007): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 4007): BootCompletedWorkflow: ==================================================
D/MediaProviderUtils( 3711): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3711): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3711): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3711): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3711): Process mounted intent for unmounted storage: /storage/ext_sd
,D/MediaScannerServiceEx( 3711): [disAliveExtStorageRows]+131073
,I/DeviceManagement( 4007): ModelRegistry: Loading model meta data from resources...,
,D/MediaProvider( 3711): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3711): [update][14]#1#
,I/GoogleHttpClient( 1926): GMS http client unavailable, use old client,
,I/ActivityManager(  974): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=4031 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/DeviceManagement( 4007): BackgroundController: *** Update after boot...
,I/DeviceManagement( 4007): SessionStateController: Checking invariants...
D/MediaProvider( 3711): [update][30]#0#
D/MediaScannerServiceEx( 3711): [disAliveExtStorageRows]--1, 0
,D/MediaProviderUtils( 3711): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3711): calcVolumeId: /storage/ext_sd,
D/MediaProviderUtils( 3711): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3711): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3711): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3711): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3711): [sendStorageAddedIfNeed]: /storage/usb : unmounted,
,D/MediaProvider( 3711): [update][8]#1#
I/art     (  407): Explicit concurrent mark sweep GC freed 8623(365KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 190us total 31.288ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 153us total 23.221ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 167us total 21.940ms
,D/MediaProvider( 3711): [update][54]#0#,
,D/MediaScannerServiceEx( 3711): [disAliveExtStorageRows]--1, 0,
,I/DeviceManagement( 4007): BackgroundController: Invariants are unchanged.,
,I/htcbackup-core( 4031): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4007): SessionStateController: Checking invariants...
,I/ActivityManager(  974): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4060 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,V/SmsReceiverService( 3757): updateNotificationAndShortcutStatus: 
,D/MessagingNotification( 3757): New incoming message, can't cancel notification now,
D/MessagingNotification( 3757): newMsgCnt: 0, false
I/DeviceManagement( 4007): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
I/DeviceManagement( 4007): ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup],
D/Process (  974): killProcessQuiet, pid=3474
I/ActivityManager(  974): Killing 3474:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActionCombine( 4031): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,I/DeviceManagement( 4007): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,I/DeviceManagement( 4007): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/ActivityManager(  974): Recipient 3474,
,I/ActionCombine( 1319): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/PMS     (  974): releaseWL(3b33abf9): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
,D/DotMatrix( 1319): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/DotMatrix( 1319): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix,
I/DeviceManagement( 4007): Perf: *** Cache update - start...
,I/DeviceManagement( 4007): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 4007): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 4007): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 4007): Perf: Scan enabled apps - start...
,I/RemoteViews( 1233): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1233): apply : com.htc.backup 4 15 5 38
I/RemoteViews( 1233): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1233): setHTCTheme(com.htc.backup,true,33751145),
,I/RemoteViews( 1233): apply : com.htc.backup 0 6 3 5
I/RemoteViews( 1233): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1233): apply : com.htc.backup 0 2 2 5
I/RemoteViews( 1233): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1233): apply : com.htc.backup 1 2 1 5
I/RemoteViews( 1233): apply : com.htc.backup 0 13 20 50
,I/ActivityManager(  974): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4087 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a,
D/Process (  974): killProcessQuiet, pid=3497
I/ActivityManager(  974): Killing 3497:com.htc.music:mediaplaybackservice/u0a48 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/DeviceManagement( 4007): EnabledAppBuilder: Examining 270 installed apps for DM enabled apps...
,I/DeviceManagement( 4007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500100, versionName=6.5.853822
,W/ResourcesManager( 4007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/DeviceManagement( 4007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031464, versionName=6.3.860159
,I/DeviceManagement( 4007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444607021, versionName=4.2.857167
,I/ActivityManager(  974): Recipient 3497
,W/ResourcesManager( 4007): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  974): Explicit concurrent mark sweep GC freed 15878(760KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.312ms total 155.591ms,
I/DeviceManagement( 4007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658011289, versionName=7.00.515351
,W/ResourcesManager( 4007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResetNotifyBootCompleteReceiver( 1493): userSerialNumber = 0,
D/ResetNotifyBootCompleteReceiver( 1493): Receive bootcomplete intent
D/ResetNotifyBootCompleteReceiver( 1493): isOwnerUser = true
,I/ActivityManager(  974): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4111 uid=10155 gids={50155, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/HtcCupdXmlParser( 4087): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory),
,D/ActivityThread( 4087): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,W/ResourcesManager( 4007): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4007): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 4007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/DeviceManagement( 4007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001316, versionName=6.5.860193
,W/ResourceType( 4007): ResTable_typeSpec entry count inconsistent: given 2, previously 1426,
,I/DeviceManagement( 4007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001224, versionName=1.2.853019
,I/HtcCupdXmlParser( 4087): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,W/ResourcesManager( 4007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/AlarmManager(  974): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  974): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  974): [AlarmQueuing] init alarm queuing list
,D/QXDM2SD:HtcNative( 1493): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true,
I/ActivityManager(  974): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4134 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,W/ResourcesManager( 4007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/DeviceManagement( 4007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715
I/ActivityManager(  974): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4155 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  974): Killing 3521:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=3521
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 4007): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4007): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4007): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4007): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.,
,I/DeviceManagement( 4007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001208, versionName=2.2.848686
,I/ActivityManager(  974): Recipient 3521,
,I/DeviceManagement( 4007): EnabledAppBuilder: Found 8 DM enabled apps.
,I/DeviceManagement( 4007): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
,I/DeviceManagement( 4007): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
,I/DeviceManagement( 4007): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,I/DeviceManagement( 4007): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
,I/DeviceManagement( 4007): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity
,I/DeviceManagement( 4007): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns
,I/DeviceManagement( 4007): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend,
,I/DeviceManagement( 4007): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm,
,I/DeviceManagement( 4007): Perf: Scan enabled apps - complete: 704 ms,
,I/DeviceManagement( 4007): Perf: *** Enabled app cache update - complete: 707 ms
,I/DeviceManagement( 4007): Perf: *** Config cache update - start...
,I/DeviceManagement( 4007): ConfigCacheController: *** Updating config cache...,
I/DeviceManagement( 4007): ConfigCacheController: *** Updating stale config cache entries...
,I/art     ( 4007): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>,
I/art     ( 4007): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,W/System.err( 4007): Starting the internal HTTP client
,I/DeviceManagement( 4007): ConfigCacheController: Getting config update from server: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs/versions/c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17/cid/MDoxOjIwMTQtMDEtMDlUMDQ6MTI6MjQuMjMxWg
,I/AlarmManager(  974): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@2b5d7dc2
,I/DeviceManagement( 4007): DeviceClientResource: Active network...,
I/DeviceManagement( 4007):   No active network
,I/DeviceManagement( 4007): DeviceClientResourceController: Network is unavailable: code=1010 description=There is no active network.
,I/DeviceManagement( 4007): BackgroundController: *** Network unavailable!,
I/AlarmManager(  974): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@392bd7d3
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=1, flag=1, pid=4007, uid=10099, userID:0
I/DeviceManagement( 4007): Perf: *** Config cache update - complete: 145 ms
I/DeviceManagement( 4007): Perf: *** Cache update - complete: 854 ms
,I/DeviceManagement( 4007): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@1c86cd2b]
,I/AlarmManager(  974): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@339f5f10
,I/DeviceManagement( 4007): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@a1d42b2] args=[Bundle[mParcelledData.dataSize=132]]
,I/DeviceManagement( 4007): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 4007): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/AlarmManager(  974): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  974): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  974): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  974): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  974): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  974): [AlarmQueuing] add queuing package: jp.naver.line.android
,I/AlarmManager(  974): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  974): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  974): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  974): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  974): [AlarmQueuing] add queuing package: com.facebook.orca
,I/AlarmManager(  974): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  974): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  974): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
,I/ActivityManager(  974): Killing 3543:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=3543
I/DeviceManagement( 4007): SessionStateController: Checking invariants...
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 4155): -onCreate(),
,I/DeviceManagement( 4007): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/ActivityManager(  974): Recipient 3543
,I/DeviceManagement( 4007): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@a1d42b2]
,I/DeviceManagement( 4007): WorkflowService: Stopping workflow service
,I/ActivityManager(  974): Killing 3575:com.htc.HTCSpeaker/u0a54 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=3575
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 3575,
,V/Settings:HtcSettingsApplication( 4155): [4155/4155] onCreate(),
,I/htcbackup-core( 4031): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.11.05 at 12:06:52.457 CET] interval end=[2015.11.12 at 12:06:52.457 CET]
W/ContextImpl( 4155): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  974): Start proc com.android.settings:remote for service com.android.settings/.framework.app.HtcIntentService: pid=4179 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,V/AlarmManager(  974): sending alarm PendingIntent{2e835c3c: PendingIntentRecord{2670bdc5 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=17, w=1447326412457, Int=604800000
,D/TetherSettings( 4155): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4155): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4155): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4155): Cust_ConnectToPC   : spcsc>false
D/        ( 4155): Cust_ConnectToPC   : IPT>true
D/        ( 4155): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4155): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4155): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4155): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4155): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,I/SmartNS_Utility( 4155): setISNotification
,D/DotMatrix( 1319): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/DotMatrix( 1319): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
,I/RemoteViews( 1233): reapply : com.htc.backup 4 38,
I/RemoteViews( 1233): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1233): apply : com.htc.backup 1 2 0 5
I/RemoteViews( 1233): setHTCTheme(com.htc.backup,true,33751145)
V/Settings:HtcSettingsApplication( 4179): [4179/4179] onCreate()
,I/RemoteViews( 1233): apply : com.htc.backup 0 2 0 5
,I/RemoteViews( 1233): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1233): apply : com.htc.backup 1 2 0 5
I/RemoteViews( 1233): reapply : com.htc.backup 12 50
,D/SmartNS_Utility( 4155): usb_cable_connect = 1
D/SmartNS_Utility( 4155): usb_denied = 0
I/SmartNS_PSService( 4155): usb notificaiton:true
,E/WifiStateMachine(  974): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 4155): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 4155): usb_cable_connect = 1,
D/SmartNS_Utility( 4155): usb_denied = 0
I/SmartNS_PSService( 4155): usb notificaiton:true
,E/WifiStateMachine(  974): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1319): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/DotMatrix( 1319): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/ActivityManager(  974): Killing 3615:com.htc.lmw/u0a58 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=3615
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/RemoteViews( 1233): setHTCTheme(com.android.settings,true,33751145)
,I/RemoteViews( 1233): apply : com.android.settings 0 11 2 36,
,I/RemoteViews( 1233): reapply : com.android.settings 1 36,
,I/ActivityManager(  974): Recipient 3615
,D/Process (  974): killProcessQuiet, pid=3646
I/ActivityManager(  974): Killing 3646:com.android.managedprovisioning/u0a63 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/HtcModeClient( 3171): handler message = 4011,
,E/HtcModeClient( 3171): Check connection and retry 2 times.
,I/ActivityManager(  974): Recipient 3646
,W/ContextImpl(  974): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,I/ActivityManager(  974): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4204 uid=9987 gids={49987, 9997} abi=arm64-v8a
,D/SmartDim(  974): Init customizeScreenOffDelayClass error,
,I/SensorManager(  974): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@2aa47141, sensor = {Sensor name="Accelerometer Sensor", vendor="hTC Corp.", version=1, type=1, maxRange=39.2266, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
,W/SensorService(  974): Following SensorService logs are not warning, just make sure they are printed
W/BroadcastQueue(  974): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{1505e07d u0 ReceiverList{1d30f6d4 974 system/1000/u0 local:2a91a427}}
W/SensorService(  974): enable: get sensor name = Accelerometer Sensor
W/SensorService(  974): pid=974, uid=1000
W/SensorService(  974): Active sensors: size = 3
W/SensorService(  974): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  974): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  974): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  974): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2aa47141, eanble = 1, strlen(mName) = 36
W/SensorService(  974): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  974): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@136b7597
W/SensorService(  974): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3c669aae
W/SensorService(  974): Listener[2] = com.htc.smartdim.sensor_eye@2aa47141
W/SensorService(  974): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  974): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@2aa47141, sensor = {Sensor name="CM36686 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
,W/SensorService(  974): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  974): enable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  974): pid=974, uid=1000
W/SensorService(  974): Active sensors: size = 4
W/SensorService(  974): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  974): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  974): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  974): Significant Motion (handle=0x0000000d, connections=1)
,W/SensorService(  974): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2aa47141, eanble = 1, strlen(mName) = 36
W/SensorService(  974): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  974): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@136b7597
W/SensorService(  974): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3c669aae
W/SensorService(  974): Listener[2] = com.htc.smartdim.sensor_eye@2aa47141
W/SensorService(  974): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  974): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4228 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActivityManager(  974): Killing 2151:com.google.android.gms/u0a24 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=2151
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 ,
,I/ActivityManager(  974): Recipient 2151
,I/SensorManager(  974): dispatchSensorEvent: Proximity = 9.0, mListener = com.htc.smartdim.sensor_eye@2aa47141,
,I/ActivityManager(  974): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4249 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  974): Killing 3794:com.htc.cs.pns/u0a71 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=3794
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  974): Recipient 3794
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4249, uid=10072, userID:0
,W/global  ( 4249): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 4249): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 4249): [apache-http] Connection GC has been deprecated!
,I/ActivityManager(  974): Waited long enough for: ServiceRecord{2acf66be u0 com.google.android.gms/.gcm.GcmService}
,W/global  ( 4249): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 4249): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  974): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4286 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/Settings( 4249): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 4249): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4286): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4286): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4249, uid=10072, userID:0
,I/MultiDex( 4286): VM with version 2.1.0 has multidex support,
I/MultiDex( 4286): install
I/MultiDex( 4286): VM has multidex support, MultiDex support library is disabled.
,D/Volley  ( 4249): [390] DiskBasedCache.clear: Cache cleared.,
,D/Volley  ( 4249): [384] DiskBasedCache.clear: Cache cleared.
,V/JNIHelp ( 4286): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  974): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4312 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
D/Process (  974): killProcessQuiet, pid=3826
I/ActivityManager(  974): Killing 3826:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  407): Explicit concurrent mark sweep GC freed 8717(370KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 223us total 28.790ms
,W/ActivityThread( 4286): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4286): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35054356: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4286): Installed default security provider GmsCore_OpenSSL
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 159us total 20.598ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 144us total 18.575ms
,I/ActivityManager(  974): Recipient 3826
,D/Finsky  ( 4249): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 4249): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4249): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ResourcesManager( 4312): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4312): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 4312): VM with version 2.1.0 has multidex support
I/MultiDex( 4312): install
I/MultiDex( 4312): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 4249): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 4312): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 4312): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35da124: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,W/ActivityThread( 4312): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 4312): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  974): Killing 3849:com.htc.showme/u0a81 (adj 15): empty #17
,D/Process (  974): killProcessQuiet, pid=3849
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  974): Recipient 3849
,V/GLSUser ( 1926): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED,
,D/PMS     (  974): acquireWL(223482a5): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1926 10024 null
,I/ActivityManager(  974): Killing 2854:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=2854
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/NotificationStore( 1926): System rebooted after Notification storage file was last written
,I/NotificationStore( 1926): Deleting the file
,D/PMS     (  974): releaseWL(223482a5): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null,
,I/ActivityManager(  974): Recipient 2854
,V/GmsCoreStatsServiceLauncher( 4312): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,V/Finsky  ( 4249): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/PersistentNotificationBroadcastReceiver( 1926): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/InstanceID/Rpc( 4312): Found 10024
,D/FileApkUtils( 4312): Spent 27ms computing apk sha1.
,D/FileApkUtils( 4312): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 4312): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 4312): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 4312): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971
,I/art     (  974): Explicit concurrent mark sweep GC freed 15202(747KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.490ms total 151.573ms
,D/GmsModuleFndr( 4312): Beginning GMS chimera module scan
,W/asset   ( 4312): Copying FileAsset 0x555d1b1a40 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.
,D/PMS     (  974): acquireWL(24644207): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4312 10024 null
,D/PMS     (  974): acquireWL(23386f34): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4312 10024 WorkSource{10024 com.google.android.gms}
,D/GmsModuleFndr( 4312): Module pkg com.google.android.apps.kids.familylink not installed, skipping
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1926, uid=10024, userID:0
,I/ActivityManager(  974): Delay finish: com.google.android.gms/.nearby.sharing.NearbySharingBroadcastReceiver
,D/ChimeraCfgMgr( 4312): Beginning module configuration check
,D/ChimeraCfgMgr( 4312): Module APKs unchanged, check complete,
I/ActivityManager(  974): Resuming delayed broadcast
,D/PMS     (  974): acquireWL(3fcefad2): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4312 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  974): acquireWL(3d17b659): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4312 10024 null
,D/GCM     ( 4312): COMPAT: Multi user not supported
,D/PMS     (  974): acquireWL(1e7df21e): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4312 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1926): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/PMS     (  974): acquireWL(2c845f15): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4312 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(23386f34): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  974): releaseWL(24644207): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  974): releaseWL(1e7df21e): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4312): Disabling old GoogleServicesFramework version,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4312, uid=10024, userID:0,
I/GCoreUlr( 4312): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4312, uid=10024, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4312, uid=10024, userID:0
,D/SystemUpdateService( 4312): onCreate
,D/PMS     (  974): acquireWL(36d8d791): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  974): Delay finish: com.google.android.gms/.tron.AlarmReceiver
,D/SystemUpdateService( 4312): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/GCoreUlr( 1818): DispatchingService.onCreate()
,I/ConfigService( 1926): onCreate
,I/ConfigFetchService( 4312): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/CheckinService( 4312): Checking schedule, now: 1457358111769 next: 1456765623471
I/CheckinService( 4312): active receiver: enabled
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4312, uid=10024, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4312, uid=10024, userID:0
,D/PMS     (  974): acquireWL(2c4dc701): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4312, uid=10024, userID:0
V/AuthZen ( 4312): Handling intent: android.intent.action.BOOT_COMPLETED
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4312, uid=10024, userID:0
,D/AuthZenEventHandler( 4312): Handling event: android.intent.action.BOOT_COMPLETED
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4312, uid=10024, userID:0,
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4312, uid=10024, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4312, uid=10024, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4312, uid=10024, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4312, uid=10024, userID:0
,D/PMS     (  974): acquireWL(354ed23d): PARTIAL_WAKE_LOCK  Icing 0x1 4312 10024 WorkSource{10024 com.google.android.gms}
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4312, uid=10024, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4312, uid=10024, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4312, uid=10024, userID:0
,I/SystemUpdateService( 4312): cancelUpdate (empty URL)
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4312, uid=10024, userID:0
I/SystemUpdateService( 4312): active receiver: disabled
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4312, uid=10024, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4312, uid=10024, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4312, uid=10024, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4312, uid=10024, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4312, uid=10024, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4312, uid=10024, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4312, uid=10024, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4312, uid=10024, userID:0
,I/GCoreUlr( 1818): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4312, uid=10024, userID:0
,D/PMS     (  974): releaseWL(354ed23d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/System.err(  974): java.lang.Throwable: stack dump
,W/System.err(  974): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  974): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  974): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  974): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothManagerService(  974): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  974): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@253eed8a:true
W/BaseAppContext( 4312): Using Auth Proxy for data requests.
,I/GLSUser ( 4312): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1818, uid=10024, userID:0,
I/GLSUser ( 4312): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/ConfigFetchService( 4312): service connected
,I/art     ( 1926): Explicit concurrent mark sweep GC freed 16452(991KB) AllocSpace objects, 6(120KB) LOS objects, 51% free, 3MB/7MB, paused 836us total 39.626ms
,I/ActivityManager(  974): Resuming delayed broadcast
,D/PMS     (  974): releaseWL(3fcefad2): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(36d8d791): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(2c845f15): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/SystemUpdateService( 4312): onDestroy
,D/ChimeraCfgMgr( 4312): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/AuthZen ( 4312): Fetching signing key...
,I/Kids    ( 4312): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/ConfigFetchService( 4312): ConfigApi connection successful.
,I/AuthZen ( 4312): Signing key fetched successfully!
,W/BaseAppContext( 4312): Using Auth Proxy for data requests.
,I/ActivityManager(  974): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4413 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/AuthZen ( 4312): Starting Enrollment...
I/GCoreUlr( 1818): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/AuthZen ( 4312): getting auth token. Attempt 0
,D/PMS     (  974): acquireWL(36589760): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(36589760): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1818): Unbound from all location providers
,I/GLSActivity( 1926): [ac] getting account id
D/PMS     (  974): releaseWL(2c4dc701): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms}
,W/ResourcesManager( 4413): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/GLSUser ( 1926): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1926): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GCoreUlr( 1818): DispatchingService.onDestroy()
,D/PMS     (  974): acquireWL(303bf8ea): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(303bf8ea): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1818): Unbound from all location providers
,I/GLSUser ( 1926): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/GLSUser ( 1926): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,I/GLSUser ( 1926): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1926): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1926): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AuthZen ( 4312): Error getting auth token,
E/AuthZen ( 4312): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4312): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4312): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4312): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4312): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4312): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 4312): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 4312): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4312): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4312): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4312): 	,at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4312): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4312): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4312): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4312): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/a       ( 4312): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 4312): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 4312): Clearing transaction cache,
,D/PMS     (  974): acquireWL(2c58b9b6): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 974 1000 null
,D/PMS     (  974): releaseWL(2c58b9b6): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/Babel_SMS( 4413): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4413): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 3757): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3757): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 4413): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml,
I/Babel_SMS( 4413): MmsConfig.loadFromDatabase
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4413, uid=10112, userID:0
,E/Babel_SMS( 4413): canonicalizeMccMnc: invalid mccmnc ,
I/Babel_SMS( 4413): MmsConfig.loadFromResources
,E/Babel_SMS( 4413): canonicalizeMccMnc: invalid mccmnc nullnull,
,I/Babel_SMS( 4413): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,W/Settings( 4413): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/Babel_Crash( 4413): startup - clean,
,I/Babel   ( 4413): deleted: false for 0,
,W/art     ( 4413): Suspending all threads took: 6.152ms,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4413, uid=10112, userID:0,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4413, uid=10112, userID:0,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4413, uid=10112, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4413, uid=10112, userID:0,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4413, uid=10112, userID:0,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4413, uid=10112, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4413, uid=10112, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4413, uid=10112, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4413, uid=10112, userID:0,
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4413, uid=10112, userID:0
,W/VideoCapabilities( 4413): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 4413): Unsupported mime video/x-ms-wmv
,W/Utils   ( 4413): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 4413): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4413): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4413): Unsupported mime audio/qcelp
,W/VideoCapabilities( 4413): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 4413): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4413): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4413): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4413): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4413): Unrecognized profile 2130706433 for video/avc,
,I/vclib   ( 4413): onServiceConnected
W/Babel   ( 4413): Attempted to change video mute state without an active call.
,I/ActivityManager(  974): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4445 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/ResourcesManager( 4445): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4445): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4445): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 4445): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 4445): Installed default security provider GmsCore_OpenSSL
,W/art     ( 4445): Suspending all threads took: 6.626ms,
,E/cutils-trace( 4477): Error opening trace file: Permission denied (13)
,I/dex2oat ( 4477): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads639995543.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads639995543.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 4477): dex2oat: override thread count:4
,I/dex2oat ( 4477): dex2oat took 35.072ms (threads: 4),
,E/YouTube MDX( 4445): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 4445): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
,D/libc    ( 4445): [NET] android_getaddrinfofornet-, SUCCESS
,D/VoldConnector(  974): SND -> {11 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 4445): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  974): SND -> {12 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 4445): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  974): SND -> {13 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/,
W/ContextImpl( 4445): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,D/VoldConnector(  974): SND -> {14 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/},
W/ContextImpl( 4445): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/InstanceID/Rpc( 4445): Found 10024
I/ActivityManager(  974): Waited long enough for: ServiceRecord{23b85ad1 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,D/VoldConnector(  974): SND -> {15 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 4445): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
,I/ActivityManager(  974): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4523 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  974): Killing 3872:com.htc.feedback/u0a83 (adj 15): empty #17,
D/Process (  974): killProcessQuiet, pid=3872
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 3872,
,W/ActivityManager(  974): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,V/AlarmManager(  974): sending alarm PendingIntent{3e899faa: PendingIntentRecord{36baf79b com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=52733, Int=259200000,
V/AlarmManager(  974): sending alarm PendingIntent{2594e311: PendingIntentRecord{dba0c76 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457358114019, Int=0
,I/HtcModeClient( 3171): handler message = 4011
,E/HtcModeClient( 3171): Check connection and retry 3 times.
,I/Gmail   ( 4523): getAccountsCursor
,W/GAV2    ( 4523): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.UploadsManager( 4312): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,W/ActivityManager(  974): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     (  974): Explicit concurrent mark sweep GC freed 15865(909KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 15MB/23MB, paused 1.932ms total 170.018ms
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4523, uid=10106, userID:0
,W/ActivityManager(  974): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,E/Gmail   ( 4523): Error finding the version of the Email provider.....
E/Gmail   ( 4523): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4523): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4523): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4523): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4523): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4523): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 4523): We do not support migrating this version of the Email provider.
,I/Gmail   ( 4523): Observing account changes for notifications
,W/ActivityManager(  974): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4523, uid=10106, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4523, uid=10106, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4523, uid=10106, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4523, uid=10106, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4523, uid=10106, userID:0,
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4523, uid=10106, userID:0
I/Gmail   ( 4523): getAccountsCursor
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.UploadsManager( 4312): End new media; added: 0, uploading: 0, time: 218 ms
,I/ActivityManager(  974): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4569 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  974): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4523, uid=10106, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4523, uid=10106, userID:0
,W/ActivityManager(  974): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityThread( 4523): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@19c13a94 that was originally bound here,
E/ActivityThread( 4523): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@19c13a94 that was originally bound here
E/ActivityThread( 4523): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4523): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4523): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 4523): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 4523): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4523): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4523): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4523): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4523): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4523): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4523): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4523): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4523): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4523): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  974): Unbind failed: could not find connection for android.os.BinderProxy@c5a4cfe
,E/SQLiteLog( 4523): (283) recovered 1491 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal,
,I/Gmail   ( 4523): notifyAccountChanged,
,I/Gmail   ( 4523): getAccountsCursor
,I/Gmail   ( 4523): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4523): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/PMS     (  974): acquireWL(2718fdd6): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4523 10106 null,
,I/Gmail   ( 4523): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,I/Gmail   ( 4523): calculateUnknownSyncRationalesAndPurgeInBackground: running,
I/Gmail   ( 4523): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/PMS     (  974): acquireWL(2718fdd6): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4523 10106 null
,I/Gmail   ( 4523): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,D/PMS     (  974): acquireWL(2718fdd6): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4523 10106 null
,I/Gmail   ( 4523): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4523, uid=10106, userID:0
,D/Process (  974): killProcessQuiet, pid=3894
,I/ActivityManager(  974): Killing 3894:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 3894
,I/Gmail   ( 4523): master sync=false, engine sync=true,
,I/Gmail   ( 4523): getAccountsCursor,
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationManagerService(  974): getProviders()=[passive],
I/Gmail   ( 4523): master sync=false, engine sync=true
,I/ActivityManager(  974): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4601 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,E/AndroidHttpClient( 4249): Leak found
E/AndroidHttpClient( 4249): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4249): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4249): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4249): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4249): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4249): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4249): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4249): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4249): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4249): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4249): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4249): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4249): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4249): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4249): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4249): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4249): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4569, uid=10085, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4569, uid=10085, userID:0,
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4569, uid=10085, userID:0
,W/BroadcastQueue(  974): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000),
D/Process (  974): killProcessQuiet, pid=3927
I/ActivityManager(  974): Killing 3927:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  974): Recipient 3927
,I/ActivityManager(  974): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4636 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/WifiTrafficPoller(  974): ADD_CLIENT: 6
,D/WifiService(  974): New client listening to asynchronous messages
,I/VelvetNetworkClient( 4569): Network connection not availble,
,I/htcbackup-core( 4031): SuperSaverModeReceiver: on receiving action com.htc.server.htcpowersaver.action.OFF,
I/htcbackup-core( 4031): SuperSaverModeReceiver: going to send resume event
,D/GCM     ( 1926): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1926): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/htcbackup-core( 4031): BackupRestoreManager: onHandleIntent
I/htcbackup-core( 4031): BackupRestoreManager: resume
,V/GmsCoreStatsServiceLauncher( 4312): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/htcbackup-core( 4031): BackupRestoreManager: Storage is not configured
,E/htcbackup-core( 4031): BackupStatus: Ignoring failure message - backup already failed with message:  CONNECTION_FAIL_STORAGE
,I/ActivityManager(  974): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4666 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4312, uid=10024, userID:0
,I/WebViewFactory( 4569): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49,
D/AccFlag ( 1493): sku_id=118
W/ResourcesManager( 4666): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4666): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 4666): VM with version 2.1.0 has multidex support,
I/MultiDex( 4666): install
I/MultiDex( 4666): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  974): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4693 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,D/LocationInitializer( 4312): Restart initialization of location
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1493): sku_id=118
I/LibraryLoader( 4569): Time to load native libraries: 13 ms (timestamps 5745-5758)
,I/LibraryLoader( 4569): Expected native library version number "",actual native library version number ""
,W/art     ( 4569): Attempt to remove local handle scope entry from IRT, ignoring
,V/JNIHelp ( 4666): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64
D/AccFlag ( 1493): sku_id=118
,W/System.err( 4031): Starting the HTTP client
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
D/AccFlag ( 1493): sku_id=118
,W/htcbackup-core( 4031): BackupServiceClientResourceProxy: Reseting appServerErrorCount
,W/htcbackup-core( 4031): BackupRestoreManager: No sense account found - aborting,
I/htcbackup-core( 4031): BackupRestoreManager: DM is not ready, pending resume
,W/ActivityThread( 4666): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 4666): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35054356: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4666): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 4666): callingUid 10024, callindPid: 4666,
,E/MDM     ( 1818): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,W/art     ( 4569): Attempt to remove local handle scope entry from IRT, ignoring,
,I/ImageRamCache( 4693): create image Cache, size: 31457280.
I/ImageRamCache( 4693): [resize] ImageRamCache resized to: 30Mb.
,I/ImageRamCache( 4693): create image Cache, size: 31457280.
,I/FeedSettings( 4693): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 4693): GroupBudget 0.500000 0.380000
I/FeedSettings( 4693): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4693): changeLocale(): en_GB
,I/ActivityManager(  974): Killing 3968:com.google.android.configupdater/u0a98 (adj 15): empty #17
,D/Process (  974): killProcessQuiet, pid=3968
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/Prism.AllAppsOptionsMa_( 4693): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4693): loadGridSize() with Alternative
,I/ActivityManager(  974): Recipient 3968
,D/CustomHighlightReceiver( 4693): [custom highlight] onReceive
,D/CustomHighlightService( 4693): [custom highlight] onHandleIntent
,D/NewsDB  ( 4693): set custom highlight []
,I/ActivityManager(  974): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4739 uid=10035 gids={50035, 9997} abi=arm64-v8a
,D/CustomHighlightService( 4693): [custom highlight] set tags 
,D/Process (  974): killProcessQuiet, pid=4060
I/ActivityManager(  974): Killing 4060:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 4060,
,D/Process (  974): killProcessQuiet, pid=4087,
I/ActivityManager(  974): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4761 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  974): Killing 4087:com.htc.htccupd/u0a13 (adj 15): empty #17
,I/ActivityManager(  974): Recipient 4087
,D/SMSBackup( 4761): Got a database change event,
,I/ActivityManager(  974): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4782 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
D/Process (  974): killProcessQuiet, pid=4134
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  974): Killing 4134:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,I/ActivityManager(  974): Recipient 4134,
,D/MessagingShortcutReceiver( 3757): keep hiding shortcut bubble,
,D/MessagingShortcut( 3757): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 3757): After query: 0
D/MessagingShortcut( 3757): mPresentUnreadCount: -1,
,D/MessageUtils( 3757): [getShortcut] com.htc.sense.mms.ui.ConversationList, false,
,D/MessagingShortcut( 3757): setMsgShortcutDrawable> 0, false
,D/MessagingShortcut( 3757): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1319): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1319): [EventService] reorderNotification, total:0
D/DotMatrix( 1319): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1319): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  974): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4804 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,D/PMS     (  974): releaseWL(2718fdd6): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
,I/art     (  407): Explicit concurrent mark sweep GC freed 8641(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 189us total 29.478ms
,W/ResourcesManager( 4804): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 157us total 20.103ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 159us total 19.726ms,
,I/ActivityManager(  974): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4826 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/TodoTaskshortcut( 4804): update TASK shortcut>
,I/art     (  974): Explicit concurrent mark sweep GC freed 9613(467KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.542ms total 158.658ms
,D/PMS     (  974): acquireWL(193f9d4): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4804 10069 null
D/PMS     (  974): acquireWL(1018277d): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4804 10069 null
,D/PMS     (  974): releaseWL(193f9d4): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 4804): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 4804): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4804): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4804): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
D/PMS     (  974): releaseWL(1018277d): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 4804): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4804): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4804): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4804): stopSelfResult true
,D/Process (  974): killProcessQuiet, pid=4007
,I/ActivityManager(  974): Killing 4007:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MdScBootUi( 4782): [870.1.2.] boot 118,
,D/MdScBoot( 4782): [870.1.] 30@-134129 -> 40,
,D/MdScSimSt( 4782): [870.1.2.] qry 118: 0+1 running 0
,I/ActivityManager(  974): Recipient 4007
,D/Prism.PackageStateRece_( 1538): action: android.intent.action.PACKAGE_ADDED
,I/[PluginManager]RegisterService( 1456): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1456): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  974): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4860 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,D/Process (  974): killProcessQuiet, pid=4179
I/ActivityManager(  974): Killing 4179:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/DeviceManagement( 4860): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4860 dbg=false s=true,
,I/DeviceManagement( 4860): PackageUpdateReceiver: vvv Package added: [com.example.hello],
,I/ActivityManager(  974): Recipient 4179,
,D/Process (  974): killProcessQuiet, pid=4204
I/ActivityManager(  974): Killing 4204:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  974): Recipient 4204
,D/Process (  974): killProcessQuiet, pid=4228
I/ActivityManager(  974): Killing 4228:com.android.smith/1000 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 4228
,I/ActivityManager(  974): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4883 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/HtcCupdReceiver(Provider)( 4883):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED,
,D/ContactMessageStore( 1493): MSG_NOTIFY_CS_TO_SYNC >>,
,D/ContactMessageStore( 1493): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  974): killProcessQuiet, pid=4286
I/ActivityManager(  974): Killing 4286:com.google.android.gms:car/u0a24 (adj 15): empty #17
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/Settings:HtcWirelessFeatureFlags( 4155): id/is att sku: 118/false,
,E/Settings:HtcWrapHeaderInfo( 4155): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4155): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 4155): updateDevelopment, bPrefShow = true,
,E/Settings:HtcUmcWidgetEnabler( 4155): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportHomeButton]support         :false
,I/ActivityManager(  974): Recipient 4286,
,D/PackageBroadcastService( 4312): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello,
,E/Settings:HtcVoWifiWidgetEnabler( 4155): isSupportVoWifi: null
I/ActivityManager(  974): Cannot resolve ContentProvider=com.htc.vowifi
D/ChimeraCfgMgr( 4312): Loading module com.google.android.gms.games from APK com.google.android.play.games
E/ActivityThread( 4155): Failed to find provider info for com.htc.vowifi
D/ChimeraModuleLdr( 4312): Loading module APK com.google.android.play.games
,I/ActivityManager(  974): Waited long enough for: ServiceRecord{1c797eeb u0 com.htc.HTCSpeaker/.NGFService}
,D/PMS     (  974): acquireWL(3fd4af6c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4312 10024 null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4155): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4155): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4155): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4155): [supportHomeButton]support         :false
,E/Settings:HtcVoWifiWidgetEnabler( 4155): isSupportVoWifi: null,
I/ActivityManager(  974): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4155): Failed to find provider info for com.htc.vowifi
,I/art     ( 4312): Background partial concurrent mark sweep GC freed 14904(879KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 5.292ms total 61.185ms
,I/ConfigFetchService( 4312): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  974): acquireWL(1b135658): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4312 10024 WorkSource{10374 com.example.hello},
,I/ConfigFetchService( 4312): launchTask
D/PMS     (  974): releaseWL(3fd4af6c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  974): acquireWL(b9ac3b1): PARTIAL_WAKE_LOCK  Icing 0x1 4312 10024 WorkSource{10024 com.google.android.gms},
,D/ChimeraCfgMgr( 4312): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4312): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4312): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/ConfigFetchTask( 4312): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WKcWMWvCU23ME-060oMI-0Nt2IjOb3iC_tLRYeRUCexn4OtPmmJcXEgqD3ZCQtJ-bFpFS_Ud9Gl0JMrv656wJP4FJRw9Yser-Q7_IOhdj7HzT8Olja7A3gGIHINz5t70wYo6olADobN6Ier3TB-mXNIhOx9wtE1MCFa8SbOLKn9wnkIVvfXavfqa9XQEjp-EPn0pB_,
,I/PeopleContactsSync( 4312): CP2 sync disabled
I/GoogleURLConnFactory( 4312): Using platform SSLCertificateSocketFactory
,D/Vision  ( 4312): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4312, uid=10024, userID:0
D/Vision  ( 4312): Failed to find package metadata for com.example.hello
D/Vision  ( 4312): No vision deps
,I/ActivityManager(  974): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4918 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/Icing   ( 4312): Storage manager: low false usage 1.98MB avail 5.80GB capacity 7.95GB
,D/libc    ( 4312): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4312): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4312): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4312): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 4312): [NET] android_getaddrinfo_proxy+
D/libc    ( 4312): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4312): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4312): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 4312): fetch service done; releasing wakelock
,D/PMS     (  974): releaseWL(1b135658): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10374 com.example.hello}
I/ConfigFetchService( 4312): stopping self
,W/Icing   ( 4312): Received bad json for section weights override -- ignoring.,
,W/Icing   ( 4312): Received bad json for corpus context scoring override -- ignoring.
,W/Icing   ( 4312): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4312): Received bad json for corpus context scoring override -- ignoring.
,W/BaseAppContext( 4312): Using Auth Proxy for data requests.,
W/BaseAppContext( 4312): Using Auth Proxy for data requests.
,E/Icing   ( 4312): Loading extension by file descriptor -1 failed,
,I/art     ( 1926): Explicit concurrent mark sweep GC freed 10604(585KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 966us total 51.454ms
,W/BaseAppContext( 4312): Using Auth Proxy for data requests.
,W/BaseAppContext( 4312): Using Auth Proxy for data requests.
,W/BaseAppContext( 4312): Using Auth Proxy for data requests.
,W/BaseAppContext( 4312): Using Auth Proxy for data requests.
,I/Icing   ( 4312): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 4312): Internal init done: storage state 0
,I/Icing   ( 4312): Post-init done
,D/PMS     (  974): releaseWL(b9ac3b1): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/GAv4    ( 4918): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 4918):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4918):   adb logcat -s GAv4
,W/GAv4    ( 4918): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4918): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4918): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/AnalyticsTrackerProxyImpl( 4918): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,I/HtcModeClient( 3171): handler message = 4011,
E/HtcModeClient( 3171): Check connection and retry 4 times.
,D/ChimeraCfgMgr( 4312): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4312): Module APK com.google.android.play.games already loaded
,I/GAV2    ( 4523): Thread[GAThread,5,main]: No campaign data found.,
,D/VoldConnector(  974): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 4918): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,I/ActivityManager(  974): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4964 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Process (  974): killProcessQuiet, pid=4445
I/ActivityManager(  974): Killing 4445:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,W/ResourcesManager( 4918): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4918): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  974): Recipient 4445
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/GAv4-SVC( 4312): Google Analytics 7.8.99 is starting up.,
,W/ResourcesManager( 4964): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 4918): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 4918): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4918): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  974): acquireWL(78f107): PARTIAL_WAKE_LOCK  AsyncService 0x1 4964 10167 null,
,D/PMS     (  974): acquireWL(1ae3285d): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 4964 10167 null
,D/PMS     (  974): releaseWL(78f107): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  974): releaseWL(1ae3285d): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 4569): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE,
,D/PMS     (  974): acquireWL(62996a3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1926 10024 WorkSource{10024 com.google.android.gms}
,D/MtpReceiver( 3711): [MTP][handleUsbStateAsync]+
,D/MtpReceiver( 3711): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3711): [MTP][handleUsbState]+
,I/ActivityManager(  974): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4999 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,D/MtpReceiver( 3711): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpService( 3711): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpReceiver( 3711): [MTP][handleUsbState]-
V/AlarmManager(  974): sending alarm PendingIntent{157453cc: PendingIntentRecord{2fd80615 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=60212, Int=0
D/MtpReceiver( 3711): [MTP][handleMessage]-
D/PMS     (  974): releaseWL(62996a3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/MtpDatabase( 3711): TotalSize=1886532,MediaCacheLimit=6000
,D/MtpService( 3711): [isMtpConnected] connected: true
,I/ClockController( 1233): schedule update now=1457358120034 next=59966,
,D/WeatherUtility( 1233): Weather sync is On,
W/WeatherTimeKeeper( 1233): [refreshWeatherData] no weather data
,I/Clock   ( 1233): updateClock:14:42 Europe/Warsaw
I/Clock   ( 1233): updateClock:14:42 Europe/Warsaw
I/Clock   ( 1233): updateClock:14:42 Europe/Warsaw
,W/asset   ( 4569): Copying FileAsset 0x555d1efba0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,E/MediaScannerService( 3711): [onStartCommand] --- Should not be here, redirect request. ----
,E/MediaScannerService( 3711): [handleMessage] --- Should not be here, ignore request. ----
,D/SyncApplication( 4999): Loading default preferences
,D/PMS     (  974): acquireWL(31375064): PARTIAL_WAKE_LOCK  Icing 0x1 4312 10024 WorkSource{10024 com.google.android.gms}
W/Resources( 4999): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/PMS     (  974): releaseWL(31375064): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): acquireWL(31303782): PARTIAL_WAKE_LOCK  Icing 0x1 4312 10024 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  974): ADD_CLIENT: 7
D/WifiService(  974): New client listening to asynchronous messages,
,D/SyncApplication( 4999): Overriding preferences with custom values
,E/MediaScannerServiceEx( 3711): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3711): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0,
,D/MediaScannerServiceEx( 3711): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3711): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3711): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3711): calcVolumeId: /storage/usb,
,D/MediaScannerServiceEx( 3711): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3711): [AliveExtStorageRows]+65537, 11223344,
I/UpdateIcingCorporaServi( 4569): UpdateCorporaTask done [took 269 ms] updated apps [took 269 ms] 
,D/Process (  974): killProcessQuiet, pid=4523
I/ActivityManager(  974): Killing 4523:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/SyncApplication( 4999): Updating preferences succeeded
,D/MediaProvider( 3711): [update][7]#0#
,D/MediaProvider( 3711): [update][1]#0#
,D/MediaProvider( 3711): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3711): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3711): [update][3]#1#
,D/MediaScannerServiceEx( 3711): [AliveExtStorageRows]-0, 0
,D/PMS     (  974): acquireWL(169a47fc): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3711 10017 null,
,I/ActivityManager(  974): Recipient 4523
,E/SyncApplication( 4999): Application created.,
,D/MediaScanner( 3711): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,I/CalendarDefines( 4999): getNewCalendarAuthority()...,
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4999, uid=10005, userID:0
,W/PackageManager(  974): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4999): enableAppOperation()+
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4999, uid=10005, userID:0
,W/VolumeInfo( 4999): Unable to read mount points
W/VolumeInfo( 4999): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4999): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 4999): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 4999): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 4999): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 4999): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 4999): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 4999): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 4999): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 4999): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 4999): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 4999): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 4999): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 4999): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 4999): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 4999): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4999): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 4999): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 4999): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 4999): 	,... 13 more
W/PackageManager(  974): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
V/VolumeInfo( 4999): Found 0 mount point(s)
V/VolumeInfo( 4999): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/SyncApplication( 4999): enableAppOperation()-
,D/VolumeInfo( 4999): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/HTCUtilities( 4999): isNeorSinged() + 
,D/VolumeInfo( 4999): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 4999): Can not create volume ID for unmounted volume null
,D/HTCUtilities( 4999): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>,
,D/HTCUtilities( 4999): isNeorSinged() return false
,D/CDMountReceiver( 4999): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true,
D/CDMountReceiver( 4999): USB connected to PC
,D/FOTAReceiver( 4999): onReceive() enter ,
,D/FOTAReceiver( 4999): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/TetherSettings( 4155): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 4155): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4155): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4155): Cust_ConnectToPC   : spcsc>false
D/        ( 4155): Cust_ConnectToPC   : IPT>true
D/        ( 4155): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4155): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4155): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4155): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4155): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4155): usb_cable_connect = 1
,D/SmartNS_Utility( 4155): usb_denied = 0
,I/SmartNS_NSReceiver( 4155): locked:falsesecurity:falseisLocked:false,
D/SmartNS_NSReceiver( 4155): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 4155): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 4155): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 ,
,I/SmartNS_PSService( 4155): onReceive:com.htc.intent.action.USB_CONNECT2PC,
,W/Settings( 4155): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4155):  defaultType:0
I/SmartNS_PSService( 4155): fail notificaiton:false
D/SmartNS_Utility( 4155): usb_cable_connect = 1
,D/SmartNS_Utility( 4155): usb_denied = 0
I/SmartNS_PSService( 4155): usb notificaiton:true
E/WifiStateMachine(  974): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  974): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5033 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/RemoteViews( 1233): reapply : com.android.settings 1 36
,D/DotMatrix( 1319): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_Utility( 4155): usb_cable_connect = 1
D/SmartNS_Utility( 4155): usb_denied = 0
,I/SmartNS_PSService( 4155): usb notificaiton:true,
E/WifiStateMachine(  974): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1319): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_Utility( 4155): usb_cable_connect = 1
,D/SmartNS_Utility( 4155): usb_denied = 0
,I/RemoteViews( 1233): reapply : com.android.settings 2 36
,I/ActivityManager(  974): Killing 4693:com.htc.sense.news/u0a74 (adj 15): empty #17
,D/Process (  974): killProcessQuiet, pid=4693
I/SmartNS_PSService( 4155): KeyGuard locked:falseKeyGuard is secured:false
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/SmartNS_PSService( 4155): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/ActivityManager(  974): Recipient 4693,
,D/Process (  974): killProcessQuiet, pid=4739,
I/ActivityManager(  974): Killing 4739:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,W/ContextImpl( 5033): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  974): Recipient 4739,
,I/ActivityManager(  974): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5056 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/Process (  974): killProcessQuiet, pid=4761,
,I/ActivityManager(  974): Killing 4761:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 4761,
I/Icing   ( 4312): Indexing FBE7E5D8BA1B80556F1315772AF6A2582D6BF376 from com.google.android.googlequicksearchbox
,W/ResourcesManager( 5056): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Icing   ( 4312): Indexing done FBE7E5D8BA1B80556F1315772AF6A2582D6BF376,
,D/PMS     (  974): releaseWL(31303782): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/Process (  974): killProcessQuiet, pid=4782
I/ActivityManager(  974): Killing 4782:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaProvider( 3711): [update][14]#1#
,D/MediaScanner( 3711):  prescan time: 463ms,
D/MediaScanner( 3711):     scan time: 534ms
,D/MediaScanner( 3711): postscan time: 2ms
D/MediaScanner( 3711):    total time: 999ms
D/MediaScanner( 3711): -----------------------------------------------------------------
D/MediaScanner( 3711): firstscan(media) time: 274ms
D/MediaScanner( 3711): secondscan(non-media) time: 260ms
D/MediaScanner( 3711):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3711):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0,
D/MediaScanner( 3711):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3711):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,D/MediaProvider( 3711): [delete][5],
D/MediaProvider( 3711): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3711): [recoverParentNodes] - 0
D/MediaProvider( 3711): [update][5]
D/MediaScannerServiceEx( 3711): [scan] Recover Parent Node is finished!
,D/MediaScannerServiceEx( 3711): [updateImage]+
,D/MediaScannerServiceEx( 3711): [updateImage]-0,
,I/ActivityManager(  974): Recipient 4782
,D/MediaScannerServiceEx( 3711): [1] scan finished
D/PMS     (  974): releaseWL(169a47fc): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaProviderUtils( 3711): calcVolumeId: /storage/emulated/0,
D/MediaProviderUtils( 3711): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3711): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3711): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3711): Process mounted intent for unmounted storage: /storage/ext_sd
I/CalendarProvider2( 5056): Created com.android.providers.calendar.CalendarAlarmManager@15746b9c(com.htc.providers.calendar.HtcCalendarProvider@320389a5)
D/MediaScannerServiceEx( 3711): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3711): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/CalendarProvider2( 5056): wait start:true
,D/MediaProvider( 3711): [update][10]#1#
,D/MediaProvider( 3711): [update][23]#0#
,D/MediaScannerServiceEx( 3711): [disAliveExtStorageRows]--1, 0
,D/MediaProviderUtils( 3711): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3711): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3711): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3711): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3711): Process mounted intent for unmounted storage: /storage/usb
,D/MediaScannerServiceEx( 3711): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3711): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3711): [update][7]#1#
,D/FlexNetS( 5056): updateSvcAllowedInSettings:false
,D/CalendarProvider2( 5056): wait end:false,
,D/MediaProvider( 3711): [update][37]#0#,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4312, uid=10024, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4312, uid=10024, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4312, uid=10024, userID:0,
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4312, uid=10024, userID:0
,I/art     (  974): Explicit concurrent mark sweep GC freed 14369(711KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.335ms total 157.896ms,
D/PMS     (  974): acquireWL(1cfda82c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1926 10024 WorkSource{10024 com.google.android.gms}
D/MediaScannerServiceEx( 3711): [disAliveExtStorageRows]--1, 0
D/libc    ( 1926): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1926): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1926): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1926): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1926): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1926): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1926): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  974): releaseWL(1cfda82c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  974): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5085 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/AccTypeManager( 1698): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,W/ResourcesManager( 1493): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/SystemReader(  974): Cannot find grip_rejection_width, use default value instead,
,W/ResourcesManager(  974): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/AccTypeManager( 1698): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PhoneApp( 1493): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Prism.ItemManager( 1538): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1538): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1538): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1698): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Launcher( 1538): Deferring update until onResume
D/Launcher( 1538): waitUntilResume // bindAppsUpdated
,W/PackageManager(  974): Unable to load service info ResolveInfo{2d08ac8c com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  974): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  974): ,	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  974): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  974): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  974): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  974): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  974): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  974): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  974): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  974): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  974): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  974): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  974): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  974): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  974): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  974): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,W/ContextImpl( 5085): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
E/ExternalAccountType( 1698): Unsupported attribute readOnly
,D/PowerUsageList:PowerUsageHelper( 5085): MY_DEBUG = false,
,D/PMS     (  974): acquireWL(31625cb5): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5085 1000 null,
,I/ActivityManager(  974): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5110 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,D/PowerUsageService( 5085): repeat time = 1457359021982
,D/WeatherUtility( 1456): Weather sync is On
,D/WSP     ( 1456): [Receiver] auto sync agent, auto sync is enabled, reset schedule,
,I/BackupManagerService(  974): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/GmsNetworkLocationProvi( 1818): DISABLE
,I/GCoreNlp( 1818): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SocialFeedProvider( 1538): +disConnect socialManager
I/SocialFeedProvider( 1538): disconnect socialManager
,I/SocialFeedProvider( 1538): -disConnect socialManager,
,I/ActivityManager(  974): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5136 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,D/LocationProviderProxy(  974): applying state to connected service
,D/PMS     (  974): acquireWL(1b335e7b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 5110): Weather sync is On
D/PMS     (  974): releaseWL(1b335e7b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  974): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5157 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
,D/LocationProviderProxy(  974): applying state to connected service
V/AlarmManager(  974): sending alarm PendingIntent{2299d4f1: PendingIntentRecord{3dc748d6 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1457358122093, Int=0
,I/PowerUsageList:PowerUsageHelper( 5085): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PMS     (  974): acquireWL(36c71c62): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(36c71c62): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/WeatherRequest( 5110): request cur loc, but there is no sys cur
,W/Settings( 5110): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ResourcesManager( 5136): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  974): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5178 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,D/PMS     (  974): acquireWL(c9daeb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:BatterySipperExt( 5085): gen(), null == sipper.uidObj, userId = 0
D/PMS     (  974): releaseWL(c9daeb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/ActionCombine( 5110): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/RemoteViews( 1538): reapply : com.htc.widget.weatherclock 8 17
,I/ImageRamCache( 5157): create image Cache, size: 31457280.,
I/ImageRamCache( 5157): [resize] ImageRamCache resized to: 30Mb.
,I/ImageRamCache( 5157): create image Cache, size: 31457280.
,I/FeedSettings( 5157): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5157): GroupBudget 0.500000 0.380000
,I/FeedSettings( 5157): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5157): changeLocale(): en_GB,
,I/Prism.AllAppsOptionsMa_( 5157): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 5157): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 5157): action: com.htc.sense.hsp.HANDLE_ULOG
,I/SocialManager[SocialBiLogHelper]( 5157): last commit ulog time 1457330043579
,I/SocialManager[SocialBiLogHelper]( 5157): skip commit this time,
,I/EASAppSvc( 5178): [ NA ]onCreate
,I/VersionUtil( 5178): [ NA ]setIsFOTAing: true
,I/VersionUtil( 5178): [ NA ]onUpgrade: current version=100, latest version=100,
I/VersionUtil( 5178): [ NA ]setIsFOTAing: false,
,D/HtcAdjCursorFactory( 5178): Set CursorWindow size to: 4194304 KB, Tid: 5210,
,D/ORMLib  ( 4804): put(),
,D/PowerUsageService( 5085): calcPower(), no data
I/ActivityManager(  974): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5216 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  974): Killing 3757:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=3757
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/art     (  407): Explicit concurrent mark sweep GC freed 8684(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 224us total 25.966ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 263us total 22.432ms,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 146us total 21.290ms
,I/CalendarProvider2( 5056): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 5056): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  974): Recipient 3757,
,D/Process (  974): killProcessQuiet, pid=4413
,I/ActivityManager(  974): Killing 4413:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 4413,
,D/Process (  974): killProcessQuiet, pid=4826
I/ActivityManager(  974): Killing 4826:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  974): ADD_CLIENT: 8
D/WifiService(  974): New client listening to asynchronous messages
,W/EAS_NetworkUtil( 5178): [ NA ]getNetworkInfo: NetworkInfo is null
,I/MusicStore( 5216): Database version: 120,
E/SQLiteLog( 5136): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal
,I/ActivityManager(  974): Recipient 4826
,V/AlarmManager(  974): sending alarm PendingIntent{39f5216a: PendingIntentRecord{1f89b65b com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1457358123026, Int=0
,I/EASAppSvc( 5178): [ NA ]onDestroy
I/EASAppSvc( 5178): [ NA ]> uninitEASService
I/EASAppSvc( 5178): [ NA ]onCreate
,I/EASRequestController( 5178): [ NA ]release
,I/VersionUtil( 5178): [ NA ]setIsFOTAing: true
,I/VersionUtil( 5178): [ NA ]onUpgrade: current version=100, latest version=100,
I/VersionUtil( 5178): [ NA ]setIsFOTAing: false
,D/EASPublicBinder( 5178): [ NA ]release
D/TaskBinder( 5178): [ NA ]release
D/TaskBinder( 5178): [ NA ]release
,I/EASAppSvc( 5178): [ NA ]< uninitEASService
,W/EAS_NetworkUtil( 5178): [ NA ]getNetworkInfo: NetworkInfo is null
,I/ActivityManager(  974): Killing 4601:com.google.android.partnersetup/u0a27 (adj 15): empty #17,
D/Process (  974): killProcessQuiet, pid=4601
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/ORMLib  ( 4804): put(),
,I/ActivityManager(  974): Recipient 4601,
,I/EASAppSvc( 5178): [ NA ]onDestroy
,I/EASAppSvc( 5178): [ NA ]> uninitEASService
,D/VoldConnector(  974): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5216): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/EASRequestController( 5178): [ NA ]release
,I/ActivityManager(  974): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5257 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,D/EASPublicBinder( 5178): [ NA ]release
,D/TaskBinder( 5178): [ NA ]release
D/TaskBinder( 5178): [ NA ]release
I/EASAppSvc( 5178): [ NA ]< uninitEASService
,I/Prism.ItemManager( 1538): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1538): loadItems() com.htc.launcher.pageview.WidgetManager@3fbb9d3b +
I/Prism.WidgetManager( 1538): onLoadItems() +
,I/ConfigService( 1926): onDestroy
,W/ResourcesManager( 1538): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/VoldConnector(  974): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5216): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  974): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5216): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/ActivityManager(  974): Killing 4860:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=4860
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 5216): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5216): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ORMLib  ( 4804): put()
,I/ActivityManager(  974): Recipient 4860,
,W/ResourcesManager( 1538): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/ActivityManager(  974): Killing 4883:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,D/Process (  974): killProcessQuiet, pid=4883
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,V/JNIHelp ( 5216): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 5216): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5216): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@165ab90: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5216): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5216): GMSCore installation verified
,W/asset   ( 1538): Copying FileAsset 0x555d723420 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,I/ActivityManager(  974): Recipient 4883,
,D/PhoneApp( 1493): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1493): -- N1 =0
,D/PhoneApp( 1493): -- N2 =0
,D/PhoneApp( 1493): -- N3 =0,
,E/Prism.WidgetManager( 1538): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1538): onLoadItems() -
I/Prism.ItemManager( 1538): loadItems() com.htc.launcher.pageview.WidgetManager@3fbb9d3b -
,I/ActivityManager(  974): Waited long enough for: ServiceRecord{331031a u0 com.htc.backup/.notifications.contextual.ContextualReminderControlService},
,I/ConfigStore( 5216): Config Database version: 1
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5216, uid=10159, userID:0,
,D/WifiDisplayAdapter(  974): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  974):     Client/Owner: Client
D/WifiDisplayAdapter(  974):     GroupId: 
D/WifiDisplayAdapter(  974):     Passphrase: 
D/WifiDisplayAdapter(  974):     SessionId: 0
D/WifiDisplayAdapter(  974):     IP Address: }
,D/MediaRouterService(  974): Client com.google.android.music (pid 5216): Registered
,D/WifiDisplayAdapter(  974): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  974):     Client/Owner: Client
D/WifiDisplayAdapter(  974):     GroupId: 
D/WifiDisplayAdapter(  974):     Passphrase: 
D/WifiDisplayAdapter(  974):     SessionId: 0
D/WifiDisplayAdapter(  974):     IP Address: }
,I/MediaRouter( 5216): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,D/TelephonyReceiver( 1493): bind: true,
,I/ActivityManager(  974): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5290 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  974): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5305 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/HtcModeClient( 3171): handler message = 4011,
E/HtcModeClient( 3171): Check connection and retry 5 times.
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5216, uid=10159, userID:0,
,I/GHttpClientFactory( 5216): Using our fixed implementation of GMSCore's GoogleHttpClient,
D/DFPI.PIReciver( 5290): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/GoogleURLConnFactory( 5216): Using platform SSLCertificateSocketFactory
,I/DFPI.ApkInstallService( 5290): onHandleIntent
I/DFPI.ApkInstallService( 5290): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5290): check CID = HTC__102,
I/DFPI.ApkInstallService( 5290): There is no Demo.apk in sd card or phone storage
,W/HtcWrapAdjustableCursorFactory( 5305): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 5305): onCreate,
I/ActivityManager(  974): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5339 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/art     (  974): Explicit concurrent mark sweep GC freed 29992(1549KB) AllocSpace objects, 2(336KB) LOS objects, 33% free, 16MB/24MB, paused 1.732ms total 168.347ms,
,V/GetPrviateResource( 5305): GetPrviateResource
I/ActivityManager(  974): Killing 4249:com.android.vending/u0a72 (adj 15): empty #17
V/GetPrviateResource( 5305): GetPrviateResource
D/Process (  974): killProcessQuiet, pid=4249
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  974): releaseWL(31625cb5): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/MessageCustFlag( 5305): sense_version=6.0,
,D/GenericMessagesProvider( 5305): query uri: content://htc-messages/wappush/count
,D/BTAccessoryUtil( 5305): createReceiver
,E/SQLiteLog( 5305): (14) cannot open file at line 30058 of [9491ba7d73]
,E/SQLiteLog( 5305): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 5305): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5305): DB info: errno = 2, errno message = No such file or directory
,E/SQLiteDatabase( 5305): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 5305): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5305): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5305): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5305): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5305): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5305): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5305): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5305): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5305): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5305): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5305): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5305): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 5305): ,	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5305): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5305): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5305): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 5305): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5305): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5305): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/System.err( 5305): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5305): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 5305): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5305): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5305): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/System.err( 5305): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5305): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 5305): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 5305): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 5305): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5305): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5305): ,	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
W/System.err( 5305): 	at android.os.Binder.execTransact(Binder.java:454)
,I/ActivityManager(  974): Recipient 4249
,I/ActivityManager(  974): Killing 4918:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=4918
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/PMS     (  974): acquireWL(3b27ad15): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 974 1000 null,
I/BatteryService(  974): n_update end
D/PMS     (  974): releaseWL(3b27ad15): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  974): Recipient 4918,
,D/TelephonyReceiver( 1493): switchBindHtcMsgCursor: null
,D/HtcPowerSaver(  974): updateBatteryInfo
D/BTAccessoryUtil( 5305): registerReceiver return intent = null
D/PowerUI ( 1233): closing low battery warning: level=100
D/MessageCustFlag( 5305): sku_id=118
D/PowerUI ( 1233): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcBuildUtils( 5305): getRATByHtcTelephonyCapability:1
D/DotMatrix( 1319): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1319): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1319): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
W/SystemReader( 5305): Cannot find qct_8960_interface, use default value instead
I/IntentController( 1233): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  974): plugged=true pluggin=true
D/UsbnetService(  974): BroadcastReceiver::onReceive+
D/UsbnetService(  974): onReceive BATTERY_CHANGED
D/PMS     (  974): runPSCheck
D/UsbnetService(  974):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  974): Checking...
D/UsbnetService(  974): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  974): >> updateStatus
D/WifiController(  974): handleMessage: E msg.what=155652
D/WifiController(  974): battery changed pluggedType: 2
D/WifiController(  974): processMsg: ApStaDisabledState
D/WifiController(  974): processMsg: DefaultState
D/WifiController(  974): handleMessage: X
,I/HtcPowerSaver(  974): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  974): << updateStatus
,I/ActivityManager(  974): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5364 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,D/VoldConnector(  974): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/},
,I/BatteryController( 1233): status:5 level:100 unsupport:false plugged:true,
W/ContextImpl( 5339): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache,
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5364): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5364): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5364): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/PMS     (  974): acquireWL(88f0585): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5056 10011 null
,D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm),
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
D/DFPI.PIReciver( 5290): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
E/SQLiteLog( 5056): (284) automatic index on view_events(_id)
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5364): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/DFPI.ApkInstallService( 5290): onHandleIntent
I/DFPI.ApkInstallService( 5290): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5290): check CID = HTC__102
I/DFPI.ApkInstallService( 5290): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5364): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/PMS     (  974): releaseWL(88f0585): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null,
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/DFPI.PIReciver( 5290): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
I/DFPI.ApkInstallService( 5290): onHandleIntent
,I/DFPI.ApkInstallService( 5290): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5290): check CID = HTC__102,
I/DFPI.ApkInstallService( 5290): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/DFPI.PIReciver( 5290): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/DFPI.ApkInstallService( 5290): onHandleIntent
I/DFPI.ApkInstallService( 5290): Media Scan Finished Case 
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
D/DFPI.ApkInstallService( 5290): check CID = HTC__102
I/DFPI.ApkInstallService( 5290): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] startService,
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  974): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5396 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a,
,I/SoundPicker( 5364): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
V/SoundPicker( 5364): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 5364): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5,
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96,
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5364): TurnFileToMediaUriService [checkFileExistence],
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2),
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/MediaStoreImporter( 5216): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/DFPI.PIReciver( 5290): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/DFPI.ApkInstallService( 5290): onHandleIntent
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
I/DFPI.ApkInstallService( 5290): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5290): check CID = HTC__102
I/DFPI.ApkInstallService( 5290): There is no Demo.apk in sd card or phone storage,
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5364): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5364): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5364): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5364): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/DFPI.PIReciver( 5290): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/DFPI.ApkInstallService( 5290): onHandleIntent
I/DFPI.ApkInstallService( 5290): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5290): check CID = HTC__102
I/DFPI.ApkInstallService( 5290): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5,
I/MediaStoreImporter( 5216): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,D/DFPI.PIReciver( 5290): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5290): onHandleIntent
,I/DFPI.ApkInstallService( 5290): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5290): check CID = HTC__102,
I/DFPI.ApkInstallService( 5290): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] startService
,D/TelephonyReceiver( 1493): bind: false,
,D/TelephonyReceiver( 1493): switchBindHtcMsgCursor: null
I/art     ( 3711): Explicit concurrent mark sweep GC freed 55440(3MB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1531KB/5MB, paused 630us total 43.114ms
D/GCM     ( 1926): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,D/AuthorizationBluetoothService( 1926): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,V/GmsCoreStatsServiceLauncher( 4312): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4312, uid=10024, userID:0
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
D/WearableService( 4666): callingUid 10024, callindPid: 4666
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,E/MDM     ( 1818): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4312): Restart initialization of location
I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/GCM     ( 1926): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1926): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/MediaStoreImporter( 5216): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
V/GmsCoreStatsServiceLauncher( 4312): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5364): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5364): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5364): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4312, uid=10024, userID:0
,E/MDM     ( 1818): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/LocationInitializer( 4312): Restart initialization of location
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/MediaStoreImporter( 5216): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5364): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5364): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5364): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/ActionCombine( 5396): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/DotMatrix( 1319): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/RemoteViews( 1233): setHTCTheme(com.htc.updater,true,33751145)
I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/MediaStoreImporter( 5216): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
I/RemoteViews( 1233): apply : com.htc.updater 0 14 2 36
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,D/PMS     (  974): acquireWL(3e02ee56): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1926 10024 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
D/PMS     (  974): releaseWL(3e02ee56): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
D/PMS     (  974): acquireWL(3861ded7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1926 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,D/PMS     (  974): releaseWL(3861ded7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5364): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5364): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5364): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/FindExtension( 1233): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1233): Defer allocateBuffers to drawing time
I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5364): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5364): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5364): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/art     (  974): Explicit concurrent mark sweep GC freed 13106(612KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 3.333ms total 183.454ms
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/PMS     (  974): acquireWL(2359722e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1926 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,D/PMS     (  974): releaseWL(2359722e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/ActivityManager(  974): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5438 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/art     ( 3711): Explicit concurrent mark sweep GC freed 4719(212KB) AllocSpace objects, 0(0B) LOS objects, 73% free, 1486KB/5MB, paused 7.013ms total 34.471ms
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/MediaStoreImporter( 5216): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  974): Killing 4964:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,D/Process (  974): killProcessQuiet, pid=4964
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PhoneMonitor( 5438): Register our PhoneStateListener
,I/ActivityManager(  974): Recipient 4964
,I/ActivityManager(  974): Killing 4569:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  974): killProcessQuiet, pid=4569
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 5438): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 5438): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  974): Recipient 4569
,D/WifiService(  974): Client connection lost with reason: 4
,D/GCM     ( 1926): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,D/ChimeraCfgMgr( 4312): Loading module com.google.android.gms.kids from APK com.google.android.gms,
I/Kids    ( 4312): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/ActivityManager(  974): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5462 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/ActivityManager(  974): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/GAV2    ( 5462): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 5462): getAccountsCursor
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=5462, uid=10106, userID:0,
W/ActivityManager(  974): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  974): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5462): Observing account changes for notifications
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5462, uid=10106, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5462, uid=10106, userID:0
,W/ActivityManager(  974): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  974): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5496 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,E/Gmail   ( 5462): Error finding the version of the Email provider.....,
E/Gmail   ( 5462): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5462): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5462): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5462): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5462): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5462): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5462): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 5462): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5462): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5462): getAccountsCursor
,D/Process (  974): killProcessQuiet, pid=4999,
,I/ActivityManager(  974): Killing 4999:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5496): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  974): Recipient 4999
D/WifiService(  974): Client connection lost with reason: 4
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/SQLiteLog( 5462): (283) recovered 1492 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal,
,D/Messaging( 5305): supportCMAS(SIE)/init? false/true,
,D/MmsConfig( 5305): networkCode: 
,D/MessageCustFlag( 5305): sku_id=118
,D/MmsConfig( 5305): SIE smsPri: null
,D/MmsConfig( 5305): networkCode: 
,D/MmsConfig( 5305): packageName: com.htc.vvm.att does not exist,
,D/Messaging( 5305): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 5305): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 5305): 
D/MmsAsyncWorkHandler( 5305): HM tk = 20001
D/ReportIndicatorCache( 5305): MSG_QUERY_REPORTS >>
D/SettingsManager( 5305): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@15746b9c
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1493): sku_id=118
D/DraftCache( 5305): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5305): [DraftCache/1] refresh
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1493):  slotId = -1000
,D/MmsSmsV2Provider( 1493): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MmsConfig( 5305): networkCode: 
,D/DraftCache( 5305): [DraftCache/121] rebuildCache
,D/Messaging( 5305): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1493):  slotId = -1000
D/MmsSmsV2Provider( 1493): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,I/Messaging( 5305): mccmnc> 
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/MmsSmsV2Provider( 1493):  slotId = -1000
D/MmsSmsV2Provider( 1493): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 5305): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1493):  slotId = -1000
D/MmsSmsV2Provider( 1493): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 5305): mNeedToUpdateDate2: false
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/Jerry   ( 1493): URI_DRAFT
,D/DraftCache( 5305): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 5305): [DraftCache/121] rebuildCache time: 13
D/MmsAsyncWorkHandler( 5305): 
D/MmsAsyncWorkHandler( 5305): HM tk = 20002
,D/PhoneStorageUtil( 5305): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5305): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5305): createReceiver
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1493): sku_id=118
,D/MessageCustFlag( 5305): sense_version=6.0
D/Jerry   ( 5305): start to preload cursor >>>>>>>
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1493):  slotId = -1000
,I/Gmail   ( 5462): notifyAccountChanged,
,D/TelephUtils( 1493): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
V/MmsProvider( 1493): Update uri=content://mms, match=0
V/MmsProvider( 1493): selection=st=129 AND m_type!=134
D/Messaging( 5305): Reset downloading state: 0
V/MmsSystemEventReceiver( 5305): TransactionService is going to be woken up.
D/Messaging( 5305): ViewCache CreatePreload
D/Messaging( 5305): ViewCache CreatePreloadOnlyMultipleOpsList
,I/Gmail   ( 5462): getAccountsCursor
,V/TransactionService( 5305): 1-Creating TransactionService
I/Gmail   ( 5462): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
,D/AccFlag ( 1493): sku_id=118
V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/TransactionService( 5305): onStartCommand: 1
D/MmsSystemEventReceiver( 5305): unRegisterForConnectionStateChanges
,V/TransactionService( 5305): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5305): Loading previous transactions.
D/Cust_MMSMS( 5305): _has_set_default_values_2=true
I/Gmail   ( 5462): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/MsgPreferenceUtils( 5305): def_index: 0
,D/MsgPreferenceUtils( 5305): globalIndex = 1
,D/TelephUtils( 1493): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/AccFlag ( 1493): device_type: 1
,I/Gmail   ( 5462): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5462): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/MsgPreferenceUtils( 5305): phone state: true
D/MsgPreferenceUtils( 5305): sd state: false
D/MsgPreferenceUtils( 5305): vIndex = 0
,D/TransactionService( 5305): Force clearing mTransactionList
D/TransactionService( 5305): Force set service start id to 1
V/TransactionService( 5305): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5305): unRegisterForConnectionStateChanges
D/TransactionService( 5305): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 5305): Destroying TransactionService
,V/TransactionService( 5305): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,I/Babel_SMS( 5496): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5496): MmsConfig.loadMmsSettings,
,D/MmsCustomizationProvider( 5305): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 5305): query uri: content://htc-mms-customization/mms-ua/ua_profile,
,I/Gmail   ( 5462): master sync=false, engine sync=true
,I/Babel_SMS( 5496): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml,
I/Babel_SMS( 5496): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5496): canonicalizeMccMnc: invalid mccmnc ,
,I/Babel_SMS( 5496): MmsConfig.loadFromResources
E/Babel_SMS( 5496): canonicalizeMccMnc: invalid mccmnc nullnull,
I/Babel_SMS( 5496): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5496, uid=10112, userID:0
,W/Settings( 5496): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/art     ( 1926): Explicit concurrent mark sweep GC freed 9774(482KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 662us total 34.607ms
,I/Babel_Crash( 5496): startup - clean
,I/Babel   ( 5496): deleted: false for 0
,I/Gmail   ( 5462): getAccountsCursor
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/Gmail   ( 5462): master sync=false, engine sync=true
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5496, uid=10112, userID:0,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5496, uid=10112, userID:0
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5496, uid=10112, userID:0,
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5496, uid=10112, userID:0,
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5496, uid=10112, userID:0
,D/PMS     (  974): acquireWL(2ff3a84c): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5496 10112 null,
,W/VideoCapabilities( 5496): Unrecognized profile 2130706433 for video/avc
,D/AuthorizationBluetoothService( 1926): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1926): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/GmsCoreStatsServiceLauncher( 4312): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4312, uid=10024, userID:0
,E/MDM     ( 1818): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4312): Restart initialization of location
,W/VideoCapabilities( 5496): Unsupported mime video/x-ms-wmv,
D/DFPI.PIReciver( 5290): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/NotifUtils( 5462): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false,
W/Utils   ( 5496): could not parse size range '64x64-1920X1080'
,I/DFPI.ApkInstallService( 5290): onHandleIntent
I/DFPI.ApkInstallService( 5290): Media Scan Finished Case 
W/AudioCapabilities( 5496): Unsupported mime audio/qcelp
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/AudioCapabilities( 5496): Unsupported mime audio/x-ms-wma
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] startService
,W/AudioCapabilities( 5496): Unsupported mime audio/qcelp
I/SoundPicker( 5364): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5364): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5364): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
,D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5364): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/DFPI.ApkInstallService( 5290): check CID = HTC__102
I/DFPI.ApkInstallService( 5290): There is no Demo.apk in sd card or phone storage
W/VideoCapabilities( 5496): Unsupported mime video/x-ms-wmv
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/NotifUtils( 5462): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,D/DFPI.PIReciver( 5290): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/DFPI.ApkInstallService( 5290): onHandleIntent
I/DFPI.ApkInstallService( 5290): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5290): check CID = HTC__102,
I/DFPI.ApkInstallService( 5290): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
D/DFPI.PIReciver( 5290): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/DFPI.ApkInstallService( 5290): onHandleIntent,
I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/DFPI.ApkInstallService( 5290): Media Scan Finished Case 
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
D/DFPI.ApkInstallService( 5290): check CID = HTC__102
I/DFPI.ApkInstallService( 5290): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5364): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/VideoCapabilities( 5496): Unsupported profile 4 for video/mp4v-es
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,W/VideoCapabilities( 5496): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5496): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5496): Unrecognized profile 2130706433 for video/avc
,I/MediaStoreImporter( 5216): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/art     (  974): Explicit concurrent mark sweep GC freed 10047(494KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.605ms total 149.999ms
,W/VideoCapabilities( 5496): Unrecognized profile 2130706433 for video/avc,
,I/art     ( 5364): Explicit concurrent mark sweep GC freed 11743(771KB) AllocSpace objects, 2(40KB) LOS objects, 87% free, 304KB/2MB, paused 310us total 30.517ms,
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5364): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5364): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5364): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma),
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/MediaStoreImporter( 5216): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/vclib   ( 5496): onServiceConnected
,W/Babel   ( 5496): Attempted to change video mute state without an active call.,
,I/ActivityManager(  974): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5581 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,W/ResourcesManager( 5496): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5496): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5364): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5364): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm),
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122,
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96,
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5364): TurnFileToMediaUriService [checkFileExistence]
,D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/MediaStoreImporter( 5216): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5364): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac,
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5364): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5364): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5364): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/LocationManagerService(  974): getProviders()=[passive],
,V/JNIHelp ( 5496): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  974): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5607 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,D/Process (  974): killProcessQuiet, pid=4155,
I/ActivityManager(  974): Killing 4155:com.android.settings/1000 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,W/System  ( 5496): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 5496): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  974): Recipient 4155,
,D/Process (  974): killProcessQuiet, pid=5033
I/ActivityManager(  974): Killing 5033:com.htc.backupreset/1000 (adj 15): empty #17
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
,I/[PluginManager]RegisterService( 1456): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1456): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  974): Recipient 5033
,I/ActivityManager(  974): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5631 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/Babel   ( 5496): connection state changed from UNKNOWN to DISCONNECTED,
,E/PhoneInterfaceManager( 1493): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/VideoCapabilities( 5496): Unrecognized profile 2130706433 for video/avc,
W/VideoCapabilities( 5496): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5496): Unrecognized profile 2130706433 for video/avc
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5631): -onCreate(),
,D/PMS     (  974): releaseWL(2ff3a84c): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,V/Settings:HtcSettingsApplication( 5631): [5631/5631] onCreate()
,I/ActivityManager(  974): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5659 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  974): killProcessQuiet, pid=5085,
I/ActivityManager(  974): Killing 5085:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/Settings:HtcWirelessFeatureFlags( 5631): id/is att sku: 118/false,
,E/Settings:HtcWrapHeaderInfo( 5631): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5631): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5631): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5631): isSupportMusicChannel(): false
,I/ActivityManager(  974): Recipient 5085
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportHomeButton]support         :false
,V/AlarmManager(  974): sending alarm PendingIntent{813ddb2: PendingIntentRecord{27add103 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1457358128512, Int=0,
,I/ActivityManager(  974): Cannot resolve ContentProvider=com.htc.vowifi,
E/ActivityThread( 5631): Failed to find provider info for com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 5631): isSupportVoWifi: null,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5631): The wrap header doesn't exist in header list.,
E/Settings:HtcWrapHeaderInfo( 5631): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5631): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportRecentAppsButton]support         :false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5631): [supportHomeButton]support         :false
,E/Settings:HtcVoWifiWidgetEnabler( 5631): isSupportVoWifi: null
I/ActivityManager(  974): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5631): Failed to find provider info for com.htc.vowifi
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5659, uid=10072, userID:0
,W/global  ( 5659): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5659): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 5659): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5659): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5659): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  974): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5699 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 5659): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5659): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/art     (  407): Explicit concurrent mark sweep GC freed 8644(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 302us total 30.926ms
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5659, uid=10072, userID:0,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 243us total 26.235ms
,W/ResourcesManager( 5699): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5699): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 240us total 25.469ms,
,D/Finsky  ( 5659): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5659): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5659): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
I/MultiDex( 5699): VM with version 2.1.0 has multidex support,
I/MultiDex( 5699): install
I/MultiDex( 5699): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5699): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/PackageBroadcastService( 4312): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5659): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,I/ActivityManager(  974): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5727 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Process (  974): killProcessQuiet, pid=5110,
I/ActivityManager(  974): Killing 5110:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/PackageBroadcastService( 4312): Null package name or gms related package.  Ignoreing.
,W/ActivityThread( 5699): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5699): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35054356: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5699): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  974): Recipient 5110
,D/PMS     (  974): acquireWL(b5b1762): PARTIAL_WAKE_LOCK  Icing 0x1 4312 10024 WorkSource{10024 com.google.android.gms}
,I/Icing   ( 4312): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5727): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,D/PMS     (  974): releaseWL(b5b1762): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/HtcModeClient( 3171): handler message = 4011
,E/HtcModeClient( 3171): Check connection and retry 6 times.
,D/PMS     (  974): acquireWL(20e328dc): PARTIAL_WAKE_LOCK  AsyncService 0x1 5727 10167 null,
,D/PMS     (  974): releaseWL(20e328dc): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,D/PMS     (  974): acquireWL(ad430ba): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5727 10167 null
,I/UpdateIcingCorporaServi( 5581): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  974): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5763 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,D/PMS     (  974): releaseWL(ad430ba): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/Process (  974): killProcessQuiet, pid=4804
,I/ActivityManager(  974): Killing 4804:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 4804
,I/UpdateIcingCorporaServi( 5581): UpdateCorporaTask done [took 156 ms] updated apps [took 155 ms] ,
,D/Process (  974): killProcessQuiet, pid=5157
I/ActivityManager(  974): Killing 5157:com.htc.sense.news/u0a74 (adj 15): empty #17
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 5763): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  974): Recipient 5157,
,V/AlarmManager(  974): sending alarm PendingIntent{14e9b774: PendingIntentRecord{3520a49d com.android.vending startService}}, i=null, t=0, cnt=1, w=1457358129726, Int=0
V/Finsky  ( 5659): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,D/CalendarApplication( 5763): onCreate
,D/Finsky  ( 5659): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ProviderChangeReceiver( 5763): ---------------------------------------------------,
D/ProviderChangeReceiver( 5763): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/HtcAlertService( 5763): start to updateAlertNotification!,
,I/art     (  974): Explicit concurrent mark sweep GC freed 10072(536KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.815ms total 164.988ms
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/WSP     ( 1456): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1456): Weather sync is On
,I/ActivityManager(  974): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5791 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/WSP     ( 1456): [Receiver] next auto-sync alarm event is 60 mins later, at time: Mon Mar 07 15:42:10 CET 2016,
,W/WSP     ( 1456): [Receiver] can't get active network info
,D/HtcAlertService( 5763): No fired or scheduled alerts
,D/HtcAlertUtils( 5763): -- cancelReminderNotification --
D/HtcAlertUtils( 5763): broadcastExistReminder!
,D/DotMatrix( 1319): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/GLSUser ( 1926): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1926): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1926): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1926): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WSP     ( 1456): [SyncService] no data connection, stop sync service,
,W/ResourcesManager( 5791): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/Finsky  ( 5659): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/ActivityManager(  974): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5816 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,I/Task_Calendar( 5791): Set ICALENDAR_UID to sync_data7 due to SDK_INT is 21
,D/TodoTaskshortcut( 5791): update TASK shortcut>
,I/GLSUser ( 1926): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1926): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1926): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1926): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncApplication( 5816): Loading default preferences,
V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Resources( 5816): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/GLSUser ( 1926): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1926): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1926): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1926): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5659): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,E/WifiTrafficPoller(  974): ADD_CLIENT: 7,
D/WifiService(  974): New client listening to asynchronous messages
,D/SyncApplication( 5816): Overriding preferences with custom values
,D/SyncApplication( 5816): Updating preferences succeeded,
E/SyncApplication( 5816): Application created.
,W/VolumeInfo( 5816): Unable to read mount points
W/VolumeInfo( 5816): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5816): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5816): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5816): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5816): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5816): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5816): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5816): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5816): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5816): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5816): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5816): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5816): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5816): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
W/VolumeInfo( 5816): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5816): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5816): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5816): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5816): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5816): 	... 13 more
V/VolumeInfo( 5816): Found 0 mount point(s)
V/VolumeInfo( 5816): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,I/CalendarDefines( 5816): getNewCalendarAuthority()...,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5816, uid=10005, userID:0,
,W/PackageManager(  974): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5816, uid=10005, userID:0
W/PackageManager(  974): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 5816): enableAppOperation()+
,D/VolumeInfo( 5816): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/SyncApplication( 5816): enableAppOperation()-
,D/HTCUtilities( 5816): isNeorSinged() + 
,D/VolumeInfo( 5816): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 5816): Can not create volume ID for unmounted volume null
,I/ActivityManager(  974): Waited long enough for: ServiceRecord{2e36a712 u0 com.htc.club/com.mcrm.autonotification.NotificationService}
,D/HTCUtilities( 5816): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>,
D/HTCUtilities( 5816): isNeorSinged() return false
,E/AndroidHttpClient( 5659): Leak found
E/AndroidHttpClient( 5659): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5659): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5659): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5659): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5659): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
,E/AndroidHttpClient( 5659): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5659): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5659): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5659): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
,E/AndroidHttpClient( 5659): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5659): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5659): ,	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5659): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5659): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5659): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5659): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
,E/AndroidHttpClient( 5659): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/CDMountReceiver( 5816): whether to enable CD Auto-mount: true,
D/CDMountReceiver( 5816): showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,I/ActionCombine( 5816): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,D/CDMountReceiver( 5816): enable CD Auto-mount: true,
,D/DotMatrix( 1319): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
D/PMS     (  974): releaseWL(231ad9a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10005}
D/HTCUtilities( 5816): enable auto-mount
D/VoldConnector(  974): SND -> {21 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
D/HTCUtilities( 5816): enable auto-mount
I/HtcMountManagerAdapter( 5816): mHtcMountManager is  null
I/HtcMountManagerAdapter( 5816): mStorageManager is  not null
D/PMS     (  974): acquireWL(366df1b1): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5216 10159 null
I/HtcMountManagerAdapter( 5816): mHtcMountManager is  null
I/HtcMountManagerAdapter( 5816): mStorageManager is  not null
,D/VoldConnector(  974): SND -> {22 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
,D/MountService(  974): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  974): mountISO: /system/etc/PCTOOL.ISO
,I/RemoteViews( 1233): apply : com.nero.android.htc.sync 0 12 4 38
,I/RemoteViews( 1233): apply : com.nero.android.htc.sync 0 13 3 53
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5216, uid=10159, userID:0
,D/PMS     (  974): releaseWL(366df1b1): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 5216): Conditions not met for autocaching. okToAttempt=false,
I/MusicLeanback( 5216): Stop autocaching.
,D/GCM     ( 1926): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1926): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4312): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4312, uid=10024, userID:0
,E/MDM     ( 1818): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
D/LocationInitializer( 4312): Restart initialization of location
,E/GmsUtils( 5216): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5216): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Process (  974): killProcessQuiet, pid=5178
I/ActivityManager(  974): Killing 5178:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 5178
,D/WifiService(  974): Client connection lost with reason: 4
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1926): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1926): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1926): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1926): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1926): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5659): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 5659): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5659): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 5659): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/Finsky  ( 5659): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive
,D/Process (  974): killProcessQuiet, pid=5056
I/ActivityManager(  974): Killing 5056:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/DeviceConnectionService( 1818): client connected with version: 7571000
,I/ActivityManager(  974): Recipient 5056,
,D/Process (  974): killProcessQuiet, pid=5257
I/ActivityManager(  974): Killing 5257:com.htc.task.gtask/u0a66 (adj 15): empty #18
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 5257,
,I/GAV2    ( 5462): Thread[GAThread,5,main]: No campaign data found.,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4312, uid=10024, userID:0,
,I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4312, uid=10024, userID:0
I/PackageManager(  974):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4312, uid=10024, userID:0
I/CheckinService( 4312): Done disabling old GoogleServicesFramework version
,D/AutoSetting( 1456): service - handleMessage() stop self,
,D/AutoSetting( 1456): service - handleMessage() quit looper
,D/AutoSetting( 1456): service - onDestroy() END
,I/HtcModeClient( 3171): handler message = 4011,
,E/HtcModeClient( 3171): Check connection and retry 7 times.
,D/Process (  974): killProcessQuiet, pid=5396
I/ActivityManager(  974): Killing 5396:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 5396
,D/Process (  974): killProcessQuiet, pid=5438
I/ActivityManager(  974): Killing 5438:com.google.android.setupwizard/u0a77 (adj 15): empty #17,
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 5438,
,I/art     (  974): Explicit concurrent mark sweep GC freed 15409(675KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.362ms total 141.114ms,
,I/HtcModeClient( 3171): handler message = 4011
E/HtcModeClient( 3171): Check connection and retry 8 times.
,W/MediaManager( 5136): [DualLensScanUtil],	mmpCursor count is 0
,D/Process (  974): killProcessQuiet, pid=5305
,I/ActivityManager(  974): Killing 5305:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 5305
,I/ActivityManager(  974): Waited long enough for: ServiceRecord{7630591 u0 com.htc.musicenhancer/.EnhancerService},
,D/Process (  974): killProcessQuiet, pid=5290
I/ActivityManager(  974): Killing 5290:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 5290
,I/HtcModeClient( 3171): handler message = 4011
,E/HtcModeClient( 3171): Check connection and retry 9 times.
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ContactMessageStore( 1493): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1493): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  974): acquireWL(34a52d82): PARTIAL_WAKE_LOCK  *alarm* 0x1 974 1000 WorkSource{10072},
,V/AlarmManager(  974): sending alarm PendingIntent{32be2c93: PendingIntentRecord{193ff4d0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457358145245, Int=0,
V/AlarmManager(  974): sending alarm PendingIntent{25b2ccc9: PendingIntentRecord{2c68bdad com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=88438, Int=0
V/AlarmManager(  974): sending alarm PendingIntent{33fc9fce: PendingIntentRecord{294feef android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=84890, Int=0
V/AlarmManager(  974): sending alarm PendingIntent{1af78dfc: PendingIntentRecord{35926c85 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=85271, Int=0
,D/PMS     (  974): acquireWL(2046eada): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1926 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1926): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1926): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1926): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1926): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1926): [NET] android_getaddrinfo_proxy+
D/libc    ( 1926): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1926): [NET] android_getaddrinfo_proxy-, NODATA
,D/libc    (  974): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
,D/libc    (  974): [NET] android_getaddrinfofornet-, err=8
D/libc    (  974): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/PMS     (  974): releaseWL(34a52d82): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  974): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  974): [NET] android_getaddrinfo_proxy+
D/libc    (  974): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  974): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  974): releaseWL(2046eada): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/Finsky  ( 5659): [567] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5659): [1] 5.onFinished: Installation state replication succeeded.
,I/HtcModeClient( 3171): handler message = 4011,
E/HtcModeClient( 3171): Check connection and retry 10 times.,
,I/HtcModeClient( 3171): handler message = 4011,
,E/HtcModeClient( 3171): Check connection and retry 11 times.
,D/PMS     (  974): acquireWL(1b7dce7): PARTIAL_WAKE_LOCK  Icing 0x1 4312 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  974): releaseWL(1b7dce7): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  974): acquireWL(3b56a73d): PARTIAL_WAKE_LOCK  Icing 0x1 4312 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(3b56a73d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): acquireWL(2ba981df): PARTIAL_WAKE_LOCK  Icing 0x1 4312 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  974): releaseWL(2ba981df): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): acquireWL(21a080f5): PARTIAL_WAKE_LOCK  Icing 0x1 4312 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(21a080f5): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  974): acquireWL(314e5cfb): PARTIAL_WAKE_LOCK  Icing 0x1 4312 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  974): releaseWL(314e5cfb): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl(  974): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/HtcModeClient( 3171): handler message = 4011,
,E/HtcModeClient( 3171): Check connection and retry 12 times.
,I/HtcModeClient( 3171): handler message = 4011,
E/HtcModeClient( 3171): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3171): Don't start project servcice
,D/HtcModeClient( 3171): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 3171): connectState: CONNECTION_READY = false,
D/SilentMusic( 3171): call stop,
,D/HtcModeClient( 3171): close connection
W/HtcModeClient( 3171): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3171): read the terminate packet, so break
I/ActivityManager(  974): Killing 3171:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=3171
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 3171
,I/ActivityManager(  974): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5877 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/PMS     (  974): acquireWL(3d44118): PARTIAL_WAKE_LOCK  *alarm* 0x1 974 1000 WorkSource{10076}
,V/AlarmManager(  974): sending alarm PendingIntent{3dc53771: PendingIntentRecord{36433956 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457358165275, Int=60000
D/PMS     (  974): releaseWL(3d44118): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 5877): SMSBackupAgentService started,
D/SMSBackup( 5877): Checking restore status,
,D/SMSBackup( 5877): Restore complete,
D/SMSBackup( 5877): cancelCheckAlarm
,D/SMSBackup( 5877): SMSBackupAgentService completed: completed in 0.0 seconds
,I/ActivityManager(  974): Killing 5364:com.htc.sdm/u0a79 (adj 15): empty #17,
D/Process (  974): killProcessQuiet, pid=5364
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 5364,
,I/PMS     (  974): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  974): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3c669aae
W/SensorService(  974): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  974): disable: get sensor name = Accelerometer Sensor
W/SensorService(  974): pid=974, uid=1000
,W/SensorService(  974): Active sensors: size = 4
W/PMN     (  974): goingToSleep
W/SensorService(  974): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  974): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  974): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  974): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  974): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3c669aae, eanble = 0, strlen(mName) = 91
W/SensorService(  974): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  974): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@136b7597
W/SensorService(  974): Listener[1] = com.htc.smartdim.sensor_eye@2aa47141
W/SensorService(  974): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1233): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off,
,W/PMS     (  974): mWirelessDisplayManager is null
I/PMS     (  974): Sleeping (uid 1000)...
D/XAN-DPS (  974): prepareColorFade 1
D/PMS     (  974): acquireWL(3a5856c4): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 974 1000 null
,W/PMS     (  974): mWirelessDisplayManager is still null
W/PMN     (  974): goingToSleep done
,D/PMS     (  974): releaseWL(3a5856c4): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,W/HtcSystemUPManager(  974): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,I/ActivityManager(  974): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5900 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/AlarmManager(  974): ACTION_SCREEN_ON
,I/Adreno-EGL(  974): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  974): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  974): Build Date: 03/09/15 Mon
I/Adreno-EGL(  974): Local Branch: 
I/Adreno-EGL(  974): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  974): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  974):                  d74aa161a12b9c6fc6332151
,I/AlarmManager(  974): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  974): [AlarmQueuing] done recovering
I/AlarmManager(  974): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  974): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiStateMachine(  974): handleMessage: E msg.what=131167
E/WifiStateMachine(  974): processMsg: InitialState
E/WifiStateMachine(  974):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  974): processMsg: DefaultState
E/WifiStateMachine(  974):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
,V/SRS_Proc(  400): ParamSet string: screen_state=on
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  974):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiController(  974): handleMessage: E msg.what=155650,
D/WifiController(  974): processMsg: ApStaDisabledState
D/WifiController(  974): processMsg: DefaultState
D/WifiController(  974): handleMessage: X
D/GpsLocationProvider(  974): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/NetworkPolicy(  974): updateScreenOn: false
V/NetworkPolicy(  974): updateIfacesLocked()
,D/NetworkManagementService(  974): isBandwidthControlEnabled: doneSignal.getCount()= 0
,W/ResourcesManager( 5900): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/WifiStateMachine(  974): getWifiLinkLayerStats: WIFI is not enbled
D/WifiStateMachine(  974): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  974): handleScreenStateChanged Exit: true
E/WifiStateMachine(  974): handleMessage: X
E/WifiStateMachine(  974): handleMessage: E msg.what=131154
E/WifiStateMachine(  974): processMsg: InitialState
E/WifiStateMachine(  974):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  974): processMsg: DefaultState
,E/WifiStateMachine(  974):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0,
E/WifiStateMachine(  974): handleMessage: X
E/WifiStateMachine(  974): handleMessage: E msg.what=131127
E/WifiStateMachine(  974): processMsg: InitialState
E/WifiStateMachine(  974):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  974): processMsg: DefaultState
E/WifiStateMachine(  974):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  974): handleMessage: X
E/WifiStateMachine(  974): handleMessage: E msg.what=131129
E/WifiStateMachine(  974): processMsg: InitialState
E/WifiStateMachine(  974):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  974): processMsg: DefaultState
E/WifiStateMachine(  974):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  974): handleMessage: X
,D/DotMatrix( 1319): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/CalendarProvider2( 5900): Created com.android.providers.calendar.CalendarAlarmManager@15746b9c(com.htc.providers.calendar.HtcCalendarProvider@320389a5),
,I/IntentController( 1233): receive(android.intent.action.SCREEN_ON,1,false)
,D/CalendarProvider2( 5900): wait start:true,
,D/PMS     (  974): acquireWL(343aa406): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): acquireWL(3d95dac7): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(343aa406): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  974): releaseWL(3d95dac7): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/AlarmManager(  974): ACTION_SCREEN_OFF
,I/AlarmManager(  974): [AlarmQueuing] screen off now: 
,I/AlarmManager(  974): [AlarmQueuing] data connection: true
I/AlarmManager(  974): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  974): stopDataStallAlarm 
D/WifiDisplayAdapter(  974): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  974):     Client/Owner: Client
D/WifiDisplayAdapter(  974):     GroupId: 
D/WifiDisplayAdapter(  974):     Passphrase: 
D/WifiDisplayAdapter(  974):     SessionId: 0
D/WifiDisplayAdapter(  974):     IP Address: }
E/WifiDataStallTracker(  974): ENABLE_DATA_MONITOR_POLL false Token 0
E/WifiStateMachine(  974): handleMessage: E msg.what=131167
E/WifiStateMachine(  974): processMsg: InitialState
E/WifiStateMachine(  974):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  974): processMsg: DefaultState
E/WifiStateMachine(  974):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  974):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
,D/WifiStateMachine(  974): getWifiLinkLayerStats: WIFI is not enbled
E/WifiStateMachine(  974): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  974): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  974): handleScreenStateChanged Exit: false
E/WifiStateMachine(  974): handleMessage: X
E/WifiStateMachine(  974): handleMessage: E msg.what=131154
E/WifiStateMachine(  974): processMsg: InitialState
V/SRS_Proc(  400): ParamSet string: screen_state=off
E/WifiStateMachine(  974):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  974): processMsg: DefaultState
E/WifiStateMachine(  974):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  974): handleMessage: X
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  974): handleMessage: E msg.what=155651
D/WifiController(  974): processMsg: ApStaDisabledState
D/WifiController(  974): processMsg: DefaultState
D/WifiController(  974): handleMessage: X
,D/NetworkPolicy(  974): updateScreenOn: false
V/NetworkPolicy(  974): updateIfacesLocked()
D/NetworkManagementService(  974): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/XAN-DPS (  974): prepareColorFade done
,D/XAN-DPS (  974): setBrightness to 0
D/CalendarProvider2( 5900): wait end:false
,I/SensorManager(  974): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@136b7597
,I/DisplayManagerService(  974): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  974): Following SensorService logs are not warning, just make sure they are printed
V/ActivityManager(  974): Display changed displayId=0
W/SensorService(  974): disable: get sensor name = CM32181 Light sensor
,I/ActivityManager(  974): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5929 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/DotMatrix( 1319): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1319): [EventService] mbHDMIConnect: false, mCoverOn:false
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
W/SensorService(  974): pid=974, uid=1000
,W/SensorService(  974): Active sensors: size = 3
W/SensorService(  974): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  974): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  974): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  974): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@136b7597, eanble = 0, strlen(mName) = 67
W/SensorService(  974): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  974): Listener[0] = com.htc.smartdim.sensor_eye@2aa47141
W/SensorService(  974): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager( 1233): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@39c45905, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  974): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  974): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  974): pid=1233, uid=10041,
W/SensorService(  974): Active sensors: size = 4
W/SensorService(  974): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  974): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  974): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  974): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  974): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@39c45905, eanble = 1, strlen(mName) = 57
W/SensorService(  974): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  974): Listener[0] = com.htc.smartdim.sensor_eye@2aa47141
,W/SensorService(  974): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@39c45905
W/SensorService(  974): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  974): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1319): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1319): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1493): start background delete task...
,I/IntentController( 1233): receive(android.intent.action.SCREEN_OFF,1,false)
,D/PMS     (  974): acquireWL(11ccfa92): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  974): releaseWL(11ccfa92): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
D/ContactMessageStore( 1493): size: 0 , 0
D/ContactMessageStore( 1493): Background delete complete
D/PMS     (  974): acquireWL(278b5c63): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1818 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  974): releaseWL(278b5c63): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 5929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5929): MY_DEBUG = false
,W/ContextImpl( 5929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,I/RemoteViews( 1233): setHTCTheme(com.htc.updater,true,33751145),
,D/PMS     (  974): acquireWL(10bc2dde): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5929 1000 null
,D/SmartSyncUtils( 5929): isEpsOn(), nState = 0
,I/RemoteViews( 1233): apply : com.htc.updater 1 13 0 36
,W/ContextImpl(  974): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  974): releaseWL(10bc2dde): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/SmartDim(  974): Init customizeScreenOffDelayClass error
,W/ContextImpl( 5929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 5929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncUtils( 5929): isEpsOn(), nState = 0
D/SmartSyncUtils( 5929): isEpsOn(), nState = 0
,W/ContextImpl( 5929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl(  974): Excessive delay in setPowerMode(): 283ms
D/PMS     (  974): Setting HAL interactive mode to false
W/HtcSystemUPManager(  974): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  974): Setting HAL interactive mode to false done
D/PMS     (  974): Setting HAL auto-suspend mode to true
D/PMS     (  974): Setting HAL auto-suspend mode done
D/HABCtrl (  974): TPE algorithm. remove timeout.
D/PMS     (  974): OOBE c monitor 11
I/InputManager(  974): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/InputMethodManagerService(  974): screenObserver, isScreenOn=false
D/StatusBarManagerService(  974): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  974): Disable input method client, pid=3243
,I/IntentController( 1233): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/PMS     (  974): acquireWL(13259dd5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 974 1000 null,
W/ContextImpl(  974): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
I/BatteryService(  974): n_update end
,I/SensorManager(  974): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@2aa47141,
D/PMS     (  974): releaseWL(13259dd5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/SensorService(  974): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  974): disable: get sensor name = Accelerometer Sensor
,D/NfcService( 1509): ScreenObserver: OFF
D/NfcService( 1509): applyRouting - 0
,W/SensorService(  974): pid=974, uid=1000
D/PMS     (  974): acquireWL(4d949ea): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1509 1027 null
W/SensorService(  974): Active sensors: size = 3
W/SensorService(  974): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  974): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  974): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  974): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2aa47141, eanble = 0, strlen(mName) = 36
W/SensorService(  974): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  974): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@39c45905
W/SensorService(  974): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  974): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  974): disable: get sensor name = CM36686 Proximity sensor
D/NfcService( 1509): applyRouting -2
D/NfcService( 1509): applyRouting
,D/NfcService( 1509): Ignore this applyRouting...
D/PMS     (  974): releaseWL(4d949ea): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/PhoneStatusBar( 1233): setImeWindowStatus(false,false)
,W/SensorService(  974): pid=974, uid=1000,
W/SensorService(  974): Active sensors: size = 2
W/SensorService(  974): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  974): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  974): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2aa47141, eanble = 0, strlen(mName) = 36
W/SensorService(  974): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  974): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@39c45905
,W/SensorService(  974): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/HtcPowerSaver(  974): updateBatteryInfo
,I/SensorManager(  974): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@2aa47141
D/PowerUI ( 1233): closing low battery warning: level=100
,D/DotMatrix( 1319): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1319): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1319): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1233): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1233): receive(android.intent.action.BATTERY_CHANGED,1,false)
E/ActivityThread(  974): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1bcc36e6 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  974): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1bcc36e6 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  974): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  974): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  974): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  974): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  974): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  974): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  974): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285),
E/ActivityThread(  974): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  974): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  974): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  974): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  974): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  974): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  974): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  974): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  974): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  974): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  974): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  974): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  974): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5963 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/NotificationService(  974): plugged=true pluggin=true
D/UsbnetService(  974): BroadcastReceiver::onReceive+
,D/UsbnetService(  974): onReceive BATTERY_CHANGED
D/PMS     (  974): runPSCheck
D/UsbnetService(  974):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  974): Checking...
D/UsbnetService(  974): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  974): >> updateStatus
D/WifiController(  974): handleMessage: E msg.what=155652
D/WifiController(  974): battery changed pluggedType: 2
D/WifiController(  974): processMsg: ApStaDisabledState
D/WifiController(  974): processMsg: DefaultState
D/WifiController(  974): handleMessage: X
I/PowerUsageList:PowerUsageHelper( 5929): PowerProfile::POWER_SCREEN_FULL = 154.8,
,I/HtcPowerSaver(  974): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  974): << updateStatus
,I/ClockController( 1233): stop clock update:screen off
,D/PowerUsageList:BatterySipperExt( 5929): gen(), null == sipper.uidObj, userId = 0,
,I/BatteryController( 1233): status:5 level:100 unsupport:false plugged:true,
,D/PowerUsageService( 5929): calcPower(), no data,
,D/PowerUsageList:PowerUsageHelper( 5929): MY_DEBUG = false
,D/SmartSyncUtils( 5929): getMobilePolicyEnabled, result = true,
,E/WifiTrafficPoller(  974): ADD_CLIENT: 7
D/WifiService(  974): New client listening to asynchronous messages,
I/ActivityManager(  974): Killing 5607:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  974): killProcessQuiet, pid=5607
,D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 ,
,I/ActivityManager(  974): Recipient 5607
,D/Process (  974): killProcessQuiet, pid=5631,
I/ActivityManager(  974): Killing 5631:com.android.settings/1000 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 5631
,I/CalendarProvider2( 5900): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 5900): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 5763): ---------------------------------------------------
,D/ProviderChangeReceiver( 5763): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/HtcAlertService( 5763): start to updateAlertNotification!,
,D/Process (  974): killProcessQuiet, pid=5727
I/ActivityManager(  974): Killing 5727:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/PMS     (  974): releaseWL(3d17b659): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  974): Recipient 5727
,D/HtcAlertService( 5763): No fired or scheduled alerts
D/HtcAlertUtils( 5763): -- cancelReminderNotification --
,D/HtcAlertUtils( 5763): broadcastExistReminder!
,D/DotMatrix( 1319): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcUPManager( 1233): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,D/ContactMessageStore( 1493): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1493): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  974): acquireWL(1a05f4db): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 974 1000 WorkSource{1000},
V/AlarmManager(  974): sending alarm PendingIntent{157453cc: PendingIntentRecord{2fd80615 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=120212, Int=0
V/AlarmManager(  974): sending alarm PendingIntent{21862b78: PendingIntentRecord{3e2f4251 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457358182048, Int=0
D/PMS     (  974): acquireWL(3bfa1ab6): PARTIAL_WAKE_LOCK  *backup* 0x1 974 1000 null
,D/PMS     (  974): releaseWL(1a05f4db): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/BackupManagerService(  974): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  974): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  974): releaseWL(3bfa1ab6): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/WeatherUtility( 1233): Weather sync is On
,W/WeatherTimeKeeper( 1233): [refreshWeatherData] no weather data
,D/Process (  974): killProcessQuiet, pid=5339
I/ActivityManager(  974): Killing 5339:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  974): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  974): Recipient 5339
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  974): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  974): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,W/ContextImpl(  974): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,D/PMS     (  974): acquireWL(1c6503b7): PARTIAL_WAKE_LOCK  *alarm* 0x1 974 1000 WorkSource{10024},
V/AlarmManager(  974): sending alarm PendingIntent{34ae8724: PendingIntentRecord{554b28d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141125, Int=0
V/AlarmManager(  974): sending alarm PendingIntent{39852c42: PendingIntentRecord{2c68bdad com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=141328, Int=0
,V/AlarmManager(  974): sending alarm PendingIntent{1af78dfc: PendingIntentRecord{35926c85 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=148474, Int=0
V/AlarmManager(  974): sending alarm PendingIntent{e3c2453: PendingIntentRecord{ddef190 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=160316, Int=0
,D/PMS     (  974): acquireWL(3ae6ea89): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1926 10024 WorkSource{10024 com.google.android.gms},
,D/libc    (  974): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4,
D/libc    (  974): [NET] android_getaddrinfofornet-, err=8
D/PMS     (  974): releaseWL(1c6503b7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  974): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  974): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    (  974): [NET] android_getaddrinfo_proxy+,
D/libc    (  974): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1926): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1926): [NET] android_getaddrinfofornet-, err=8
D/libc    (  974): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    ( 1926): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1926): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1926): [NET] android_getaddrinfo_proxy+
D/libc    ( 1926): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1926): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  974): releaseWL(3ae6ea89): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  974): acquireWL(1ebdca8e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 974 1000 null,
I/BatteryService(  974): n_update end
D/PMS     (  974): releaseWL(1ebdca8e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  974): BroadcastReceiver::onReceive+
D/NotificationService(  974): plugged=true pluggin=true
D/UsbnetService(  974): onReceive BATTERY_CHANGED
D/PowerUI ( 1233): closing low battery warning: level=100
,D/UsbnetService(  974):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  974): updateBatteryInfo
D/UsbnetService(  974): BroadcastReceiver::onReceive-
D/WifiController(  974): battery changed pluggedType: 2
D/WifiController(  974): handleMessage: E msg.what=155652
D/PMS     (  974): runPSCheck
D/DotMatrix( 1319): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  974): Checking...
D/WifiController(  974): processMsg: ApStaDisabledState
I/HtcPowerSaver(  974): >> updateStatus
D/WifiController(  974): processMsg: DefaultState
D/PowerUI ( 1233): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  974): handleMessage: X
I/HtcPowerSaver(  974): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1319): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  974): << updateStatus
D/DotMatrix( 1319): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1233): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1233): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1493): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 5
,TIME-OUT KILL (timeout was 150000ms)
```
