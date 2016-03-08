#### Test 617033519c823d7_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 300us total 22.944ms
--------- beginning of system
I/BootReceiver(  944): Copying /sys/fs/pstore/console-ramoops to DropBox (SYSTEM_LAST_KMSG)
E/SharedPreferencesImpl(  944): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  944): Copying audit failures to DropBox
E/SharedPreferencesImpl(  944): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/Process (  944): killProcessQuiet, pid=2398
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/BootReceiver(  944): Copied 0 worth of audits to DropBox
I/ActivityManager(  944): Killing 2398:com.htc.sense.news/u0a74 (adj 15): empty #17
I/BootReceiver(  944): Checking for fsck errors
I/BootReceiver(  944): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  944): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
E/SharedPreferencesImpl(  944): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  944): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
I/BootReceiver(  944): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  944): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,E/SharedPreferencesImpl(  944): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  944): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  944): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  944): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  944): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  944): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
I/BootReceiver(  944): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  944): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
E/SharedPreferencesImpl(  944): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  944): Copying /data/tombstones/tombstone_07 to DropBox (SYSTEM_TOMBSTONE)
I/BootReceiver(  944): Copying /data/tombstones/tombstone_08 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  944): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/ActivityManager(  944): Recipient 2398
E/SharedPreferencesImpl(  944): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  944): Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
I/ActivityManager(  944): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=3134 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 5001, 1024} abi=arm64-v8a
I/[FDDMI]BootCompletedReceiver( 3102): BootCompletedReceiver :android.intent.action.BOOT_COMPLETED
D/OtaStartupReceiver( 1478): onReceive: android.intent.action.BOOT_COMPLETED
W/HtcActiveEngineManager(  944): Can't find out the target sensor
E/WifiStateMachine(  944): handleMessage: E msg.what=131206
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState CMD_BOOT_COMPLETED 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState CMD_BOOT_COMPLETED 0 0
E/WifiStateMachine(  944): handleMessage: X
D/ConnectivityService(  944): Got NetworkFactory Messenger for WIFI
D/ConnectivityService(  944): NetworkFactory connected
D/WIFI    (  944): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI    (  944):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  944): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  944): enter WifiNetworkFactory startNetwork. mIPTStart:false
W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/UsbnetService(  944): onReceive ACTION_BOOT_COMPLETED
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/UsbnetService(  944): UsbnetHandler::handleMessage+:4
W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1473 com.android.server.backup.BackupManagerService.notifyBackupEnabled:10562 com.android.server.backup.BackupManagerService.access$3400:164 com.android.server.backup.BackupManagerService$BootCompleteReceiver.onReceive:10549 android.app.LoadedApk$ReceiverDispatcher$Args.run:950 
D/UsbnetService(  944): MESSAGE_BOOT_COMPLETED+
D/UsbnetService(  944): systemReady+
D/WifiService(  944): updateDevicePolicy Exchange policy allowWifiStatus = 1
D/WifiService(  944): updateDevicePolicy Exchange policy allowInternetSharingStatus = 1
I/ActivityManager(  944): Start proc com.htc.autobot for broadcast com.htc.autobot/.UsbReceiver: pid=3157 uid=10047 gids={50047, 9997, 3003, 3002, 3001, 5003, 1024} abi=arm64-v8a
D/UsbnetService(  944): systemReady-
I/ActivityManager(  944): Killing 2611:com.htc.showme/u0a81 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=2611
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/UsbnetService(  944): UsbnetHandler::handleMessage-
D/ConnectivityService(  944): Got NetworkFactory Messenger for usbnet
D/usbnet  (  944): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/ConnectivityService(  944): NetworkFactory connected
D/usbnet  (  944):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  944): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/cutils-trace( 3132): Error opening trace file: Permission denied (13)
D/CustomizationManager( 3132): ====startRecUseTime====
D/htc.customization.log.level( 3132):  is 
W/CustomizationLogLevel( 3132): Level value is invalid, use default level 2
I/ActivityManager(  944): Recipient 2611
D/CustomizationManager( 3132):  Read ACC file spent 0.031 (s)
D/CIDMapFileReader( 3132): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3132): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3132): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3132): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3132): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3132): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3132): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3132): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 3132): Parsing tag category name = system
I/CustomizationCIDLoader( 3132): Parsing tag category name = application
I/CustomizationCIDLoader( 3132): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3132): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3132): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3132): Parsing tag category name = Settings
I/CustomizationCIDLoader( 3132): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3132): add string-array item, value = 42507
I/CustomizationCIDLoader( 3132): add string-array item, value = 21902
I/CustomizationCIDLoader( 3132): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 3132): add string-array item, value = 23420
I/CustomizationCIDLoader( 3132): add string-array item, value = 22299
I/CustomizationCIDLoader( 3132): add string-array item, value = 24002
I/CustomizationCIDLoader( 3132): add string-array item, value = 23210
I/CustomizationCIDLoader( 3132): add string-array item, value = 23205
I/CustomizationCIDLoader( 3132): add string-array item, value = 23806
I/CustomizationCIDLoader( 3132): add string-array item, value = 23430
I/CustomizationCIDLoader( 3132): add string-array item, value = 23408
I/CustomizationCIDLoader( 3132): add string-array item, value = 27205
I/CustomizationCIDLoader( 3132): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 3132): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 3132): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 3132): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 3132): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 3132): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 3132): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 3132): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 3132): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 3132): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 3132): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 3132): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 3132):  Read CID file spent 0.081 (s)
D/CustomizationManager( 3132):  All configurations done spent 0.082 (s)
D/UsbReceiver( 3157): onReceiver android.intent.action.BOOT_COMPLETED
D/HtcModeClient( 3157): power connected, start service
I/ActivityManager(  944): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=3193 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/MediaProvider( 3134): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
D/MediaProvider( 3134): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 3134): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 3134): [MP][DEBUG] Storage State: removed
D/MediaProvider( 3134): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/MediaProvider( 3134): [MP][DEBUG] Storage State: removed
D/Utils   ( 3157): CMD:getprop ro.htc.htcmode.socket.type
I/System  ( 3157): exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.util.Utils.systemCmd:34)
E/SQLiteLog( 3134): (283) recovered 51 frames from WAL file /data/data/com.android.providers.media/databases/external.db-wal
D/HtcModeClient( 3157): sSocketMode = LocalSocket
D/HtcModeClient( 3157): start the htcmodeservice thread
D/HtcModeClient( 3157): initCanAgent
I/CANMesgAgentLocalSocket( 3157): CANAgent Id = 0
D/HtcModeClient( 3157): sense info: version = none, id = 2
I/ActivityManager(  944): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 3132 on display 0
I/Prism.ItemManager( 1529): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1529): loadItems() com.htc.launcher.pageview.WidgetManager@30486054 +
I/Prism.WidgetManager( 1529): onLoadItems() +
D/PMS     (  944): acquireHCC(14911490): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 944 1000 null
D/PMS     (  944): acquireHCC(2d69d189): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 944 1000 null
W/asset   (  944): Copying FileAsset 0x55b00c61a0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/HtcModeClient( 3157): display info: width = 1080, height = 1776
D/HtcModeClient( 3157): display info: mode = 10
D/HtcModeClient( 3157): onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
D/HtcModeClient( 3157): connectState: BT_TURNON_BYME = false
D/HtcModeClient( 3157): connectState: CONNECTION_READY = false
D/HtcModeClient( 3157): connectState: ENABLE_PROJECTBYAPP = false
D/HtcModeClient( 3157): connectState: ENTER_PROJECTMODE = false
D/HtcModeClient( 3157): connectState: PHONE_PULGIN = false
D/HtcModeClient( 3157): connectState: Force_AWAKE = false
D/HtcModeClient( 3157): connectState: PHONE_PULGIN = true
D/HtcModeClient( 3157): connectState: POWERCONNECTED_READY = true
D/PMS     (  944): acquireWL(2094fd45): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 944 1000 null
V/AlarmManager(  944): sending alarm PendingIntent{20fd79cb: PendingIntentRecord{50ae5a8 android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=39381, Int=0
I/FeedHostManager( 1529): [onPause]
I/FeedProviderManager( 1529): onPause
I/AnimationUtil(  944): isHTCRecent(HelloWorld/Recent screens.)/6
D/DotMatrix( 2104): [CoverService] onDestroy, version: 1.3
I/SocialFeedProvider( 1529): +onPause
I/FeedHostManager( 1529): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@173bf4b1
I/SocialFeedProvider( 1529): -onPause
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  944): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3228 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ResourcesManager( 1529): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/SensorManager( 2104): unregisterListenerImpl++: listener = com.htc.dotmatrix.CoverService$7@1bb30084
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = CM36686 Proximity sensor
W/ContextImpl( 3193): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.powersaver.PowerSaverNotificationReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
W/SensorService(  944): pid=2104, uid=10041
W/SensorService(  944): Active sensors: size = 3
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  944): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.dotmatrix.CoverService$7@1bb30084, eanble = 0, strlen(mName) = 41
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  944): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@12a5c5ca
W/SensorService(  944): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@358c20e1
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 2104): [CoverService] unregisterCallContentObserver()
D/Process (  944): killProcessQuiet, pid=2634
I/ActivityManager(  944): Killing 2634:com.htc.zero:re_proc/u0a110 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/asset   ( 3228): Copying FileAsset 0xac4c0370 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/StatusBarManagerService(  944): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
I/TrimMemoryManager( 1529): [trimMemory] 20
I/ActivityManager(  944): Recipient 2634
D/Process (  944): killProcessQuiet, pid=2104
I/ActivityManager(  944): Killing 2104:com.htc.dotmatrix/u0a41 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 1529): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  944): Recipient 2104
D/PowerSaverNotificationService( 3193): updateNotification, mToggle = false
D/AlertReceiver( 2559): beginStartingService
D/PMS     (  944): acquireWL(247dd04a): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 2032 10011 null
D/PMS     (  944): acquireWL(2446bbb): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 2559 10010 null
D/PMS     (  944): releaseWL(247dd04a): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 null
I/WebViewFactory( 3228): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/DFPI.PIReciver( 2925): onReceiver action:android.intent.action.BOOT_COMPLETED
D/DFPI    ( 2925): getInstance = com.htc.demoflopackageinstaller.ApkInstallHelper@1bb30084
W/CustomizationIntentService( 1636): failed at default contact creation!
W/CustomizationIntentService( 1636): java.lang.SecurityException: Requesting code from com.htc.contacts (with uid 10038) to be run in process android.process.acore (with uid 10013)
W/CustomizationIntentService( 1636): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1793)
W/CustomizationIntentService( 1636): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1768)
W/CustomizationIntentService( 1636): 	at android.app.ContextImpl.createPackageContextAsUser(ContextImpl.java:2266)
W/CustomizationIntentService( 1636): 	at android.app.ContextImpl.createPackageContext(ContextImpl.java:2253)
W/CustomizationIntentService( 1636): 	at android.content.ContextWrapper.createPackageContext(ContextWrapper.java:658)
W/CustomizationIntentService( 1636): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.handleIntentInternal(CustomizationIntentService.java:143)
W/CustomizationIntentService( 1636): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.onHandleIntent(CustomizationIntentService.java:104)
W/CustomizationIntentService( 1636): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/CustomizationIntentService( 1636): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/CustomizationIntentService( 1636): 	at android.os.Looper.loop(Looper.java:155)
W/CustomizationIntentService( 1636): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/CustomizationIntentService( 1636): handleIntentInternal(): action = com.htc.intent.action.PRELOAD_CONTACTS, original action = android.intent.action.BOOT_COMPLETED, launched by: null
W/CustomizationIntentService( 1636): AFH Enable: false, LEONCHAME: false
D/HtcAlertService( 2559): start to updateAlertNotification!
W/CustomizationIntentService( 1636): hasBeenInit true
W/CustomizationIntentService( 1636): isNewChameleonHFASupported false
W/CustomizationIntentService( 1636): isHFA true
W/CustomizationIntentService( 1636): setupWizRun 1
D/DFPI    ( 2925): set install APK prefrence is false
D/HtcAlertService( 2559): No fired or scheduled alerts
D/HtcAlertUtils( 2559): -- cancelReminderNotification --
D/HtcAlertUtils( 2559): broadcastExistReminder!
D/PMS     (  944): releaseWL(2446bbb): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
W/AlertReceiver( 2559): stopSelfResult true
I/ActivityManager(  944): Killing 2702:com.htc.sense.browser/u0a9 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=2702
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/LibraryLoader( 3228): Time to load native libraries: 13 ms (timestamps 9742-9755)
I/LibraryLoader( 3228): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3228): Binding Chromium to main looper Looper (main, tid 1) {3a1eb4a2}
I/LibraryLoader( 3228): Expected native library version number "",actual native library version number ""
I/chromium( 3228): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3228): Initializing chromium process, singleProcess=true
W/asset   ( 1529): Copying FileAsset 0x55affd00e0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
W/art     ( 3228): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  944): Recipient 2702
E/SysUtils( 3228): ApplicationContext is null in ApplicationStatus
I/Prism.WidgetManager( 1529): onLoadItems() -
I/Prism.ItemManager( 1529): loadItems() com.htc.launcher.pageview.WidgetManager@30486054 -
I/ActivityManager(  944): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=3261 uid=10020 gids={50020, 9997, 1028, 1015} abi=arm64-v8a
W/chromium( 3228): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3228): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3228): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3228): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3228): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 3228): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 3228): Build Date: 03/09/15 Mon
I/Adreno-EGL( 3228): Local Branch: 
I/Adreno-EGL( 3228): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 3228): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 3228):                  d74aa161a12b9c6fc6332151
D/PhoneApp( 1478): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1478): -- N1 =0
D/PhoneApp( 1478): -- N2 =0
D/PhoneApp( 1478): -- N3 =0
W/System.err(  944): java.lang.Throwable: stack dump
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  944): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fabd0dd:true
W/System.err(  944): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  944): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  944): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  944): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 3228): 98007278: getState() :  mService = null. Returning STATE_OFF
D/FlexNetS( 2032): setNetMode:0, false
D/FlexNetS( 2032): set2gLowSignalEnablePref: false
V/FlexNetS( 2032): [DRX] setHigherPowerIn2GPref to: true
D/FlexNetS( 2032): setSimCardisWhiteList: false
V/FlexNetS( 2032): setSimCardCamp3GNetworkSignalPref to: false
D/FlexNetS( 2032): setCampNetworkisBlackList: false
V/FlexNetS( 2032): [DRX] setHigherPowerIn2GPref to: true
V/FlexNetS( 2032): setRilHandOverW2GEnable: 0
D/FlexNetS( 2032): updateSvcAllowedInSettings:false
W/art     ( 3228): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3228): onDetachedFromWindow called when already detached. Ignoring
I/ActivityManager(  944): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3303 uid=10026 gids={50026, 9997} abi=arm64-v8a
D/Process (  944): killProcessQuiet, pid=2752
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  944): Killing 2752:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/SystemWebViewEngine( 3228): CordovaWebView is running on device made by: HTC
I/ActivityManager(  944): Recipient 2752
W/art     ( 3228): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3228): Attempt to remove local handle scope entry from IRT, ignoring
V/OneTimeInitializerReceiver( 3303): OneTimeInitializerReceiver.onReceive
,I/ActivityManager(  944): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3328 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,V/OneTimeService( 3303): OneTimeService.onHandleIntent
,W/chromium( 3228): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/Process (  944): killProcessQuiet, pid=2897
,I/ActivityManager(  944): Killing 2897:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/FindExtension( 3228): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/InputMethodManager( 3228): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1e819c7f, mServedView=org.apache.cordova.engine.SystemWebView{418844c VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1587ac95
I/InputMethodManagerService(  944): Disable input method client, pid=1529
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
I/InputMethodManagerService(  944): Enable input method client, pid=3228
,W/XT9_C   ( 1360): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1360): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1360): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1360): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0,
,I/ActivityManager(  944): Recipient 2897
,D/PMS     (  944): releaseWL(2094fd45): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  944): Displayed com.example.hello/.MainActivity: +1s68ms,
,W/BindingManager( 3228): Cannot call determinedVisibility() - never saw a connection for the pid: 3228,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.partnersetup, clsName=com.google.android.partnersetup.PhoneStateReceiver, state=1, flag=1, pid=3328, uid=10027, userID:0,
,I/chromium( 3228): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10),
,I/ActivityManager(  944): Start proc com.htc.video for broadcast com.htc.video/.videowidget.videoDMC.DLNAReceiver: pid=3365 uid=10029 gids={50029, 9997, 3002, 3003, 1028, 1015, 1023, 2001} abi=arm64-v8a,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=3328, uid=10027, userID:0
,D/PMS     (  944): acquireWL(ca11367): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(ca11367): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/JsMessageQueue( 3228): Set native->JS mode to OnlineEventsBridgeMode
,I/RlzPingService( 3328): Setting next ping for 1458031393562
,E/AndroidProtocolHandler( 3228): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/PMS     (  944): acquireWL(3cc701bd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(3cc701bd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(c217f03): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(c217f03): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(1e482e80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(1e482e80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  944): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=3393 uid=10031 gids={50031, 9997, 3003} abi=arm64-v8a
D/Process (  944): killProcessQuiet, pid=1760
I/ActivityManager(  944): Killing 1760:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  944): Recipient 1760
,D/jxcore_app_log( 3228): JniHelper::setJavaVM(0xab3528f8), pthread_self() = -1402564728,
,W/jxcore-log( 3228): Initializing JXcore engine,
W/jxcore-log( 3228): JXcore engine is ready
,D/PMS     (  944): acquireWL(3f41b2ac): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(3f41b2ac): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/Process (  944): killProcessQuiet, pid=2951
I/ActivityManager(  944): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=3415 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  944): Killing 2951:com.htc.task/u0a69 (adj 15): empty #17
,D/PMS     (  944): acquireWL(1071ab75): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(1071ab75): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,W/jxcore-log( 3228): Starting JXcore engine
,W/jxcore-log( 3228): Platform android
,W/jxcore-log( 3228): 
W/jxcore-log( 3228): Process ARCH arm
W/jxcore-log( 3228): 
,I/ActivityManager(  944): Recipient 2951
,I/jxcore-log( 3228): JXcore Cordova bridge is ready!
I/jxcore-log( 3228): 
W/jxcore-log( 3228): JXcore engine is started
,E/jxcore  ( 3228): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js,
E/jxcore  ( 3228): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/Process (  944): killProcessQuiet, pid=2986
I/ActivityManager(  944): Killing 2986:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 2986,
,D/PMS     (  944): releaseHCC(14911490): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  944): releaseHCC(2d69d189): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/art     (  944): Explicit concurrent mark sweep GC freed 33355(2MB) AllocSpace objects, 53(3MB) LOS objects, 33% free, 15MB/23MB, paused 1.582ms total 135.260ms
D/PMS     (  944): acquireWL(1da9cb7b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(1da9cb7b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/FindExtension( 3228): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,E/Personalize.BootComple_( 3415): onReceive() + Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.home.personalize/.receiver.BootCompleteInitializer (has extras) }
E/Personalize.BootComple_( 3415): action android.intent.action.BOOT_COMPLETED,
,E/Personalize.Utilities( 3415): SimpleLauncher not found: com.htc.simplelauncher
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.htc.home.personalize, clsName=com.htc.home.personalize.SimpleModeEntryActivity, state=2, flag=1, pid=3415, uid=1000, userID:0
,E/Personalize.BootComple_( 3415): initialize: false
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.htc.simplelauncher, clsName=null, state=2, flag=0, pid=3415, uid=1000, userID:0
,E/Personalize.Utilities( 3415): setApplicationEnabled IllegalArgumentException com.htc.simplelauncher
,V/BootCompletedReceiver( 2773): ensureAndExecuteUserProfiling: ensureAndExecuteUserProfiling 
,D/PeopleYouKnow( 2773): receive intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.contacts/.peopleyouknow.PeopleYouKnowReceiver (has extras) }
,D/Process (  944): killProcessQuiet, pid=2800
I/ActivityManager(  944): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=3437 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  944): Killing 2800:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  944): Recipient 2800
,V/HtcDataRoamingWidget.DisableWidgetReceiver( 3437): ACTION_BOOT_COMPLETED,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.dataroaming, clsName=com.htc.rosiewidgets.dataroaming.HtcSettingWidgetProvider, state=1, flag=1, pid=3437, uid=10040, userID:0,
,V/HtcDataStripWidget.DisableWidgetReceiver( 3437): ACTION_BOOT_COMPLETED,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.datastrip, clsName=com.htc.rosiewidgets.datastrip.HtcSettingWidgetProvider, state=1, flag=1, pid=3437, uid=10040, userID:0
,D/Process (  944): killProcessQuiet, pid=3022
I/ActivityManager(  944): Killing 3022:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  944): Recipient 3022,
,D/DotMatrix( 1304): [EventReceiver] onReceive, version:1.3,
,I/ActivityManager(  944): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3458 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/art     (  446): Explicit concurrent mark sweep GC freed 8648(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 215us total 28.026ms
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 187us total 23.057ms,
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 180us total 22.078ms
,I/ActivityManager(  944): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=3480 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 3002, 3001, 2001, 1023} abi=armeabi-v7a
,W/ResourcesManager( 3480): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
,I/ActivityManager(  944): Killing 3049:com.android.settings/1000 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=3049
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 3049
,D/MediaSessionHelper( 3480): Attempting to get helper with context android.app.ReceiverRestrictedContext@30951231
,D/Process (  944): killProcessQuiet, pid=3102
I/ActivityManager(  944): Killing 3102:com.futuredial/u0a82 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaSessionService(  944): Created session for package com.htc.music with tag MediaSessionHelper-com.htc.music
,D/MediaSessionHelper( 3480): addMediaButtonListener added PendingIntent{12f40697: android.os.BinderProxy@1de9dd16}
,I/ActivityManager(  944): Recipient 3102,
,I/ActivityManager(  944): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=3503 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/Process (  944): killProcessQuiet, pid=3084
I/ActivityManager(  944): Killing 3084:com.android.keychain/1000 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  944): Recipient 3084
,I/ActivityManager(  944): Killing 3193:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=3193,
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 3193
,I/ActivityManager(  944): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3525 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/Process (  944): killProcessQuiet, pid=2559
I/ActivityManager(  944): Killing 2559:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  944): Recipient 2559
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncServiceReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
D/PowerUsageList:PowerUsageHelper( 3525): MY_DEBUG = false
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,V/AlarmManager(  944): sending alarm PendingIntent{f0437b0: PendingIntentRecord{2fe38629 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457426596285, Int=0
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,I/[PluginManager]RegisterService( 1437): onHandleIntent, action: android.intent.action.BOOT_COMPLETED, data: null
,D/HtcAppUPService( 1437): CustomizationReceiver  receieve: android.intent.action.BOOT_COMPLETED
,D/HtcAppUPService( 1437): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.BOOT_COMPLETED cmp=com.htc.sense.hsp/.upservice.HtcUPService }, this = com.htc.sense.hsp.upservice.HtcUPService@199f6cba,
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.startService:208 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.onHandleIntent:71 android.app.IntentService$ServiceHandler.handleMessage:65 
,D/AutoSetting( 1437): receiver - intent: android.intent.action.BOOT_COMPLETED,
,I/WSP     ( 1437): [Receiver] EVENT - BOOT COMPLETED, is settings existed? true
,D/HtcAppUPService( 1437): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.BOOT_COMPLETED
,I/ActivityManager(  944): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=3557 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a
,D/AutoSetting( 1437): service - onStartCommand() action: com.htc.app.autosetting.bootcomplete
D/AutoSetting( 1437): service - onStartCommand() boot completed, remove cache
D/AutoSetting( 1437): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1437): service - handleMessage() removing cache
D/AutoSetting( 1437): service - AddressCache: clean up all cache
D/AutoSetting( 1437): service - handleMessage() setting current location null
,D/HtcAppUPService( 1437): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true,
,D/WeatherUtility( 1216): Weather sync is On
W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data,
D/HtcAppUPService( 1437): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
I/ActivityManager(  944): Killing 2925:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=2925
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/Bundle  ( 1437): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/FeatureList( 1437): feature
D/FeatureList( 1437): type,
D/FeatureList( 1437): description
,W/Bundle  ( 1437): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): ,	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
,W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1437): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	,at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
,W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1437): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1437): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1437): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1437): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
,W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1437): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
,W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1437): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1437): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102),
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  944): Recipient 2925,
,W/Bundle  ( 1437): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1437): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1437): Attempt to cast generated internal exception:
W/Bundle  ( 1437): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1437): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1437): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1437): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/BootReceiver( 3557): onReceive: android.intent.action.BOOT_COMPLETED,
,D/BootReceiver( 3557): boot completed:
,D/BootReceiver( 3557): isValid:  isEnabledEasyAccess = true, isEnabledQuickDial = true
D/BootReceiver( 3557): Valid
D/BootReceiver( 3557): startService:
,I/ActivityManager(  944): Start proc com.htc.HTCSpeaker:ngfservice for service com.htc.HTCSpeaker/.NGFService: pid=3578 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a
,D/Process (  944): killProcessQuiet, pid=3134
,I/ActivityManager(  944): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=3596 uid=10058 gids={50058, 9997, 1028, 1015, 1023} abi=arm64-v8a
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  944): Killing 3134:android.process.media/u0a17 (adj 15): empty #17
,D/PluginProvider( 1437): Begin Apply Batch,
,E/PluginProvider( 1437): conflict when insert feature, ignored
,I/ActivityManager(  944): Recipient 3134
,D/NGFService( 3578): onCreate +++
,D/SettingUtils( 3578): getProcessNormalFlag: true,
D/NGFService( 3578): onCreate last time crash or 1st run=false
,D/SettingUtils( 3578): setProcessNormalFlag: false
,D/NGFService( 3578): getAudioStreamType: ScoOn =false
D/SoundEffects( 3578): init +++ 3
,W/LMW     ( 3596): [3625][ActionDeviceStorageHandler] onActionBootComplete++,
,W/LMW     ( 3596): [3625][ActionDeviceStorageHandler] onActionBootComplete--,
,I/ActivityManager(  944): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3628 uid=10063 gids={50063, 9997, 1028, 3003} abi=arm64-v8a
D/Process (  944): killProcessQuiet, pid=3261
I/ActivityManager(  944): Killing 3261:com.htc.fm/u0a20 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/AudioCache(  413): Heap size overflow! req size: 1058400, max size: 1048576
,W/NuPlayerRenderer(  413): AudioSink write short frame count 0 < 9824,
,D/PluginProvider( 1437): apply Batch success,
,I/ActivityManager(  944): Recipient 3261,
,D/NGFLanguageMgr( 3578): LanguageFromSystem: language:en  country:gb,
D/NGFLanguageMgr( 3578): language package name = preload_package,
,I/[PluginManager]RegisterService( 1437): Notify Carousel that a new TabPlugin has been installed!
,I/ActivityManager(  944): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=3697 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 5001, 1024} abi=arm64-v8a,
,D/Process (  944): killProcessQuiet, pid=2032
I/ActivityManager(  944): Killing 2032:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/NMT     ( 3578): NMT version: 1.6.1-B006 REL,
D/NGFService( 3578): Audio Dump Folder: Elvis = /data/data/com.htc.HTCSpeaker/files/htcspeak_elvis, PCM = /data/data/com.htc.HTCSpeaker/files/htcspeak_pcm
,I/ActivityManager(  944): Recipient 2032
,D/NGFService( 3578): applyCurrentSystemLanguage +++
,D/NGFService( 3578): grammar support language:[United States English, Taiwanese Mandarin, Chinese Mandarin, German, Latin American Spanish, European Spanish, European French, Italian, British English, Japanese, Canadian French, Chinese Cantonese, Danish, Greek, Finnish, Dutch, Norwegian, Polish, Brazilian Portuguese, European Portuguese, Russian, Swedish, Australian English, Turkish],
,D/NGFLanguageMgr( 3578): LanguageFromSystem: language:en  country:gb
D/NGFService( 3578): Elvis language uses the language: 2
D/NGFService( 3578): setCurrentNGFLanguageMgr: Language = 2, CurrentLanguage = 0
D/NGFService( 3578): setCurrentNGFLanguageMgr: set language = British English
D/NGFService( 3578): bluetoothInitialize +++
,W/System.err(  944): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  944): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f8c229d:true
W/System.err(  944): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  944): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
,W/System.err(  944): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  944): 	at android.os.Binder.execTransact(Binder.java:454)
,D/NGFService( 3578): cloud_init +++
D/NGFLanguageMgr( 3578): getCloudServerDNSName: language = 2, DNS name = cc.nvc.engb.nuancemobility.net
,D/MediaProvider( 3697): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
,D/MediaProvider( 3697): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 3697): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 3697): [MP][DEBUG] Storage State: removed
D/MediaProvider( 3697): [MP][DEBUG] Sorting: order:2, path:/storage/usb
,D/MediaProvider( 3697): [MP][DEBUG] Storage State: removed
,E/SQLiteLog( 3697): (283) recovered 51 frames from WAL file /data/user/0/com.android.providers.media/databases/external.db-wal,
,D/NGFService( 3578): elvisInitalize +++
,D/MediaScannerReceiver( 3697): onReceive Intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.media/.MediaScannerReceiver (has extras) }
,D/MediaProviderUtils( 3697): [startScan]volume:internal, action:android.intent.action.MEDIA_MOUNTED
,D/MediaProviderUtils( 3697): [startScan]volume:external, action:android.intent.action.MEDIA_MOUNTED
,D/NGFService( 3578): elvisInitalize lang = British English,
D/NGFService( 3578): elvisInitalize: Freq Type:16000
D/NGFService( 3578): tts_init +++,
D/NGFLanguageMgr( 3578): getVocalizerFolderName: language = 2, folder name = vocalizer_eng
,I/HtcModeClient( 3157): handler message = 4011
,E/HtcModeClient( 3157): Check connection and retry 1 times.
,D/NGFLanguageMgr( 3578): LanguageFromSystem: language:en  country:gb
,D/NGFLanguageMgr( 3578): language package name = preload_package
,D/NGFService( 3578): load vocalizer language = British English
,E/NGFService( 3578): registerObserver
,D/NGFService( 3578): onCreate: Battery Level Remaining: 100%
,D/NGFService( 3578): onStartCommand(): service start
D/NGFService( 3578): onStartCommand() action = com.htc.HTCSpeaker.NGFService.QuickCall
D/NGFService( 3578): QuickCall
,W/NMT     ( 3578): Fail to open read-stream for file generic.lst,
,W/NMT-OemFile( 3578): fopen(): Failed to open file sysdct.dat
,D/NGFService( 3578): Elvis is initialization Success,
D/NGFService( 3578): bElvisInitializeCompleted = true,
W/NMT-OemFile( 3578): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
,D/MediaScannerServiceEx( 3697): Action not in map, volume = internal, action = android.intent.action.MEDIA_MOUNTED
D/MediaScannerServiceEx( 3697): Action not in map, volume = external, action = android.intent.action.MEDIA_MOUNTED
D/NGFService( 3578): GrammarState = 0
D/NGFService( 3578): loadGrammar +++
D/NGFService( 3578): loadGrammar asr_grammar
,W/NMT-OemFile( 3578): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
I/NGFService( 3578): GrammarDepot contains a valid Elvis Grammar0
,D/NGFService( 3578): loadGrammar from cache
W/NMT-OemFile( 3578): fopen(): Failed to open file sysdct.dat
W/NMT-OemFile( 3578): fopen(): Failed to open file sysdct.dat
,D/MtpReceiver( 3697): [MTP][handleUsbStateAsync]+
D/PMS     (  944): acquireWL(1fd1a26a): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3697 10017 null
,D/MtpReceiver( 3697): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3697): [MTP][handleUsbState]+
,W/NMT-OemFile( 3578): fopen(): Failed to open file clm.dat
W/NMT     ( 3578): Fail to open read-stream for file elvisBritish Englishname.lst
,I/ActivityManager(  944): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=3739 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/NMT     ( 3578): Fail to open read-stream for file elvisBritish Englishartist.lst
,D/MediaProvider( 3697): bindService() MTP Service Connection.
,D/MtpReceiver( 3697): [MTP][scanExternalVolumeIfNeed] scan external volume
,D/MtpReceiver( 3697): [MTP][handleUsbState]-
,D/MtpReceiver( 3697): [MTP][handleMessage]-
W/NMT     ( 3578): Fail to open read-stream for file elvisBritish Englishplaylist.lst
,W/NMT     ( 3578): Fail to open read-stream for file elvisBritish Englishsong.lst
W/NMT     ( 3578): Fail to open read-stream for file elvisBritish Englishalbum.lst
W/NMT     ( 3578): Fail to open read-stream for file elvisBritish Englishgeneric.lst
,D/MtpService( 3697): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpService( 3697): addStorageInternal without MtpServer
,D/MediaScanner( 3697): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
,D/MtpService( 3697): [MTP][onCreate]-
I/ActionCombine( 3697): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,W/NMT-OemFile( 3578): fopen(): Failed to open file daniel_userdct_eng.dat
D/MtpService( 3697): [MTP] startForeground
,E/SQLiteLog( 3697): (283) recovered 92 frames from WAL file /data/user/0/com.android.providers.media/databases/internal.db-wal
,D/MtpService( 3697): updating state; isCurrentUser=true, mMtpLocked=false
,D/PMS     (  944): acquireWL(18a7194b): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2132 10024 null
,D/MtpDatabase( 3697): TotalSize=1886532,MediaCacheLimit=6000
,D/SettingUtils( 3578): setProcessNormalFlag: true
D/NGFService( 3578): RebuildListener constraintList size 17
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/NGFService( 3578): RebuildListener: onComplete0
D/NGFService( 3578): onComplete GRAMMAR_STATE_DEFAULT
D/NGFService( 3578): switchScenario: htc_screen_140_19
D/NGFService( 3578): Activated grammar scenario [call, play, search, help, check_message, find, cancel, exit, more]
,D/NGFService( 3578): Activated grammar constraintNames [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3578): Loading grammar completed.
D/NGFService( 3578): update contact cache completed
D/SettingUtils( 3578): set Updatge Contact Cache: false
,D/MtpService( 3697): starting MTP server in MTP mode,
,D/MtpService( 3697): addStorageInternal 65537 /storage/emulated/0,
,D/MtpService( 3697): [checkStorageState] Storage state - mounted
,W/HtcWrapAdjustableCursorFactory( 3739): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MtpDatabase( 3697): [MTP][addStorage] iHostType =2
D/MtpService( 3697): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
,I/RemoteViews( 1216): apply : com.android.providers.media 0 11 2 36
,D/MessageFrequencyProvider( 3739): onCreate
,V/GetPrviateResource( 3739): GetPrviateResource
,V/GetPrviateResource( 3739): GetPrviateResource
,I/RemoteViews( 1216): apply : com.android.providers.media 0 12 1 51
,D/MessageCustFlag( 3739): sense_version=6.0
,D/BTAccessoryUtil( 3739): createReceiver
,D/BTAccessoryUtil( 3739): registerReceiver return intent = null
,D/MessageCustFlag( 3739): sku_id=118
,D/HtcBuildUtils( 3739): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3739): Cannot find qct_8960_interface, use default value instead
,V/MmsSystemEventReceiver( 3739): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) }
,I/iu.UploadsManager( 2132): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/ExchangePolicystatus( 3739): onReceive()
D/ExchangePolicystatus( 3739): onReceive(): ACTION_BOOT_COMPLETED
,D/MessageUtils( 3739): Text messaging allow status = allow
D/Messaging( 3739): EAS allow SMS !!!
D/ExchangePolicystatus( 3739): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
D/Messaging( 3739): EAS allow SMS !!!
,I/ActivityManager(  944): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=3775 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,D/PMS     (  944): acquireWL(cab3272): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 3739 10064 null
,V/SmsReceiverService( 3739): onStart: #1, @430649743
,V/SmsReceiverService( 3739): action: android.intent.action.BOOT_COMPLETED
D/SmsReceiverService( 3739): isCbm: false
D/SmsReceiverService( 3739): isDiscard: false
D/SettingsManager( 3739): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@31687533
V/AlarmManager(  944): sending alarm PendingIntent{12905b40: PendingIntentRecord{36c48a79 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=44693, Int=0
W/MediaScanner( 3697): Error opening directory '/oem/media/', skipping: No such file or directory.
,V/SmsReceiverService( 3739): handleBootCompleted
,W/MediaScanner( 3697): Error opening directory '/oem/media/', skipping: No such file or directory.
D/MediaScanner( 3697):  prescan time: 118ms
D/MediaScanner( 3697):     scan time: 37ms,
D/MediaScanner( 3697): postscan time: 0ms
D/MediaScanner( 3697):    total time: 155ms
D/MediaScanner( 3697): -----------------------------------------------------------------
D/MediaScanner( 3697): firstscan(media) time: 25ms
D/MediaScanner( 3697): secondscan(non-media) time: 8ms
D/MediaScanner( 3697):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3697):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3697):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3697):  [Total]    File(Image+Video+Audio+Others) in database : 339
,W/ResourcesManager( 3739): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/MediaScannerService( 3697): [handleMessage] --- Should not be here, ignore request. ----
E/MediaScannerService( 3697): [onStartCommand] --- Should not be here, redirect request. ----
I/iu.UploadsManager( 2132): End new media; added: 0, uploading: 0, time: 74 ms
D/PMS     (  944): releaseWL(18a7194b): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1478): sku_id=118
D/SmsReceiverService( 3739): OutBoxSize = 0
D/SmsReceiverService( 3739): sendFirstQueuedMessage start: 0
D/MessageCustFlag( 3739): sku_id=118
D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1478): sku_id=118
,D/MediaProvider( 3697): [delete][86],
D/MediaProvider( 3697): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3697): [recoverParentNodes] - 0,
D/MediaProvider( 3697): [update][15]
D/PMS     (  944): releaseWL(1fd1a26a): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3697): [scan] Recover Parent Node is finished!
E/MediaScannerServiceEx( 3697): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3697): [ServiceHandler][handleMessage] , action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
,E/cutils-trace( 3799): Error opening trace file: Permission denied (13),
I/dex2oat ( 3799): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 3799): dex2oat: override thread count:4
,I/art     (  944): Explicit concurrent mark sweep GC freed 11431(607KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 15MB/23MB, paused 1.414ms total 125.056ms
,D/MediaScannerServiceEx( 3697): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3697): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3697): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3697): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3697): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3697): [AliveExtStorageRows]+65537, 11223344
D/MessageCustFlag( 3739): sku_id=118
,D/SmsReceiverService( 3739): sendFirstQueuedMessage end cnt> 0
,D/SpaceBufferUtil( 3739): > createBufferFile()
,D/SpaceBufferUtil( 3739): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
D/SpaceBufferUtil( 3739): < createBufferFile()
D/MediaProvider( 3697): [update][12]#0#
,D/MediaProvider( 3697): [update][9]#0#
,D/MediaProvider( 3697): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3697): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3697): [update][8]#1#,
,D/MediaScannerServiceEx( 3697): [AliveExtStorageRows]-0, 0
,D/PMS     (  944): acquireWL(67603be): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3697 10017 null,
,D/MediaScanner( 3697): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,I/dex2oat ( 3799): dex2oat took 668.374ms (threads: 4),
,I/PushClient( 3775): ApplicationMonitor {3a97dc1c}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 3775): ApplicationMonitor {3a97dc1c}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 3775): ApplicationMonitor {3a97dc1c}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 3775): ApplicationMonitor {3a97dc1c}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 3775): ApplicationMonitor {3a97dc1c}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 3775): ApplicationMonitor {3a97dc1c}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 3775): ApplicationMonitor {3a97dc1c}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 3775): ApplicationMonitor {3a97dc1c}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 3775): ApplicationMonitor {3a97dc1c}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 3775): String {2b182068}: handleBroadcast(): Schedule update on boot completed.,
I/ActivityManager(  944): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3808 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/Process (  944): killProcessQuiet, pid=3303
I/ActivityManager(  944): Killing 3303:com.google.android.onetimeinitializer/u0a26 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 3303,
,D/SMSBackup( 3808): Got ACTION_BOOT_COMPLETED event
,D/SMSBackup( 3808): setCheckAlarm,
,D/SMSBackup( 3808): Next check is scheduled at 60s from now
,D/Process (  944): killProcessQuiet, pid=3365
I/ActivityManager(  944): Killing 3365:com.htc.video/u0a29 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  944): Recipient 3365,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1478, uid=1001, userID:0,
,I/ActivityManager(  944): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=3830 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/[AppShowMeDebug]BootCompletedReceiver( 3830): received boot complete
,I/[AppShowMeDebug]BootCompletedReceiver( 3830): push flag is false, skip check,
,I/ActivityManager(  944): Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=3853 uid=10083 gids={50083, 9997, 1007, 3003, 1028} abi=arm64-v8a
,I/ActivityManager(  944): Killing 3328:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=3328
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  944): Recipient 3328,
,D/MediaScanner( 3697):  prescan time: 614ms
D/MediaScanner( 3697):     scan time: 709ms
,D/MediaScanner( 3697): postscan time: 7ms
D/MediaScanner( 3697):    total time: 1330ms
D/MediaScanner( 3697): -----------------------------------------------------------------
D/MediaScanner( 3697): firstscan(media) time: 454ms
D/MediaScanner( 3697): secondscan(non-media) time: 255ms
D/MediaScanner( 3697):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3697):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3697):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3697):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,D/MediaProvider( 3697): [delete][32]
,D/MediaProvider( 3697): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3697): [recoverParentNodes] - 0,
D/MediaProvider( 3697): [update][5]
D/MediaScannerServiceEx( 3697): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3697): [updateImage]+
,D/MyReportAgent( 3853): PolicyReceiver  receieve: android.intent.action.BOOT_COMPLETED,
,D/MediaScannerServiceEx( 3697): [updateImage]-0
,D/PMS     (  944): releaseWL(67603be): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null,
D/MediaScannerServiceEx( 3697): [2] scan finished,
D/MediaProviderUtils( 3697): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3697): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3697): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3697): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1,
W/MediaScannerServiceEx( 3697): Process mounted intent for unmounted storage: /storage/ext_sd
,D/MyReportAgent( 3853): DatabaseHelper [DatabaseHelper constructor]
D/MyReportAgent( 3853): PolicyStore [Init] Get cached policy bundle
,D/MyReportAgent( 3853): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE
,I/ActivityManager(  944): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3875 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
D/MediaScannerServiceEx( 3697): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3697): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3697): [update][8]#1#
,D/MyReportAgent( 3853): ReportServiceHandler on boot complete event 
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.htc.feedback, clsName=com.htc.feedback.reportagent.receiver.PowerConnectedReceiver, state=2, flag=1, pid=3853, uid=10083, userID:0
V/MyReportAgent( 3853): ReportServiceHandler unregister the PowerConnected Listener
,D/Process (  944): killProcessQuiet, pid=3393
,I/ActivityManager(  944): Killing 3393:com.htc.csrecommend/u0a31 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/HtcModeClient( 3157): handler message = 4009
,I/HtcModeClient( 3157): start to setup the connection
,D/MediaProvider( 3697): [update][29]#0#
,D/MediaScannerServiceEx( 3697): [disAliveExtStorageRows]--1, 0
,I/ActivityManager(  944): Recipient 3393,
,D/MediaProviderUtils( 3697): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3697): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3697): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3697): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3697): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3697): [disAliveExtStorageRows]+196609
,I/ActivityManager(  944): Killing 3415:com.htc.home.personalize/1000 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=3415
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/MediaProvider( 3697): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3697): [update][10]#1#
,D/MediaProvider( 3697): [update][27]#0#
,D/MediaScannerServiceEx( 3697): [disAliveExtStorageRows]--1, 0
,D/Messaging( 3739): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 3739): networkCode: 
,D/MmsConfig( 3739): SIE smsPri: null
D/MmsConfig( 3739): networkCode: 
,D/MmsConfig( 3739): packageName: com.htc.vvm.att does not exist,
,D/Messaging( 3739): mNeedToUpdateDate2 start,
,D/ReportIndicatorCache( 3739): startAsyncQueryReports ---,
D/MmsAsyncWorkHandler( 3739): 
D/MmsAsyncWorkHandler( 3739): HM tk = 20001,
D/ReportIndicatorCache( 3739): MSG_QUERY_REPORTS >>
,D/DraftCache( 3739): [DraftCache/1] DraftCache.constructor,
D/DraftCache( 3739): [DraftCache/1] refresh
,D/MmsConfig( 3739): networkCode: ,
,I/Messaging( 3739): mccmnc> 
,D/Messaging( 3739): ViewCache CreatePreloadOnlyConversationList,
,D/MessageCustFlag( 3739): sense_version=6.0,
,D/Jerry   ( 3739): start to preload cursor >>>>>>>
,I/ActivityManager(  944): Recipient 3415
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
E/MediaScannerServiceEx( 3697): [getStorageMaskIdFromPath] path is null
D/MmsSmsV2Provider( 1478):  slotId = -1000
D/MediaScannerServiceEx( 3697): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MmsSmsV2Provider( 1478): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/UpdaterAPK | UpdaterBootCompleteReceiver( 3875): onReceive() - start htcCheckinService
D/MediaScannerServiceEx( 3697): [handleExternalVolume] ext storage
,D/MediaProviderUtils( 3697): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3697): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3697): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3697): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3697): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 3697): [update][8]#0#
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/AccFlag ( 1478): sku_id=118
D/PhoneStorageUtil( 3739): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3739): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 3739): createReceiver
,D/MediaProvider( 3697): [update][9]#0#
,D/DraftCache( 3739): [DraftCache/86] rebuildCache
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1478):  slotId = -1000
D/MmsSmsV2Provider( 1478): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MediaProvider( 3697): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted,
I/htcCheckinService(  944): htcCheckinProvider V2.1
D/MtpService( 3697): [sendStorageAdded] Already send to MTP: /storage/emulated/0
I/ActivityManager(  944): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3907 uid=10090 gids={50090, 9997, 1028} abi=arm64-v8a
D/htcCheckinService(  944): htcCheckinService() the mIsServiceRunning = true
I/htcCheckinService(  944): Checkin service onCreate()!
D/MediaProvider( 3697): [update][12]#1#
D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1478):  slotId = -1000
,D/MediaScannerServiceEx( 3697): [AliveExtStorageRows]-0, 0
,D/PMS     (  944): acquireWL(3412391e): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3697 10017 null
D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1478):  slotId = -1000
D/MmsSmsV2Provider( 1478): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 3739): ViewCache CreatePreload
D/htcCheckinService(  944): onStartCommand()
D/htcCheckinService(  944): onStartCommand() the action name = null
D/Messaging( 3739): mNeedToUpdateDate2: false
D/Messaging( 3739): ViewCache CreatePreloadOnlyMultipleOpsList
D/htcCheckinService(  944): InitThread start
,D/TelephUtils( 1478): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,V/MmsProvider( 1478): Update uri=content://mms, match=0
V/MmsProvider( 1478): selection=st=129 AND m_type!=134
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 84
D/Jerry   ( 1478): URI_DRAFT
D/Messaging( 3739): Reset downloading state: 0
V/MmsSystemEventReceiver( 3739): TransactionService is going to be woken up.
,D/MediaScanner( 3697): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,D/Process (  944): killProcessQuiet, pid=2773
I/ActivityManager(  944): Killing 2773:com.htc.contacts/u0a38 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/Cust_MMSMS( 3739): _has_set_default_values_2=true,
D/DraftCache( 3739): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3739): [DraftCache/86] rebuildCache time: 4
D/MmsAsyncWorkHandler( 3739): 
D/MmsAsyncWorkHandler( 3739): HM tk = 20002
,D/MsgPreferenceUtils( 3739): def_index: 0
D/MsgPreferenceUtils( 3739): globalIndex = 1
,D/MsgPreferenceUtils( 3739): phone state: true,
D/MsgPreferenceUtils( 3739): sd state: false
D/MsgPreferenceUtils( 3739): vIndex = 0
,I/ActivityManager(  944): Recipient 2773,
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/MmsSmsV2Provider( 1478):  slotId = -1000
D/MmsSmsV2Provider( 1478): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
V/TransactionService( 3739): 1-Creating TransactionService
,D/Messaging( 3739): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1478): sku_id=118
V/TransactionService( 3739): onStartCommand: 1
D/MmsSystemEventReceiver( 3739): unRegisterForConnectionStateChanges
,V/TransactionService( 3739): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
,V/TransactionService( 3739): Loading previous transactions.
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/AccFlag ( 1478): sku_id=118
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1478): device_type: 1
,D/TransactionService( 3739): Force clearing mTransactionList
,D/TransactionService( 3739): Force set service start id to 1
V/TransactionService( 3739): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 3739): unRegisterForConnectionStateChanges
,V/TransactionService( 3739): Destroying TransactionService
D/TransactionService( 3739): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 3739): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/PMS     (  944): acquireWL(28721718): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 3907 10090 null,
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 ,
W/ContextImpl(  944): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
,I/WorldClock.Global( 3907): isHEPDevice = true
,I/ActivityManager(  944): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3946 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a,
,W/SystemReader( 3907): Cannot find support_china_sense_feature, use default value instead
,I/WorldClock.AlarmUtils( 3907): saveSupportOffAlarmInPreference: isSupport = false,
,I/WorldClock.AlarmService( 3907): isDeviceEncryptionEnabled = false
,D/PMS     (  944): releaseWL(28721718): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
,I/ActivityManager(  944): Killing 3437:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=3437
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/WorldClock.AlarmService( 3907): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
,I/WorldClock.AlarmUtils( 3907): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  944): Recipient 3437,
,I/WorldClock.AlarmUtils( 3907): Cancel any alarm from alarm manager,
,I/WorldClock.AlarmUtils( 3907): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon,
,I/IntentController( 1216): receive(android.intent.action.ALARM_CHANGED,1,false)
,I/WorldClock.AlarmUtils( 3907): isDeviceEncryptionEnabled = false,
,E/UpdateRequestReceiver( 3946): ignoring update request
,I/WorldClock.AlarmUtils( 3907): Calculate next off alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmService( 3907): resetStopwatchToDefault
,E/UpdateRequestReceiver( 3946): ignoring update request
I/WorldClock.DmdCmd( 3907): This version is general off mode alarm function
,W/WorldClock.DmdCmd( 3907): Conn: fail e = java.io.IOException: No such file or directory
,E/UpdateRequestReceiver( 3946): ignoring update request,
,E/UpdateRequestReceiver( 3946): ignoring update request
,E/UpdateRequestReceiver( 3946): ignoring update request
,E/UpdateRequestReceiver( 3946): ignoring update request
,I/WorldClock.AlarmService( 3907): resetTimerToDefault
,I/ActivityManager(  944): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=3987 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
D/Process (  944): killProcessQuiet, pid=3458
I/ActivityManager(  944): Killing 3458:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  446): Explicit concurrent mark sweep GC freed 8642(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 188us total 27.230ms
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 163us total 21.396ms,
,I/ActivityManager(  944): Recipient 3458
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 177us total 22.314ms
,I/DeviceManagement( 3987): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=3987 dbg=false s=true,
,I/DeviceManagement( 3987): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null],
,I/DeviceManagement( 3987): WorkflowService: Starting workflow service
,I/DeviceManagement( 3987): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@5d778ee] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 3987): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3987): BootCompletedWorkflow: Boot completed,
I/DeviceManagement( 3987): BootCompletedWorkflow: ==================================================
,I/DeviceManagement( 3987): ModelRegistry: Loading model meta data from resources...
,I/GoogleHttpClient( 1921): GMS http client unavailable, use old client
,I/ActivityManager(  944): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=4011 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/DeviceManagement( 3987): BackgroundController: *** Update after boot...,
,I/DeviceManagement( 3987): SessionStateController: Checking invariants...,
,V/SmsReceiverService( 3739): updateNotificationAndShortcutStatus: ,
D/MessagingNotification( 3739): New incoming message, can't cancel notification now
D/MessagingNotification( 3739): newMsgCnt: 0, false
,D/Process (  944): killProcessQuiet, pid=3480
I/ActivityManager(  944): Killing 3480:com.htc.music:mediaplaybackservice/u0a48 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/htcbackup-core( 4011): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3987): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 3987): SessionStateController: Checking invariants...,
,I/ActivityManager(  944): Recipient 3480,
,I/DeviceManagement( 3987): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,D/PMS     (  944): releaseWL(cab3272): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
,I/DeviceManagement( 3987): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40],
,I/DeviceManagement( 3987): ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup]
D/AutoSetting( 1437): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1437): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1437): service - requestNLP() NetworkLocationProvider not enabled
,I/ActivityManager(  944): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4039 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/DeviceManagement( 3987): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,I/ActionCombine( 4011): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,D/MediaScanner( 3697):  prescan time: 417ms
,D/MediaScanner( 3697):     scan time: 946ms
D/MediaScanner( 3697): postscan time: 41ms
D/MediaScanner( 3697):    total time: 1404ms
D/MediaScanner( 3697): -----------------------------------------------------------------
D/MediaScanner( 3697): firstscan(media) time: 637ms
,D/MediaScanner( 3697): secondscan(non-media) time: 309ms
D/MediaScanner( 3697):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
,D/MediaScanner( 3697):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3697):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3697):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,I/DeviceManagement( 3987): Perf: *** Cache update - start...
,I/DeviceManagement( 3987): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 3987): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 3987): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 3987): Perf: Scan enabled apps - start...
,D/MediaProvider( 3697): [delete][25]
D/MediaProvider( 3697): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,I/ActionCombine( 1304): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/MediaProvider( 3697): [recoverParentNodes] - 0
D/MediaProvider( 3697): [update][13]
,D/MediaScannerServiceEx( 3697): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3697): [updateImage]+
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
,D/MediaScannerServiceEx( 3697): [updateImage]-0
,I/RemoteViews( 1216): setHTCTheme(com.htc.backup,true,33751145)
D/PMS     (  944): releaseWL(3412391e): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3697): [3] scan finished
D/MediaProviderUtils( 3697): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3697): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3697): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3697): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3697): Process mounted intent for unmounted storage: /storage/ext_sd
,D/MediaScannerServiceEx( 3697): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3697): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3697): [update][5]#1#
,I/RemoteViews( 1216): apply : com.htc.backup 2 15 6 38
,I/RemoteViews( 1216): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1216): setHTCTheme(com.htc.backup,true,33751145),
I/DeviceManagement( 3987): EnabledAppBuilder: Examining 270 installed apps for DM enabled apps...
,I/ActivityManager(  944): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4067 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
D/Process (  944): killProcessQuiet, pid=2202,
I/ActivityManager(  944): Killing 2202:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/RemoteViews( 1216): apply : com.htc.backup 0 4 3 5,
I/RemoteViews( 1216): setHTCTheme(com.htc.backup,true,33751145)
D/MediaProvider( 3697): [update][30]#0#
D/MediaScannerServiceEx( 3697): [disAliveExtStorageRows]--1, 0
I/RemoteViews( 1216): apply : com.htc.backup 0 2 1 5
I/RemoteViews( 1216): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1216): apply : com.htc.backup 1 1 1 5
I/RemoteViews( 1216): apply : com.htc.backup 1 11 15 50
,I/DeviceManagement( 3987): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500100, versionName=6.5.853822
,W/ResourcesManager( 3987): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/DeviceManagement( 3987): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031464, versionName=6.3.860159
,I/DeviceManagement( 3987): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444607021, versionName=4.2.857167
,W/ResourcesManager( 3987): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/ActivityManager(  944): Recipient 2202
,I/DeviceManagement( 3987): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658011289, versionName=7.00.515351,
,I/art     (  944): Explicit concurrent mark sweep GC freed 15725(754KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.275ms total 135.266ms
,W/ResourcesManager( 3987): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/MediaProviderUtils( 3697): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3697): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3697): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3697): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
,W/MediaScannerServiceEx( 3697): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3697): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3697): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3697): [update][6]#1#
,W/ResourcesManager( 3987): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3987): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 3987): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,D/ResetNotifyBootCompleteReceiver( 1478): userSerialNumber = 0,
D/ResetNotifyBootCompleteReceiver( 1478): Receive bootcomplete intent,
D/ResetNotifyBootCompleteReceiver( 1478): isOwnerUser = true
,I/DeviceManagement( 3987): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001316, versionName=6.5.860193
,I/HtcCupdXmlParser( 4067): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  944): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4091 uid=10155 gids={50155, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/MediaProvider( 3697): [update][41]#0#
D/ActivityThread( 4067): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
D/MediaScannerServiceEx( 3697): [disAliveExtStorageRows]--1, 0
,W/ResourceType( 3987): ResTable_typeSpec entry count inconsistent: given 2, previously 1426
,I/DeviceManagement( 3987): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001224, versionName=1.2.853019
,I/HtcCupdXmlParser( 4067): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory),
,W/ResourcesManager( 3987): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 3987): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/DeviceManagement( 3987): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715
,D/QXDM2SD:HtcNative( 1478): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,W/ResourcesManager( 3987): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
,I/ActivityManager(  944): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4115 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/AlarmManager(  944): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  944): [AlarmQueuing] post alarm-list load task,
I/AlarmManager(  944): [AlarmQueuing] init alarm queuing list
W/ResourcesManager( 3987): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  944): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4135 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,I/ActivityManager(  944): Killing 3503:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  944): killProcessQuiet, pid=3503
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 3987): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 3987): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 3987): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.,
,I/DeviceManagement( 3987): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001208, versionName=2.2.848686
,I/DeviceManagement( 3987): EnabledAppBuilder: Found 8 DM enabled apps.
,I/DeviceManagement( 3987): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs,
,I/DeviceManagement( 3987): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
,I/DeviceManagement( 3987): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,I/DeviceManagement( 3987): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
,I/DeviceManagement( 3987): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity
,I/DeviceManagement( 3987): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns,
,I/DeviceManagement( 3987): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,I/DeviceManagement( 3987): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm,
,I/DeviceManagement( 3987): Perf: Scan enabled apps - complete: 730 ms
I/DeviceManagement( 3987): Perf: *** Enabled app cache update - complete: 733 ms
I/DeviceManagement( 3987): Perf: *** Config cache update - start...
,I/DeviceManagement( 3987): ConfigCacheController: *** Updating config cache...,
I/DeviceManagement( 3987): ConfigCacheController: *** Updating stale config cache entries...
,I/ActivityManager(  944): Recipient 3503
,I/art     ( 3987): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>,
I/art     ( 3987): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,W/System.err( 3987): Starting the internal HTTP client,
,I/DeviceManagement( 3987): ConfigCacheController: Getting config update from server: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs/versions/c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17/cid/MDoxOjIwMTQtMDEtMDlUMDQ6MTI6MjQuMjMxWg,
,I/DeviceManagement( 3987): DeviceClientResource: Active network...
I/DeviceManagement( 3987):   No active network
,I/DeviceManagement( 3987): DeviceClientResourceController: Network is unavailable: code=1010 description=There is no active network.
,I/DeviceManagement( 3987): BackgroundController: *** Network unavailable!
,I/DeviceManagement( 3987): Perf: *** Config cache update - complete: 179 ms
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=1, flag=1, pid=3987, uid=10099, userID:0
I/DeviceManagement( 3987): Perf: *** Cache update - complete: 916 ms
,I/DeviceManagement( 3987): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@5d778ee]
,I/DeviceManagement( 3987): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@c45b801] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 3987): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 3987): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3987): SessionStateController: Checking invariants...
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 4115): -onCreate()
,I/AlarmManager(  944): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@116451b7
,I/AlarmManager(  944): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@2326bd24,
,V/Settings:HtcSettingsApplication( 4115): [4115/4115] onCreate(),
,I/AlarmManager(  944): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@32f7b08d,
W/ContextImpl( 4115): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  944): Start proc com.android.settings:remote for service com.android.settings/.framework.app.HtcIntentService: pid=4159 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
I/AlarmManager(  944): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  944): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  944): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  944): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
,I/AlarmManager(  944): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  944): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  944): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  944): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  944): [AlarmQueuing] add queuing package: com.htc.android.mail,
I/AlarmManager(  944): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  944): [AlarmQueuing] add queuing package: com.facebook.orca
D/Process (  944): killProcessQuiet, pid=3525
I/AlarmManager(  944): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  944): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  944): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/ActivityManager(  944): Killing 3525:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/DeviceManagement( 3987): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true,
,I/DeviceManagement( 3987): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@c45b801],
,I/HtcModeClient( 3157): handler message = 4011
E/HtcModeClient( 3157): Check connection and retry 2 times.
,I/ActivityManager(  944): Recipient 3525,
,D/TetherSettings( 4115): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 4115): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4115): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4115): Cust_ConnectToPC   : spcsc>false
D/        ( 4115): Cust_ConnectToPC   : IPT>true
D/        ( 4115): Cust_ConnectToPC   : Singel_USB>false,
,W/Settings( 4115): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/DeviceManagement( 3987): WorkflowService: Stopping workflow service
,D/Process (  944): killProcessQuiet, pid=3557
I/ActivityManager(  944): Killing 3557:com.htc.HTCSpeaker/u0a54 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/SmartNS_Utility( 4115): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4115): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4115): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 4115): setISNotification
,V/Settings:HtcSettingsApplication( 4159): [4159/4159] onCreate(),
,D/SmartNS_Utility( 4115): usb_cable_connect = 1,
,D/SmartNS_Utility( 4115): usb_denied = 0,
,I/SmartNS_PSService( 4115): usb notificaiton:true
,E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false,
,I/ActivityManager(  944): Recipient 3557,
,I/htcbackup-core( 4011): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.11.05 at 12:06:52.457 CET] interval end=[2015.11.12 at 12:06:52.457 CET]
,I/ActionCombine( 4115): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,V/AlarmManager(  944): sending alarm PendingIntent{1404508e: PendingIntentRecord{3235c0af com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=17, w=1447326412457, Int=604800000
,D/SmartNS_Utility( 4115): usb_cable_connect = 1
,D/SmartNS_Utility( 4115): usb_denied = 0
,I/ActivityManager(  944): Killing 3596:com.htc.lmw/u0a58 (adj 15): empty #17
I/SmartNS_PSService( 4115): usb notificaiton:true
D/Process (  944): killProcessQuiet, pid=3596
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1216): setHTCTheme(com.android.settings,true,33751145)
,I/RemoteViews( 1216): apply : com.android.settings 1 10 2 36,
,I/ActivityManager(  944): Recipient 3596,
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true,
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/ActivityManager(  944): Killing 3628:com.android.managedprovisioning/u0a63 (adj 15): empty #17
,D/Process (  944): killProcessQuiet, pid=3628
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/RemoteViews( 1216): reapply : com.htc.backup 5 38,
,I/RemoteViews( 1216): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1216): apply : com.htc.backup 2 2 0 5,
I/RemoteViews( 1216): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1216): apply : com.htc.backup 0 2 0 5,
I/RemoteViews( 1216): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1216): apply : com.htc.backup 0 2 0 5
I/RemoteViews( 1216): reapply : com.htc.backup 13 50
,I/RemoteViews( 1216): reapply : com.android.settings 0 36,
,I/ActivityManager(  944): Recipient 3628
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,I/ActivityManager(  944): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4186 uid=9987 gids={49987, 9997} abi=arm64-v8a,
,D/SmartDim(  944): Init customizeScreenOffDelayClass error
,W/BroadcastQueue(  944): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{6de366 u0 ReceiverList{3046ffc1 944 system/1000/u0 local:35b9b8a8}}
I/SensorManager(  944): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@35f8e79a, sensor = {Sensor name="Accelerometer Sensor", vendor="hTC Corp.", version=1, type=1, maxRange=39.2266, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): enable: get sensor name = Accelerometer Sensor
W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 3
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  944): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
,W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@35f8e79a, eanble = 1, strlen(mName) = 36
,W/SensorService(  944): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  944): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@12a5c5ca
W/SensorService(  944): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@358c20e1
W/SensorService(  944): Listener[2] = com.htc.smartdim.sensor_eye@35f8e79a
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  944): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@35f8e79a, sensor = {Sensor name="CM36686 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): enable: get sensor name = CM36686 Proximity sensor
W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 4
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  944): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@35f8e79a, eanble = 1, strlen(mName) = 36
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  944): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@12a5c5ca
W/SensorService(  944): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@358c20e1
W/SensorService(  944): Listener[2] = com.htc.smartdim.sensor_eye@35f8e79a
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  944): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4209 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  944): Killing 2132:com.google.android.gms/u0a24 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=2132
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/SensorManager(  944): dispatchSensorEvent: Proximity = 9.0, mListener = com.htc.smartdim.sensor_eye@35f8e79a
,I/ActivityManager(  944): Recipient 2132
,I/ActivityManager(  944): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4230 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  944): Killing 3775:com.htc.cs.pns/u0a71 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=3775
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  944): Recipient 3775
,I/ActivityManager(  944): Waited long enough for: ServiceRecord{276b77f9 u0 com.google.android.gms/.gcm.GcmService}
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4230, uid=10072, userID:0
,W/global  ( 4230): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 4230): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 4230): [apache-http] Connection GC has been deprecated!
,W/global  ( 4230): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 4230): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  944): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4267 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/art     (  446): Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 356us total 29.402ms
,W/Settings( 4230): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4230): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4267): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4267): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 243us total 27.725ms
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4230, uid=10072, userID:0,
,I/MultiDex( 4267): VM with version 2.1.0 has multidex support
,I/MultiDex( 4267): install
I/MultiDex( 4267): VM has multidex support, MultiDex support library is disabled.
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 198us total 23.601ms
,D/Volley  ( 4230): [395] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4230): [389] DiskBasedCache.clear: Cache cleared.
,V/JNIHelp ( 4267): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  944): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4293 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
D/Process (  944): killProcessQuiet, pid=3808
I/ActivityManager(  944): Killing 3808:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,W/ActivityThread( 4267): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4267): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@cb1975: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4267): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  944): Recipient 3808
,D/Finsky  ( 4230): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 4230): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4230): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
W/ResourcesManager( 4293): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4293): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 4293): VM with version 2.1.0 has multidex support
,I/MultiDex( 4293): install
I/MultiDex( 4293): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 4230): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 4293): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 4293): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 4293): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@bfbc15b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4293): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  944): Killing 3830:com.htc.showme/u0a81 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=3830
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  944): Recipient 3830
,V/GLSUser ( 1921): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED,
,D/PMS     (  944): acquireWL(24272dee): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1921 10024 null
,D/Process (  944): killProcessQuiet, pid=3853,
,I/ActivityManager(  944): Killing 3853:com.htc.feedback/u0a83 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/NotificationStore( 1921): System rebooted after Notification storage file was last written
I/NotificationStore( 1921): Deleting the file
,D/PMS     (  944): releaseWL(24272dee): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,I/ActivityManager(  944): Recipient 3853
,V/GmsCoreStatsServiceLauncher( 4293): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,V/Finsky  ( 4230): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/PersistentNotificationBroadcastReceiver( 1921): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/art     (  944): Explicit concurrent mark sweep GC freed 14617(730KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.446ms total 152.732ms
,W/InstanceID/Rpc( 4293): Found 10024
,D/FileApkUtils( 4293): Spent 25ms computing apk sha1.,
D/FileApkUtils( 4293): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 4293): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 4293): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 4293): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971,
,D/GmsModuleFndr( 4293): Beginning GMS chimera module scan
,W/asset   ( 4293): Copying FileAsset 0x55afa59110 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.
,D/PMS     (  944): acquireWL(1f5eab08): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4293 10024 null
,D/GmsModuleFndr( 4293): Module pkg com.google.android.apps.kids.familylink not installed, skipping,
D/PMS     (  944): acquireWL(39b72a1): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4293 10024 WorkSource{10024 com.google.android.gms}
D/ChimeraCfgMgr( 4293): Beginning module configuration check
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1921, uid=10024, userID:0
,D/ChimeraCfgMgr( 4293): Module APKs unchanged, check complete
,D/PMS     (  944): acquireWL(1d74f487): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4293 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(4332f52): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4293 10024 null
,D/GCM     ( 4293): COMPAT: Multi user not supported
,D/PMS     (  944): acquireWL(da25223): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4293 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1921): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED,
,I/ActivityManager(  944): Delay finish: com.google.android.gms/.tron.AlarmReceiver
,D/PMS     (  944): releaseWL(1f5eab08): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  944): releaseWL(da25223): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(3bbded7f): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4293 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(39b72a1): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms},
,I/GCoreUlr( 4293): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/PMS     (  944): acquireWL(15b956aa): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1777): DispatchingService.onCreate(),
I/CheckinService( 4293): Disabling old GoogleServicesFramework version,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4293, uid=10024, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4293, uid=10024, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4293, uid=10024, userID:0
,D/SystemUpdateService( 4293): onCreate
,D/PMS     (  944): acquireWL(2197324d): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4293, uid=10024, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4293, uid=10024, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4293, uid=10024, userID:0
,D/SystemUpdateService( 4293): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4293, uid=10024, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4293, uid=10024, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4293, uid=10024, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4293, uid=10024, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4293, uid=10024, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4293, uid=10024, userID:0
,I/ConfigService( 1921): onCreate
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4293, uid=10024, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4293, uid=10024, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4293, uid=10024, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4293, uid=10024, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4293, uid=10024, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4293, uid=10024, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4293, uid=10024, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4293, uid=10024, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4293, uid=10024, userID:0
I/ConfigFetchService( 4293): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/GCoreUlr( 1777): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,V/AuthZen ( 4293): Handling intent: android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 4293): Handling event: android.intent.action.BOOT_COMPLETED
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4293, uid=10024, userID:0,
,W/System.err(  944): java.lang.Throwable: stack dump
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4293, uid=10024, userID:0
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  944): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  944): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  944): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/BluetoothManagerService(  944): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@864beb2:true
W/System.err(  944): 	at android.os.Binder.execTransact(Binder.java:454)
I/CheckinService( 4293): Checking schedule, now: 1457426605672 next: 1456765623471
I/CheckinService( 4293): active receiver: enabled
,I/SystemUpdateService( 4293): cancelUpdate (empty URL)
,I/SystemUpdateService( 4293): active receiver: disabled
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4293, uid=10024, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4293, uid=10024, userID:0
,I/art     ( 4293): Background partial concurrent mark sweep GC freed 3391(233KB) AllocSpace objects, 2(40KB) LOS objects, 50% free, 3MB/7MB, paused 6.889ms total 53.747ms
,W/BaseAppContext( 4293): Using Auth Proxy for data requests.
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1777, uid=10024, userID:0
,D/PMS     (  944): acquireWL(14ad41dc): PARTIAL_WAKE_LOCK  Icing 0x1 4293 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(15b956aa): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSUser ( 4293): [ChannelManager] Attempting to channel bind connection HttpClient.,
,I/art     ( 1921): Explicit concurrent mark sweep GC freed 5456(358KB) AllocSpace objects, 6(120KB) LOS objects, 51% free, 3MB/7MB, paused 700us total 42.898ms
,I/art     ( 1777): Explicit concurrent mark sweep GC freed 23059(1445KB) AllocSpace objects, 8(160KB) LOS objects, 46% free, 4MB/8MB, paused 880us total 66.622ms,
,I/ConfigFetchService( 4293): service connected
,I/ActivityManager(  944): Resuming delayed broadcast
,I/GLSUser ( 4293): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
D/PMS     (  944): releaseWL(1d74f487): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(14ad41dc): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(3bbded7f): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/SystemUpdateService( 4293): onDestroy
,D/ChimeraCfgMgr( 4293): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/Kids    ( 4293): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
D/ConfigFetchService( 4293): ConfigApi connection successful.
,I/AuthZen ( 4293): Fetching signing key...
,I/GCoreUlr( 1777): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/AuthZen ( 4293): Signing key fetched successfully!
,I/ActivityManager(  944): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4392 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/PMS     (  944): acquireWL(2d15ef86): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
W/BaseAppContext( 4293): Using Auth Proxy for data requests.
D/PMS     (  944): releaseWL(2d15ef86): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1777): Unbound from all location providers
,D/PMS     (  944): releaseWL(2197324d): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms},
I/AuthZen ( 4293): Starting Enrollment...
,I/art     (  447): Explicit concurrent mark sweep GC freed 8691(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 266us total 19.175ms
,D/AuthZen ( 4293): getting auth token. Attempt 0
,I/art     (  447): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 266us total 15.223ms,
,I/GLSActivity( 1921): [ac] getting account id
W/ResourcesManager( 4392): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  447): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 229us total 15.070ms
,I/GCoreUlr( 1777): DispatchingService.onDestroy()
,D/PMS     (  944): acquireWL(55cb13f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(55cb13f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1777): Unbound from all location providers
,I/GLSUser ( 1921): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1921): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GLSUser ( 1921): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227,
,I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AuthZen ( 4293): Error getting auth token
E/AuthZen ( 4293): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4293): 	at com.google.android.gms.auth.p.b(SourceFile:442)
,E/AuthZen ( 4293): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4293): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4293): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4293): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4293): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 4293): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 4293): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4293): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4293): 	,at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4293): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4293): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4293): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4293): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4293): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/a       ( 4293): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 4293): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 4293): Clearing transaction cache
,D/PMS     (  944): acquireWL(26f5225b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 944 1000 null
,D/PMS     (  944): releaseWL(26f5225b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/Babel_SMS( 4392): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 4392): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 3739): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3739): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 4392): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 4392): MmsConfig.loadFromDatabase
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4392, uid=10112, userID:0
,E/Babel_SMS( 4392): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4392): MmsConfig.loadFromResources
,E/Babel_SMS( 4392): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4392): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,W/Settings( 4392): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/Babel_Crash( 4392): startup - clean
,I/Babel   ( 4392): deleted: false for 0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4392, uid=10112, userID:0,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4392, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4392, uid=10112, userID:0,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4392, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4392, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4392, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4392, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4392, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4392, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4392, uid=10112, userID:0
,W/VideoCapabilities( 4392): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4392): Unsupported mime video/x-ms-wmv
,W/Utils   ( 4392): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 4392): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4392): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4392): Unsupported mime audio/qcelp
,W/VideoCapabilities( 4392): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 4392): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 4392): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 4392): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 4392): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 4392): Unrecognized profile 2130706433 for video/avc,
,I/vclib   ( 4392): onServiceConnected,
W/Babel   ( 4392): Attempted to change video mute state without an active call.
,I/ActivityManager(  944): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4425 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/ResourcesManager( 4425): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4425): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/art     ( 4425): No such thread id for suspend: 19
,V/JNIHelp ( 4425): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 4425): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 4425): Installed default security provider GmsCore_OpenSSL
,E/cutils-trace( 4458): Error opening trace file: Permission denied (13)
,I/dex2oat ( 4458): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1885156617.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads1885156617.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 4458): dex2oat: override thread count:4
,I/dex2oat ( 4458): dex2oat took 56.284ms (threads: 4),
,I/ActivityManager(  944): Waited long enough for: ServiceRecord{261c34d5 u0 com.htc.autobot/.htcmodeclient.HtcModeService},
,E/YouTube MDX( 4425): Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
,D/libc    ( 4425): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4,
D/libc    ( 4425): [NET] android_getaddrinfofornet-, SUCCESS
,D/VoldConnector(  944): SND -> {11 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/ContextImpl( 4425): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,I/HtcModeClient( 3157): handler message = 4011
E/HtcModeClient( 3157): Check connection and retry 3 times.
,D/VoldConnector(  944): SND -> {12 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
W/ContextImpl( 4425): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,D/VoldConnector(  944): SND -> {13 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
,W/ContextImpl( 4425): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,D/VoldConnector(  944): SND -> {14 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 4425): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,V/AlarmManager(  944): sending alarm PendingIntent{2fe1796: PendingIntentRecord{563ef17 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=53499, Int=259200000
,V/AlarmManager(  944): sending alarm PendingIntent{223afced: PendingIntentRecord{187c1722 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457426607523, Int=0
,W/InstanceID/Rpc( 4425): Found 10024
,D/VoldConnector(  944): SND -> {15 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 4425): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,I/iu.UploadsManager( 4293): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400,
,I/iu.UploadsManager( 4293): End new media; added: 0, uploading: 0, time: 45 ms
,I/ActivityManager(  944): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4508 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  944): killProcessQuiet, pid=2842
I/ActivityManager(  944): Killing 2842:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 2842,
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/Gmail   ( 4508): getAccountsCursor,
,I/art     (  944): Explicit concurrent mark sweep GC freed 16336(905KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 15MB/23MB, paused 1.565ms total 157.850ms
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4508, uid=10106, userID:0
W/ActivityManager(  944): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4508): Observing account changes for notifications
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4508, uid=10106, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4508, uid=10106, userID:0,
,W/GAV2    ( 4508): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 4508): Error finding the version of the Email provider.....,
E/Gmail   ( 4508): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4508): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4508): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4508): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4508): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4508): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4508): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 4508): We do not support migrating this version of the Email provider.
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4508, uid=10106, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4508, uid=10106, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4508, uid=10106, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4508, uid=10106, userID:0,
,I/Gmail   ( 4508): getAccountsCursor
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  944): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4549 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4508, uid=10106, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4508, uid=10106, userID:0
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 4508): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2e1e078b that was originally bound here
E/ActivityThread( 4508): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2e1e078b that was originally bound here
E/ActivityThread( 4508): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4508): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4508): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 4508): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 4508): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4508): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4508): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4508): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4508): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4508): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4508): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4508): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4508): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4508): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4508): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  944): Unbind failed: could not find connection for android.os.BinderProxy@35c32d83
,E/SQLiteLog( 4508): (283) recovered 1511 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 4508): notifyAccountChanged
,I/Gmail   ( 4508): getAccountsCursor,
I/Gmail   ( 4508): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4508): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/PMS     (  944): acquireWL(3702c9fb): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4508 10106 null
,I/Gmail   ( 4508): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,I/Gmail   ( 4508): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4508): calculateUnknownSyncRationalesAndPurgeInBackground: running,
D/PMS     (  944): acquireWL(3702c9fb): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4508 10106 null
,I/Gmail   ( 4508): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,D/PMS     (  944): acquireWL(3702c9fb): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4508 10106 null
,I/Gmail   ( 4508): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4508, uid=10106, userID:0
,D/Process (  944): killProcessQuiet, pid=3875
I/ActivityManager(  944): Killing 3875:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/AndroidHttpClient( 4230): Leak found,
E/AndroidHttpClient( 4230): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4230): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4230): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4230): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4230): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4230): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4230): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4230): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4230): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144),
E/AndroidHttpClient( 4230): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4230): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4230): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4230): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4230): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4230): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4230): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4230): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824),
,I/ActivityManager(  944): Recipient 3875
,V/AlarmManager(  944): sending alarm PendingIntent{32eb5e2: PendingIntentRecord{1b7f5394 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=55915, Int=0,
,D/LocationManagerService(  944): getProviders()=[passive]
,I/Gmail   ( 4508): master sync=false, engine sync=true,
,I/ActivityManager(  944): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4581 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4549, uid=10085, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4549, uid=10085, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4549, uid=10085, userID:0
,I/Gmail   ( 4508): getAccountsCursor
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
I/Gmail   ( 4508): master sync=false, engine sync=true
,W/BroadcastQueue(  944): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000),
D/WifiService(  944): New client listening to asynchronous messages
,E/WifiTrafficPoller(  944): ADD_CLIENT: 6
,I/VelvetNetworkClient( 4549): Network connection not availble,
,I/ActivityManager(  944): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4618 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  944): Killing 3907:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=3907
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  944): Recipient 3907
,D/Process (  944): killProcessQuiet, pid=3946
I/ActivityManager(  944): Killing 3946:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 3946
,I/htcbackup-core( 4011): SuperSaverModeReceiver: on receiving action com.htc.server.htcpowersaver.action.OFF,
I/htcbackup-core( 4011): SuperSaverModeReceiver: going to send resume event
,I/htcbackup-core( 4011): BackupRestoreManager: onHandleIntent
I/htcbackup-core( 4011): BackupRestoreManager: resume
,I/ActivityManager(  944): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=4640 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,E/htcbackup-core( 4011): BackupRestoreManager: Storage is not configured,
E/htcbackup-core( 4011): BackupStatus: Ignoring failure message - backup already failed with message:  CONNECTION_FAIL_STORAGE
,W/ResourcesManager( 4640): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 4640): Created com.android.providers.calendar.CalendarAlarmManager@31687533(com.htc.providers.calendar.HtcCalendarProvider@35a1a0f0),
,D/CalendarProvider2( 4640): wait start:true
,W/System.err( 4011): Starting the HTTP client,
,W/htcbackup-core( 4011): BackupServiceClientResourceProxy: Reseting appServerErrorCount
,D/FlexNetS( 4640): updateSvcAllowedInSettings:false,
D/CalendarProvider2( 4640): wait end:false
,W/htcbackup-core( 4011): BackupRestoreManager: No sense account found - aborting,
I/htcbackup-core( 4011): BackupRestoreManager: DM is not ready, pending resume
,I/ActivityManager(  944): Start proc com.htc.showme for broadcast com.htc.showme/.update.MobileNetworkTurnOnReceiver: pid=4673 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/[AppShowMeDebug]MobileNetworkTurnOnReceiver( 4673): onReceive statefalse
,D/Process (  944): killProcessQuiet, pid=4039
I/ActivityManager(  944): Killing 4039:com.htc.backupreset/1000 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  944): Recipient 4039
,D/FlexNetS( 4640): updateSvcAllowedInSettings:false,
,D/FlexNetS( 4640): updateSvcAllowedInSettings:false,
,D/FlexNetS( 4640): updateSvcAllowedInSettings:false,
,D/FlexNetS( 4640): updateSvcAllowedInSettings:false,
,D/FlexNetS( 4640): updateSvcAllowedInSettings:false,
,D/FlexNetS( 4640): updateSvcAllowedInSettings:false
,D/FlexNetS( 4640): updateSvcAllowedInSettings:false,
,D/FlexNetS( 4640): updateSvcAllowedInSettings:false,
,I/ActivityManager(  944): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=4694 uid=10009 gids={50009, 9997, 5001, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/browser ( 4694): Browser versionCode = 760001576 versionName = 7.0.2514321356,
,W/SWE_UI  ( 4694): SWE using SurfaceView - Multi-Process,
,I/LibraryLoader( 4694): Loading: swewebviewchromium
,I/LibraryLoader( 4694): Time to load native libraries: 63 ms (timestamps 9957-20)
,I/LibraryLoader( 4694): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 4694): Initializing chromium process, renderers=9
,I/LibraryLoader( 4694): Expected native library version number "",actual native library version number ""
,I/chromium( 4694): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,W/art     ( 4694): Attempt to remove local handle scope entry from IRT, ignoring,
,W/chromium( 4694): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 4694): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 4694): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4694): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4694): Local Branch: 
I/Adreno-EGL( 4694): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4694): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4694):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  944): Killing 4067:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=4067
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  944): Recipient 4067
,V/IccIntentReceiver( 1636): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT icc slot: 0
,I/SIMStateChangeReceiver( 4640): SIM state: ABSENT
,I/SIMStateChangeReceiver( 4640): remove notification
,D/FlexNetS( 4640): updateSvcAllowedInSettings:false
,I/ActivityManager(  944): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=4742 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,I/CalendarProvider2( 4640): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 4640): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Process (  944): killProcessQuiet, pid=4135
I/ActivityManager(  944): Killing 4135:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 4135,
,D/PMS     (  944): releaseWL(3702c9fb): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
,I/ActivityManager(  944): Killing 4159:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=4159
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.appDiedLocked:5130 
,I/ActivityManager(  944): Recipient 4159
,D/ExchangePolicystatus( 3739): onReceive()
D/SmsReceiver( 3739): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 3739): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 3739): onReceive(): else
,D/GCM     ( 1921): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1921): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,D/AccTypeManager( 4742): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,V/GmsCoreStatsServiceLauncher( 4293): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/AccTypeManager( 4742): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  944): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4772 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4293, uid=10024, userID:0
,W/ResourcesManager( 4772): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4772): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
,D/AccFlag ( 1478): sku_id=118
V/IccIntentReceiver( 1636): IccIntent: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED icc state: null icc slot: 0
,I/MultiDex( 4772): VM with version 2.1.0 has multidex support
I/MultiDex( 4772): install
I/MultiDex( 4772): VM has multidex support, MultiDex support library is disabled.
,D/AccTypeManager( 4742): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  944): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4796 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,E/ExternalAccountType( 4742): Unsupported attribute readOnly,
,I/art     (  446): Explicit concurrent mark sweep GC freed 8681(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 166us total 18.829ms
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 94
D/AccFlag ( 1478): sku_id=118
,D/AccTypeManager( 4742): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
V/JNIHelp ( 4772): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 139us total 16.162ms
,D/AccTypeManager( 4742): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 120us total 17.059ms,
,D/AccTypeManager( 4742): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 4742): Unsupported attribute readOnly
,W/ActivityThread( 4772): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4772): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@cb1975: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4772): Installed default security provider GmsCore_OpenSSL
,I/art     (  944): Explicit concurrent mark sweep GC freed 10924(590KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.296ms total 130.417ms
,D/LocationInitializer( 4293): Restart initialization of location,
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 94,
D/AccFlag ( 1478): sku_id=118
D/WearableService( 4772): callingUid 10024, callindPid: 4772
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 96
D/AccFlag ( 1478): sku_id=118
,E/MDM     ( 1777): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ImageRamCache( 4796): create image Cache, size: 31457280.
,I/ImageRamCache( 4796): [resize] ImageRamCache resized to: 30Mb.
,I/ImageRamCache( 4796): create image Cache, size: 31457280.
,I/FeedSettings( 4796): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true,
I/FeedSettings( 4796): GroupBudget 0.500000 0.380000
I/FeedSettings( 4796): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4796): changeLocale(): en_GB,
,I/Prism.AllAppsOptionsMa_( 4796): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 4796): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 4796): [custom highlight] onReceive,
,D/CustomHighlightService( 4796): [custom highlight] onHandleIntent,
,D/NewsDB  ( 4796): set custom highlight [],
,I/ActivityManager(  944): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4827 uid=10035 gids={50035, 9997} abi=arm64-v8a,
,D/CustomHighlightService( 4796): [custom highlight] set tags 
,I/ActivityManager(  944): Killing 3987:com.htc.cs.dm/u0a99 (adj 15): empty #17
,D/Process (  944): killProcessQuiet, pid=3987
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 3987
,D/Process (  944): killProcessQuiet, pid=4186
I/ActivityManager(  944): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4849 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  944): Killing 4186:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17,
,I/ActivityManager(  944): Recipient 4186,
,I/ActivityManager(  944): Waited long enough for: ServiceRecord{1b6d1edc u0 com.htc.HTCSpeaker/.NGFService}
,D/ContactMessageStore( 1478): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1478): MSG_NOTIFY_CS_TO_SYNC <<
,D/SMSBackup( 4849): Got a database change event,
,I/ActivityManager(  944): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4870 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,D/Process (  944): killProcessQuiet, pid=4209
I/ActivityManager(  944): Killing 4209:com.android.smith/1000 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 ,
,I/ActivityManager(  944): Recipient 4209
,D/MessagingShortcutReceiver( 3739): keep hiding shortcut bubble,
,D/MessagingShortcut( 3739): updateMsgShortcut, msg count> -1,
D/MessagingShortcut( 3739): After query: 0
D/MessagingShortcut( 3739): mPresentUnreadCount: -1
,D/MessageUtils( 3739): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 3739): setMsgShortcutDrawable> 0, false
,D/MessagingShortcut( 3739): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1304): [EventService] reorderNotification, total:0
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  944): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4892 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
,W/ResourcesManager( 4892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/ActivityManager(  944): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4914 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/TodoTaskshortcut( 4892): update TASK shortcut>
,D/PMS     (  944): acquireWL(3b875edd): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4892 10069 null
,D/PMS     (  944): acquireWL(1378ea52): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4892 10069 null
,D/PMS     (  944): releaseWL(3b875edd): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null,
,E/TodoTaskNotifyService( 4892): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4892): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 4892): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
D/PMS     (  944): releaseWL(1378ea52): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 4892): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4892): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4892): stopSelfResult true,
,D/Prism.PackageStateRece_( 1529): action: android.intent.action.PACKAGE_ADDED
I/ActivityManager(  944): Killing 4115:com.android.settings/1000 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=4115
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/[PluginManager]RegisterService( 1437): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello,
I/[PluginManager]RegisterService( 1437): handle notify Blinkfeed plugin client changed,
,D/MdScBoot( 4870): [697.1.] 30@-084303 -> 40
,D/MdScBootUi( 4870): [697.1.2.] boot 118,
,D/MdScSimSt( 4870): [697.1.2.] qry 118: 0+1 running 0,
,I/ActivityManager(  944): Recipient 4115,
,I/HtcModeClient( 3157): handler message = 4011,
E/HtcModeClient( 3157): Check connection and retry 4 times.
,I/ActivityManager(  944): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4946 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,D/Process (  944): killProcessQuiet, pid=4267
,I/ActivityManager(  944): Killing 4267:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  944): Recipient 4267
,D/Process (  944): killProcessQuiet, pid=4230,
I/ActivityManager(  944): Killing 4230:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 4230
,I/DeviceManagement( 4946): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4946 dbg=false s=true,
,I/DeviceManagement( 4946): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,D/Process (  944): killProcessQuiet, pid=4425
I/ActivityManager(  944): Killing 4425:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  944): Recipient 4425
,I/ActivityManager(  944): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4968 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a,
,D/HtcCupdReceiver(Provider)( 4968):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED,
,I/ActivityManager(  944): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4989 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActivityManager(  944): Killing 4508:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=4508
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  944): Recipient 4508
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 4989): -onCreate(),
,V/Settings:HtcSettingsApplication( 4989): [4989/4989] onCreate(),
,D/Process (  944): killProcessQuiet, pid=4549,
I/ActivityManager(  944): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5011 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  944): Killing 4549:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17,
,D/Settings:HtcWirelessFeatureFlags( 4989): id/is att sku: 118/false,
,E/Settings:HtcWrapHeaderInfo( 4989): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4989): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 4989): updateDevelopment, bPrefShow = true,
,I/ActivityManager(  944): Recipient 4549
D/WifiService(  944): Client connection lost with reason: 4
,E/Settings:HtcUmcWidgetEnabler( 4989): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportHomeButton]support         :false
,I/ActivityManager(  944): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 4989): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 4989): isSupportVoWifi: null,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4989): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 4989): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4989): isSupportMusicChannel(): false,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4989): [supportHomeButton]support         :false
,I/ActivityManager(  944): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 4989): isSupportVoWifi: null
E/ActivityThread( 4989): Failed to find provider info for com.htc.vowifi
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5011, uid=10072, userID:0,
,W/global  ( 5011): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 5011): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 5011): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5011): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 5011): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  944): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5052 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/Settings( 5011): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5011): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5011, uid=10072, userID:0
,W/ResourcesManager( 5052): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5052): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5052): VM with version 2.1.0 has multidex support,
I/MultiDex( 5052): install
I/MultiDex( 5052): VM has multidex support, MultiDex support library is disabled.
,D/Process (  944): killProcessQuiet, pid=4673
,I/ActivityManager(  944): Killing 4673:com.htc.showme/u0a81 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  944): Recipient 4673
,D/Finsky  ( 5011): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5011): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5011): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 5052): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/PackageBroadcastService( 4293): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 4293): Loading module com.google.android.gms.games from APK com.google.android.play.games,
D/ChimeraModuleLdr( 4293): Loading module APK com.google.android.play.games
,D/Finsky  ( 5011): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
D/PMS     (  944): acquireWL(365eb750): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4293 10024 null
,W/ActivityThread( 5052): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5052): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@cb1975: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5052): Installed default security provider GmsCore_OpenSSL
,I/art     ( 1921): Explicit concurrent mark sweep GC freed 9561(521KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 648us total 41.050ms
,I/ConfigFetchService( 4293): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
,D/PMS     (  944): acquireWL(2785e78b): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4293 10024 WorkSource{10374 com.example.hello}
I/ConfigFetchService( 4293): launchTask
,D/PMS     (  944): releaseWL(365eb750): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  944): acquireWL(1122068): PARTIAL_WAKE_LOCK  Icing 0x1 4293 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4293): Loading module com.google.android.gms.games from APK com.google.android.play.games,
D/ChimeraModuleLdr( 4293): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4293): Loading module com.google.android.gms.vision from APK com.google.android.gms,
,V/ConfigFetchTask( 4293): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WKcWMWvCU23ME-060oMI-0Nt2IjOb3iC_tLRYeRUCexn4OtPmmJcXEgqD3ZCQtJ-bFpFS_Ud9Gl0JMrv656wJP4FJRw9Yser-Q7_IOhdj7HzT8Olja7A3gGIHINz5t70wYo6olADobN6Ier3TB-mXNIhOx9wtE1MCFa8SbOLKn9wnkIVvfXavfqa9XQEjp-EPn0pB_
,I/PeopleContactsSync( 4293): CP2 sync disabled
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4293, uid=10024, userID:0,
,D/Vision  ( 4293): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 4293): Failed to find package metadata for com.example.hello
D/Vision  ( 4293): No vision deps
,I/GoogleURLConnFactory( 4293): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  944): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5090 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/art     (  446): Explicit concurrent mark sweep GC freed 8644(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 243us total 39.438ms
,I/Icing   ( 4293): Storage manager: low false usage 2.04MB avail 5.80GB capacity 7.95GB,
D/libc    ( 4293): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4293): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 4293): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4293): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4293): [NET] android_getaddrinfo_proxy+
D/libc    ( 4293): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4293): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4293): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname,
I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 245us total 23.737ms
I/ActivityManager(  944): Killing 4694:com.htc.sense.browser/u0a9 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=4694
D/PMS     (  944): releaseWL(2785e78b): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10374 com.example.hello},
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ConfigFetchService( 4293): fetch service done; releasing wakelock
I/ConfigFetchService( 4293): stopping self
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 150us total 16.202ms
W/Icing   ( 4293): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4293): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4293): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4293): Received bad json for corpus context scoring override -- ignoring.
,I/ActivityManager(  944): Recipient 4694
,V/Finsky  ( 5011): [1] GearheadStateMonitor.onReady: sIsProjecting:false
W/BaseAppContext( 4293): Using Auth Proxy for data requests.
,W/BaseAppContext( 4293): Using Auth Proxy for data requests.
,W/BaseAppContext( 4293): Using Auth Proxy for data requests.
,W/BaseAppContext( 4293): Using Auth Proxy for data requests.
,E/Icing   ( 4293): Loading extension by file descriptor -1 failed
,W/BaseAppContext( 4293): Using Auth Proxy for data requests.
,W/BaseAppContext( 4293): Using Auth Proxy for data requests.
,V/AlarmManager(  944): sending alarm PendingIntent{c769480: PendingIntentRecord{abc6ab9 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457426614914, Int=0,
D/Finsky  ( 5011): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 5011): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 4293): updateResources: need to parse f{com.google.android.gms}
,I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  944): Explicit concurrent mark sweep GC freed 12890(620KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.237ms total 131.440ms
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/Icing   ( 4293): Internal init done: storage state 0
,I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5011): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Icing   ( 4293): Post-init done
,D/PMS     (  944): releaseWL(1122068): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/GAv4    ( 5090): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5090):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5090):   adb logcat -s GAv4
,W/GAv4    ( 5090): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5090): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5090): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,E/AndroidHttpClient( 5011): Leak found
E/AndroidHttpClient( 5011): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5011): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5011): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5011): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5011): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5011): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5011): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5011): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5011): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5011): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5011): 	at android.os.Handler.dispatchMessage(Handler.java:102),
E/AndroidHttpClient( 5011): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5011): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5011): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5011): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5011): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5011): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,W/AnalyticsTrackerProxyImpl( 5090): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45,
,D/ChimeraCfgMgr( 4293): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4293): Module APK com.google.android.play.games already loaded
,I/SocialFeedProvider( 1529): +disConnect socialManager,
I/SocialFeedProvider( 1529): disconnect socialManager
I/SocialFeedProvider( 1529): -disConnect socialManager
,D/VoldConnector(  944): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 5090): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4293, uid=10024, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4293, uid=10024, userID:0,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4293, uid=10024, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4293, uid=10024, userID:0
,I/ActivityManager(  944): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5140 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,W/ResourcesManager( 5090): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5090): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5140): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 5090): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/AccTypeManager( 4742): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/AccTypeManager( 1672): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  944): Cannot find grip_rejection_width, use default value instead
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/System  ( 5090): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5090): Installed default security provider GmsCore_OpenSSL
,D/AccTypeManager( 4742): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1672): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  944): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 1529): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1529): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1529): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 4796): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4796): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/PhoneApp( 1478): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Launcher( 1529): Deferring update until onResume
D/Launcher( 1529): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1672): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/AccTypeManager( 4742): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1672): Unsupported attribute readOnly,
E/ExternalAccountType( 4742): Unsupported attribute readOnly
,W/PackageManager(  944): Unable to load service info ResolveInfo{211790f com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  944): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  944): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  944): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  944): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  944): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  944): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  944): ,	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  944): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  944): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  944): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  944): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/BackupManagerService(  944): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,V/GmsNetworkLocationProvi( 1777): DISABLE
,I/GCoreNlp( 1777): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5011): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
D/Finsky  ( 5011): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/LocationProviderProxy(  944): applying state to connected service
D/PMS     (  944): acquireWL(339b5ea8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(339b5ea8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,D/LocationProviderProxy(  944): applying state to connected service
,D/PMS     (  944): acquireWL(2deeadc1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(3f9bbd54): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(2deeadc1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/Finsky  ( 5011): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/PMS     (  944): releaseWL(3f9bbd54): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/Finsky  ( 5011): [1] DailyHygiene.reschedule: Scheduling new run in 277 minutes (failures=4)
,D/Process (  944): killProcessQuiet, pid=4640
,I/ActivityManager(  944): Killing 4640:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/DeviceConnectionService( 1777): client connected with version: 7571000
,I/ActivityManager(  944): Recipient 4640
,V/AlarmManager(  944): sending alarm PendingIntent{11c945f2: PendingIntentRecord{312eb443 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1457426616023, Int=0
,D/PMS     (  944): acquireWL(30da53f9): PARTIAL_WAKE_LOCK  AsyncService 0x1 5140 10167 null
,I/SocialManager[SocialBiLogHelper]( 4796): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4796): last commit ulog time 1457416495541
I/SocialManager[SocialBiLogHelper]( 4796): skip commit this time
,D/PMS     (  944): releaseWL(30da53f9): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  944): acquireWL(7a162ec): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5140 10167 null
,D/PMS     (  944): releaseWL(7a162ec): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,I/ActivityManager(  944): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5176 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
D/Process (  944): killProcessQuiet, pid=4742
,I/ActivityManager(  944): Killing 4742:com.htc.contacts/u0a38 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 4742
,D/Process (  944): killProcessQuiet, pid=4827
I/ActivityManager(  944): Killing 4827:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 4827
,D/PMS     (  944): acquireWL(3be7a14a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1921): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1921): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1921): [NET] android_getaddrinfo_proxy+
D/libc    ( 1921): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1921): [NET] android_getaddrinfo_proxy-, NODATA
,D/MtpReceiver( 3697): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3697): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3697): [MTP][handleUsbState]+
D/PMS     (  944): releaseWL(3be7a14a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  944): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5201 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a,
,D/MtpReceiver( 3697): [MTP][scanExternalVolumeIfNeed] scan external volume
,D/MtpService( 3697): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpReceiver( 3697): [MTP][handleUsbState]-
D/MtpReceiver( 3697): [MTP][handleMessage]-,
D/MtpDatabase( 3697): TotalSize=1886532,MediaCacheLimit=6000
,D/PMS     (  944): acquireWL(1d5d8931): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 4293 10024 null,
D/MtpService( 3697): [isMtpConnected] connected: true
,I/iu.UploadsManager( 4293): End new media; added: 0, uploading: 0, time: 55 ms,
,D/PMS     (  944): releaseWL(1d5d8931): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,E/MediaScannerService( 3697): [onStartCommand] --- Should not be here, redirect request. ----
,E/MediaScannerService( 3697): [handleMessage] --- Should not be here, ignore request. ----
,D/LocationManagerService(  944): getProviders()=[passive]
,D/SyncApplication( 5201): Loading default preferences
,W/Resources( 5201): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,D/WifiService(  944): New client listening to asynchronous messages
E/WifiTrafficPoller(  944): ADD_CLIENT: 6
,D/SyncApplication( 5201): Overriding preferences with custom values,
,E/MediaScannerServiceEx( 3697): [getStorageMaskIdFromPath] path is null
,D/MediaScannerServiceEx( 3697): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,D/MediaScannerServiceEx( 3697): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3697): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3697): calcVolumeId: /storage/ext_sd
D/SyncApplication( 5201): Updating preferences succeeded
D/MediaProviderUtils( 3697): calcVolumeId: /storage/usb
,E/SyncApplication( 5201): Application created.
,I/UpdateIcingCorporaServi( 5176): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE,
I/CalendarDefines( 5201): getNewCalendarAuthority()...,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5201, uid=10005, userID:0
D/MediaScannerServiceEx( 3697): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3697): [AliveExtStorageRows]+65537, 11223344
,W/PackageManager(  944): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync,
D/SyncApplication( 5201): enableAppOperation()+
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5201, uid=10005, userID:0
I/art     ( 3697): Background sticky concurrent mark sweep GC freed 13091(946KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 3MB/4MB, paused 5.109ms total 17.005ms
W/PackageManager(  944): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
W/VolumeInfo( 5201): Unable to read mount points
W/VolumeInfo( 5201): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5201): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5201): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5201): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5201): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5201): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5201): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5201): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5201): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5201): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5201): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5201): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5201): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5201): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5201): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5201): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5201): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5201): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,W/VolumeInfo( 5201): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5201): 	... 13 more
V/VolumeInfo( 5201): Found 0 mount point(s)
V/VolumeInfo( 5201): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/MediaProvider( 3697): [update][8]#0#
,D/SyncApplication( 5201): enableAppOperation()-
,D/MediaProvider( 3697): [update][2]#0#
,D/VolumeInfo( 5201): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/HTCUtilities( 5201): isNeorSinged() + ,
,D/VolumeInfo( 5201): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 5201): Can not create volume ID for unmounted volume null
,D/HTCUtilities( 5201): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>,
,D/HTCUtilities( 5201): isNeorSinged() return false,
,D/CDMountReceiver( 5201): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 5201): USB connected to PC
,D/MediaProvider( 3697): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3697): [sendStorageAdded] Already send to MTP: /storage/emulated/0,
D/MediaProvider( 3697): [update][38]#1#
,D/MediaScannerServiceEx( 3697): [AliveExtStorageRows]-0, 0
,D/PMS     (  944): acquireWL(2f103725): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3697 10017 null,
,D/MediaScanner( 3697): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
D/FOTAReceiver( 5201): onReceive() enter 
D/FOTAReceiver( 5201): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/TetherSettings( 4989): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4989): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4989): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4989): Cust_ConnectToPC   : spcsc>false
D/        ( 4989): Cust_ConnectToPC   : IPT>true
D/        ( 4989): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4989): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4989): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4989): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4989): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4989): usb_cable_connect = 1
,D/SmartNS_Utility( 4989): usb_denied = 0
,I/SmartNS_NSReceiver( 4989): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 4989): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 4989): onReceive:com.htc.intent.action.USB_CONNECT2PC,
,W/ContextImpl( 4989): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_PSService( 4989): onReceive:com.htc.intent.action.USB_CONNECT2PC,
W/Settings( 4989): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4989):  defaultType:0
I/SmartNS_PSService( 4989): fail notificaiton:false
,W/asset   ( 5176): Copying FileAsset 0x55afa11a40 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/SmartNS_Utility( 4989): usb_cable_connect = 1,
D/SmartNS_Utility( 4989): usb_denied = 0,
I/SmartNS_PSService( 4989): usb notificaiton:true
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 4989): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/UpdateIcingCorporaServi( 5176): UpdateCorporaTask done [took 144 ms] updated apps [took 144 ms] 
,D/SmartNS_Utility( 4989): usb_cable_connect = 1
,D/SmartNS_Utility( 4989): usb_denied = 0
I/SmartNS_PSService( 4989): usb notificaiton:true
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1216): reapply : com.android.settings 1 36
,D/Process (  944): killProcessQuiet, pid=4849
I/ActivityManager(  944): Killing 4849:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/SmartNS_Utility( 4989): usb_cable_connect = 1
D/SmartNS_Utility( 4989): usb_denied = 0
,D/PMS     (  944): acquireWL(1218f6ab): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,I/SmartNS_PSService( 4989): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 4989): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/ActivityManager(  944): Recipient 4849
,I/ActivityManager(  944): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5240 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/Process (  944): killProcessQuiet, pid=4870
I/ActivityManager(  944): Killing 4870:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1216): reapply : com.android.settings 1 36
,I/Prism.ItemManager( 1529): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1529): loadItems() com.htc.launcher.pageview.WidgetManager@30486054 +
,I/Prism.WidgetManager( 1529): onLoadItems() +
,I/Prism.ItemManager( 4796): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4796): loadItems() com.htc.launcher.pageview.WidgetManager@b9992b4 +
I/Prism.WidgetManager( 4796): onLoadItems() +
,W/ResourcesManager( 1529): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 4796): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/ActivityManager(  944): Recipient 4870
,I/HtcModeClient( 3157): handler message = 4011
,E/HtcModeClient( 3157): Check connection and retry 5 times.
,D/PMS     (  944): releaseWL(1218f6ab): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 5240): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 ,
,I/ActivityManager(  944): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5263 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/ActivityManager(  944): Killing 3739:com.htc.sense.mms/u0a64 (adj 15): empty #17,
D/Process (  944): killProcessQuiet, pid=3739
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 4796): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1529): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  944): Recipient 3739,
,D/PhoneApp( 1478): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1478): -- N1 =0
D/PhoneApp( 1478): -- N2 =0
D/PhoneApp( 1478): -- N3 =0
,I/ActivityManager(  944): Waited long enough for: ServiceRecord{37f28cbc u0 com.htc.backup/.notifications.contextual.ContextualReminderControlService}
,W/asset   ( 1529): Copying FileAsset 0x55afff9950 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,W/asset   ( 4796): Copying FileAsset 0x55afb9fed0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,W/ResourcesManager( 5263): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5263): Created com.android.providers.calendar.CalendarAlarmManager@31687533(com.htc.providers.calendar.HtcCalendarProvider@35a1a0f0)
,D/CalendarProvider2( 5263): wait start:true
,I/Prism.WidgetManager( 4796): onLoadItems() -
I/Prism.ItemManager( 4796): loadItems() com.htc.launcher.pageview.WidgetManager@b9992b4 -
,E/Prism.WidgetManager( 1529): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1529): onLoadItems() -
I/Prism.ItemManager( 1529): loadItems() com.htc.launcher.pageview.WidgetManager@30486054 -
,I/art     (  944): Explicit concurrent mark sweep GC freed 24727(1352KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.839ms total 138.931ms
,D/FlexNetS( 5263): updateSvcAllowedInSettings:false
,D/CalendarProvider2( 5263): wait end:false,
,I/ActivityManager(  944): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5289 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/PMS     (  944): acquireWL(15c98caa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
,I/BatteryService(  944): n_update end
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): releaseWL(15c98caa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  944): updateBatteryInfo
D/PowerUI ( 1216): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: ApStaDisabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): handleMessage: X
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  944): << updateStatus
,W/ContextImpl( 5289): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  944): acquireWL(19b90c38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5289 1000 null
,D/PowerUsageList:PowerUsageHelper( 5289): MY_DEBUG = false
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  944): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5314 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,D/PowerUsageService( 5289): repeat time = 1457427518179
,D/WeatherUtility( 1437): Weather sync is On
,D/WSP     ( 1437): [Receiver] auto sync agent, auto sync is enabled, reset schedule,
,I/ActivityManager(  944): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5337 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,D/WeatherUtility( 5314): Weather sync is On,
,W/ResourcesManager( 5337): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/ActivityManager(  944): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5361 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,I/PowerUsageList:PowerUsageHelper( 5289): PowerProfile::POWER_SCREEN_FULL = 154.8
,W/WeatherRequest( 5314): request cur loc, but there is no sys cur,
W/Settings( 5314): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActionCombine( 5314): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/PowerUsageList:BatterySipperExt( 5289): gen(), null == sipper.uidObj, userId = 0
,I/RemoteViews( 1529): reapply : com.htc.widget.weatherclock 14 17
,D/MediaProvider( 3697): [update][43]#1#
,D/MediaScanner( 3697):  prescan time: 612ms,
,D/MediaScanner( 3697):     scan time: 929ms
D/MediaScanner( 3697): postscan time: 6ms
D/MediaScanner( 3697):    total time: 1547ms
D/MediaScanner( 3697): -----------------------------------------------------------------
D/MediaScanner( 3697): firstscan(media) time: 389ms
D/MediaScanner( 3697): secondscan(non-media) time: 540ms
D/MediaScanner( 3697):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3697):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3697):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3697):  [Total]    File(Image+Video+Audio+Others) in database : 1549,
,I/EASAppSvc( 5361): [ NA ]onCreate,
,I/VersionUtil( 5361): [ NA ]setIsFOTAing: true
,I/VersionUtil( 5361): [ NA ]onUpgrade: current version=100, latest version=100,
I/VersionUtil( 5361): [ NA ]setIsFOTAing: false
,D/HtcAdjCursorFactory( 5361): Set CursorWindow size to: 4194304 KB, Tid: 5385
,D/MediaProvider( 3697): [delete][77]
D/MediaProvider( 3697): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/PowerUsageService( 5289): calcPower(), no data
,D/Process (  944): killProcessQuiet, pid=4392
I/ActivityManager(  944): Killing 4392:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaProvider( 3697): [recoverParentNodes] - 0
D/MediaProvider( 3697): [update][14],
D/MediaScannerServiceEx( 3697): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3697): [updateImage]+
,D/ORMLib  ( 4892): put(),
,D/MediaScannerServiceEx( 3697): [updateImage]-0
,I/ActivityManager(  944): Recipient 4392,
,D/PMS     (  944): releaseWL(2f103725): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3697): [1] scan finished
,D/MediaProviderUtils( 3697): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3697): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3697): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3697): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1,
I/ActivityManager(  944): Killing 4914:com.htc.mobiledata/u0a46 (adj 15): empty #17
W/MediaScannerServiceEx( 3697): Process mounted intent for unmounted storage: /storage/ext_sd
D/Process (  944): killProcessQuiet, pid=4914
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 4914,
,D/MediaScannerServiceEx( 3697): [disAliveExtStorageRows]+131073
,D/WifiService(  944): New client listening to asynchronous messages
,E/WifiTrafficPoller(  944): ADD_CLIENT: 7
,W/EAS_NetworkUtil( 5361): [ NA ]getNetworkInfo: NetworkInfo is null
,D/MediaProvider( 3697): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3697): [update][9]#1#
,I/ActivityManager(  944): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5395 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/EASAppSvc( 5361): [ NA ]onDestroy,
I/EASAppSvc( 5361): [ NA ]> uninitEASService
I/CalendarProvider2( 5263): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 5263): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/EASAppSvc( 5361): [ NA ]onCreate
,I/VersionUtil( 5361): [ NA ]setIsFOTAing: true
,I/EASRequestController( 5361): [ NA ]release
,D/MediaProvider( 3697): [update][42]#0#
,I/ActivityManager(  944): Killing 4581:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=4581
D/MediaScannerServiceEx( 3697): [disAliveExtStorageRows]--1, 0
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/VersionUtil( 5361): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5361): [ NA ]setIsFOTAing: false
,D/EASPublicBinder( 5361): [ NA ]release
,D/TaskBinder( 5361): [ NA ]release
D/TaskBinder( 5361): [ NA ]release
I/EASAppSvc( 5361): [ NA ]< uninitEASService
,D/ORMLib  ( 4892): put(),
,I/ActivityManager(  944): Recipient 4581,
,W/EAS_NetworkUtil( 5361): [ NA ]getNetworkInfo: NetworkInfo is null
,D/MediaProviderUtils( 3697): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3697): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3697): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3697): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3697): Process mounted intent for unmounted storage: /storage/usb
,D/MediaScannerServiceEx( 3697): [disAliveExtStorageRows]+196609
,I/EASAppSvc( 5361): [ NA ]onDestroy
E/SQLiteLog( 5337): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal
,I/EASAppSvc( 5361): [ NA ]> uninitEASService
V/AlarmManager(  944): sending alarm PendingIntent{220fc780: PendingIntentRecord{1c8121b9 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1457426619226, Int=0
,D/MediaProvider( 3697): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3697): [update][13]#1#
,I/ActivityManager(  944): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5427 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/EASRequestController( 5361): [ NA ]release
,D/MediaProvider( 3697): [update][28]#0#
,D/MediaScannerServiceEx( 3697): [disAliveExtStorageRows]--1, 0
,D/EASPublicBinder( 5361): [ NA ]release,
D/TaskBinder( 5361): [ NA ]release,
D/TaskBinder( 5361): [ NA ]release
I/EASAppSvc( 5361): [ NA ]< uninitEASService
,I/ActivityManager(  944): Killing 4946:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=4946
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 4946
,D/ORMLib  ( 4892): put()
,D/Process (  944): killProcessQuiet, pid=4968,
I/ActivityManager(  944): Killing 4968:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/MusicStore( 5395): Database version: 120
,I/ActivityManager(  944): Recipient 4968,
,D/PMS     (  944): releaseWL(19b90c38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/VoldConnector(  944): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5395): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,I/ConfigService( 1921): onDestroy,
,D/Process (  944): killProcessQuiet, pid=5090
I/ActivityManager(  944): Killing 5090:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/VoldConnector(  944): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5395): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  944): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 5395): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,I/ActivityManager(  944): Recipient 5090,
,W/ResourcesManager( 5395): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5395): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5395): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 5395): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 5395): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@292b1837: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 5395): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5395): GMSCore installation verified
,I/ConfigStore( 5395): Config Database version: 1,
,I/art     ( 1921): Explicit concurrent mark sweep GC freed 13514(744KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 867us total 48.374ms,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5395, uid=10159, userID:0,
,D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
,D/MediaRouterService(  944): Client com.google.android.music (pid 5395): Registered,
,D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
,I/MediaRouter( 5395): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,D/TelephonyReceiver( 1478): bind: true
,D/PMS     (  944): acquireWL(1594a00c): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5263 10011 null
,I/ActivityManager(  944): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5470 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,E/SQLiteLog( 5263): (284) automatic index on view_events(_id)
,I/ActivityManager(  944): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5489 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/PMS     (  944): releaseWL(1594a00c): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5395, uid=10159, userID:0
,W/HtcWrapAdjustableCursorFactory( 5470): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 5470): onCreate
,I/GHttpClientFactory( 5395): Using our fixed implementation of GMSCore's GoogleHttpClient
,V/GetPrviateResource( 5470): GetPrviateResource
V/GetPrviateResource( 5470): GetPrviateResource
,D/DFPI.PIReciver( 5489): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,D/MessageCustFlag( 5470): sense_version=6.0
D/GenericMessagesProvider( 5470): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 5470): (14) cannot open file at line 30058 of [9491ba7d73]
E/SQLiteLog( 5470): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 5470): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5470): DB info: errno = 2, errno message = No such file or directory
I/GoogleURLConnFactory( 5395): Using platform SSLCertificateSocketFactory
,D/BTAccessoryUtil( 5470): createReceiver
D/BTAccessoryUtil( 5470): registerReceiver return intent = null
D/MessageCustFlag( 5470): sku_id=118
,E/SQLiteDatabase( 5470): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 5470): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5470): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5470): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5470): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5470): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5470): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5470): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5470): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5470): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5470): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5470): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5470): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 5470): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5470): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5470): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5470): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 5470): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5470): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5470): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/System.err( 5470): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5470): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 5470): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5470): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5470): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/System.err( 5470): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5470): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 5470): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 5470): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 5470): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5470): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5470): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
W/System.err( 5470): 	at android.os.Binder.execTransact(Binder.java:454)
I/DFPI.ApkInstallService( 5489): onHandleIntent
D/HtcBuildUtils( 5470): getRATByHtcTelephonyCapability:1
I/DFPI.ApkInstallService( 5489): Media Scan Finished Case 
W/SystemReader( 5470): Cannot find qct_8960_interface, use default value instead
,D/TelephonyReceiver( 1478): switchBindHtcMsgCursor: null
D/DFPI.ApkInstallService( 5489): check CID = HTC__102
I/DFPI.ApkInstallService( 5489): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  944): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5519 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/Process (  944): killProcessQuiet, pid=5052
I/ActivityManager(  944): Killing 5052:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5052
,D/Process (  944): killProcessQuiet, pid=5011,
I/ActivityManager(  944): Killing 5011:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5011
,I/ActivityManager(  944): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5544 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a,
,I/art     (  944): Explicit concurrent mark sweep GC freed 21078(1052KB) AllocSpace objects, 2(344KB) LOS objects, 33% free, 16MB/24MB, paused 1.305ms total 157.567ms,
,D/Process (  944): killProcessQuiet, pid=4796
,I/ActivityManager(  944): Killing 4796:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/SoundPicker( 5544): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/ActivityManager(  944): Recipient 4796
,I/SoundPicker( 5544): SoundPickerReceiver [onReceive] startService
D/VoldConnector(  944): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
,W/ContextImpl( 5519): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
I/SoundPicker( 5544): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5544): TurnFileToMediaUriService fromMediaScanned = true
,D/DFPI.PIReciver( 5489): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5544): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,I/DFPI.ApkInstallService( 5489): onHandleIntent
,I/DFPI.ApkInstallService( 5489): Media Scan Finished Case 
,D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/DFPI.ApkInstallService( 5489): check CID = HTC__102
,I/DFPI.ApkInstallService( 5489): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma),
,I/SoundPicker( 5544): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5544): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/DFPI.PIReciver( 5489): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/DFPI.ApkInstallService( 5489): onHandleIntent
I/DFPI.ApkInstallService( 5489): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5489): check CID = HTC__102
I/DFPI.ApkInstallService( 5489): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5544): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/DFPI.PIReciver( 5489): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/DFPI.ApkInstallService( 5489): onHandleIntent
I/DFPI.ApkInstallService( 5489): Media Scan Finished Case 
,I/SoundPicker( 5544): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5544): SoundPickerReceiver [onReceive] startService
,D/DFPI.ApkInstallService( 5489): check CID = HTC__102
I/DFPI.ApkInstallService( 5489): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/ActivityManager(  944): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5575 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9,
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/art     (  446): Explicit concurrent mark sweep GC freed 8660(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 208us total 26.627ms
,I/SoundPicker( 5544): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5544): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5544): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5544): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 185us total 22.394ms
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 152us total 21.056ms
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
I/MediaStoreImporter( 5395): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,D/TelephonyReceiver( 1478): bind: false
,D/TelephonyReceiver( 1478): switchBindHtcMsgCursor: null
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
D/DFPI.PIReciver( 5489): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/DFPI.ApkInstallService( 5489): onHandleIntent
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
I/DFPI.ApkInstallService( 5489): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5489): check CID = HTC__102
I/DFPI.ApkInstallService( 5489): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5544): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5544): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5544): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5544): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/DFPI.PIReciver( 5489): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/MediaStoreImporter( 5395): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0,
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/DFPI.ApkInstallService( 5489): onHandleIntent
I/DFPI.ApkInstallService( 5489): Media Scan Finished Case 
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
D/DFPI.ApkInstallService( 5489): check CID = HTC__102
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/DFPI.ApkInstallService( 5489): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5544): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5544): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,D/DFPI.PIReciver( 5489): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/DFPI.ApkInstallService( 5489): onHandleIntent
I/DFPI.ApkInstallService( 5489): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5489): check CID = HTC__102
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5544): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 5489): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5544): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,D/GCM     ( 1921): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
D/AuthorizationBluetoothService( 1921): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,V/GmsCoreStatsServiceLauncher( 4293): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5544): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5544): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm),
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5544): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/MediaStoreImporter( 5395): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/WearableService( 4772): callingUid 10024, callindPid: 4772,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4293, uid=10024, userID:0
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,E/MDM     ( 1777): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
D/GCM     ( 1921): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 4293): Restart initialization of location
,D/AuthorizationBluetoothService( 1921): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,V/GmsCoreStatsServiceLauncher( 4293): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4293, uid=10024, userID:0
E/MDM     ( 1777): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
D/LocationInitializer( 4293): Restart initialization of location
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac,
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5544): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5544): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5544): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/MediaStoreImporter( 5395): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/ActionCombine( 5575): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false,
,I/RemoteViews( 1216): setHTCTheme(com.htc.updater,true,33751145)
,D/PMS     (  944): acquireWL(15e002d2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,I/RemoteViews( 1216): apply : com.htc.updater 0 11 2 36
D/PMS     (  944): releaseWL(15e002d2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(11a95fa3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(11a95fa3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/art     (  944): Explicit concurrent mark sweep GC freed 10167(495KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.175ms total 134.032ms,
I/MediaStoreImporter( 5395): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5544): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5544): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5,
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5544): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
D/PMS     (  944): acquireWL(2c6f38cc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms},
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/FindExtension( 1216): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/ThreadedRenderer( 1216): Defer allocateBuffers to drawing time
,D/PMS     (  944): releaseWL(2c6f38cc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/ActivityManager(  944): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5619 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
I/MediaStoreImporter( 5395): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5544): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5544): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
,D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5544): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/PhoneMonitor( 5619): Register our PhoneStateListener
,I/ActivityManager(  944): Killing 5140:com.google.android.apps.plus/u0a167 (adj 15): empty #17,
,D/Process (  944): killProcessQuiet, pid=5140
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 5619): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 5619): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  944): Recipient 5140
,D/GCM     ( 1921): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 4293): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4293): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/ActivityManager(  944): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5644 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,W/ResourcesManager( 5644): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Messaging( 5470): supportCMAS(SIE)/init? false/true,
,D/MmsConfig( 5470): networkCode: 
,D/MessageCustFlag( 5470): sku_id=118
,D/MmsConfig( 5470): SIE smsPri: null
D/MmsConfig( 5470): networkCode: 
,D/MmsConfig( 5470): packageName: com.htc.vvm.att does not exist
,D/Messaging( 5470): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 5470): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 5470): 
D/MmsAsyncWorkHandler( 5470): HM tk = 20001
,D/ReportIndicatorCache( 5470): MSG_QUERY_REPORTS >>
,D/SettingsManager( 5470): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@31687533
,D/DraftCache( 5470): [DraftCache/1] DraftCache.constructor,
D/DraftCache( 5470): [DraftCache/1] refresh
D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1478): sku_id=118
,I/HtcModeClient( 3157): handler message = 4011
D/MmsConfig( 5470): networkCode: 
,I/Messaging( 5470): mccmnc> 
E/HtcModeClient( 3157): Check connection and retry 6 times.,
,D/DraftCache( 5470): [DraftCache/122] rebuildCache
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94,
D/MmsSmsV2Provider( 1478):  slotId = -1000
D/MmsSmsV2Provider( 1478): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Messaging( 5470): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/MmsSmsV2Provider( 1478):  slotId = -1000
D/MmsSmsV2Provider( 1478): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,I/Babel_SMS( 5644): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 5644): MmsConfig.loadMmsSettings
D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/Jerry   ( 1478): URI_DRAFT
,D/MmsCustomizationProvider( 5470): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MessageCustFlag( 5470): sense_version=6.0
,D/MmsSmsV2Provider( 1478):  slotId = -1000
D/MmsSmsV2Provider( 1478): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/DraftCache( 5470): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 5470): [DraftCache/122] rebuildCache time: 11
D/Jerry   ( 5470): start to preload cursor >>>>>>>
D/MmsAsyncWorkHandler( 5470): 
D/MmsAsyncWorkHandler( 5470): HM tk = 20002
,D/Messaging( 5470): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 96
D/PhoneStorageUtil( 5470): HtcWrapEnvironment.getSupportedStorages() >1
D/MmsSmsV2Provider( 1478):  slotId = -1000
,D/MmsSmsV2Provider( 1478): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 5470): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5470): createReceiver
D/MmsCustomizationProvider( 5470): query uri: content://htc-mms-customization/mms-ua/ua_profile
,D/Messaging( 5470): mNeedToUpdateDate2: false
D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
,D/AccFlag ( 1478): sku_id=118
I/Babel_SMS( 5644): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
D/TelephUtils( 1478): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 84
,V/MmsProvider( 1478): Update uri=content://mms, match=0
V/MmsProvider( 1478): selection=st=129 AND m_type!=134
I/Babel_SMS( 5644): MmsConfig.loadFromDatabase
,D/Messaging( 5470): Reset downloading state: 0
,V/MmsSystemEventReceiver( 5470): TransactionService is going to be woken up.,
D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1478):  slotId = -1000
,V/TransactionService( 5470): 1-Creating TransactionService
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/AccFlag ( 1478): sku_id=118
,D/Messaging( 5470): ViewCache CreatePreload
,D/Messaging( 5470): ViewCache CreatePreloadOnlyMultipleOpsList
E/Babel_SMS( 5644): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5644): MmsConfig.loadFromResources
E/Babel_SMS( 5644): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5644): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
V/TransactionService( 5470): onStartCommand: 1
D/MmsSystemEventReceiver( 5470): unRegisterForConnectionStateChanges
,V/TransactionService( 5470): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5644, uid=10112, userID:0
V/TransactionService( 5470): Loading previous transactions.
,D/Cust_MMSMS( 5470): _has_set_default_values_2=true
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/AccFlag ( 1478): device_type: 1
D/MsgPreferenceUtils( 5470): def_index: 0
,D/TransactionService( 5470): Force clearing mTransactionList
,D/MsgPreferenceUtils( 5470): globalIndex = 1
D/TransactionService( 5470): Force set service start id to 1
V/TransactionService( 5470): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5470): unRegisterForConnectionStateChanges
,V/TransactionService( 5470): Destroying TransactionService
D/TransactionService( 5470): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 5470): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 5470): phone state: true
D/MsgPreferenceUtils( 5470): sd state: false
D/MsgPreferenceUtils( 5470): vIndex = 0,
,W/Settings( 5644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5644): startup - clean,
,I/Babel   ( 5644): deleted: false for 0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5644, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5644, uid=10112, userID:0,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5644, uid=10112, userID:0,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5644, uid=10112, userID:0,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5644, uid=10112, userID:0
,D/PMS     (  944): acquireWL(3e95d53a): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5644 10112 null,
,W/VideoCapabilities( 5644): Unrecognized profile 2130706433 for video/avc,
,I/ActivityManager(  944): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5701 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,W/VideoCapabilities( 5644): Unsupported mime video/x-ms-wmv
,W/Utils   ( 5644): could not parse size range '64x64-1920X1080',
,W/AudioCapabilities( 5644): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5644): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5644): Unsupported mime audio/qcelp
W/VideoCapabilities( 5644): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 5644): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5644): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5644): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5644): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5644): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/vclib   ( 5644): onServiceConnected
,W/Babel   ( 5644): Attempted to change video mute state without an active call.
,W/ResourcesManager( 5644): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5644): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Gmail   ( 5701): getAccountsCursor
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GAV2    ( 5701): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=5701, uid=10106, userID:0
W/ActivityManager(  944): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5701): Observing account changes for notifications,
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5701, uid=10106, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5701, uid=10106, userID:0
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5701): Error finding the version of the Email provider.....
E/Gmail   ( 5701): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5701): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5701): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5701): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5701): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5701): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5701): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 5701): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5701): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5701): getAccountsCursor
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  944): acquireWL(3bf8a551): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1921): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1921): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1921): [NET] android_getaddrinfo_proxy+,
D/libc    ( 1921): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1921): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): releaseWL(3bf8a551): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  944): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5747 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 5701): (283) recovered 1512 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ResourcesManager( 5747): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/JNIHelp ( 5644): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/CalendarApplication( 5747): onCreate,
,D/ProviderChangeReceiver( 5747): ---------------------------------------------------
,D/ProviderChangeReceiver( 5747): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,I/ActivityManager(  944): Killing 5176:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17,
D/Process (  944): killProcessQuiet, pid=5176
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/HtcAlertService( 5747): start to updateAlertNotification!
,I/Gmail   ( 5701): notifyAccountChanged
,I/Gmail   ( 5701): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5701): getAccountsCursor
,I/Gmail   ( 5701): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5701): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5701): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/System  ( 5644): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 5644): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  944): Recipient 5176
,I/art     (  944): Explicit concurrent mark sweep GC freed 7197(365KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.384ms total 163.543ms
,D/GCM     ( 1921): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AuthorizationBluetoothService( 1921): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/HtcAlertService( 5747): No fired or scheduled alerts
,D/HtcAlertUtils( 5747): -- cancelReminderNotification --
,D/HtcAlertUtils( 5747): broadcastExistReminder!
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/GmsCoreStatsServiceLauncher( 4293): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4293, uid=10024, userID:0
,E/MDM     ( 1777): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/PhoneInterfaceManager( 1478): [PhoneIntfMgr] getIccId: ICC ID is null or empty.,
,D/LocationInitializer( 4293): Restart initialization of location,
,W/VideoCapabilities( 5644): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5644): Unrecognized profile 2130706433 for video/avc
,I/Babel   ( 5644): connection state changed from UNKNOWN to DISCONNECTED
,D/GCM     ( 1921): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,W/VideoCapabilities( 5644): Unrecognized profile 2130706433 for video/avc
,D/AuthorizationBluetoothService( 1921): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4293): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/Gmail   ( 5701): master sync=false, engine sync=true
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4293, uid=10024, userID:0,
I/Gmail   ( 5701): getAccountsCursor
,E/MDM     ( 1777): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Gmail   ( 5701): master sync=false, engine sync=true
,D/LocationInitializer( 4293): Restart initialization of location
,D/PMS     (  944): releaseWL(3e95d53a): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/NotifUtils( 5701): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false,
,I/NotifUtils( 5701): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,D/Process (  944): killProcessQuiet, pid=5201,
I/ActivityManager(  944): Killing 5201:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  944): Recipient 5201,
D/WifiService(  944): Client connection lost with reason: 4
,D/PMS     (  944): acquireWL(38ef2031): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5644 10112 null,
,I/ActivityManager(  944): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5793 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,D/PMS     (  944): releaseWL(38ef2031): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/LocationManagerService(  944): getProviders()=[passive]
,I/ActivityManager(  944): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5821 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
,D/Process (  944): killProcessQuiet, pid=4989
,I/ActivityManager(  944): Killing 4989:com.android.settings/1000 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  944): Recipient 4989,
,I/ActivityManager(  944): Killing 5240:com.htc.backupreset/1000 (adj 15): empty #17,
D/Process (  944): killProcessQuiet, pid=5240,
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 ,
,I/ActivityManager(  944): Recipient 5240,
,I/[PluginManager]RegisterService( 1437): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1437): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  944): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5843 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5843): -onCreate()
,V/Settings:HtcSettingsApplication( 5843): [5843/5843] onCreate(),
,D/Process (  944): killProcessQuiet, pid=5289
I/ActivityManager(  944): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5867 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  944): Killing 5289:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/Settings:HtcWirelessFeatureFlags( 5843): id/is att sku: 118/false,
,E/Settings:HtcWrapHeaderInfo( 5843): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5843): The wrap header doesn't exist in header list.
,I/ActivityManager(  944): Recipient 5289
,E/Settings:HtcWrapHeaderInfo( 5843): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5843): isSupportMusicChannel(): false,
I/ActivityManager(  944): Waited long enough for: ServiceRecord{112d57c7 u0 com.htc.club/com.mcrm.autonotification.NotificationService}
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportHomeButton]support         :false
,I/ActivityManager(  944): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5843): Failed to find provider info for com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 5843): isSupportVoWifi: null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5843): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 5843): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5843): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportHomeButton]hasHomeKey      :false,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5843): [supportHomeButton]support         :false
,I/ActivityManager(  944): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 5843): isSupportVoWifi: null
E/ActivityThread( 5843): Failed to find provider info for com.htc.vowifi
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5867, uid=10072, userID:0,
,W/global  ( 5867): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5867): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 5867): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5867): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5867): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  944): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5909 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/Settings( 5867): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5867): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 5909): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5909): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5867, uid=10072, userID:0
,I/MultiDex( 5909): VM with version 2.1.0 has multidex support,
I/MultiDex( 5909): install
I/MultiDex( 5909): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 5867): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 5867): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5867): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,V/JNIHelp ( 5909): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/PackageBroadcastService( 4293): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5867): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,I/ActivityManager(  944): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5937 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/PackageBroadcastService( 4293): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  944): Killing 5314:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=5314
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,W/ActivityThread( 5909): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5909): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@cb1975: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5909): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  944): Recipient 5314,
,V/AlarmManager(  944): sending alarm PendingIntent{7329a7f: PendingIntentRecord{38d8aa4c com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1457426624961, Int=0
,D/PMS     (  944): acquireWL(3aebda95): PARTIAL_WAKE_LOCK  Icing 0x1 4293 10024 WorkSource{10024 com.google.android.gms},
,I/Icing   ( 4293): updateResources: need to parse f{com.google.android.gms},
,W/ResourcesManager( 5937): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PMS     (  944): releaseWL(3aebda95): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(68dc74d): PARTIAL_WAKE_LOCK  AsyncService 0x1 5937 10167 null
,D/PMS     (  944): releaseWL(68dc74d): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  944): acquireWL(6a12713): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5937 10167 null
,I/UpdateIcingCorporaServi( 5793): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/art     ( 1921): Explicit concurrent mark sweep GC freed 11629(573KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 604us total 37.765ms
,D/PMS     (  944): releaseWL(6a12713): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/Finsky  ( 5867): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive
,D/Process (  944): killProcessQuiet, pid=4892,
I/ActivityManager(  944): Killing 4892:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,V/Finsky  ( 5867): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/UpdateIcingCorporaServi( 5793): UpdateCorporaTask done [took 118 ms] updated apps [took 117 ms] 
,I/ActivityManager(  944): Recipient 4892,
,D/Process (  944): killProcessQuiet, pid=5361,
I/ActivityManager(  944): Killing 5361:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5361
D/WifiService(  944): Client connection lost with reason: 4
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4293, uid=10024, userID:0,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4293, uid=10024, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4293, uid=10024, userID:0
I/CheckinService( 4293): Done disabling old GoogleServicesFramework version,
,I/ActivityManager(  944): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=5980 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/Finsky  ( 5867): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  944): sending alarm PendingIntent{ded216f: PendingIntentRecord{abc6ab9 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457426625691, Int=0
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 5980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 5843): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 5843): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 5843): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5843): Cust_ConnectToPC   : spcsc>false
D/        ( 5843): Cust_ConnectToPC   : IPT>true
D/        ( 5843): Cust_ConnectToPC   : Singel_USB>false
W/ContextImpl( 5843): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
D/SmartNS_NSReceiver( 5843): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5843): Index of the first 1 = -1
,W/ContextImpl( 5843): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Finsky  ( 5867): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/Settings( 5843): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5843): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5843): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5843): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SmartNS_Utility( 5843): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 5843): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
D/DFPI.PIReciver( 5489): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5489): onHandleIntent
I/DFPI.ApkInstallService( 5489): Media Scan Finished Case ,
D/DFPI.ApkInstallService( 5489): check CID = HTC__102
I/DFPI.ApkInstallService( 5489): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5544): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5544): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5544): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
V/SoundPicker( 5544): TurnFileToMediaUriService fromMediaScanned = true
I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/SoundPicker( 5544): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma),
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2),
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/art     (  944): Explicit concurrent mark sweep GC freed 12765(615KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.624ms total 162.936ms
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/ProviderChangeReceiver( 5747): ---------------------------------------------------
D/ProviderChangeReceiver( 5747): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/HtcAlertService( 5747): start to updateAlertNotification!
D/DFPI.PIReciver( 5489): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/HtcAlertService( 5747): No fired or scheduled alerts
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
D/HtcAlertUtils( 5747): -- cancelReminderNotification --
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/HtcAlertUtils( 5747): broadcastExistReminder!
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/DFPI.ApkInstallService( 5489): onHandleIntent
I/DFPI.ApkInstallService( 5489): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5489): check CID = HTC__102
I/DFPI.ApkInstallService( 5489): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
I/SoundPicker( 5544): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5544): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DFPI.PIReciver( 5489): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,I/WSP     ( 1437): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WeatherUtility( 1437): Weather sync is On
I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/DFPI.ApkInstallService( 5489): onHandleIntent
I/DFPI.ApkInstallService( 5489): Media Scan Finished Case 
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/DFPI.ApkInstallService( 5489): check CID = HTC__102
,I/DFPI.ApkInstallService( 5489): There is no Demo.apk in sd card or phone storage
I/WSP     ( 1437): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Mar 08 10:43:46 CET 2016
,I/SoundPicker( 5544): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/WSP     ( 1437): [Receiver] can't get active network info
I/SoundPicker( 5544): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5544): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5544): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5544): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,W/Finsky  ( 5867): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/MediaStoreImporter( 5395): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,V/WSP     ( 1437): [SyncService] no data connection, stop sync service
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
,D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/ActivityManager(  944): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=6013 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,W/ResourcesManager( 6013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 3697): Explicit concurrent mark sweep GC freed 2745(128KB) AllocSpace objects, 0(0B) LOS objects, 73% free, 1495KB/5MB, paused 535us total 28.920ms
I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
E/AndroidHttpClient( 5867): Leak found
E/AndroidHttpClient( 5867): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5867): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5867): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5867): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5867): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5867): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5867): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5867): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5867): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5867): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5867): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5867): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5867): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5867): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5867): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5867): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5867): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/MediaStoreImporter( 5395): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/ActivityManager(  944): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=6038 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/Task_Calendar( 6013): Set ICALENDAR_UID to sync_data7 due to SDK_INT is 21
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5544): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5544): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5544): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5544): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/TodoTaskshortcut( 6013): update TASK shortcut>
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 1, mode_wcdma),
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/MediaStoreImporter( 5395): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5544): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,D/SyncApplication( 6038): Loading default preferences
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,W/Resources( 6038): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5544): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5544): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5544): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/WifiService(  944): New client listening to asynchronous messages
,E/WifiTrafficPoller(  944): ADD_CLIENT: 6
,D/SyncApplication( 6038): Overriding preferences with custom values
,D/SyncApplication( 6038): Updating preferences succeeded
,E/SyncApplication( 6038): Application created.
,D/AutoSetting( 1437): service - handleMessage() stop self
,W/VolumeInfo( 6038): Unable to read mount points,
W/VolumeInfo( 6038): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 6038): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 6038): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 6038): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 6038): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 6038): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 6038): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 6038): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 6038): ,	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 6038): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 6038): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 6038): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 6038): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 6038): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 6038): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 6038): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 6038): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 6038): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 6038): 	at libcore.io.IoBridge.open(IoBridge.java:442)
,W/VolumeInfo( 6038): 	... 13 more
V/VolumeInfo( 6038): Found 0 mount point(s),
V/VolumeInfo( 6038): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 6038): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 6038): getNewCalendarAuthority()...,
D/VolumeInfo( 6038): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/VolumeInfo( 6038): Can not create volume ID for unmounted volume null
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=6038, uid=10005, userID:0
W/PackageManager(  944): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
,D/AutoSetting( 1437): service - handleMessage() quit looper
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=6038, uid=10005, userID:0
W/PackageManager(  944): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 6038): enableAppOperation()+
D/AutoSetting( 1437): service - onDestroy() END
,D/SyncApplication( 6038): enableAppOperation()-
,D/HTCUtilities( 6038): isNeorSinged() + 
,D/HTCUtilities( 6038): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 6038): isNeorSinged() return false
,D/CDMountReceiver( 6038): whether to enable CD Auto-mount: true
D/CDMountReceiver( 6038): showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,I/ActionCombine( 6038): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/CDMountReceiver( 6038): enable CD Auto-mount: true,
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/PMS     (  944): releaseWL(293495a6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10005},
,D/HTCUtilities( 6038): enable auto-mount
,D/GCM     ( 1921): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/HTCUtilities( 6038): enable auto-mount
I/HtcMountManagerAdapter( 6038): mHtcMountManager is  null
I/HtcMountManagerAdapter( 6038): mStorageManager is  not null
D/AuthorizationBluetoothService( 1921): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/VoldConnector(  944): SND -> {21 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
I/HtcMountManagerAdapter( 6038): mHtcMountManager is  null
D/VoldConnector(  944): SND -> {22 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
I/HtcMountManagerAdapter( 6038): mStorageManager is  not null
D/MountService(  944): mountISO: /system/etc/PCTOOL.ISO
,D/MountService(  944): mountISO: /system/etc/PCTOOL.ISO
,V/GmsCoreStatsServiceLauncher( 4293): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/Process (  944): killProcessQuiet, pid=5427
I/ActivityManager(  944): Killing 5427:com.htc.task.gtask/u0a66 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/RemoteViews( 1216): apply : com.nero.android.htc.sync 0 10 5 38
,I/RemoteViews( 1216): apply : com.nero.android.htc.sync 0 9 3 53,
,I/ActivityManager(  944): Recipient 5427
,D/PMS     (  944): acquireWL(1226a736): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10024}
V/AlarmManager(  944): sending alarm PendingIntent{b2bd637: PendingIntentRecord{27927a4 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457426626662, Int=0
D/PMS     (  944): releaseWL(1226a736): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4293, uid=10024, userID:0
,E/MDM     ( 1777): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4293): Restart initialization of location,
,I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  944): acquireWL(13d9552f): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5395 10159 null
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5867): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5867): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,I/art     (  944): Explicit concurrent mark sweep GC freed 10664(457KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.844ms total 183.022ms
,D/Finsky  ( 5867): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/iu.UploadsManager( 4293): End new media; added: 0, uploading: 0, time: 301 ms
,D/Finsky  ( 5867): [1] DailyHygiene.reschedule: Scheduling new run in 777 minutes (failures=5),
,D/Process (  944): killProcessQuiet, pid=5263,
I/ActivityManager(  944): Killing 5263:com.htc.bgp/u0a11 (adj 15): empty #17
,D/DeviceConnectionService( 1777): client connected with version: 7571000
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5395, uid=10159, userID:0
,I/ActivityManager(  944): Recipient 5263
,D/PMS     (  944): releaseWL(13d9552f): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 5395): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5395): Stop autocaching.
,D/Finsky  ( 5867): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive
,E/GmsUtils( 5395): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 5395): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/Process (  944): killProcessQuiet, pid=5575
I/ActivityManager(  944): Killing 5575:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/HtcModeClient( 3157): handler message = 4011,
,E/HtcModeClient( 3157): Check connection and retry 7 times.
,I/ActivityManager(  944): Recipient 5575,
,I/GAV2    ( 5701): Thread[GAThread,5,main]: No campaign data found.,
,I/GAv4-SVC( 4293): Google Analytics 7.8.99 is starting up.
,D/Process (  944): killProcessQuiet, pid=5619
I/ActivityManager(  944): Killing 5619:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5619,
,D/Process (  944): killProcessQuiet, pid=5470
I/ActivityManager(  944): Killing 5470:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5470
,I/HtcModeClient( 3157): handler message = 4011,
,E/HtcModeClient( 3157): Check connection and retry 8 times.
,W/MediaManager( 5337): [DualLensScanUtil],	mmpCursor count is 0
,D/Process (  944): killProcessQuiet, pid=5821,
I/ActivityManager(  944): Killing 5821:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5821,
,D/Process (  944): killProcessQuiet, pid=5937
I/ActivityManager(  944): Killing 5937:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5937
,I/ActivityManager(  944): Waited long enough for: ServiceRecord{681e372 u0 com.htc.musicenhancer/.EnhancerService},
,I/HtcModeClient( 3157): handler message = 4011,
E/HtcModeClient( 3157): Check connection and retry 9 times.
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  944): acquireWL(1bd11ed): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000},
V/AlarmManager(  944): sending alarm PendingIntent{25be084d: PendingIntentRecord{30ff2f02 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=87051, Int=0
,D/PMS     (  944): releaseWL(1bd11ed): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1216): Weather sync is On,
W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,I/ClockController( 1216): schedule update now=1457426640058 next=59942,
,I/Clock   ( 1216): updateClock:09:44 Europe/Warsaw,
I/Clock   ( 1216): updateClock:09:44 Europe/Warsaw
I/Clock   ( 1216): updateClock:09:44 Europe/Warsaw
,D/PMS     (  944): acquireWL(392b02b3): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10072}
,V/AlarmManager(  944): sending alarm PendingIntent{3b94e070: PendingIntentRecord{165dfe9 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457426641187, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{39cf846e: PendingIntentRecord{32c9170f android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=85420, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{93f939c: PendingIntentRecord{15b391a5 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=85803, Int=0
,D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  944): releaseWL(392b02b3): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  944): [NET] android_getaddrinfofornet-, err=8
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  944): [NET] android_getaddrinfo_proxy+
D/libc    (  944): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    (  944): [NET] android_getaddrinfo_proxy-, NODATA
,D/Finsky  ( 5867): [602] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5867): [1] 5.onFinished: Installation state replication succeeded.,
,D/ContactMessageStore( 1478): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1478): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 3157): handler message = 4011
,E/HtcModeClient( 3157): Check connection and retry 10 times.
,I/HtcModeClient( 3157): handler message = 4011,
,E/HtcModeClient( 3157): Check connection and retry 11 times.
,D/PMS     (  944): acquireWL(3e73797a): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10024},
V/AlarmManager(  944): sending alarm PendingIntent{348a152b: PendingIntentRecord{1b7f5394 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=96819, Int=0
D/PMS     (  944): acquireWL(3b804d88): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(3e73797a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1921): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1921): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1921): [NET] android_getaddrinfo_proxy+
D/libc    ( 1921): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/PMS     (  944): releaseWL(3b804d88): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1921): [NET] android_getaddrinfo_proxy-, NODATA
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/HtcModeClient( 3157): handler message = 4011,
E/HtcModeClient( 3157): Check connection and retry 12 times.,
,D/PMS     (  944): acquireWL(2b93505d): PARTIAL_WAKE_LOCK  Icing 0x1 4293 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(2b93505d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(2679fea3): PARTIAL_WAKE_LOCK  Icing 0x1 4293 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(2679fea3): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): acquireWL(11652e15): PARTIAL_WAKE_LOCK  Icing 0x1 4293 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(11652e15): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/HtcModeClient( 3157): handler message = 4011,
E/HtcModeClient( 3157): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3157): Don't start project servcice
,D/HtcModeClient( 3157): setEject: MEDIA_EJECT_STATE = true,
,D/HtcModeClient( 3157): connectState: CONNECTION_READY = false
,D/SilentMusic( 3157): call stop
D/HtcModeClient( 3157): close connection,
,W/HtcModeClient( 3157): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3157): read the terminate packet, so break
,D/Process (  944): killProcessQuiet, pid=3157
I/ActivityManager(  944): Killing 3157:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 3157,
,I/ActivityManager(  944): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6099 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  944): acquireWL(355d352a): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10076}
V/AlarmManager(  944): sending alarm PendingIntent{275e9f1b: PendingIntentRecord{1a628b8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457426658751, Int=60000
D/PMS     (  944): releaseWL(355d352a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,I/art     (  446): Explicit concurrent mark sweep GC freed 8674(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 220us total 33.635ms,
,I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 171us total 23.696ms
,D/SMSBackup( 6099): SMSBackupAgentService started,
D/SMSBackup( 6099): Checking restore status
,D/SMSBackup( 6099): Restore complete,
D/SMSBackup( 6099): cancelCheckAlarm
,D/SMSBackup( 6099): SMSBackupAgentService completed: completed in 0.0 seconds,
,I/ActivityManager(  944): Killing 5793:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=5793
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 168us total 22.005ms
,I/ActivityManager(  944): Recipient 5793,
,I/PMS     (  944): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@358c20e1
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  944): pid=944, uid=1000
,W/PMN     (  944): goingToSleep
W/SensorService(  944): Active sensors: size = 4
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  944): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@358c20e1, eanble = 0, strlen(mName) = 91
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 2,
W/SensorService(  944): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@12a5c5ca
W/SensorService(  944): Listener[1] = com.htc.smartdim.sensor_eye@35f8e79a
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1216): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,D/PMS     (  944): acquireWL(29f179f6): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 944 1000 null,
W/PMS     (  944): mWirelessDisplayManager is null
W/PMS     (  944): mWirelessDisplayManager is still null
,W/PMN     (  944): goingToSleep done
,I/PMS     (  944): Sleeping (uid 1000)...
,D/XAN-DPS (  944): prepareColorFade 1
D/PMS     (  944): releaseWL(29f179f6): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/ActivityManager(  944): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6122 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,D/AlarmManager(  944): ACTION_SCREEN_ON
,I/AlarmManager(  944): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  944): [AlarmQueuing] done recovering
I/AlarmManager(  944): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  944): [AlarmQueuing] done EPS screen off alarm recovering
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  944): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  944): Build Date: 03/09/15 Mon
I/Adreno-EGL(  944): Local Branch: 
I/Adreno-EGL(  944): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  944): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  944):                  d74aa161a12b9c6fc6332151
,E/WifiStateMachine(  944): handleMessage: E msg.what=131167
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  944):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState,
,V/SRS_Proc(  413): ParamSet string: screen_state=on,
E/audio_a2dp_hw(  413): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  944): handleMessage: E msg.what=155650
D/NetworkPolicy(  944): updateScreenOn: false
D/WifiController(  944): processMsg: ApStaDisabledState
V/NetworkPolicy(  944): updateIfacesLocked()
D/WifiController(  944): processMsg: DefaultState
,D/NetworkManagementService(  944): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiController(  944): handleMessage: X
D/GpsLocationProvider(  944): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/WifiStateMachine(  944): getWifiLinkLayerStats: WIFI is not enbled,
W/ResourcesManager( 6122): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/WifiStateMachine(  944): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  944): handleScreenStateChanged Exit: true
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131154
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  944): processMsg: DefaultState
,E/WifiStateMachine(  944):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131127
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0,
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131129
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  944): handleMessage: X
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/CalendarProvider2( 6122): Created com.android.providers.calendar.CalendarAlarmManager@31687533(com.htc.providers.calendar.HtcCalendarProvider@35a1a0f0)
I/IntentController( 1216): receive(android.intent.action.SCREEN_ON,1,false)
,D/CalendarProvider2( 6122): wait start:true
,D/PMS     (  944): acquireWL(2c512fe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(109a4601): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(2c512fe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(109a4601): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 6122): wait end:false
,D/AlarmManager(  944): ACTION_SCREEN_OFF
I/AlarmManager(  944): [AlarmQueuing] screen off now: 
I/AlarmManager(  944): [AlarmQueuing] data connection: true
I/AlarmManager(  944): [AlarmQueuing] wifi connection: false
D/XAN-DPS (  944): prepareColorFade done
D/WifiDataStallTracker(  944): stopDataStallAlarm 
D/XAN-DPS (  944): setBrightness to 0
,E/WifiDataStallTracker(  944): ENABLE_DATA_MONITOR_POLL false Token 0
E/WifiStateMachine(  944): handleMessage: E msg.what=131167
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiStateMachine(  944): getWifiLinkLayerStats: WIFI is not enbled
D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
E/WifiStateMachine(  944): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  944): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  944): handleScreenStateChanged Exit: false
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131154
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
,E/WifiStateMachine(  944):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): handleMessage: X
V/SRS_Proc(  413): ParamSet string: screen_state=off
,E/audio_a2dp_hw(  413): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  944): handleMessage: E msg.what=155651
D/WifiController(  944): processMsg: ApStaDisabledState,
D/WifiController(  944): processMsg: DefaultState
D/NetworkPolicy(  944): updateScreenOn: false
D/WifiController(  944): handleMessage: X
V/NetworkPolicy(  944): updateIfacesLocked()
D/NetworkManagementService(  944): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@12a5c5ca
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = CM32181 Light sensor
,I/DisplayManagerService(  944): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/ContextImpl( 5980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 3
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
,W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@12a5c5ca, eanble = 0, strlen(mName) = 67
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  944): Listener[0] = com.htc.smartdim.sensor_eye@35f8e79a
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
V/ActivityManager(  944): Display changed displayId=0
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/DotMatrix( 1304): [EventService]  onDisplayChanged: 0
,D/DotMatrix( 1304): [EventService] mbHDMIConnect: false, mCoverOn:false
W/ContextImpl( 5980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5980): MY_DEBUG = false
,I/SensorManager( 1216): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@1c40cfc, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  944): pid=1216, uid=10041
W/SensorService(  944): Active sensors: size = 4
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1),
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@1c40cfc, eanble = 1, strlen(mName) = 56
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  944): Listener[0] = com.htc.smartdim.sensor_eye@35f8e79a
W/SensorService(  944): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@1c40cfc
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/GpsLocationProvider(  944): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1304): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1478): start background delete task...
,D/PMS     (  944): acquireWL(17be8d32): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5980 1000 null
,I/IntentController( 1216): receive(android.intent.action.SCREEN_OFF,1,false)
,D/SmartSyncUtils( 5980): isEpsOn(), nState = 0
D/ContactMessageStore( 1478): size: 0 , 0
,D/ContactMessageStore( 1478): Background delete complete
D/PMS     (  944): acquireWL(11d38a83): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(11d38a83): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(2f981400): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(2f981400): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  944): Init customizeScreenOffDelayClass error
,D/PMS     (  944): releaseWL(17be8d32): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 5980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,I/RemoteViews( 1216): setHTCTheme(com.htc.updater,true,33751145),
I/RemoteViews( 1216): apply : com.htc.updater 1 8 1 36
,W/ContextImpl( 5980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 5980): isEpsOn(), nState = 0
,D/SmartSyncUtils( 5980): isEpsOn(), nState = 0
,W/ContextImpl( 5980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@35f8e79a
W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 3
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@35f8e79a, eanble = 0, strlen(mName) = 36
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  944): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@1c40cfc
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 2
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@35f8e79a, eanble = 0, strlen(mName) = 36
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  944): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@1c40cfc
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@35f8e79a
E/ActivityThread(  944): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@ca7b8cb that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  944): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@ca7b8cb that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  944): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  944): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
,E/ActivityThread(  944): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  944): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  944): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  944): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  944): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  944): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  944): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  944): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  944): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  944): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  944): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  944): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  944): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  944): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  944): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  944): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  944): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/PowerUsageList:PowerUsageHelper( 5980): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/ActivityManager(  944): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6164 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,D/PowerUsageList:BatterySipperExt( 5980): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 5980): calcPower(), no data,
,D/PowerUsageList:PowerUsageHelper( 5980): MY_DEBUG = false
,D/SmartSyncUtils( 5980): getMobilePolicyEnabled, result = true,
D/WifiService(  944): New client listening to asynchronous messages
E/WifiTrafficPoller(  944): ADD_CLIENT: 7
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  944): Setting HAL interactive mode to false
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  944): Setting HAL interactive mode to false done
D/SurfaceControl(  944): Excessive delay in setPowerMode(): 292ms
D/PMS     (  944): Setting HAL auto-suspend mode to true
D/PMS     (  944): Setting HAL auto-suspend mode done
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/HABCtrl (  944): TPE algorithm. remove timeout.
D/PMS     (  944): OOBE c monitor 11
I/InputManager(  944): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/IntentController( 1216): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false),
I/InputMethodManagerService(  944): screenObserver, isScreenOn=false
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  944): Disable input method client, pid=3228
,I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
,D/NfcService( 1495): ScreenObserver: OFF
,D/NfcService( 1495): applyRouting - 0
,D/PMS     (  944): acquireWL(3a4bdf): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1495 1027 null
,D/NfcService( 1495): applyRouting -2
,D/NfcService( 1495): applyRouting
D/NfcService( 1495): Ignore this applyRouting...
,D/PMS     (  944): acquireWL(296a702c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/PMS     (  944): releaseWL(3a4bdf): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(296a702c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): updateBatteryInfo
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1216): closing low battery warning: level=100
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  944): BroadcastReceiver::onReceive+,
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PMS     (  944): runPSCheck
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: ApStaDisabledState
D/WifiController(  944): processMsg: DefaultState
,D/WifiController(  944): handleMessage: X
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/ClockController( 1216): stop clock update:screen off,
,I/ActivityManager(  944): Killing 5843:com.android.settings/1000 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=5843
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  944): Recipient 5843,
,I/CalendarProvider2( 6122): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
,W/ContentResolver( 6122): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 5747): ---------------------------------------------------
D/ProviderChangeReceiver( 5747): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/HtcAlertService( 5747): start to updateAlertNotification!
,D/Process (  944): killProcessQuiet, pid=5489
,I/ActivityManager(  944): Killing 5489:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/PMS     (  944): releaseWL(4332f52): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,I/ActivityManager(  944): Recipient 5489,
,D/HtcAlertService( 5747): No fired or scheduled alerts
,D/HtcAlertUtils( 5747): -- cancelReminderNotification --
,D/HtcAlertUtils( 5747): broadcastExistReminder!
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcUPManager( 1216): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,D/ContactMessageStore( 1478): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1478): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  944): acquireWL(3e875af5): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1000},
V/AlarmManager(  944): sending alarm PendingIntent{2bd6908a: PendingIntentRecord{1f21c6fb android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457426675861, Int=0,
D/PMS     (  944): acquireWL(2d246318): PARTIAL_WAKE_LOCK  *backup* 0x1 944 1000 null
D/PMS     (  944): releaseWL(3e875af5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  944): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  944): Requested init for com.google.android.gms.backup.BackupTransportService but not found,
D/PMS     (  944): releaseWL(2d246318): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,I/ActivityManager(  944): Killing 5519:com.htc.musicenhancer/u0a49 (adj 15): empty #17,
D/Process (  944): killProcessQuiet, pid=5519
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5519
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  944): acquireWL(b3fb171): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/UsbnetService(  944): BroadcastReceiver::onReceive+
I/BatteryService(  944): n_update end
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PMS     (  944): releaseWL(b3fb171): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/NotificationService(  944): plugged=true pluggin=true
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1216): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): updateBatteryInfo
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  944): runPSCheck
D/WifiController(  944): handleMessage: E msg.what=155652
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: ApStaDisabledState
I/HtcPowerSaver(  944): >> updateStatus
,D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): handleMessage: X
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  944): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  944): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,D/PMS     (  944): acquireWL(20952b56): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000},
V/AlarmManager(  944): sending alarm PendingIntent{25be084d: PendingIntentRecord{30ff2f02 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=147051, Int=0
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
V/AlarmManager(  944): sending alarm PendingIntent{93f939c: PendingIntentRecord{15b391a5 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=148266, Int=0
D/libc    (  944): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  944): sending alarm PendingIntent{2d3bd7d7: PendingIntentRecord{58898c4 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=160631, Int=0
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
V/AlarmManager(  944): sending alarm PendingIntent{254cf3ad: PendingIntentRecord{38d0a6e2 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141595, Int=0
D/libc    (  944): [NET] android_getaddrinfofornet-, pass to proxy
,V/AlarmManager(  944): sending alarm PendingIntent{387c1a73: PendingIntentRecord{1b7f5394 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=150498, Int=0
,D/PMS     (  944): acquireWL(4d87d30): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/libc    (  944): [NET] android_getaddrinfo_proxy+
D/libc    (  944): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  402): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    (  944): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1921): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1921): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1921): [NET] android_getaddrinfo_proxy+
D/libc    ( 1921): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  402): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1921): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): releaseWL(4d87d30): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(20952b56): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1216): Weather sync is On
,W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/TelephonyReceiver( 1478): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5
,TIME-OUT KILL (timeout was 150000ms)
```
