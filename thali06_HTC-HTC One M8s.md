#### Test 6170335145aca32_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/Messaging( 2841): Reset downloading state: 0
V/MmsSystemEventReceiver( 2841): TransactionService is going to be woken up.
D/Jerry   ( 2841): start to preload cursor >>>>>>>
D/DraftCache( 2841): [DraftCache/56] rebuildCache
--------- beginning of system
I/ActivityManager(  958): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3021 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/Jerry   ( 1525): URI_DRAFT
V/TransactionService( 2841): 1-Creating TransactionService
D/DraftCache( 2841): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 2841): [DraftCache/56] rebuildCache time: 2
D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1525):  slotId = -1000
V/TransactionService( 2841): onStartCommand: 1
D/MmsSystemEventReceiver( 2841): unRegisterForConnectionStateChanges
V/TransactionService( 2841): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 2841): Loading previous transactions.
E/SQLiteLog( 1525): (284) automatic index on pending_msgs(msg_id)
E/SQLiteLog( 1525): (284) automatic index on sqlite_sq_55B3130350(thread_id)
D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 89
D/AccFlag ( 1525): device_type: 1
D/TransactionService( 2841): Force clearing mTransactionList
D/TransactionService( 2841): Force set service start id to 1
V/TransactionService( 2841): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 2841): unRegisterForConnectionStateChanges
D/TransactionService( 2841): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 2841): Destroying TransactionService
V/TransactionService( 2841): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/Messaging( 2841): ViewCache CreatePreload
D/Messaging( 2841): ViewCache CreatePreloadOnlyMultipleOpsList
D/Cust_MMSMS( 2841): _has_set_default_values_2=true
D/MsgPreferenceUtils( 2841): def_index: 0
D/MsgPreferenceUtils( 2841): globalIndex = 1
D/MsgPreferenceUtils( 2841): phone state: true
D/MsgPreferenceUtils( 2841): sd state: false
D/MsgPreferenceUtils( 2841): vIndex = 0
W/ResourcesManager( 3021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PMS     (  958): acquireWL(d36053f): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3021 10069 null
D/PMS     (  958): acquireWL(e0a2355): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3021 10069 null
D/PMS     (  958): releaseWL(d36053f): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/TodoTaskshortcut( 3021): update TASK shortcut>
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
I/TodoTaskNotifyService( 3021): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  958): releaseWL(e0a2355): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 3021): stopSelfResult true
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
I/[AppShowMeDebug]MobileNetworkTurnOnReceiver( 2564): onReceive statefalse
D/Process (  958): killProcessQuiet, pid=2534
I/ActivityManager(  958): Killing 2534:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/ActivityManager(  958): Recipient 2534
E/cutils-trace( 3061): Error opening trace file: Permission denied (13)
D/CustomizationManager( 3061): ====startRecUseTime====
D/htc.customization.log.level( 3061):  is 
W/CustomizationLogLevel( 3061): Level value is invalid, use default level 2
V/IccIntentReceiver( 1655): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT icc slot: 0
I/SIMStateChangeReceiver( 2044): SIM state: ABSENT
I/SIMStateChangeReceiver( 2044): remove notification
D/FlexNetS( 2044): updateSvcAllowedInSettings:false
D/MessagingNotification( 2841): New incoming message, can't cancel notification now
D/MessagingNotification( 2841): newMsgCnt: 0, false
D/ExchangePolicystatus( 2841): onReceive()
D/ExchangePolicystatus( 2841): onReceive(): ACTION_SIM_STATE_CHANGED
D/CustomizationManager( 3061):  Read ACC file spent 0.035 (s)
D/ExchangePolicystatus( 2841): onReceive(): else
D/SmsReceiver( 2841): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/CIDMapFileReader( 3061): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3061): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3061): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3061): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3061): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3061): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3061): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3061): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 3061): Parsing tag category name = system
I/CustomizationCIDLoader( 3061): Parsing tag category name = application
I/CustomizationCIDLoader( 3061): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3061): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3061): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3061): Parsing tag category name = Settings
I/CustomizationCIDLoader( 3061): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3061): add string-array item, value = 42507
I/CustomizationCIDLoader( 3061): add string-array item, value = 21902
I/CustomizationCIDLoader( 3061): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 3061): add string-array item, value = 23420
I/CustomizationCIDLoader( 3061): add string-array item, value = 22299
I/CustomizationCIDLoader( 3061): add string-array item, value = 24002
I/CustomizationCIDLoader( 3061): add string-array item, value = 23210
I/CustomizationCIDLoader( 3061): add string-array item, value = 23205
I/CustomizationCIDLoader( 3061): add string-array item, value = 23806
I/CustomizationCIDLoader( 3061): add string-array item, value = 23430
I/CustomizationCIDLoader( 3061): add string-array item, value = 23408
I/CustomizationCIDLoader( 3061): add string-array item, value = 27205
I/CustomizationCIDLoader( 3061): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 3061): add string-array item, value = 21902:C:1:0
V/IccIntentReceiver( 1655): IccIntent: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED icc state: null icc slot: 0
I/CustomizationCIDLoader( 3061): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 3061): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 3061): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 3061): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 3061): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 3061): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 3061): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 3061): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 3061): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 3061): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 3061):  Read CID file spent 0.091 (s)
D/CustomizationManager( 3061):  All configurations done spent 0.091 (s)
D/AutoSetting( 1498): receiver - intent: android.intent.action.USER_PRESENT
I/ActivityManager(  958): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=3080 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/AutoSetting( 1498): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ActivityManager(  958): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 3061 on display 0
D/PMS     (  958): acquireHCC(6a28ef8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 958 1000 null
D/PMS     (  958): acquireHCC(26969fd1): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 958 1000 null
W/asset   (  958): Copying FileAsset 0x55b2f68060 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  958): acquireWL(15eda2a4): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 958 1000 null
I/AnimationUtil(  958): isHTCRecent(HelloWorld/Recent screens.)/5
I/ActivityManager(  958): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3103 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/Prism.ItemManager( 1577): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1577): loadItems() com.htc.launcher.pageview.WidgetManager@2d6e4ff +
I/Prism.WidgetManager( 1577): onLoadItems() +
I/Prism.ItemManager( 2394): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 2394): loadItems() com.htc.launcher.pageview.WidgetManager@38c9865 +
I/Prism.WidgetManager( 2394): onLoadItems() +
I/FeedHostManager( 1577): [onPause]
I/FeedProviderManager( 1577): onPause
I/FeedHostManager( 1577): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@339f3d68
I/SocialFeedProvider( 1577): +onPause
I/SocialFeedProvider( 1577): -onPause
W/asset   ( 3103): Copying FileAsset 0xac164de0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/HtcSystemUPManager(  958): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 3080): -onCreate()
D/StatusBarManagerService(  958): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
I/TrimMemoryManager( 1577): [trimMemory] 20
E/ActivityThread( 1577): Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1577): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1577): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3624)
E/ActivityThread( 1577): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3712)
E/ActivityThread( 1577): 	at android.app.ActivityThread.access$1100(ActivityThread.java:144)
E/ActivityThread( 1577): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1388)
E/ActivityThread( 1577): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1577): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1577): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/ActivityThread( 1577): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1577): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1577): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread( 1577): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/ResourcesManager( 1577): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 2394): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/Settings:HtcSettingsApplication( 3080): [3080/3080] onCreate()
D/TetherSettings( 3080): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3080): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3080): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3080): Cust_ConnectToPC   : spcsc>false
D/        ( 3080): Cust_ConnectToPC   : IPT>true
D/        ( 3080): Cust_ConnectToPC   : Singel_USB>false
I/WebViewFactory( 3103): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/ActivityManager(  958): Activity reported stop, but no longer stopping: ActivityRecord{26b7080e u0 com.htc.launcher/.Launcher t11}
W/Settings( 3080): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3080): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3080): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3080): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PSReceiver( 3080): onReceive:android.intent.action.USER_PRESENT
D/DotMatrix( 2131): [CoverService] onDestroy, version: 1.3
W/ContextImpl( 3080): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_PSService( 3080): onReceive:android.intent.action.USER_PRESENT
I/SensorManager( 2131): unregisterListenerImpl++: listener = com.htc.dotmatrix.CoverService$7@3dc26def
W/SensorService(  958): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  958): disable: get sensor name = CM36686 Proximity sensor
W/Settings( 3080): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3080):  defaultType:0
W/SensorService(  958): pid=2131, uid=10041
W/SensorService(  958): Active sensors: size = 3
W/SensorService(  958): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  958): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  958): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  958): SensorService::listenerSensor++: mName = com.htc.dotmatrix.CoverService$7@3dc26def, eanble = 0, strlen(mName) = 41
W/SensorService(  958): Active Listeners: mActiveListeners.size() = 2
I/ActivityManager(  958): Killing 2581:com.htc.zero:re_proc/u0a110 (adj 15): empty #17
W/SensorService(  958): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@cd8754d
W/SensorService(  958): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@25fa7940
W/SensorService(  958): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 2131): [CoverService] unregisterCallContentObserver()
D/Process (  958): killProcessQuiet, pid=2581
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/LibraryLoader( 3103): Time to load native libraries: 10 ms (timestamps 9322-9332)
I/LibraryLoader( 3103): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3103): Binding Chromium to main looper Looper (main, tid 1) {7ea65da}
I/LibraryLoader( 3103): Expected native library version number "",actual native library version number ""
I/chromium( 3103): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3103): Initializing chromium process, singleProcess=true
W/art     ( 3103): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3103): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  958): Recipient 2581
D/Process (  958): killProcessQuiet, pid=2131
I/ActivityManager(  958): Killing 2131:com.htc.dotmatrix/u0a41 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/chromium( 3103): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/Atfwd_Sendcmd(  445): AtCmdFwd service not published, waiting... retryCnt : 3
W/chromium( 3103): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3103): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3103): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3103): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 3103): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 3103): Build Date: 03/09/15 Mon
I/Adreno-EGL( 3103): Local Branch: 
I/Adreno-EGL( 3103): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 3103): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 3103):                  d74aa161a12b9c6fc6332151
W/ResourcesManager( 2394): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1577): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  958): Recipient 2131
W/System.err(  958): java.lang.Throwable: stack dump
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  958): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  958): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  958): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  958): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@282e1f41:true
D/BluetoothAdapter( 3103): 503071489: getState() :  mService = null. Returning STATE_OFF
D/Process (  958): killProcessQuiet, pid=2482
I/ActivityManager(  958): Killing 2482:com.htc.club/u0a181 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/asset   ( 1577): Copying FileAsset 0x55b34ecfd0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
W/asset   ( 2394): Copying FileAsset 0x55b30ca4f0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
I/ActivityManager(  958): Recipient 2482
D/PhoneApp( 1525): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1525): -- N1 =0
D/PhoneApp( 1525): -- N2 =0
D/PhoneApp( 1525): -- N3 =0
V/UserPresentBroadcastReceiver( 1814): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
I/Prism.WidgetManager( 1577): onLoadItems() -
I/Prism.ItemManager( 1577): loadItems() com.htc.launcher.pageview.WidgetManager@2d6e4ff -
I/Prism.WidgetManager( 2394): onLoadItems() -
I/Prism.ItemManager( 2394): loadItems() com.htc.launcher.pageview.WidgetManager@38c9865 -
I/ActivityManager(  958): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.SuperSaverModeReceiver: pid=3147 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a
W/art     ( 3103): Attempt to remove local handle scope entry from IRT, ignoring
E/SQLiteLog( 1881): (283) recovered 52 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal
W/AwContents( 3103): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3103): CordovaWebView is running on device made by: HTC
I/Scheduler( 1881): Use PeriodicScheduler
W/art     ( 3103): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3103): Attempt to remove local handle scope entry from IRT, ignoring
W/InstanceID/Rpc( 1881): Found 10024
W/chromium( 3103): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 3103): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/htcbackup-core( 3147): ModelRegistry: Loading model meta data from resources...
I/htcbackup-core( 3147): SuperSaverModeReceiver: on receiving action com.htc.server.htcpowersaver.action.OFF
I/htcbackup-core( 3147): SuperSaverModeReceiver: going to send resume event
,D/PMS     (  958): acquireWL(758cc7a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 958 1000 null
,D/UsbDeviceManager(  958): boot completed
D/UsbDeviceManager(  958): [USBNET] handleMessage: 4; mConnected=true, mConfiguration=true
D/UsbDeviceManager(  958): [USBNET] update2: 105,0
,V/SystemUIService( 1220): BOOT_COMPLETED received
D/UsbDeviceManager(  958): sendStickyBroadcast: broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true; SetCurrentFunctions= mtp,mass_storage,adb
,D/PMS     (  958): releaseWL(758cc7a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/UsbnetService(  958): BroadcastReceiver::onReceive+
,D/PMS     (  958): acquireWL(f786c2b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 958 1000 null
I/InputMethodManager( 3103): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3b59dcd7, mServedView=org.apache.cordova.engine.SystemWebView{bd6b9c4 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@289f00ad
,I/htcbackup-core( 3147): BackupRestoreManager: onHandleIntent
D/UsbDeviceManager(  958): [USBNET] handleMessage: 105; mConnected=true, mConfiguration=true
I/htcbackup-core( 3147): BackupRestoreManager: resume
,D/PMS     (  958): releaseWL(f786c2b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/Tethering(  958): got USB_STATE change: usbConnected=true, mRndisEnabled=false, mUsbTetherRequested=false
W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1626 com.android.server.usb.UsbDeviceManager$UsbHandler.handleMessage:1624 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:155 android.os.HandlerThread.run:61 
D/UsbnetService(  958): onReceive ACTION_USB_STATE: true,false
D/UsbDeviceManager(  958): [USBNET] sendStickyBroadcast ACTION_USB_CONNECT2PC: 1
D/UsbnetService(  958): BroadcastReceiver::onReceive-
I/InputMethodManagerService(  958): Disable input method client, pid=1577
I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
D/StatusBarManagerService(  958): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  958): Enable input method client, pid=3103
,W/ResourcesManager(  958): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/XT9_C   ( 1375): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1375): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1375): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1375): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/ActivityManager(  958): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3185 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/art     (  408): Explicit concurrent mark sweep GC freed 8662(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 160us total 18.255ms
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 138us total 16.317ms
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 145us total 16.516ms
,W/BindingManager( 3103): Cannot call determinedVisibility() - never saw a connection for the pid: 3103
,I/ActivityManager(  958): Displayed com.example.hello/.MainActivity: +1s56ms,
I/ActivityManager(  958): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=3210 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,D/MountService(  958): sharing = 0 
D/MountService(  958): Unmount PCTOOL.ISO,
D/VoldConnector(  958): SND -> {10 mountISO unmount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
D/MountService(  958): unmountISO --
D/PMS     (  958): releaseWL(15eda2a4): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/RecoverySystem(  958): No recovery log file
,I/chromium( 3103): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/ActivityManager(  958): Start proc com.futuredial for broadcast com.futuredial/.ui.BootCompletedReceiver: pid=3235 uid=10082 gids={50082, 9997, 3002, 3001} abi=arm64-v8a
,I/BootReceiver(  958): Copying /sys/fs/pstore/console-ramoops to DropBox (SYSTEM_LAST_KMSG),
E/SharedPreferencesImpl(  958): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  958): Copying audit failures to DropBox,
E/SharedPreferencesImpl(  958): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  958): Copied 0 worth of audits to DropBox
,D/JsMessageQueue( 3103): Set native->JS mode to OnlineEventsBridgeMode
I/BootReceiver(  958): Checking for fsck errors
I/ActivityManager(  958): Killing 2461:com.htc.sense.socialplugins/u0a21 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=2461
I/BootReceiver(  958): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/SharedPreferencesImpl(  958): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  958): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
,E/AndroidProtocolHandler( 3103): Unable to open asset URL: file:///android_asset/www/jxcore.js,
E/SharedPreferencesImpl(  958): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,W/ResourcesManager( 3235): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 3235): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/BootReceiver(  958): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  958): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml,
,I/ActivityManager(  958): Recipient 2461
,E/SharedPreferencesImpl(  958): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  958): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
,I/[FDDMI]BootCompletedReceiver( 3235): BootCompletedReceiver :android.intent.action.BOOT_COMPLETED,
,I/DeviceManagement( 3210): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=3210 dbg=false s=true
,E/SharedPreferencesImpl(  958): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  958): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
,I/DeviceManagement( 3210): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
,I/DeviceManagement( 3210): ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup]
,I/DeviceManagement( 3210): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,I/BootReceiver(  958): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  958): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/DeviceManagement( 3210): WorkflowService: Starting workflow service
,I/DeviceManagement( 3210): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@13114394] args=[Bundle[mParcelledData.dataSize=132]]
,I/DeviceManagement( 3210): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
,D/OtaStartupReceiver( 1525): onReceive: android.intent.action.BOOT_COMPLETED
,W/HtcActiveEngineManager(  958): Can't find out the target sensor
,I/BootReceiver(  958): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  958): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/DeviceManagement( 3210): ModelRegistry: Loading model meta data from resources...
E/WifiStateMachine(  958): handleMessage: E msg.what=131206
E/WifiStateMachine(  958): processMsg: InitialState
E/WifiStateMachine(  958):  InitialState CMD_BOOT_COMPLETED 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_BOOT_COMPLETED 0 0
,E/WifiStateMachine(  958): handleMessage: X
D/ConnectivityService(  958): Got NetworkFactory Messenger for WIFI
D/ConnectivityService(  958): NetworkFactory connected
,W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
D/UsbnetService(  958): BroadcastReceiver::onReceive+
,D/UsbnetService(  958): onReceive ACTION_BOOT_COMPLETED
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/UsbnetService(  958): UsbnetHandler::handleMessage+:4
D/UsbnetService(  958): MESSAGE_BOOT_COMPLETED+
D/WIFI    (  958): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI    (  958):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  958): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  958): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/UsbnetService(  958): systemReady+
D/jxcore_app_log( 3103): JniHelper::setJavaVM(0xaaff68f8), pthread_self() = -1406080928
D/UsbnetService(  958): systemReady-
,D/UsbnetService(  958): UsbnetHandler::handleMessage-
D/ConnectivityService(  958): Got NetworkFactory Messenger for usbnet
D/ConnectivityService(  958): NetworkFactory connected
,W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1473 com.android.server.backup.BackupManagerService.notifyBackupEnabled:10562 com.android.server.backup.BackupManagerService.access$3400:164 com.android.server.backup.BackupManagerService$BootCompleteReceiver.onReceive:10549 android.app.LoadedApk$ReceiverDispatcher$Args.run:950 
,D/usbnet  (  958): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/usbnet  (  958):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  958): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/WifiService(  958): updateDevicePolicy Exchange policy allowWifiStatus = 1
D/WifiService(  958): updateDevicePolicy Exchange policy allowInternetSharingStatus = 1
,I/DeviceManagement( 3210): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/ActivityManager(  958): Start proc com.htc.autobot for broadcast com.htc.autobot/.UsbReceiver: pid=3265 uid=10047 gids={50047, 9997, 3003, 3002, 3001, 5003, 1024} abi=arm64-v8a
,I/BootReceiver(  958): Copying /data/tombstones/tombstone_07 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  958): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/Process (  958): killProcessQuiet, pid=2394
I/ActivityManager(  958): Killing 2394:com.htc.sense.news/u0a74 (adj 15): empty #17
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/DeviceManagement( 3210): SessionStateController: Checking invariants...,
,E/SharedPreferencesImpl(  958): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  958): Copying /data/tombstones/tombstone_08 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  958): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  958): Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
,W/jxcore-log( 3103): Initializing JXcore engine
,W/jxcore-log( 3103): JXcore engine is ready
,I/ActivityManager(  958): Recipient 2394
,W/jxcore-log( 3103): Starting JXcore engine,
,I/ActivityManager(  958): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=3287 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 5001, 1024} abi=arm64-v8a
,D/UsbReceiver( 3265): onReceiver android.intent.action.BOOT_COMPLETED
D/HtcModeClient( 3265): power connected, start service
,D/Utils   ( 3265): CMD:getprop ro.htc.htcmode.socket.type
,I/ActivityManager(  958): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=3310 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/System  ( 3265): exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.util.Utils.systemCmd:34)
,W/jxcore-log( 3103): Platform android
W/jxcore-log( 3103): 
,W/jxcore-log( 3103): Process ARCH arm
W/jxcore-log( 3103): 
,D/HtcModeClient( 3265): sSocketMode = LocalSocket,
D/HtcModeClient( 3265): start the htcmodeservice thread
,D/HtcModeClient( 3265): initCanAgent,
,I/CANMesgAgentLocalSocket( 3265): CANAgent Id = 0,
,D/HtcModeClient( 3265): sense info: version = none, id = 2
,D/HtcModeClient( 3265): display info: width = 1080, height = 1776,
D/HtcModeClient( 3265): display info: mode = 10
,I/DeviceManagement( 3210): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/jxcore-log( 3103): JXcore Cordova bridge is ready!
I/jxcore-log( 3103): 
W/jxcore-log( 3103): JXcore engine is started
,E/jxcore  ( 3103): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js,
E/jxcore  ( 3103): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/art     (  958): Explicit concurrent mark sweep GC freed 30964(2033KB) AllocSpace objects, 53(3MB) LOS objects, 33% free, 15MB/23MB, paused 1.550ms total 144.607ms
,I/DeviceManagement( 3210): SessionStateController: Checking invariants...
,D/HtcModeClient( 3265): onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
,D/HtcModeClient( 3265): connectState: BT_TURNON_BYME = false
D/HtcModeClient( 3265): connectState: CONNECTION_READY = false
D/HtcModeClient( 3265): connectState: ENABLE_PROJECTBYAPP = false
D/HtcModeClient( 3265): connectState: ENTER_PROJECTMODE = false
D/HtcModeClient( 3265): connectState: PHONE_PULGIN = false
D/HtcModeClient( 3265): connectState: Force_AWAKE = false
D/HtcModeClient( 3265): connectState: PHONE_PULGIN = true
D/HtcModeClient( 3265): connectState: POWERCONNECTED_READY = true
,D/FindExtension( 3103): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,D/MediaProvider( 3287): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
,D/MediaProvider( 3287): [MP][DEBUG] Storage State: mounted,
D/MediaProvider( 3287): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 3287): [MP][DEBUG] Storage State: removed
D/MediaProvider( 3287): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/MediaProvider( 3287): [MP][DEBUG] Storage State: removed
,W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.powersaver.PowerSaverNotificationReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/AlertReceiver( 2607): beginStartingService
,E/SQLiteLog( 3287): (283) recovered 44 frames from WAL file /data/data/com.android.providers.media/databases/external.db-wal
D/PMS     (  958): acquireWL(e02cd48): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 2607 10010 null
D/PowerSaverNotificationService( 3310): updateNotification, mToggle = false
,D/PMS     (  958): acquireWL(3a0f9906): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 2044 10011 null
,I/DeviceManagement( 3210): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3210): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@13114394]
,I/DeviceManagement( 3210): WorkflowService: Stopping workflow service
,D/PMS     (  958): releaseWL(3a0f9906): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 null,
,D/PMS     (  958): acquireWL(531bd63): PARTIAL_WAKE_LOCK  *alarm* 0x1 958 1000 WorkSource{1000}
,V/AlarmManager(  958): sending alarm PendingIntent{3b73fd60: PendingIntentRecord{3fd65219 android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=40973, Int=0
,D/DFPI.PIReciver( 2984): onReceiver action:android.intent.action.BOOT_COMPLETED
D/DFPI    ( 2984): getInstance = com.htc.demoflopackageinstaller.ApkInstallHelper@3dc26def
,D/HtcAlertService( 2607): start to updateAlertNotification!
W/CustomizationIntentService( 1655): failed at default contact creation!
W/CustomizationIntentService( 1655): java.lang.SecurityException: Requesting code from com.htc.contacts (with uid 10038) to be run in process android.process.acore (with uid 10013)
W/CustomizationIntentService( 1655): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1793)
W/CustomizationIntentService( 1655): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1768)
W/CustomizationIntentService( 1655): 	at android.app.ContextImpl.createPackageContextAsUser(ContextImpl.java:2266)
W/CustomizationIntentService( 1655): 	at android.app.ContextImpl.createPackageContext(ContextImpl.java:2253)
W/CustomizationIntentService( 1655): 	at android.content.ContextWrapper.createPackageContext(ContextWrapper.java:658)
W/CustomizationIntentService( 1655): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.handleIntentInternal(CustomizationIntentService.java:143)
W/CustomizationIntentService( 1655): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.onHandleIntent(CustomizationIntentService.java:104)
W/CustomizationIntentService( 1655): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/CustomizationIntentService( 1655): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/CustomizationIntentService( 1655): 	at android.os.Looper.loop(Looper.java:155)
W/CustomizationIntentService( 1655): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/CustomizationIntentService( 1655): handleIntentInternal(): action = com.htc.intent.action.PRELOAD_CONTACTS, original action = android.intent.action.BOOT_COMPLETED, launched by: null
W/CustomizationIntentService( 1655): AFH Enable: false, LEONCHAME: false
,W/CustomizationIntentService( 1655): hasBeenInit true
W/CustomizationIntentService( 1655): isNewChameleonHFASupported false
W/CustomizationIntentService( 1655): isHFA true
W/CustomizationIntentService( 1655): setupWizRun 1
,D/DFPI    ( 2984): set install APK prefrence is false
,D/PMS     (  958): releaseHCC(6a28ef8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  958): releaseHCC(26969fd1): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,D/HtcAlertService( 2607): No fired or scheduled alerts,
D/HtcAlertUtils( 2607): -- cancelReminderNotification --
D/HtcAlertUtils( 2607): broadcastExistReminder!
,D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  958): Killing 2911:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=2911
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/PMS     (  958): releaseWL(e02cd48): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,I/ActivityManager(  958): Recipient 2911
,W/AlertReceiver( 2607): stopSelfResult true
,D/Process (  958): killProcessQuiet, pid=2936,
I/ActivityManager(  958): Killing 2936:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/htcbackup-core( 3147): BackupRestoreManager: Storage is not configured
,E/htcbackup-core( 3147): BackupStatus: Ignoring failure message - backup already failed with message:  CONNECTION_FAIL_STORAGE
,I/ActivityManager(  958): Recipient 2936,
,W/System.err( 3147): Starting the HTTP client
,W/htcbackup-core( 3147): BackupServiceClientResourceProxy: Reseting appServerErrorCount
,I/ActivityManager(  958): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=3361 uid=10020 gids={50020, 9997, 1028, 1015} abi=arm64-v8a
,D/Process (  958): killProcessQuiet, pid=2958,
I/ActivityManager(  958): Killing 2958:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 2958
,W/htcbackup-core( 3147): BackupRestoreManager: No sense account found - aborting,
I/htcbackup-core( 3147): BackupRestoreManager: DM is not ready, pending resume
,D/Process (  958): killProcessQuiet, pid=1718
I/ActivityManager(  958): Killing 1718:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 1718,
,D/FlexNetS( 2044): setNetMode:0, false,
,D/FlexNetS( 2044): set2gLowSignalEnablePref: false
,V/FlexNetS( 2044): [DRX] setHigherPowerIn2GPref to: true
D/FlexNetS( 2044): setSimCardisWhiteList: false
,V/FlexNetS( 2044): setSimCardCamp3GNetworkSignalPref to: false,
D/FlexNetS( 2044): setCampNetworkisBlackList: false
,V/FlexNetS( 2044): [DRX] setHigherPowerIn2GPref to: true
,V/FlexNetS( 2044): setRilHandOverW2GEnable: 0
,D/FlexNetS( 2044): updateSvcAllowedInSettings:false
,I/ActivityManager(  958): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3386 uid=10026 gids={50026, 9997} abi=arm64-v8a,
D/Process (  958): killProcessQuiet, pid=3021
I/ActivityManager(  958): Killing 3021:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 3021
,V/AlarmManager(  958): sending alarm PendingIntent{a57f3bc: PendingIntentRecord{331e3f45 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=41786, Int=0
,V/OneTimeInitializerReceiver( 3386): OneTimeInitializerReceiver.onReceive,
,V/OneTimeService( 3386): OneTimeService.onHandleIntent
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.partnersetup, clsName=com.google.android.partnersetup.PhoneStateReceiver, state=1, flag=1, pid=2795, uid=10027, userID:0
,D/PMS     (  958): acquireWL(2d10fe54): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  958): Start proc com.htc.video for broadcast com.htc.video/.videowidget.videoDMC.DLNAReceiver: pid=3416 uid=10029 gids={50029, 9997, 3002, 3003, 1028, 1015, 1023, 2001} abi=arm64-v8a
,D/PMS     (  958): releaseWL(2d10fe54): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(21faeef2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  958): releaseWL(21faeef2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=2795, uid=10027, userID:0
,I/RlzPingService( 2795): Setting next ping for 1458032635980,
,D/PMS     (  958): acquireWL(2dd1a943): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  958): releaseWL(2dd1a943): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(10a9abc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(10a9abc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(2112d0f9): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  958): releaseWL(2112d0f9): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  958): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=3442 uid=10031 gids={50031, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  958): Killing 2564:com.htc.showme/u0a81 (adj 15): empty #17
,D/Process (  958): killProcessQuiet, pid=2564,
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 2564
,D/PMS     (  958): acquireWL(2a45083e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(2a45083e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(25db969f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(25db969f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/Process (  958): killProcessQuiet, pid=2707,
I/ActivityManager(  958): Killing 2707:com.htc.sense.browser/u0a9 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 2707
,I/ActivityManager(  958): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=3463 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
D/Process (  958): killProcessQuiet, pid=2841
I/ActivityManager(  958): Killing 2841:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 2841
,D/Process (  958): killProcessQuiet, pid=3080,
I/ActivityManager(  958): Killing 3080:com.android.settings/1000 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 3080,
,I/ActivityManager(  958): Killing 3147:com.htc.backup/u0a109 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=3147
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 3147
,E/Personalize.BootComple_( 3463): onReceive() + Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.home.personalize/.receiver.BootCompleteInitializer (has extras) },
E/Personalize.BootComple_( 3463): action android.intent.action.BOOT_COMPLETED,
,E/Personalize.Utilities( 3463): SimpleLauncher not found: com.htc.simplelauncher,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.htc.home.personalize, clsName=com.htc.home.personalize.SimpleModeEntryActivity, state=2, flag=1, pid=3463, uid=1000, userID:0
,E/Personalize.BootComple_( 3463): initialize: false
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.htc.simplelauncher, clsName=null, state=2, flag=0, pid=3463, uid=1000, userID:0
,E/Personalize.Utilities( 3463): setApplicationEnabled IllegalArgumentException com.htc.simplelauncher
,V/BootCompletedReceiver( 2816): ensureAndExecuteUserProfiling: ensureAndExecuteUserProfiling ,
,D/PeopleYouKnow( 2816): receive intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.contacts/.peopleyouknow.PeopleYouKnowReceiver (has extras) },
,D/Process (  958): killProcessQuiet, pid=3185
I/ActivityManager(  958): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=3484 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  958): Killing 3185:com.android.keychain/1000 (adj 15): empty #17
,I/art     (  408): Explicit concurrent mark sweep GC freed 8659(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 202us total 37.258ms,
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 21.814ms
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 22.790ms
,I/ActivityManager(  958): Recipient 3185,
,V/HtcDataRoamingWidget.DisableWidgetReceiver( 3484): ACTION_BOOT_COMPLETED,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.dataroaming, clsName=com.htc.rosiewidgets.dataroaming.HtcSettingWidgetProvider, state=1, flag=1, pid=3484, uid=10040, userID:0
,V/HtcDataStripWidget.DisableWidgetReceiver( 3484): ACTION_BOOT_COMPLETED
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.datastrip, clsName=com.htc.rosiewidgets.datastrip.HtcSettingWidgetProvider, state=1, flag=1, pid=3484, uid=10040, userID:0,
,D/Process (  958): killProcessQuiet, pid=3235
I/ActivityManager(  958): Killing 3235:com.futuredial/u0a82 (adj 15): empty #17
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  958): Recipient 3235
,D/DotMatrix( 1307): [EventReceiver] onReceive, version:1.3
,I/ActivityManager(  958): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3505 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager(  958): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=3527 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 3002, 3001, 2001, 1023} abi=armeabi-v7a
,W/ResourcesManager( 3527): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.,
,I/ActivityManager(  958): Killing 3310:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
D/Process (  958): killProcessQuiet, pid=3310
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 3310
,D/MediaSessionHelper( 3527): Attempting to get helper with context android.app.ReceiverRestrictedContext@14d0e3c9,
,D/MediaSessionService(  958): Created session for package com.htc.music with tag MediaSessionHelper-com.htc.music,
,D/MediaSessionHelper( 3527): addMediaButtonListener added PendingIntent{3dc26def: android.os.BinderProxy@38ce6ace}
,D/Process (  958): killProcessQuiet, pid=2607,
I/ActivityManager(  958): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=3551 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  958): Killing 2607:com.htc.calendar/u0a10 (adj 15): empty #17
,I/ActivityManager(  958): Recipient 2607
,I/ActivityManager(  958): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3573 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  958): Killing 3210:com.htc.cs.dm/u0a99 (adj 15): empty #17,
D/Process (  958): killProcessQuiet, pid=3210
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 3210
,W/ContextImpl( 3573): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 3573): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncServiceReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 3573): MY_DEBUG = false
,W/ContextImpl( 3573): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 3573): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,V/AlarmManager(  958): sending alarm PendingIntent{3288a631: PendingIntentRecord{21b7e116 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457427838646, Int=0
,W/ContextImpl( 3573): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.startService:208 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.onHandleIntent:71 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/[PluginManager]RegisterService( 1498): onHandleIntent, action: android.intent.action.BOOT_COMPLETED, data: null
D/HtcAppUPService( 1498): CustomizationReceiver  receieve: android.intent.action.BOOT_COMPLETED
,D/HtcAppUPService( 1498): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.BOOT_COMPLETED cmp=com.htc.sense.hsp/.upservice.HtcUPService }, this = com.htc.sense.hsp.upservice.HtcUPService@775bffd
,D/AutoSetting( 1498): receiver - intent: android.intent.action.BOOT_COMPLETED
,I/WSP     ( 1498): [Receiver] EVENT - BOOT COMPLETED, is settings existed? true
,I/ActivityManager(  958): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=3605 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a,
,D/AutoSetting( 1498): service - onStartCommand() action: com.htc.app.autosetting.bootcomplete
D/WeatherUtility( 1220): Weather sync is On
,W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data,
D/AutoSetting( 1498): service - onStartCommand() boot completed, remove cache
D/AutoSetting( 1498): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1498): service - handleMessage() setting current location null
D/AutoSetting( 1498): service - handleMessage() removing cache
I/ActivityManager(  958): Killing 2984:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/AutoSetting( 1498): service - AddressCache: clean up all cache
D/Process (  958): killProcessQuiet, pid=2984
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/HtcAppUPService( 1498): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.BOOT_COMPLETED
,W/Bundle  ( 1498): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
,W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1498): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800),
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/FeatureList( 1498): feature,
D/FeatureList( 1498): type
D/FeatureList( 1498): description
,W/Bundle  ( 1498): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1498): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1498): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1498): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1498): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61),
W/Bundle  ( 1498): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source),
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1498): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
,W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
,W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1498): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1498): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1498): Attempt to cast generated internal exception:,
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1498): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1498): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1498): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
,W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1498): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
,W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1498): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1498): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1498): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1498): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1498): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	,at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  958): Recipient 2984,
,W/Bundle  ( 1498): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1498): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/HtcAppUPService( 1498): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
D/HtcAppUPService( 1498): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
W/Bundle  ( 1498): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1498): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1498): Attempt to cast generated internal exception:
W/Bundle  ( 1498): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1498): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1498): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1498): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1498): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1498): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/BootReceiver( 3605): onReceive: android.intent.action.BOOT_COMPLETED,
D/BootReceiver( 3605): boot completed:
,D/BootReceiver( 3605): isValid:  isEnabledEasyAccess = true, isEnabledQuickDial = true
D/BootReceiver( 3605): Valid
D/BootReceiver( 3605): startService:
,I/ActivityManager(  958): Start proc com.htc.HTCSpeaker:ngfservice for service com.htc.HTCSpeaker/.NGFService: pid=3626 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a,
,I/ActivityManager(  958): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=3639 uid=10058 gids={50058, 9997, 1028, 1015, 1023} abi=arm64-v8a,
D/Process (  958): killProcessQuiet, pid=3287
I/ActivityManager(  958): Killing 3287:android.process.media/u0a17 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 3287,
,D/PluginProvider( 1498): Begin Apply Batch
,E/PluginProvider( 1498): conflict when insert feature, ignored
,D/NGFService( 3626): onCreate +++
,D/SettingUtils( 3626): getProcessNormalFlag: true
D/NGFService( 3626): onCreate last time crash or 1st run=false
D/SettingUtils( 3626): setProcessNormalFlag: false
,D/NGFService( 3626): getAudioStreamType: ScoOn =false
,D/SoundEffects( 3626): init +++ 3
W/LMW     ( 3639): [3670][ActionDeviceStorageHandler] onActionBootComplete++
,W/LMW     ( 3639): [3670][ActionDeviceStorageHandler] onActionBootComplete--
,I/ActivityManager(  958): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3674 uid=10063 gids={50063, 9997, 1028, 3003} abi=arm64-v8a
,D/Process (  958): killProcessQuiet, pid=3361,
I/ActivityManager(  958): Killing 3361:com.htc.fm/u0a20 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/AudioCache(  402): Heap size overflow! req size: 1058400, max size: 1048576
,W/NuPlayerRenderer(  402): AudioSink write short frame count 0 < 9824
,I/ActivityManager(  958): Recipient 3361,
,D/PluginProvider( 1498): apply Batch success
,D/NGFLanguageMgr( 3626): LanguageFromSystem: language:en  country:gb
,D/NGFLanguageMgr( 3626): language package name = preload_package
,I/[PluginManager]RegisterService( 1498): Notify Carousel that a new TabPlugin has been installed!
,I/art     (  958): Explicit concurrent mark sweep GC freed 14525(783KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 15MB/23MB, paused 1.158ms total 129.445ms,
,I/ActivityManager(  958): Start proc android.process.media for broadcast com.android.providers.media/.MediaScannerReceiver: pid=3746 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 5001, 1024} abi=arm64-v8a,
D/Process (  958): killProcessQuiet, pid=2044
I/ActivityManager(  958): Killing 2044:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/NMT     ( 3626): NMT version: 1.6.1-B006 REL,
D/NGFService( 3626): Audio Dump Folder: Elvis = /data/data/com.htc.HTCSpeaker/files/htcspeak_elvis, PCM = /data/data/com.htc.HTCSpeaker/files/htcspeak_pcm
,I/ActivityManager(  958): Recipient 2044
,D/NGFService( 3626): applyCurrentSystemLanguage +++
D/NGFService( 3626): grammar support language:[United States English, Taiwanese Mandarin, Chinese Mandarin, German, Latin American Spanish, European Spanish, European French, Italian, British English, Japanese, Canadian French, Chinese Cantonese, Danish, Greek, Finnish, Dutch, Norwegian, Polish, Brazilian Portuguese, European Portuguese, Russian, Swedish, Australian English, Turkish]
D/NGFLanguageMgr( 3626): LanguageFromSystem: language:en  country:gb
D/NGFService( 3626): Elvis language uses the language: 2
D/NGFService( 3626): setCurrentNGFLanguageMgr: Language = 2, CurrentLanguage = 0,
D/NGFService( 3626): setCurrentNGFLanguageMgr: set language = British English
D/NGFService( 3626): bluetoothInitialize +++
,W/System.err(  958): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  958): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18c0c425:true
W/System.err(  958): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  958): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  958): ,	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
D/NGFService( 3626): cloud_init +++
D/NGFLanguageMgr( 3626): getCloudServerDNSName: language = 2, DNS name = cc.nvc.engb.nuancemobility.net
,D/MediaProvider( 3746): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
,D/MediaProvider( 3746): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 3746): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
,D/MediaProvider( 3746): [MP][DEBUG] Storage State: removed
D/MediaProvider( 3746): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/NGFService( 3626): elvisInitalize +++
D/MediaProvider( 3746): [MP][DEBUG] Storage State: removed,
,E/SQLiteLog( 3746): (283) recovered 44 frames from WAL file /data/data/com.android.providers.media/databases/external.db-wal,
,D/NGFService( 3626): elvisInitalize lang = British English
D/NGFService( 3626): elvisInitalize: Freq Type:16000
,D/NGFService( 3626): tts_init +++
,D/NGFLanguageMgr( 3626): getVocalizerFolderName: language = 2, folder name = vocalizer_eng
,D/MediaScannerReceiver( 3746): onReceive Intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.media/.MediaScannerReceiver (has extras) }
,D/MediaProviderUtils( 3746): [startScan]volume:internal, action:android.intent.action.MEDIA_MOUNTED
,D/MediaProviderUtils( 3746): [startScan]volume:external, action:android.intent.action.MEDIA_MOUNTED,
,D/NGFLanguageMgr( 3626): LanguageFromSystem: language:en  country:gb,
D/NGFLanguageMgr( 3626): language package name = preload_package
,I/HtcModeClient( 3265): handler message = 4011,
E/HtcModeClient( 3265): Check connection and retry 1 times.
,D/NGFService( 3626): load vocalizer language = British English
,E/NGFService( 3626): registerObserver
,D/NGFService( 3626): onCreate: Battery Level Remaining: 100%,
D/NGFService( 3626): onStartCommand(): service start
D/NGFService( 3626): onStartCommand() action = com.htc.HTCSpeaker.NGFService.QuickCall,
D/NGFService( 3626): QuickCall
,W/NMT-OemFile( 3626): fopen(): Failed to open file sysdct.dat
,W/NMT-OemFile( 3626): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat,
,W/NMT-OemFile( 3626): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
,W/NMT-OemFile( 3626): fopen(): Failed to open file sysdct.dat,
W/NMT-OemFile( 3626): fopen(): Failed to open file sysdct.dat
,W/NMT-OemFile( 3626): fopen(): Failed to open file clm.dat,
,D/NGFService( 3626): Elvis is initialization Success,
D/NGFService( 3626): bElvisInitializeCompleted = true
D/NGFService( 3626): GrammarState = 0
D/NGFService( 3626): loadGrammar +++
D/NGFService( 3626): loadGrammar asr_grammar
,W/NMT     ( 3626): Fail to open read-stream for file generic.lst
,D/MediaScannerServiceEx( 3746): Action not in map, volume = internal, action = android.intent.action.MEDIA_MOUNTED
I/NGFService( 3626): GrammarDepot contains a valid Elvis Grammar0
D/NGFService( 3626): loadGrammar from cache
D/MediaScannerServiceEx( 3746): Action not in map, volume = external, action = android.intent.action.MEDIA_MOUNTED
,V/AlarmManager(  958): sending alarm PendingIntent{27150523: PendingIntentRecord{27960a20 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=45970, Int=0
D/PMS     (  958): acquireWL(33c4ce52): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3746 10017 null
,D/MtpReceiver( 3746): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3746): [MTP][handleUsbStateAsync]1:1-
,D/MtpReceiver( 3746): [MTP][handleUsbState]+
,W/NMT     ( 3626): Fail to open read-stream for file elvisBritish Englishname.lst
,I/ActivityManager(  958): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=3786 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/MediaProvider( 3746): bindService() MTP Service Connection.
,D/MtpReceiver( 3746): [MTP][scanExternalVolumeIfNeed] scan external volume
,D/MtpReceiver( 3746): [MTP][handleUsbState]-
,W/NMT     ( 3626): Fail to open read-stream for file elvisBritish Englishartist.lst
D/MtpReceiver( 3746): [MTP][handleMessage]-
,W/NMT-OemFile( 3626): fopen(): Failed to open file daniel_userdct_eng.dat
D/MediaScanner( 3746): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
,D/MtpService( 3746): updating state; isCurrentUser=true, mMtpLocked=false
,W/NMT     ( 3626): Fail to open read-stream for file elvisBritish Englishplaylist.lst
W/NMT     ( 3626): Fail to open read-stream for file elvisBritish Englishsong.lst
W/NMT     ( 3626): Fail to open read-stream for file elvisBritish Englishalbum.lst
,D/MtpService( 3746): addStorageInternal without MtpServer
W/NMT     ( 3626): Fail to open read-stream for file elvisBritish Englishgeneric.lst
,D/MtpService( 3746): [MTP][onCreate]-
,I/ActionCombine( 3746): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,E/SQLiteLog( 3746): (283) recovered 98 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,D/MtpService( 3746): [MTP] startForeground
,D/MtpService( 3746): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 3746): TotalSize=1886532,MediaCacheLimit=6000
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/PMS     (  958): acquireWL(1f9bd149): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2107 10024 null
D/SettingUtils( 3626): setProcessNormalFlag: true
D/NGFService( 3626): RebuildListener constraintList size 17
D/NGFService( 3626): RebuildListener: onComplete0
D/NGFService( 3626): onComplete GRAMMAR_STATE_DEFAULT
D/NGFService( 3626): switchScenario: htc_screen_140_19
D/NGFService( 3626): Activated grammar scenario [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3626): Activated grammar constraintNames [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3626): Loading grammar completed.
D/NGFService( 3626): update contact cache completed
D/SettingUtils( 3626): set Updatge Contact Cache: false
,D/MtpService( 3746): starting MTP server in MTP mode
,W/HtcWrapAdjustableCursorFactory( 3786): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
D/MtpService( 3746): addStorageInternal 65537 /storage/emulated/0
D/MessageFrequencyProvider( 3786): onCreate
D/MtpService( 3746): [checkStorageState] Storage state - mounted
D/MtpDatabase( 3746): [MTP][addStorage] iHostType =2
D/MtpService( 3746): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
,V/GetPrviateResource( 3786): GetPrviateResource
,V/GetPrviateResource( 3786): GetPrviateResource
I/RemoteViews( 1220): apply : com.android.providers.media 0 13 2 36
,D/MessageCustFlag( 3786): sense_version=6.0
,D/BTAccessoryUtil( 3786): createReceiver
,D/BTAccessoryUtil( 3786): registerReceiver return intent = null,
D/MessageCustFlag( 3786): sku_id=118
,D/HtcBuildUtils( 3786): getRATByHtcTelephonyCapability:1
I/RemoteViews( 1220): apply : com.android.providers.media 0 14 2 51
,W/SystemReader( 3786): Cannot find qct_8960_interface, use default value instead
V/MmsSystemEventReceiver( 3786): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) }
,D/ExchangePolicystatus( 3786): onReceive()
,D/ExchangePolicystatus( 3786): onReceive(): ACTION_BOOT_COMPLETED
,D/MessageUtils( 3786): Text messaging allow status = allow
D/Messaging( 3786): EAS allow SMS !!!
,D/ExchangePolicystatus( 3786): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
D/Messaging( 3786): EAS allow SMS !!!
,I/iu.UploadsManager( 2107): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/ActivityManager(  958): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=3825 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,V/AlarmManager(  958): sending alarm PendingIntent{28b02468: PendingIntentRecord{e876081 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=46143, Int=0
,W/MediaScanner( 3746): Error opening directory '/oem/media/', skipping: No such file or directory.
D/PMS     (  958): acquireWL(13d19526): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 3786 10064 null
,W/MediaScanner( 3746): Error opening directory '/oem/media/', skipping: No such file or directory.
,D/MediaScanner( 3746):  prescan time: 126ms
D/MediaScanner( 3746):     scan time: 27ms
D/MediaScanner( 3746): postscan time: 0ms
D/MediaScanner( 3746):    total time: 153ms
D/MediaScanner( 3746): -----------------------------------------------------------------,
D/MediaScanner( 3746): firstscan(media) time: 16ms
D/MediaScanner( 3746): secondscan(non-media) time: 7ms
D/MediaScanner( 3746):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3746):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3746):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3746):  [Total]    File(Image+Video+Audio+Others) in database : 339
D/WeatherUtility( 1220): Weather sync is On
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,I/ClockController( 1220): schedule update now=1457427840016 next=59984
,I/Clock   ( 1220): updateClock:10:04 Europe/Warsaw
I/Clock   ( 1220): updateClock:10:04 Europe/Warsaw
,I/Clock   ( 1220): updateClock:10:04 Europe/Warsaw
,V/SmsReceiverService( 3786): onStart: #1, @155462631
,V/SmsReceiverService( 3786): action: android.intent.action.BOOT_COMPLETED
D/SmsReceiverService( 3786): isCbm: false
D/SmsReceiverService( 3786): isDiscard: false
,D/SettingsManager( 3786): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2a71fa0b
,V/SmsReceiverService( 3786): handleBootCompleted
,E/MediaScannerService( 3746): [onStartCommand] --- Should not be here, redirect request. ----
,E/MediaScannerService( 3746): [handleMessage] --- Should not be here, ignore request. ----
,W/ResourcesManager( 3786): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49,
D/AccFlag ( 1525): sku_id=118
,D/SmsReceiverService( 3786): OutBoxSize = 0,
,D/SmsReceiverService( 3786): sendFirstQueuedMessage start: 0
D/MessageCustFlag( 3786): sku_id=118
I/iu.UploadsManager( 2107): End new media; added: 0, uploading: 0, time: 88 ms
D/PMS     (  958): releaseWL(1f9bd149): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
,D/AccFlag ( 1525): sku_id=118
,D/MessageCustFlag( 3786): sku_id=118
,D/SmsReceiverService( 3786): sendFirstQueuedMessage end cnt> 0
,D/SpaceBufferUtil( 3786): > createBufferFile(),
,D/SpaceBufferUtil( 3786): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
D/SpaceBufferUtil( 3786): < createBufferFile()
,D/Process (  958): killProcessQuiet, pid=3386
I/ActivityManager(  958): Killing 3386:com.google.android.onetimeinitializer/u0a26 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaProvider( 3746): [delete][133]
,D/MediaProvider( 3746): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,E/cutils-trace( 3851): Error opening trace file: Permission denied (13),
I/dex2oat ( 3851): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 3851): dex2oat: override thread count:4
,D/MediaProvider( 3746): [recoverParentNodes] - 0
D/MediaProvider( 3746): [update][15]
D/MediaScannerServiceEx( 3746): [scan] Recover Parent Node is finished!
,I/ActivityManager(  958): Recipient 3386
,D/PMS     (  958): releaseWL(33c4ce52): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,E/MediaScannerServiceEx( 3746): [getStorageMaskIdFromPath] path is null,
D/MediaScannerServiceEx( 3746): [ServiceHandler][handleMessage] , action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3746): [handleExternalVolume] ext storage,
D/MediaProviderUtils( 3746): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3746): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3746): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3746): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3746): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 3746): [update][10]#0#
,D/MediaProvider( 3746): [update][9]#0#
,D/MediaProvider( 3746): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3746): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3746): [update][6]#1#
,D/MediaScannerServiceEx( 3746): [AliveExtStorageRows]-0, 0
,D/PMS     (  958): acquireWL(36971f14): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3746 10017 null
,D/MediaScanner( 3746): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,I/dex2oat ( 3851): dex2oat took 666.642ms (threads: 4)
,I/PushClient( 3825): ApplicationMonitor {13114394}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 3825): ApplicationMonitor {13114394}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 3825): ApplicationMonitor {13114394}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 3825): ApplicationMonitor {13114394}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 3825): ApplicationMonitor {13114394}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 3825): ApplicationMonitor {13114394}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 3825): ApplicationMonitor {13114394}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 3825): ApplicationMonitor {13114394}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 3825): ApplicationMonitor {13114394}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/ActivityManager(  958): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3860 uid=10076 gids={50076, 9997} abi=arm64-v8a,
,I/PushClient( 3825): String {2b182068}: handleBroadcast(): Schedule update on boot completed.
,D/Process (  958): killProcessQuiet, pid=2795,
I/ActivityManager(  958): Killing 2795:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 2795,
,D/SMSBackup( 3860): Got ACTION_BOOT_COMPLETED event,
,D/SMSBackup( 3860): setCheckAlarm
,D/SMSBackup( 3860): Next check is scheduled at 60s from now
,D/Process (  958): killProcessQuiet, pid=3416,
I/ActivityManager(  958): Killing 3416:com.htc.video/u0a29 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  958): Recipient 3416,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1525, uid=1001, userID:0
,I/ActivityManager(  958): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=3882 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/[AppShowMeDebug]BootCompletedReceiver( 3882): received boot complete
,I/[AppShowMeDebug]BootCompletedReceiver( 3882): push flag is false, skip check
,I/ActivityManager(  958): Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=3906 uid=10083 gids={50083, 9997, 1007, 3003, 1028} abi=arm64-v8a
,I/ActivityManager(  958): Killing 3442:com.htc.csrecommend/u0a31 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=3442
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/HtcModeClient( 3265): handler message = 4009,
I/HtcModeClient( 3265): start to setup the connection
,I/ActivityManager(  958): Recipient 3442
,D/MyReportAgent( 3906): PolicyReceiver  receieve: android.intent.action.BOOT_COMPLETED
,D/MyReportAgent( 3906): DatabaseHelper [DatabaseHelper constructor],
D/MyReportAgent( 3906): PolicyStore [Init] Get cached policy bundle
,I/ActivityManager(  958): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3928 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,D/MyReportAgent( 3906): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE,
,D/MyReportAgent( 3906): ReportServiceHandler on boot complete event ,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.htc.feedback, clsName=com.htc.feedback.reportagent.receiver.PowerConnectedReceiver, state=2, flag=1, pid=3906, uid=10083, userID:0,
V/MyReportAgent( 3906): ReportServiceHandler unregister the PowerConnected Listener
,D/Process (  958): killProcessQuiet, pid=3463
I/ActivityManager(  958): Killing 3463:com.htc.home.personalize/1000 (adj 15): empty #17,
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/MediaScanner( 3746):  prescan time: 584ms
D/MediaScanner( 3746):     scan time: 833ms
,D/MediaScanner( 3746): postscan time: 4ms
D/MediaScanner( 3746):    total time: 1421ms
D/MediaScanner( 3746): -----------------------------------------------------------------
D/MediaScanner( 3746): firstscan(media) time: 570ms
D/MediaScanner( 3746): secondscan(non-media) time: 263ms
D/MediaScanner( 3746):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3746):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3746):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3746):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,D/MediaProvider( 3746): [delete][20]
,D/MediaProvider( 3746): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3746): [recoverParentNodes] - 0
,D/MediaProvider( 3746): [update][5]
D/MediaScannerServiceEx( 3746): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3746): [updateImage]+
,D/MediaScannerServiceEx( 3746): [updateImage]-0,
,I/ActivityManager(  958): Recipient 3463
,D/MediaScannerServiceEx( 3746): [2] scan finished
D/PMS     (  958): releaseWL(36971f14): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaProviderUtils( 3746): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3746): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3746): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3746): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3746): Process mounted intent for unmounted storage: /storage/ext_sd
,D/MediaScannerServiceEx( 3746): [disAliveExtStorageRows]+131073
,D/UpdaterAPK | UpdaterBootCompleteReceiver( 3928): onReceive() - start htcCheckinService
,D/MediaProvider( 3746): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3746): [update][11]#1#
,D/Messaging( 3786): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 3786): networkCode: 
D/MmsConfig( 3786): SIE smsPri: null
D/MmsConfig( 3786): networkCode: 
,I/htcCheckinService(  958): htcCheckinProvider V2.1
D/htcCheckinService(  958): htcCheckinService() the mIsServiceRunning = true
I/htcCheckinService(  958): Checkin service onCreate()!
I/ActivityManager(  958): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3954 uid=10090 gids={50090, 9997, 1028} abi=arm64-v8a
,D/MmsConfig( 3786): packageName: com.htc.vvm.att does not exist
,D/htcCheckinService(  958): onStartCommand(),
D/htcCheckinService(  958): onStartCommand() the action name = null
D/htcCheckinService(  958): InitThread start
,D/Messaging( 3786): mNeedToUpdateDate2 start,
,D/ReportIndicatorCache( 3786): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3786): 
D/MmsAsyncWorkHandler( 3786): HM tk = 20001
D/ReportIndicatorCache( 3786): MSG_QUERY_REPORTS >>
D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1525):  slotId = -1000
D/MmsSmsV2Provider( 1525): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Process (  958): killProcessQuiet, pid=2172
I/ActivityManager(  958): Killing 2172:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/DraftCache( 3786): [DraftCache/1] DraftCache.constructor
D/DraftCache( 3786): [DraftCache/1] refresh
,D/MediaProvider( 3746): [update][96]#0#
I/Messaging( 3786): mccmnc> 
,D/MmsConfig( 3786): networkCode: 
,D/Messaging( 3786): ViewCache CreatePreloadOnlyConversationList
D/MediaScannerServiceEx( 3746): [disAliveExtStorageRows]--1, 0
,D/MessageCustFlag( 3786): sense_version=6.0
,D/Jerry   ( 3786): start to preload cursor >>>>>>>
,I/ActivityManager(  958): Recipient 2172
,D/MediaProviderUtils( 3746): calcVolumeId: /storage/emulated/0,
D/MediaProviderUtils( 3746): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3746): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3746): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3746): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3746): [disAliveExtStorageRows]+196609
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 89
D/AccFlag ( 1525): sku_id=118
,D/DraftCache( 3786): [DraftCache/86] rebuildCache
D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1525):  slotId = -1000
,D/MmsSmsV2Provider( 1525): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MediaProvider( 3746): [sendStorageAddedIfNeed]: /storage/usb : unmounted,
D/PhoneStorageUtil( 3786): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3786): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 3786): createReceiver
D/MediaProvider( 3746): [update][14]#1#
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1525):  slotId = -1000
D/MmsSmsV2Provider( 1525): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/MediaProvider( 3746): [update][35]#0#
,I/art     (  958): Explicit concurrent mark sweep GC freed 14105(647KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.176ms total 149.840ms
D/MediaScannerServiceEx( 3746): [disAliveExtStorageRows]--1, 0
,E/MediaScannerServiceEx( 3746): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3746): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,D/MediaScannerServiceEx( 3746): [handleExternalVolume] ext storage
D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1525):  slotId = -1000
,D/MediaProviderUtils( 3746): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3746): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3746): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3746): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3746): [AliveExtStorageRows]+65537, 11223344
,D/Messaging( 3786): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1525): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/PMS     (  958): acquireWL(1d934540): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 3954 10090 null
,V/MmsProvider( 1525): Update uri=content://mms, match=0
V/MmsProvider( 1525): selection=st=129 AND m_type!=134
D/Messaging( 3786): Reset downloading state: 0
V/MmsSystemEventReceiver( 3786): TransactionService is going to be woken up.
,D/MediaProvider( 3746): [update][11]#0#,
D/Messaging( 3786): ViewCache CreatePreload
D/Messaging( 3786): ViewCache CreatePreloadOnlyMultipleOpsList
D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 89
D/Jerry   ( 1525): URI_DRAFT,
V/TransactionService( 3786): 1-Creating TransactionService,
D/MediaProvider( 3746): [update][4]#0#
,D/DraftCache( 3786): hasDraft() = false mNeedNotifyChange = true
,I/WorldClock.Global( 3954): isHEPDevice = true
D/DraftCache( 3786): [DraftCache/86] rebuildCache time: 5
D/MmsAsyncWorkHandler( 3786): 
D/MmsAsyncWorkHandler( 3786): HM tk = 20002
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1525):  slotId = -1000
D/MmsSmsV2Provider( 1525): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MediaProvider( 3746): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
,D/MtpService( 3746): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/Cust_MMSMS( 3786): _has_set_default_values_2=true
D/MediaProvider( 3746): [update][13]#1#
V/TransactionService( 3786): onStartCommand: 1
D/MmsSystemEventReceiver( 3786): unRegisterForConnectionStateChanges
W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl(  958): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
D/MediaScannerServiceEx( 3746): [AliveExtStorageRows]-0, 0
V/TransactionService( 3786): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 3786): Loading previous transactions.
,D/PMS     (  958): acquireWL(15e637ca): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3746 10017 null
,D/Messaging( 3786): mNeedToUpdateDate2: false
,W/SystemReader( 3954): Cannot find support_china_sense_feature, use default value instead
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1525): sku_id=118
D/MsgPreferenceUtils( 3786): def_index: 0
,D/MsgPreferenceUtils( 3786): globalIndex = 1
,D/MsgPreferenceUtils( 3786): phone state: true
,D/MsgPreferenceUtils( 3786): sd state: false
D/MsgPreferenceUtils( 3786): vIndex = 0
,I/WorldClock.AlarmUtils( 3954): saveSupportOffAlarmInPreference: isSupport = false
,I/ActivityManager(  958): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3990 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a
,I/WorldClock.AlarmService( 3954): isDeviceEncryptionEnabled = false
D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/AccFlag ( 1525): device_type: 1
,D/PMS     (  958): releaseWL(1d934540): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/AccFlag ( 1525): sku_id=118
I/ActivityManager(  958): Killing 2816:com.htc.contacts/u0a38 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=2816
,D/MediaScanner( 3746): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/WorldClock.AlarmService( 3954): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
,I/art     (  408): Explicit concurrent mark sweep GC freed 8625(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 188us total 19.852ms
,I/WorldClock.AlarmUtils( 3954): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 146us total 16.085ms
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 120us total 15.238ms
,I/ActivityManager(  958): Recipient 2816,
,D/TransactionService( 3786): Force clearing mTransactionList
D/TransactionService( 3786): Force set service start id to 1
V/TransactionService( 3786): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 3786): unRegisterForConnectionStateChanges
D/TransactionService( 3786): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 3786): Destroying TransactionService
,V/TransactionService( 3786): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/WorldClock.AlarmUtils( 3954): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 3954): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1220): receive(android.intent.action.ALARM_CHANGED,1,false)
,I/WorldClock.AlarmUtils( 3954): isDeviceEncryptionEnabled = false,
,I/WorldClock.AlarmUtils( 3954): Calculate next off alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmService( 3954): resetStopwatchToDefault
,I/WorldClock.DmdCmd( 3954): This version is general off mode alarm function
,W/WorldClock.DmdCmd( 3954): Conn: fail e = java.io.IOException: No such file or directory
,I/WorldClock.AlarmService( 3954): resetTimerToDefault
,E/UpdateRequestReceiver( 3990): ignoring update request
,E/UpdateRequestReceiver( 3990): ignoring update request,
,E/UpdateRequestReceiver( 3990): ignoring update request,
,E/UpdateRequestReceiver( 3990): ignoring update request,
,E/UpdateRequestReceiver( 3990): ignoring update request,
,E/UpdateRequestReceiver( 3990): ignoring update request,
,I/ActivityManager(  958): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=4040 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
D/Process (  958): killProcessQuiet, pid=3484
I/ActivityManager(  958): Killing 3484:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/AutoSetting( 1498): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1498): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1498): service - requestNLP() NetworkLocationProvider not enabled
,I/ActivityManager(  958): Recipient 3484
,I/DeviceManagement( 4040): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4040 dbg=false s=true,
,I/DeviceManagement( 4040): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
,I/DeviceManagement( 4040): WorkflowService: Starting workflow service,
,I/DeviceManagement( 4040): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@1dfc4301] args=[Bundle[EMPTY_PARCEL]],
I/DeviceManagement( 4040): BootCompletedWorkflow: ==================================================,
I/DeviceManagement( 4040): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 4040): BootCompletedWorkflow: ==================================================
,I/DeviceManagement( 4040): ModelRegistry: Loading model meta data from resources...,
,I/GoogleHttpClient( 1881): GMS http client unavailable, use old client
V/SmsReceiverService( 3786): updateNotificationAndShortcutStatus: 
,D/MessagingNotification( 3786): New incoming message, can't cancel notification now
D/MessagingNotification( 3786): newMsgCnt: 0, false
,I/ActivityManager(  958): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=4064 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  958): killProcessQuiet, pid=3505,
I/ActivityManager(  958): Killing 3505:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17,
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/DeviceManagement( 4040): BackgroundController: *** Update after boot...,
,I/DeviceManagement( 4040): SessionStateController: Checking invariants...
,I/ActivityManager(  958): Recipient 3505,
,I/DeviceManagement( 4040): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 4040): SessionStateController: Checking invariants...,
,D/MediaScanner( 3746):  prescan time: 399ms
,D/MediaScanner( 3746):     scan time: 488ms
D/MediaScanner( 3746): postscan time: 2ms
D/MediaScanner( 3746):    total time: 889ms
D/MediaScanner( 3746): -----------------------------------------------------------------
D/MediaScanner( 3746): firstscan(media) time: 298ms,
D/MediaScanner( 3746): secondscan(non-media) time: 190ms
D/MediaScanner( 3746):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3746):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3746):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
,D/MediaScanner( 3746):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,D/MediaProvider( 3746): [delete][10]
D/MediaProvider( 3746): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,I/DeviceManagement( 4040): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,D/PMS     (  958): releaseWL(13d19526): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
D/MediaProvider( 3746): [recoverParentNodes] - 0
,D/MediaProvider( 3746): [update][6]
D/MediaScannerServiceEx( 3746): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3746): [updateImage]+
,D/MediaScannerServiceEx( 3746): [updateImage]-0,
D/PMS     (  958): releaseWL(15e637ca): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3746): [3] scan finished
,D/MediaProviderUtils( 3746): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3746): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3746): calcVolumeId: /storage/usb
,D/MediaScannerServiceEx( 3746): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3746): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 3746): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3746): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3746): [update][7]#1#
,I/htcbackup-core( 4064): ModelRegistry: Loading model meta data from resources...
,D/MediaProvider( 3746): [update][18]#0#
,D/MediaScannerServiceEx( 3746): [disAliveExtStorageRows]--1, 0
,D/MediaProviderUtils( 3746): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3746): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3746): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3746): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3746): Process mounted intent for unmounted storage: /storage/usb
,D/MediaScannerServiceEx( 3746): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3746): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3746): [update][2]#1#
,D/MediaProvider( 3746): [update][13]#0#,
D/MediaScannerServiceEx( 3746): [disAliveExtStorageRows]--1, 0
,I/DeviceManagement( 4040): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
,I/DeviceManagement( 4040): ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup]
,I/ActivityManager(  958): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4093 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/DeviceManagement( 4040): Perf: *** Cache update - start...
I/DeviceManagement( 4040): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 4040): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
I/DeviceManagement( 4040): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 4040): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 4040): Perf: Scan enabled apps - start...
,I/ActionCombine( 4064): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,I/DeviceManagement( 4040): EnabledAppBuilder: Examining 270 installed apps for DM enabled apps...
,I/ActionCombine( 1307): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true,
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
,I/RemoteViews( 1220): setHTCTheme(com.htc.backup,true,33751145)
,I/DeviceManagement( 4040): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500100, versionName=6.5.853822
,I/RemoteViews( 1220): apply : com.htc.backup 2 15 5 38,
,I/RemoteViews( 1220): setHTCTheme(com.htc.backup,true,33751145)
,W/ResourcesManager( 4040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/DeviceManagement( 4040): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031464, versionName=6.3.860159,
I/ActivityManager(  958): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4120 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
I/RemoteViews( 1220): setHTCTheme(com.htc.backup,true,33751145)
I/ActivityManager(  958): Killing 3527:com.htc.music:mediaplaybackservice/u0a48 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=3527
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/RemoteViews( 1220): apply : com.htc.backup 0 4 3 5
I/RemoteViews( 1220): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1220): apply : com.htc.backup 1 1 9 5,
I/RemoteViews( 1220): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1220): apply : com.htc.backup 1 1 1 5,
I/RemoteViews( 1220): apply : com.htc.backup 1 12 24 50
,I/DeviceManagement( 4040): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444607021, versionName=4.2.857167,
,W/ResourcesManager( 4040): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/DeviceManagement( 4040): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658011289, versionName=7.00.515351
,I/ActivityManager(  958): Recipient 3527
,W/ResourcesManager( 4040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4040): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4040): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 4040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/DeviceManagement( 4040): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001316, versionName=6.5.860193
,D/ResetNotifyBootCompleteReceiver( 1525): userSerialNumber = 0,
D/ResetNotifyBootCompleteReceiver( 1525): Receive bootcomplete intent
D/ResetNotifyBootCompleteReceiver( 1525): isOwnerUser = true
,I/HtcCupdXmlParser( 4120): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory),
,I/ActivityManager(  958): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4144 uid=10155 gids={50155, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityThread( 4120): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,W/ResourceType( 4040): ResTable_typeSpec entry count inconsistent: given 2, previously 1426
,I/DeviceManagement( 4040): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001224, versionName=1.2.853019
,W/ResourcesManager( 4040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/HtcCupdXmlParser( 4120): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory),
,I/DeviceManagement( 4040): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715
,W/ResourcesManager( 4040): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
,W/ResourcesManager( 4040): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/AlarmManager(  958): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  958): [AlarmQueuing] post alarm-list load task
,I/AlarmManager(  958): [AlarmQueuing] init alarm queuing list
,D/QXDM2SD:HtcNative( 1525): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,I/ActivityManager(  958): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4167 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,I/ActivityManager(  958): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4181 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/Process (  958): killProcessQuiet, pid=3551
I/ActivityManager(  958): Killing 3551:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 4040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4040): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4040): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.,
,I/DeviceManagement( 4040): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001208, versionName=2.2.848686,
,I/DeviceManagement( 4040): EnabledAppBuilder: Found 8 DM enabled apps.,
,I/DeviceManagement( 4040): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
,I/DeviceManagement( 4040): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
,I/DeviceManagement( 4040): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,I/DeviceManagement( 4040): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
,I/DeviceManagement( 4040): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity,
,I/DeviceManagement( 4040): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns
,I/DeviceManagement( 4040): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,I/DeviceManagement( 4040): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,I/DeviceManagement( 4040): Perf: Scan enabled apps - complete: 900 ms
,I/DeviceManagement( 4040): Perf: *** Enabled app cache update - complete: 900 ms
,I/DeviceManagement( 4040): Perf: *** Config cache update - start...,
,I/DeviceManagement( 4040): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 4040): ConfigCacheController: *** Updating stale config cache entries...
,I/ActivityManager(  958): Recipient 3551
,I/art     ( 4040): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>,
I/art     ( 4040): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>,
,W/System.err( 4040): Starting the internal HTTP client,
,I/DeviceManagement( 4040): ConfigCacheController: Getting config update from server: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs/versions/c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17/cid/MDoxOjIwMTQtMDEtMDlUMDQ6MTI6MjQuMjMxWg
,I/DeviceManagement( 4040): DeviceClientResource: Active network...
I/DeviceManagement( 4040):   No active network
,I/DeviceManagement( 4040): DeviceClientResourceController: Network is unavailable: code=1010 description=There is no active network.
,I/DeviceManagement( 4040): BackgroundController: *** Network unavailable!
,I/DeviceManagement( 4040): Perf: *** Config cache update - complete: 238 ms
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=1, flag=1, pid=4040, uid=10099, userID:0
,I/DeviceManagement( 4040): Perf: *** Cache update - complete: 1141 ms,
,I/DeviceManagement( 4040): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@1dfc4301]
,I/DeviceManagement( 4040): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1405dce0] args=[Bundle[mParcelledData.dataSize=132]],
I/DeviceManagement( 4040): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 4040): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4040): SessionStateController: Checking invariants...
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 4181): -onCreate()
,I/AlarmManager(  958): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@19095415,
,I/AlarmManager(  958): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@1dd5632a
,I/AlarmManager(  958): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@148e351b,
V/Settings:HtcSettingsApplication( 4181): [4181/4181] onCreate()
I/AlarmManager(  958): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  958): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  958): [AlarmQueuing] add queuing package: com.google.android.location
,I/AlarmManager(  958): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  958): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  958): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  958): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  958): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  958): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  958): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  958): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  958): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
,I/AlarmManager(  958): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  958): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
,I/ActivityManager(  958): Killing 3573:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=3573
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,W/ContextImpl( 4181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  958): Recipient 3573
,I/HtcModeClient( 3265): handler message = 4011,
,E/HtcModeClient( 3265): Check connection and retry 2 times.
,I/art     (  958): Explicit concurrent mark sweep GC freed 9966(514KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.417ms total 153.161ms,
,I/DeviceManagement( 4040): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4040): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1405dce0]
,I/ActivityManager(  958): Start proc com.android.settings:remote for service com.android.settings/.framework.app.HtcIntentService: pid=4213 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/DeviceManagement( 4040): WorkflowService: Stopping workflow service
,D/Process (  958): killProcessQuiet, pid=3605
,I/ActivityManager(  958): Killing 3605:com.htc.HTCSpeaker/u0a54 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 3605
,D/TetherSettings( 4181): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 4181): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4181): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4181): Cust_ConnectToPC   : spcsc>false
,D/        ( 4181): Cust_ConnectToPC   : IPT>true
D/        ( 4181): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4181): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4181): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4181): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4181): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,I/htcbackup-core( 4064): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.11.05 at 12:06:52.457 CET] interval end=[2015.11.12 at 12:06:52.457 CET]
I/SmartNS_Utility( 4181): setISNotification
,V/AlarmManager(  958): sending alarm PendingIntent{38b0f0cd: PendingIntentRecord{18432d82 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=17, w=1447326412457, Int=604800000,
,D/SmartNS_Utility( 4181): usb_cable_connect = 1
D/SmartNS_Utility( 4181): usb_denied = 0
,V/Settings:HtcSettingsApplication( 4213): [4213/4213] onCreate()
,I/SmartNS_PSService( 4181): usb notificaiton:true
,E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 4181): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
,D/SmartNS_Utility( 4181): usb_cable_connect = 1
,I/RemoteViews( 1220): reapply : com.htc.backup 4 38
D/SmartNS_Utility( 4181): usb_denied = 0
I/SmartNS_PSService( 4181): usb notificaiton:true
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1220): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1220): apply : com.htc.backup 1 3 0 5
I/RemoteViews( 1220): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1220): apply : com.htc.backup 1 1 0 5
,I/RemoteViews( 1220): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1220): apply : com.htc.backup 0 2 0 5
I/RemoteViews( 1220): reapply : com.htc.backup 12 50
,I/ActivityManager(  958): Killing 3639:com.htc.lmw/u0a58 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=3639
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1220): setHTCTheme(com.android.settings,true,33751145)
,I/RemoteViews( 1220): apply : com.android.settings 0 11 2 36,
,I/RemoteViews( 1220): reapply : com.android.settings 4 36,
,I/ActivityManager(  958): Recipient 3639,
,D/Process (  958): killProcessQuiet, pid=3674
I/ActivityManager(  958): Killing 3674:com.android.managedprovisioning/u0a63 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  958): Recipient 3674,
,I/ActivityManager(  958): Waited long enough for: ServiceRecord{112c60ef u0 com.google.android.gms/.gcm.GcmService},
,I/ActivityManager(  958): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4239 uid=9987 gids={49987, 9997} abi=arm64-v8a
,D/SmartDim(  958): Init customizeScreenOffDelayClass error,
,W/BroadcastQueue(  958): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{21a86c85 u0 ReceiverList{31a58dfc 958 system/1000/u0 local:2f3afeef}}
,I/SensorManager(  958): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@1c68ccc9, sensor = {Sensor name="Accelerometer Sensor", vendor="hTC Corp.", version=1, type=1, maxRange=39.2266, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  958): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  958): enable: get sensor name = Accelerometer Sensor
,W/SensorService(  958): pid=958, uid=1000
W/SensorService(  958): Active sensors: size = 3
W/SensorService(  958): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  958): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  958): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  958): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1c68ccc9, eanble = 1, strlen(mName) = 36
W/SensorService(  958): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  958): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@cd8754d
W/SensorService(  958): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@25fa7940
W/SensorService(  958): Listener[2] = com.htc.smartdim.sensor_eye@1c68ccc9
W/SensorService(  958): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  958): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@1c68ccc9, sensor = {Sensor name="CM36686 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  958): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  958): enable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  958): pid=958, uid=1000
W/SensorService(  958): Active sensors: size = 4
W/SensorService(  958): Accelerometer Sensor (handle=0x00000000, connections=2)
,W/SensorService(  958): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  958): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  958): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  958): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1c68ccc9, eanble = 1, strlen(mName) = 36
W/SensorService(  958): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  958): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@cd8754d
W/SensorService(  958): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@25fa7940
W/SensorService(  958): Listener[2] = com.htc.smartdim.sensor_eye@1c68ccc9
W/SensorService(  958): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  958): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4262 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Process (  958): killProcessQuiet, pid=2107
I/ActivityManager(  958): Killing 2107:com.google.android.gms/u0a24 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 2107
,I/SensorManager(  958): dispatchSensorEvent: Proximity = 9.0, mListener = com.htc.smartdim.sensor_eye@1c68ccc9,
,I/ActivityManager(  958): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4283 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
I/ActivityManager(  958): Killing 2772:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=2772
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  408): Explicit concurrent mark sweep GC freed 8684(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 182us total 28.577ms
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 162us total 20.805ms
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 165us total 21.584ms
,I/ActivityManager(  958): Recipient 2772
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4283, uid=10072, userID:0
,W/global  ( 4283): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 4283): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 4283): [apache-http] Connection GC has been deprecated!
,W/global  ( 4283): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 4283): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  958): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4320 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 4283): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4283): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4320): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4320): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4283, uid=10072, userID:0
,I/MultiDex( 4320): VM with version 2.1.0 has multidex support
,I/MultiDex( 4320): install
I/MultiDex( 4320): VM has multidex support, MultiDex support library is disabled.
,D/Volley  ( 4283): [394] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4283): [400] DiskBasedCache.clear: Cache cleared.
,V/JNIHelp ( 4320): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  958): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4346 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/ActivityManager(  958): Killing 3825:com.htc.cs.pns/u0a71 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=3825
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,W/ActivityThread( 4320): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4320): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f1a6a24: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4320): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  958): Recipient 3825
,D/Finsky  ( 4283): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 4283): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4283): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ResourcesManager( 4346): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4346): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/art     ( 4283): No such thread id for suspend: 35,
I/MultiDex( 4346): VM with version 2.1.0 has multidex support
I/MultiDex( 4346): install
I/MultiDex( 4346): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 4283): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 4346): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 4346): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 4346): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f8f8ea2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4346): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  958): Killing 3860:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,D/Process (  958): killProcessQuiet, pid=3860
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  958): Recipient 3860
,V/GLSUser ( 1881): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED,
,D/PMS     (  958): acquireWL(1bfad9ad): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1881 10024 null
,V/GmsCoreStatsServiceLauncher( 4346): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) },
,I/NotificationStore( 1881): System rebooted after Notification storage file was last written
,I/NotificationStore( 1881): Deleting the file
,D/PMS     (  958): releaseWL(1bfad9ad): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,I/ActivityManager(  958): Killing 3882:com.htc.showme/u0a81 (adj 15): empty #17,
,D/Process (  958): killProcessQuiet, pid=3882
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
V/Finsky  ( 4283): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/ActivityManager(  958): Recipient 3882
,D/PersistentNotificationBroadcastReceiver( 1881): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/InstanceID/Rpc( 4346): Found 10024
,D/FileApkUtils( 4346): Spent 25ms computing apk sha1.
,D/FileApkUtils( 4346): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 4346): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 4346): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 4346): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971
,D/GmsModuleFndr( 4346): Beginning GMS chimera module scan
,D/PMS     (  958): acquireWL(20c2a0cf): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4346 10024 null
,W/asset   ( 4346): Copying FileAsset 0x55b2f8ac50 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.
,D/PMS     (  958): acquireWL(2ef7ba5c): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4346 10024 WorkSource{10024 com.google.android.gms},
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1881, uid=10024, userID:0
,I/ActivityManager(  958): Delay finish: com.google.android.gms/.nearby.sharing.NearbySharingBroadcastReceiver
,D/GmsModuleFndr( 4346): Module pkg com.google.android.apps.kids.familylink not installed, skipping
,D/ChimeraCfgMgr( 4346): Beginning module configuration check
,D/ChimeraCfgMgr( 4346): Module APKs unchanged, check complete
,I/ActivityManager(  958): Resuming delayed broadcast
,D/PMS     (  958): acquireWL(3cade3a): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4346 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(12f7dee1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4346 10024 null
,D/GCM     ( 4346): COMPAT: Multi user not supported
,D/PMS     (  958): acquireWL(1c78a406): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4346 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1881): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/PMS     (  958): acquireWL(37b2881d): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4346 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(2ef7ba5c): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(20c2a0cf): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  958): releaseWL(1c78a406): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 4346): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}],
I/CheckinService( 4346): Disabling old GoogleServicesFramework version
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4346, uid=10024, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4346, uid=10024, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4346, uid=10024, userID:0
,D/PMS     (  958): acquireWL(1a5cb060): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1814 10024 WorkSource{10024 com.google.android.gms},
,I/GCoreUlr( 1814): DispatchingService.onCreate()
,I/ActivityManager(  958): Delay finish: com.google.android.gms/.tron.AlarmReceiver
,D/SystemUpdateService( 4346): onCreate
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4346, uid=10024, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4346, uid=10024, userID:0,
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4346, uid=10024, userID:0
D/SystemUpdateService( 4346): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/CheckinService( 4346): Checking schedule, now: 1457427847891 next: 1456765623471
,I/CheckinService( 4346): active receiver: enabled
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4346, uid=10024, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4346, uid=10024, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4346, uid=10024, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4346, uid=10024, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4346, uid=10024, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4346, uid=10024, userID:0,
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4346, uid=10024, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4346, uid=10024, userID:0,
I/ConfigService( 1881): onCreate
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4346, uid=10024, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4346, uid=10024, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4346, uid=10024, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4346, uid=10024, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4346, uid=10024, userID:0
,D/PMS     (  958): acquireWL(1d60a645): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4346, uid=10024, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4346, uid=10024, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4346, uid=10024, userID:0
,I/ConfigFetchService( 4346): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,V/AuthZen ( 4346): Handling intent: android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 4346): Handling event: android.intent.action.BOOT_COMPLETED
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4346, uid=10024, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4346, uid=10024, userID:0
,I/SystemUpdateService( 4346): cancelUpdate (empty URL)
,I/SystemUpdateService( 4346): active receiver: disabled
,W/System.err(  958): java.lang.Throwable: stack dump
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  958): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7ea61c1:true
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4346, uid=10024, userID:0
W/System.err(  958): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  958): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
,W/System.err(  958): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
,D/PMS     (  958): acquireWL(1bfa58fd): PARTIAL_WAKE_LOCK  Icing 0x1 4346 10024 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1814): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/art     ( 4346): Background sticky concurrent mark sweep GC freed 571(32KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 4MB/4MB, paused 6.777ms total 30.295ms,
,D/PMS     (  958): releaseWL(1bfa58fd): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1814, uid=10024, userID:0
,W/BaseAppContext( 4346): Using Auth Proxy for data requests.
,I/art     ( 1814): Explicit concurrent mark sweep GC freed 23178(1390KB) AllocSpace objects, 4(80KB) LOS objects, 46% free, 4MB/8MB, paused 2.292ms total 75.203ms,
I/ConfigFetchService( 4346): service connected
,I/ActivityManager(  958): Resuming delayed broadcast
D/PMS     (  958): releaseWL(1a5cb060): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(3cade3a): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10024 com.google.android.gms}
,I/art     ( 1881): Explicit concurrent mark sweep GC freed 6497(392KB) AllocSpace objects, 6(120KB) LOS objects, 51% free, 3MB/7MB, paused 1.433ms total 46.787ms
,I/GLSUser ( 4346): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 4346): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/AuthZen ( 4346): Fetching signing key...
,I/AuthZen ( 4346): Signing key fetched successfully!,
,W/BaseAppContext( 4346): Using Auth Proxy for data requests.
,I/AuthZen ( 4346): Starting Enrollment...
,D/AuthZen ( 4346): getting auth token. Attempt 0
,I/art     (  958): Explicit concurrent mark sweep GC freed 17655(955KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 15MB/23MB, paused 1.129ms total 125.124ms
,D/PMS     (  958): releaseWL(37b2881d): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/SystemUpdateService( 4346): onDestroy
,D/ChimeraCfgMgr( 4346): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4346): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/ConfigFetchService( 4346): ConfigApi connection successful.
,I/ActivityManager(  958): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4443 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/GLSActivity( 1881): [ac] getting account id
,I/art     (  409): Explicit concurrent mark sweep GC freed 8680(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 326us total 19.558ms
,I/GLSUser ( 1881): [ChannelManager] Attempting to channel bind connection HttpClient.,
,I/GLSUser ( 1881): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 278us total 16.390ms,
,W/ResourcesManager( 4443): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GCoreUlr( 1814): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]},
D/PMS     (  958): acquireWL(28bc19dd): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  958): releaseWL(28bc19dd): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 234us total 14.523ms
,I/GCoreUlr( 1814): Unbound from all location providers
,I/GLSUser ( 1881): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/PMS     (  958): releaseWL(1d60a645): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSUser ( 1881): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,I/GLSUser ( 1881): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1881): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1881): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1814): DispatchingService.onDestroy()
,D/PMS     (  958): acquireWL(5e68952): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(5e68952): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,I/GCoreUlr( 1814): Unbound from all location providers
,E/AuthZen ( 4346): Error getting auth token
E/AuthZen ( 4346): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4346): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4346): 	,at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4346): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4346): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4346): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4346): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 4346): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 4346): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4346): ,	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4346): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4346): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4346): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4346): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4346): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/a       ( 4346): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 4346): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 4346): Clearing transaction cache
,D/PMS     (  958): acquireWL(cbfe89e): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 958 1000 null
D/PMS     (  958): releaseWL(cbfe89e): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/Babel_SMS( 4443): MmsConfig: mnc/mcc: 0/0,
,I/Babel_SMS( 4443): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 3786): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3786): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 4443): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml,
,I/Babel_SMS( 4443): MmsConfig.loadFromDatabase
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4443, uid=10112, userID:0
,E/Babel_SMS( 4443): canonicalizeMccMnc: invalid mccmnc ,
I/Babel_SMS( 4443): MmsConfig.loadFromResources
,E/Babel_SMS( 4443): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4443): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,W/Settings( 4443): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4443): startup - clean,
,I/Babel   ( 4443): deleted: false for 0,
,W/art     ( 4443): Suspending all threads took: 9.680ms,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4443, uid=10112, userID:0,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4443, uid=10112, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4443, uid=10112, userID:0,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4443, uid=10112, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4443, uid=10112, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4443, uid=10112, userID:0,
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4443, uid=10112, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4443, uid=10112, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4443, uid=10112, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4443, uid=10112, userID:0
,W/VideoCapabilities( 4443): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 4443): Unsupported mime video/x-ms-wmv
,W/Utils   ( 4443): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 4443): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4443): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4443): Unsupported mime audio/qcelp
,W/VideoCapabilities( 4443): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 4443): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4443): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4443): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4443): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4443): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4443): onServiceConnected
W/Babel   ( 4443): Attempted to change video mute state without an active call.
,I/ActivityManager(  958): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4475 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/ResourcesManager( 4475): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4475): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,V/JNIHelp ( 4475): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 4475): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4475): Installed default security provider GmsCore_OpenSSL,
,E/cutils-trace( 4507): Error opening trace file: Permission denied (13),
I/dex2oat ( 4507): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-205820474.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads-205820474.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4507): dex2oat: override thread count:4
,I/ActivityManager(  958): Waited long enough for: ServiceRecord{1fe6ad7e u0 com.htc.autobot/.htcmodeclient.HtcModeService},
,I/dex2oat ( 4507): dex2oat took 53.372ms (threads: 4),
,E/YouTube MDX( 4475): Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
,D/libc    ( 4475): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
,D/libc    ( 4475): [NET] android_getaddrinfofornet-, SUCCESS
,W/art     ( 4475): Suspending all threads took: 6.170ms,
,D/VoldConnector(  958): SND -> {11 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
W/ContextImpl( 4475): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,I/HtcModeClient( 3265): handler message = 4011
,E/HtcModeClient( 3265): Check connection and retry 3 times.
,D/VoldConnector(  958): SND -> {12 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 4475): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  958): SND -> {13 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/ContextImpl( 4475): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,D/VoldConnector(  958): SND -> {14 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/ContextImpl( 4475): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 4475): Found 10024
,D/VoldConnector(  958): SND -> {15 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 4475): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
,V/AlarmManager(  958): sending alarm PendingIntent{394bdc: PendingIntentRecord{15aa84e5 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=54917, Int=259200000
V/AlarmManager(  958): sending alarm PendingIntent{2da85a6b: PendingIntentRecord{15fd49c8 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457427849906, Int=0
,I/ActivityManager(  958): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4556 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  958): killProcessQuiet, pid=3906
I/ActivityManager(  958): Killing 3906:com.htc.feedback/u0a83 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/iu.UploadsManager( 4346): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400,
,I/ActivityManager(  958): Recipient 3906,
,I/iu.UploadsManager( 4346): End new media; added: 0, uploading: 0, time: 255 ms
,W/ActivityManager(  958): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4556): getAccountsCursor,
,W/GAV2    ( 4556): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4556, uid=10106, userID:0,
W/ActivityManager(  958): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 4556): Observing account changes for notifications
,W/ActivityManager(  958): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4556, uid=10106, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4556, uid=10106, userID:0
,W/ActivityManager(  958): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,E/Gmail   ( 4556): Error finding the version of the Email provider.....,
E/Gmail   ( 4556): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4556): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4556): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4556): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4556): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4556): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4556): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4556): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4556): We do not support migrating this version of the Email provider.
,I/Gmail   ( 4556): getAccountsCursor,
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4556, uid=10106, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4556, uid=10106, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4556, uid=10106, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4556, uid=10106, userID:0,
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  958): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4599 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,W/ActivityManager(  958): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4556, uid=10106, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4556, uid=10106, userID:0
W/ActivityManager(  958): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 4556): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@180e5592 that was originally bound here
E/ActivityThread( 4556): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@180e5592 that was originally bound here
E/ActivityThread( 4556): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4556): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4556): 	,at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 4556): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 4556): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4556): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4556): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4556): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4556): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4556): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4556): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4556): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4556): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4556): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4556): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4556): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  958): Unbind failed: could not find connection for android.os.BinderProxy@19a059c5
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/SQLiteLog( 4556): (283) recovered 1515 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 4556): notifyAccountChanged,
,I/Gmail   ( 4556): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4556): getAccountsCursor,
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4556): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4556): calculateUnknownSyncRationalesAndPurgeInBackground: running,
,I/Gmail   ( 4556): calculateUnknownSyncRationalesAndPurgeInBackground: running,
,I/art     (  958): Explicit concurrent mark sweep GC freed 12235(648KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 15MB/23MB, paused 1.318ms total 161.158ms
,D/PMS     (  958): acquireWL(1723c772): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4556 10106 null
I/Gmail   ( 4556): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,D/PMS     (  958): acquireWL(1723c772): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4556 10106 null
,I/Gmail   ( 4556): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,D/PMS     (  958): acquireWL(1723c772): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4556 10106 null,
,I/Gmail   ( 4556): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4556, uid=10106, userID:0
,D/Process (  958): killProcessQuiet, pid=3928
I/ActivityManager(  958): Killing 3928:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 3928
,D/LocationManagerService(  958): getProviders()=[passive]
,I/ActivityManager(  958): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4631 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/Gmail   ( 4556): master sync=false, engine sync=true,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4599, uid=10085, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4599, uid=10085, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4599, uid=10085, userID:0
,I/Gmail   ( 4556): getAccountsCursor,
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4556): master sync=false, engine sync=true
,E/AndroidHttpClient( 4283): Leak found,
E/AndroidHttpClient( 4283): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4283): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4283): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4283): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4283): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4283): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4283): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4283): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4283): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4283): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4283): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4283): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4283): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4283): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4283): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4283): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4283): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/WifiTrafficPoller(  958): ADD_CLIENT: 6,
D/WifiService(  958): New client listening to asynchronous messages
W/BroadcastQueue(  958): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/VelvetNetworkClient( 4599): Network connection not availble,
,I/ActivityManager(  958): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4668 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  958): Killing 3954:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,D/Process (  958): killProcessQuiet, pid=3954
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  958): Recipient 3954
,D/GCM     ( 1881): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1881): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4346): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  958): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4693 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4346, uid=10024, userID:0
,I/WebViewFactory( 4599): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,W/ResourcesManager( 4693): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
,W/ResourcesManager( 4693): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AccFlag ( 1525): sku_id=118
,I/MultiDex( 4693): VM with version 2.1.0 has multidex support
I/MultiDex( 4693): install
I/MultiDex( 4693): VM has multidex support, MultiDex support library is disabled.
I/LibraryLoader( 4599): Time to load native libraries: 16 ms (timestamps 7740-7756)
,I/LibraryLoader( 4599): Expected native library version number "",actual native library version number "",
I/ActivityManager(  958): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4718 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,D/LocationInitializer( 4346): Restart initialization of location
,W/art     ( 4599): Attempt to remove local handle scope entry from IRT, ignoring
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 89
,D/AccFlag ( 1525): sku_id=118
,V/JNIHelp ( 4693): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 73,
D/AccFlag ( 1525): sku_id=118
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 94
D/AccFlag ( 1525): sku_id=118
,W/ActivityThread( 4693): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4693): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f1a6a24: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4693): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 4693): callingUid 10024, callindPid: 4693
,E/MDM     ( 1814): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/art     ( 4599): Attempt to remove local handle scope entry from IRT, ignoring,
,D/Process (  958): killProcessQuiet, pid=3990,
I/ActivityManager(  958): Killing 3990:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ImageRamCache( 4718): create image Cache, size: 31457280.
I/ImageRamCache( 4718): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4718): create image Cache, size: 31457280.
,I/FeedSettings( 4718): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 4718): GroupBudget 0.500000 0.380000
I/FeedSettings( 4718): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4718): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4718): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 4718): loadGridSize() with Alternative
,I/ActivityManager(  958): Recipient 3990,
,D/CustomHighlightReceiver( 4718): [custom highlight] onReceive
,D/CustomHighlightService( 4718): [custom highlight] onHandleIntent
,D/NewsDB  ( 4718): set custom highlight [],
,I/ActivityManager(  958): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4762 uid=10035 gids={50035, 9997} abi=arm64-v8a,
,D/CustomHighlightService( 4718): [custom highlight] set tags ,
,D/Process (  958): killProcessQuiet, pid=4093
I/ActivityManager(  958): Killing 4093:com.htc.backupreset/1000 (adj 15): empty #17,
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 4093,
,D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC <<,
,I/ActivityManager(  958): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4785 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/Process (  958): killProcessQuiet, pid=4120
I/ActivityManager(  958): Killing 4120:com.htc.htccupd/u0a13 (adj 15): empty #17
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  408): Explicit concurrent mark sweep GC freed 8654(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 219us total 27.560ms
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 165us total 23.148ms
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 175us total 21.547ms
,I/ActivityManager(  958): Recipient 4120,
,D/SMSBackup( 4785): Got a database change event
,I/ActivityManager(  958): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4806 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/Process (  958): killProcessQuiet, pid=4167
I/ActivityManager(  958): Killing 4167:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 4167
,D/MessagingShortcutReceiver( 3786): keep hiding shortcut bubble,
,D/MessagingShortcut( 3786): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 3786): After query: 0,
,D/MessagingShortcut( 3786): mPresentUnreadCount: -1
D/MessageUtils( 3786): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 3786): setMsgShortcutDrawable> 0, false
D/MessagingShortcut( 3786): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderNotification, total:0
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  958): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4828 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,W/ResourcesManager( 4828): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  958): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4851 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/TodoTaskshortcut( 4828): update TASK shortcut>,
,I/ActivityManager(  958): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  958): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1498): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1498): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1577): action: android.intent.action.PACKAGE_ADDED
D/Process (  958): killProcessQuiet, pid=4040
I/ActivityManager(  958): Killing 4040:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MdScBootUi( 4806): [ace.1.2.] boot 118,
,D/MdScBoot( 4806): [ace.1.] 30@-090343 -> 40
,D/MdScSimSt( 4806): [ace.1.2.] qry 118: 0+1 running 0
,D/PMS     (  958): releaseWL(1723c772): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null,
,I/ActivityManager(  958): Recipient 4040
,W/BroadcastQueue(  958): Exception when sending broadcast to ComponentInfo{com.htc.cs.dm/com.htc.cs.dm.receiver.PackageUpdateReceiver},
,W/BroadcastQueue(  958): android.os.DeadObjectException
W/BroadcastQueue(  958): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  958): 	at android.os.BinderProxy.transact(Binder.java:504)
W/BroadcastQueue(  958): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:921)
W/BroadcastQueue(  958): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:254)
W/BroadcastQueue(  958): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:989)
W/BroadcastQueue(  958): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17013)
W/BroadcastQueue(  958): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:475)
W/BroadcastQueue(  958): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/BroadcastQueue(  958): 	,at android.os.Binder.execTransact(Binder.java:454)
W/libprocessgroup(  958): failed to open /acct/uid_10099/pid_4040/cgroup.procs: No such file or directory
,I/ActivityManager(  958): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4881 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,W/ActivityManager(  958): Spurious death for ProcessRecord{5a7d385 4881:com.htc.cs.dm/u0a99}, curProc for 4040: null
,I/DeviceManagement( 4881): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4881 dbg=false s=true,
,I/DeviceManagement( 4881): PackageUpdateReceiver: vvv Package added: [com.example.hello],
,D/Process (  958): killProcessQuiet, pid=4213
I/ActivityManager(  958): Killing 4213:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  958): Recipient 4213,
,I/ActivityManager(  958): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4904 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/Process (  958): killProcessQuiet, pid=4239,
I/ActivityManager(  958): Killing 4239:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  958): Recipient 4239,
,W/Atfwd_Sendcmd(  445): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/Process (  958): killProcessQuiet, pid=4262,
I/ActivityManager(  958): Killing 4262:com.android.smith/1000 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 4262,
,D/HtcCupdReceiver(Provider)( 4904):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED,
,D/Process (  958): killProcessQuiet, pid=4320,
I/ActivityManager(  958): Killing 4320:com.google.android.gms:car/u0a24 (adj 15): empty #17
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/Settings:HtcWirelessFeatureFlags( 4181): id/is att sku: 118/false,
,E/Settings:HtcWrapHeaderInfo( 4181): no such activity!,
,I/ActivityManager(  958): Recipient 4320,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4181): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4181): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4181): isSupportMusicChannel(): false,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportHomeButton]support         :false
,D/PackageBroadcastService( 4346): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,E/Settings:HtcVoWifiWidgetEnabler( 4181): isSupportVoWifi: null
I/ActivityManager(  958): Cannot resolve ContentProvider=com.htc.vowifi
D/ChimeraCfgMgr( 4346): Loading module com.google.android.gms.games from APK com.google.android.play.games,
E/ActivityThread( 4181): Failed to find provider info for com.htc.vowifi
D/ChimeraModuleLdr( 4346): Loading module APK com.google.android.play.games
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4181): The wrap header doesn't exist in header list.
,D/PMS     (  958): acquireWL(2df360e8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4346 10024 null
,E/Settings:HtcWrapHeaderInfo( 4181): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4181): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4181): [supportHomeButton]support         :false
,E/Settings:HtcVoWifiWidgetEnabler( 4181): isSupportVoWifi: null,
I/ActivityManager(  958): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4181): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  958): Waited long enough for: ServiceRecord{219aa484 u0 com.htc.HTCSpeaker/.NGFService},
,I/ConfigFetchService( 4346): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
,I/ConfigFetchService( 4346): launchTask,
D/PMS     (  958): acquireWL(1611a394): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4346 10024 WorkSource{10374 com.example.hello}
,D/PMS     (  958): releaseWL(2df360e8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  958): acquireWL(1dd1ee3d): PARTIAL_WAKE_LOCK  Icing 0x1 4346 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4346): Loading module com.google.android.gms.games from APK com.google.android.play.games,
D/ChimeraModuleLdr( 4346): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4346): Loading module com.google.android.gms.vision from APK com.google.android.gms,
,V/ConfigFetchTask( 4346): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WKcWMWvCU23ME-060oMI-0Nt2IjOb3iC_tLRYeRUCexn4OtPmmJcXEgqD3ZCQtJ-bFpFS_Ud9Gl0JMrv656wJP4FJRw9Yser-Q7_IOhdj7HzT8Olja7A3gGIHINz5t70wYo6olADobN6Ier3TB-mXNIhOx9wtE1MCFa8SbOLKn9wnkIVvfXavfqa9XQEjp-EPn0pB_
I/PeopleContactsSync( 4346): CP2 sync disabled
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4346, uid=10024, userID:0
,D/Vision  ( 4346): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 4346): Failed to find package metadata for com.example.hello
D/Vision  ( 4346): No vision deps
,I/GoogleURLConnFactory( 4346): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  958): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4938 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/Icing   ( 4346): Storage manager: low false usage 2.04MB avail 5.80GB capacity 7.95GB,
,W/Icing   ( 4346): Received bad json for section weights override -- ignoring.,
,D/libc    ( 4346): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4346): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4346): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4346): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4346): [NET] android_getaddrinfo_proxy+
D/libc    ( 4346): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4346): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4346): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname,
,I/ConfigFetchService( 4346): fetch service done; releasing wakelock,
I/ConfigFetchService( 4346): stopping self
D/PMS     (  958): releaseWL(1611a394): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10374 com.example.hello}
,W/Icing   ( 4346): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4346): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4346): Received bad json for corpus context scoring override -- ignoring.
,W/BaseAppContext( 4346): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4346): Using Auth Proxy for data requests.
,E/Icing   ( 4346): Loading extension by file descriptor -1 failed,
,I/art     ( 1881): Explicit concurrent mark sweep GC freed 10158(561KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 830us total 48.730ms
,W/BaseAppContext( 4346): Using Auth Proxy for data requests.
,W/BaseAppContext( 4346): Using Auth Proxy for data requests.
,W/BaseAppContext( 4346): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4346): Using Auth Proxy for data requests.
,I/Icing   ( 4346): updateResources: need to parse f{com.google.android.gms}
,I/GAv4    ( 4938): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4938):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4938):   adb logcat -s GAv4
,W/GAv4    ( 4938): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,I/art     (  958): Explicit concurrent mark sweep GC freed 12115(599KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.197ms total 129.150ms
,W/GAv4    ( 4938): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/Icing   ( 4346): Internal init done: storage state 0
,W/GAv4    ( 4938): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Icing   ( 4346): Post-init done
,D/PMS     (  958): releaseWL(1dd1ee3d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/AnalyticsTrackerProxyImpl( 4938): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45,
,I/HtcModeClient( 3265): handler message = 4011,
E/HtcModeClient( 3265): Check connection and retry 4 times.
,W/art     ( 4938): Suspending all threads took: 6.460ms,
,D/VoldConnector(  958): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 4938): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,I/ActivityManager(  958): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4979 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Process (  958): killProcessQuiet, pid=4475
I/ActivityManager(  958): Killing 4475:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,W/ResourcesManager( 4938): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4938): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 4346): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4346): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  958): Recipient 4475
,W/ResourcesManager( 4979): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 4938): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 4938): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4938): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 4556): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 4346): Google Analytics 7.8.99 is starting up.
,D/PMS     (  958): acquireWL(25a0c82e): PARTIAL_WAKE_LOCK  AsyncService 0x1 4979 10167 null,
,D/PMS     (  958): acquireWL(455dd5c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 4979 10167 null
,D/PMS     (  958): releaseWL(25a0c82e): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  958): releaseWL(455dd5c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/PMS     (  958): acquireWL(e75393a): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4828 10069 null
,D/PMS     (  958): acquireWL(1c3539eb): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4828 10069 null,
,D/PMS     (  958): releaseWL(e75393a): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 4828): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference,
W/System.err( 4828): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 4828): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4828): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 4828): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4828): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PMS     (  958): releaseWL(1c3539eb): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4828): stopSelfResult true
,I/UpdateIcingCorporaServi( 4599): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/PMS     (  958): acquireWL(273e35e1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms},
,D/MtpReceiver( 3746): [MTP][handleUsbStateAsync]+,
D/MtpReceiver( 3746): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3746): [MTP][handleUsbState]+
,I/ActivityManager(  958): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5021 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
D/MtpReceiver( 3746): [MTP][scanExternalVolumeIfNeed] scan external volume
D/PMS     (  958): releaseWL(273e35e1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/MtpReceiver( 3746): [MTP][handleUsbState]-
D/MtpReceiver( 3746): [MTP][handleMessage]-
,D/MtpService( 3746): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 3746): TotalSize=1886532,MediaCacheLimit=6000
,D/MtpService( 3746): [isMtpConnected] connected: true
,W/asset   ( 4599): Copying FileAsset 0x55b2fc6740 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/UpdateIcingCorporaServi( 4599): UpdateCorporaTask done [took 101 ms] updated apps [took 101 ms] 
,D/Process (  958): killProcessQuiet, pid=4556
I/ActivityManager(  958): Killing 4556:com.google.android.gm/u0a106 (adj 15): empty #17,
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/MediaScannerService( 3746): [onStartCommand] --- Should not be here, redirect request. ----,
E/MediaScannerService( 3746): [handleMessage] --- Should not be here, ignore request. ----
,I/ActivityManager(  958): Recipient 4556
,D/SyncApplication( 5021): Loading default preferences
,W/Resources( 5021): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,E/WifiTrafficPoller(  958): ADD_CLIENT: 7,
D/WifiService(  958): New client listening to asynchronous messages
,D/SyncApplication( 5021): Overriding preferences with custom values,
,D/SyncApplication( 5021): Updating preferences succeeded,
,E/SyncApplication( 5021): Application created.,
,W/VolumeInfo( 5021): Unable to read mount points,
W/VolumeInfo( 5021): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5021): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5021): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5021): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5021): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5021): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5021): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5021): ,	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5021): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5021): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5021): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5021): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5021): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5021): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5021): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5021): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5021): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5021): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5021): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5021): 	,... 13 more
I/CalendarDefines( 5021): getNewCalendarAuthority()...
,V/VolumeInfo( 5021): Found 0 mount point(s)
,V/VolumeInfo( 5021): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5021, uid=10005, userID:0
D/SyncApplication( 5021): enableAppOperation()+
W/PackageManager(  958): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
E/MediaScannerServiceEx( 3746): [getStorageMaskIdFromPath] path is null
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5021, uid=10005, userID:0
D/MediaScannerServiceEx( 3746): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
W/PackageManager(  958): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 5021): enableAppOperation()-
D/VolumeInfo( 5021): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/MediaScannerServiceEx( 3746): [handleExternalVolume] ext storage
,D/HTCUtilities( 5021): isNeorSinged() + 
D/MediaProviderUtils( 3746): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3746): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3746): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3746): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3746): [AliveExtStorageRows]+65537, 11223344
,D/VolumeInfo( 5021): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 5021): Can not create volume ID for unmounted volume null
,D/MediaProvider( 3746): [update][6]#0#
,D/MediaProvider( 3746): [update][2]#0#
,D/HTCUtilities( 5021): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 5021): isNeorSinged() return false
,D/CDMountReceiver( 5021): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 5021): USB connected to PC
,D/MediaProvider( 3746): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3746): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3746): [update][23]#1#
,D/MediaScannerServiceEx( 3746): [AliveExtStorageRows]-0, 0
,D/PMS     (  958): acquireWL(2c89eabf): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3746 10017 null
,D/FOTAReceiver( 5021): onReceive() enter 
,D/FOTAReceiver( 5021): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/MediaScanner( 3746): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,D/TetherSettings( 4181): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4181): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4181): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 4181): Cust_ConnectToPC   : spcsc>false
D/        ( 4181): Cust_ConnectToPC   : IPT>true
D/        ( 4181): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4181): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4181): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4181): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4181): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4181): usb_cable_connect = 1
D/SmartNS_Utility( 4181): usb_denied = 0
,I/SmartNS_NSReceiver( 4181): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 4181): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 4181): onReceive:com.htc.intent.action.USB_CONNECT2PC,
,W/ContextImpl( 4181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_PSService( 4181): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 4181): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
I/SmartNS_PSService( 4181):  defaultType:0
I/SmartNS_PSService( 4181): fail notificaiton:false,
D/SmartNS_Utility( 4181): usb_cable_connect = 1
D/SmartNS_Utility( 4181): usb_denied = 0
,I/SmartNS_PSService( 4181): usb notificaiton:true
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  958): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5053 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_Utility( 4181): usb_cable_connect = 1
D/SmartNS_Utility( 4181): usb_denied = 0
I/SmartNS_PSService( 4181): usb notificaiton:true
I/RemoteViews( 1220): reapply : com.android.settings 2 36
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 4181): usb_cable_connect = 1,
D/SmartNS_Utility( 4181): usb_denied = 0
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1220): reapply : com.android.settings 1 36
,I/SmartNS_PSService( 4181): KeyGuard locked:falseKeyGuard is secured:false,
,D/SmartNS_PSService( 4181): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/ActivityManager(  958): Killing 4718:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=4718
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 4718,
,W/ContextImpl( 5053): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 ,
,I/ActivityManager(  958): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5077 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/Process (  958): killProcessQuiet, pid=4762
,I/ActivityManager(  958): Killing 4762:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  958): Recipient 4762,
,W/ResourcesManager( 5077): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/Process (  958): killProcessQuiet, pid=4785
I/ActivityManager(  958): Killing 4785:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 4785
,I/CalendarProvider2( 5077): Created com.android.providers.calendar.CalendarAlarmManager@7ea65da(com.htc.providers.calendar.HtcCalendarProvider@2a71fa0b),
,D/CalendarProvider2( 5077): wait start:true,
,D/Process (  958): killProcessQuiet, pid=4806
I/ActivityManager(  958): Killing 4806:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/SocialFeedProvider( 1577): +disConnect socialManager,
I/SocialFeedProvider( 1577): disconnect socialManager
,I/ActivityManager(  958): Recipient 4806,
,I/SocialFeedProvider( 1577): -disConnect socialManager,
,I/ActivityManager(  958): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5101 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,V/AlarmManager(  958): sending alarm PendingIntent{2e546490: PendingIntentRecord{7f2e189 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1457427856790, Int=0
,D/FlexNetS( 5077): updateSvcAllowedInSettings:false
,D/PMS     (  958): acquireWL(3cd901af): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 5077): wait end:false
D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1881): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1881): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1881): [NET] android_getaddrinfo_proxy+
D/libc    ( 1881): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1881): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  958): releaseWL(3cd901af): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  958): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5128 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/art     (  408): Explicit concurrent mark sweep GC freed 8659(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 206us total 26.209ms
,I/ImageRamCache( 5101): create image Cache, size: 31457280.,
I/ImageRamCache( 5101): [resize] ImageRamCache resized to: 30Mb.
,I/ImageRamCache( 5101): create image Cache, size: 31457280.
,I/FeedSettings( 5101): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 5101): GroupBudget 0.500000 0.380000
I/FeedSettings( 5101): GroupBudget 60 45 15
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 181us total 21.506ms
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 165us total 22.343ms
,I/Prism.ExternalStringMa_( 5101): changeLocale(): en_GB
D/MediaProvider( 3746): [update][107]#1#
,D/MediaScanner( 3746):  prescan time: 476ms
D/MediaScanner( 3746):     scan time: 733ms
D/MediaScanner( 3746): postscan time: 3ms
D/MediaScanner( 3746):    total time: 1212ms
D/MediaScanner( 3746): -----------------------------------------------------------------
D/MediaScanner( 3746): firstscan(media) time: 317ms
D/MediaScanner( 3746): secondscan(non-media) time: 416ms
D/MediaScanner( 3746):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3746):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3746):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3746):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,D/MediaProvider( 3746): [delete][12]
I/Prism.AllAppsOptionsMa_( 5101): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 5101): loadGridSize() with Alternative
,D/MediaProvider( 3746): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3746): [recoverParentNodes] - 0,
D/MediaProvider( 3746): [update][13]
D/MediaScannerServiceEx( 3746): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3746): [updateImage]+
,W/ContextImpl( 5128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/MediaScannerServiceEx( 3746): [updateImage]-0
,D/PMS     (  958): releaseWL(2c89eabf): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null,
,D/MediaScannerServiceEx( 3746): [1] scan finished
D/MediaProviderUtils( 3746): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3746): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3746): calcVolumeId: /storage/usb
,D/MediaScannerServiceEx( 3746): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3746): Process mounted intent for unmounted storage: /storage/ext_sd
,D/PMS     (  958): acquireWL(239764f2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5128 1000 null,
,I/SocialManager[SocialBiLogHelper]( 5101): action: com.htc.sense.hsp.HANDLE_ULOG
,I/SocialManager[SocialBiLogHelper]( 5101): last commit ulog time 1457416495541,
I/ActivityManager(  958): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5157 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
I/SocialManager[SocialBiLogHelper]( 5101): skip commit this time
,D/Process (  958): killProcessQuiet, pid=3786
I/ActivityManager(  958): Killing 3786:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PowerUsageList:PowerUsageHelper( 5128): MY_DEBUG = false
D/MediaScannerServiceEx( 3746): [disAliveExtStorageRows]+131073
,D/WeatherUtility( 1498): Weather sync is On
,D/MediaProvider( 3746): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3746): [update][11]#1#
,D/MediaProvider( 3746): [update][23]#0#
,D/MediaScannerServiceEx( 3746): [disAliveExtStorageRows]--1, 0
,I/ActivityManager(  958): Recipient 3786
,D/WSP     ( 1498): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,D/PowerUsageService( 5128): repeat time = 1457428757335
D/MediaProviderUtils( 3746): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3746): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3746): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3746): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3746): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3746): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3746): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3746): [update][9]#1#,
,D/PMS     (  958): acquireWL(95a3ef9): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5077 10011 null
,D/MediaProvider( 3746): [update][32]#0#
,D/MediaScannerServiceEx( 3746): [disAliveExtStorageRows]--1, 0
E/SQLiteLog( 5077): (284) automatic index on view_events(_id)
,I/ActivityManager(  958): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5183 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,D/PMS     (  958): releaseWL(95a3ef9): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/WeatherUtility( 5157): Weather sync is On
,I/ActivityManager(  958): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5204 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/PowerUsageList:PowerUsageHelper( 5128): PowerProfile::POWER_SCREEN_FULL = 154.8
,W/WeatherRequest( 5157): request cur loc, but there is no sys cur
W/Settings( 5157): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ResourcesManager( 5183): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActionCombine( 5157): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/PowerUsageList:BatterySipperExt( 5128): gen(), null == sipper.uidObj, userId = 0
,I/RemoteViews( 1577): reapply : com.htc.widget.weatherclock 9 17
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4346, uid=10024, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4346, uid=10024, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4346, uid=10024, userID:0,
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4346, uid=10024, userID:0
,D/PowerUsageService( 5128): calcPower(), no data,
,D/Process (  958): killProcessQuiet, pid=4443
I/ActivityManager(  958): Killing 4443:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/EASAppSvc( 5204): [ NA ]onCreate
,I/VersionUtil( 5204): [ NA ]setIsFOTAing: true,
,I/VersionUtil( 5204): [ NA ]onUpgrade: current version=100, latest version=100,
,I/VersionUtil( 5204): [ NA ]setIsFOTAing: false
,D/HtcAdjCursorFactory( 5204): Set CursorWindow size to: 4194304 KB, Tid: 5229,
,I/CalendarProvider2( 5077): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
,W/ContentResolver( 5077): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar),
,I/ActivityManager(  958): Recipient 4443
,D/Process (  958): killProcessQuiet, pid=4851,
I/ActivityManager(  958): Killing 4851:com.htc.mobiledata/u0a46 (adj 15): empty #17,
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  958): acquireWL(128fd431): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null,
I/BatteryService(  958): n_update end
D/PMS     (  958): releaseWL(128fd431): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  958): Recipient 4851
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/HtcPowerSaver(  958): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
W/ResourcesManager( 1525): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/AccTypeManager( 1685): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/SystemReader(  958): Cannot find grip_rejection_width, use default value instead
,I/art     (  958): Explicit concurrent mark sweep GC freed 17397(857KB) AllocSpace objects, 2(344KB) LOS objects, 33% free, 16MB/24MB, paused 8.934ms total 230.155ms
,D/ORMLib  ( 4828): put(),
W/Prism.AllAppsManager( 1577): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/ActivityManager(  958): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5239 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/Prism.ItemManager( 1577): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1577): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5101): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5101): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1685): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Launcher( 1577): Deferring update until onResume
D/WifiService(  958): New client listening to asynchronous messages
I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/Launcher( 1577): waitUntilResume // bindAppsUpdated
W/EAS_NetworkUtil( 5204): [ NA ]getNetworkInfo: NetworkInfo is null
,W/ResourcesManager(  958): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PhoneApp( 1525): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  958): Killing 4631:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=4631
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/AccTypeManager( 1685): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/PackageManager(  958): Unable to load service info ResolveInfo{c872e77 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  958): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  958): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  958): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  958): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  958): 	at android.os.Looper.loop(Looper.java:155),
W/PackageManager(  958): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  958): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  958): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  958): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  958): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  958): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/ExternalAccountType( 1685): Unsupported attribute readOnly,
,I/ActivityManager(  958): Recipient 4631
,I/BackupManagerService(  958): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/EASAppSvc( 5204): [ NA ]onDestroy
,I/EASAppSvc( 5204): [ NA ]onCreate
I/EASAppSvc( 5204): [ NA ]> uninitEASService
I/VersionUtil( 5204): [ NA ]setIsFOTAing: true
,I/VersionUtil( 5204): [ NA ]onUpgrade: current version=100, latest version=100
,I/VersionUtil( 5204): [ NA ]setIsFOTAing: false
W/EAS_NetworkUtil( 5204): [ NA ]getNetworkInfo: NetworkInfo is null
,I/EASRequestController( 5204): [ NA ]release
E/SQLiteLog( 5183): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal,
,D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/NotificationService(  958): plugged=true pluggin=true
,D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/PMS     (  958): runPSCheck
D/HtcPowerSaver(  958): Checking...
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): handleMessage: E msg.what=155652
D/WifiController(  958): processMsg: ApStaDisabledState
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): handleMessage: X
I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
E/WifiTrafficPoller(  958): ADD_CLIENT: 8
I/HtcPowerSaver(  958): << updateStatus
,D/ORMLib  ( 4828): put()
,D/EASPublicBinder( 5204): [ NA ]release
,D/TaskBinder( 5204): [ NA ]release
D/TaskBinder( 5204): [ NA ]release
I/EASAppSvc( 5204): [ NA ]< uninitEASService
,V/GmsNetworkLocationProvi( 1814): DISABLE
,I/GCoreNlp( 1814): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/AlarmManager(  958): sending alarm PendingIntent{350ca86e: PendingIntentRecord{24c96b0f com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1457427858527, Int=0,
,I/EASAppSvc( 5204): [ NA ]onDestroy,
I/EASAppSvc( 5204): [ NA ]> uninitEASService
W/System.err( 5204): java.lang.IllegalArgumentException: Receiver not registered: null
W/System.err( 5204): 	at android.app.LoadedApk.forgetReceiverDispatcher(LoadedApk.java:828)
W/System.err( 5204): 	at android.app.ContextImpl.unregisterReceiver(ContextImpl.java:1798)
W/System.err( 5204): 	at android.content.ContextWrapper.unregisterReceiver(ContextWrapper.java:510)
W/System.err( 5204): 	at com.htc.android.mail.eassvc.EASAppSvc.F(EASAppSvc.java:2451)
W/System.err( 5204): 	at com.htc.android.mail.eassvc.EASAppSvc.g(EASAppSvc.java:133)
W/System.err( 5204): 	at com.htc.android.mail.eassvc.i.run(EASAppSvc.java:1499)
,I/ActivityManager(  958): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5274 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,D/LocationProviderProxy(  958): applying state to connected service
D/PMS     (  958): acquireWL(1b4e5721): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(1b4e5721): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  958): applying state to connected service,
,D/PMS     (  958): acquireWL(36d5746): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(36d5746): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(880fe34): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1814 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  958): releaseWL(880fe34): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(3c98445d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(3c98445d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/MusicStore( 5239): Database version: 120
,D/Process (  958): killProcessQuiet, pid=4881
I/ActivityManager(  958): Killing 4881:com.htc.cs.dm/u0a99 (adj 15): empty #17,
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/ORMLib  ( 4828): put()
,I/ActivityManager(  958): Recipient 4881
,D/VoldConnector(  958): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5239): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  958): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5239): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  958): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5239): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/Process (  958): killProcessQuiet, pid=4904
I/ActivityManager(  958): Killing 4904:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 5239): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5239): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  958): releaseWL(239764f2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,I/ActivityManager(  958): Recipient 4904
,V/JNIHelp ( 5239): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/ConfigService( 1881): onDestroy,
,W/ActivityThread( 5239): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5239): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a7bf2ee: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5239): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5239): GMSCore installation verified
,W/art     ( 5239): Suspending all threads took: 9.057ms
,I/ConfigStore( 5239): Config Database version: 1,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5239, uid=10159, userID:0
,D/WifiDisplayAdapter(  958): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  958):     Client/Owner: Client
D/WifiDisplayAdapter(  958):     GroupId: 
D/WifiDisplayAdapter(  958):     Passphrase: 
D/WifiDisplayAdapter(  958):     SessionId: 0
D/WifiDisplayAdapter(  958):     IP Address: }
,D/MediaRouterService(  958): Client com.google.android.music (pid 5239): Registered
,D/WifiDisplayAdapter(  958): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  958):     Client/Owner: Client
D/WifiDisplayAdapter(  958):     GroupId: 
D/WifiDisplayAdapter(  958):     Passphrase: 
D/WifiDisplayAdapter(  958):     SessionId: 0
D/WifiDisplayAdapter(  958):     IP Address: }
,I/MediaRouter( 5239): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,D/TelephonyReceiver( 1525): bind: true
,I/ActivityManager(  958): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5308 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  958): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5322 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5239, uid=10159, userID:0
,D/DFPI.PIReciver( 5308): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
I/GHttpClientFactory( 5239): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/DFPI.ApkInstallService( 5308): onHandleIntent
,I/DFPI.ApkInstallService( 5308): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5308): check CID = HTC__102
,I/DFPI.ApkInstallService( 5308): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  958): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5354 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,I/GoogleURLConnFactory( 5239): Using platform SSLCertificateSocketFactory
,W/HtcWrapAdjustableCursorFactory( 5322): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 5322): onCreate,
,V/GetPrviateResource( 5322): GetPrviateResource,
V/GetPrviateResource( 5322): GetPrviateResource
,D/GenericMessagesProvider( 5322): query uri: content://htc-messages/wappush/count
,E/SQLiteLog( 5322): (14) cannot open file at line 30058 of [9491ba7d73]
E/SQLiteLog( 5322): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
,E/SQLiteConnection( 5322): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5322): DB info: errno = 2, errno message = No such file or directory
,D/MessageCustFlag( 5322): sense_version=6.0
E/SQLiteDatabase( 5322): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 5322): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5322): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251),
E/SQLiteDatabase( 5322): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5322): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5322): ,	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5322): 	at android.os.Binder.execTransact(Binder.java:454)
D/BTAccessoryUtil( 5322): createReceiver
I/ActivityManager(  958): Killing 4283:com.android.vending/u0a72 (adj 15): empty #17
W/System.err( 5322): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5322): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
D/BTAccessoryUtil( 5322): registerReceiver return intent = null
W/System.err( 5322): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/System.err( 5322): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5322): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 5322): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5322): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5322): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854),
,W/System.err( 5322): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5322): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 5322): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 5322): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 5322): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5322): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
D/MessageCustFlag( 5322): sku_id=118
W/System.err( 5322): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
,W/System.err( 5322): 	at android.os.Binder.execTransact(Binder.java:454)
D/Process (  958): killProcessQuiet, pid=4283
D/HtcBuildUtils( 5322): getRATByHtcTelephonyCapability:1
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
W/SystemReader( 5322): Cannot find qct_8960_interface, use default value instead
,I/ActivityManager(  958): Recipient 4283
,D/TelephonyReceiver( 1525): switchBindHtcMsgCursor: null
,I/ActivityManager(  958): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5381 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,D/Process (  958): killProcessQuiet, pid=4938,
I/ActivityManager(  958): Killing 4938:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/Prism.ItemManager( 1577): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1577): loadItems() com.htc.launcher.pageview.WidgetManager@2d6e4ff +
I/Prism.WidgetManager( 1577): onLoadItems() +
,I/Prism.ItemManager( 5101): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 5101): loadItems() com.htc.launcher.pageview.WidgetManager@f1d9f83 +
I/Prism.WidgetManager( 5101): onLoadItems() +
,I/HtcModeClient( 3265): handler message = 4011
,E/HtcModeClient( 3265): Check connection and retry 5 times.
,I/ActivityManager(  958): Recipient 4938
,W/ResourcesManager( 1577): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 5101): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/VoldConnector(  958): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
,W/ContextImpl( 5354): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] startService,
,I/SoundPicker( 5381): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5381): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5381): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/DFPI.PIReciver( 5308): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] startService
I/DFPI.ApkInstallService( 5308): onHandleIntent
I/DFPI.ApkInstallService( 5308): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5308): check CID = HTC__102
I/DFPI.ApkInstallService( 5308): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2,
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
,D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
,I/SoundPicker( 5381): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/ActivityManager(  958): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5409 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
D/DFPI.PIReciver( 5308): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5308): onHandleIntent
I/DFPI.ApkInstallService( 5308): Media Scan Finished Case 
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5381): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/DFPI.ApkInstallService( 5308): check CID = HTC__102
I/DFPI.ApkInstallService( 5308): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5381): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5381): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5381): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5381): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
D/DFPI.PIReciver( 5308): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/ActivityManager(  958): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/DFPI.ApkInstallService( 5308): onHandleIntent
I/DFPI.ApkInstallService( 5308): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5308): check CID = HTC__102
I/DFPI.ApkInstallService( 5308): There is no Demo.apk in sd card or phone storage
W/ResourcesManager( 5101): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  958): Resuming delayed broadcast
,W/ResourcesManager( 1577): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/MediaStoreImporter( 5239): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,D/TelephonyReceiver( 1525): bind: false
D/TelephonyReceiver( 1525): switchBindHtcMsgCursor: null
,D/DFPI.PIReciver( 5308): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,I/ActivityManager(  958): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/DFPI.ApkInstallService( 5308): onHandleIntent
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/DFPI.ApkInstallService( 5308): Media Scan Finished Case 
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
D/DFPI.ApkInstallService( 5308): check CID = HTC__102
I/DFPI.ApkInstallService( 5308): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  958): Resuming delayed broadcast
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5381): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5381): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
,D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5381): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/DFPI.PIReciver( 5308): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/ActivityManager(  958): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/DFPI.ApkInstallService( 5308): onHandleIntent
,I/DFPI.ApkInstallService( 5308): Media Scan Finished Case 
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/DFPI.ApkInstallService( 5308): check CID = HTC__102
,I/DFPI.ApkInstallService( 5308): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  958): Resuming delayed broadcast
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/art     (  958): Explicit concurrent mark sweep GC freed 23325(1238KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.457ms total 150.959ms
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/MediaStoreImporter( 5239): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
D/DFPI.PIReciver( 5308): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  958): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver,
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/ActivityManager(  958): Waited long enough for: ServiceRecord{1042c93 u0 com.htc.backup/.notifications.contextual.ContextualReminderControlService}
I/DFPI.ApkInstallService( 5308): onHandleIntent
I/ActivityManager(  958): Resuming delayed broadcast
I/DFPI.ApkInstallService( 5308): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5308): check CID = HTC__102
I/DFPI.ApkInstallService( 5308): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
I/SoundPicker( 5381): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,D/GCM     ( 1881): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
W/asset   ( 5101): Copying FileAsset 0x55b3084e80 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
D/PhoneApp( 1525): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1525): -- N1 =0,
,D/AuthorizationBluetoothService( 1881): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/PhoneApp( 1525): -- N2 =0,
,V/GmsCoreStatsServiceLauncher( 4346): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/PhoneApp( 1525): -- N3 =0
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,W/asset   ( 1577): Copying FileAsset 0x55b3451e60 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/SoundPicker( 5381): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5381): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5381): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5381): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4346, uid=10024, userID:0
I/MediaStoreImporter( 5239): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/WearableService( 4693): callingUid 10024, callindPid: 4693
I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/LocationInitializer( 4346): Restart initialization of location
E/MDM     ( 1814): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/GCM     ( 1881): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/AuthorizationBluetoothService( 1881): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
V/GmsCoreStatsServiceLauncher( 4346): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/Prism.WidgetManager( 5101): onLoadItems() -
,I/Prism.ItemManager( 5101): loadItems() com.htc.launcher.pageview.WidgetManager@f1d9f83 -
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4346, uid=10024, userID:0
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,E/MDM     ( 1814): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,D/LocationInitializer( 4346): Restart initialization of location
I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,E/Prism.WidgetManager( 1577): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1577): onLoadItems() -
I/Prism.ItemManager( 1577): loadItems() com.htc.launcher.pageview.WidgetManager@2d6e4ff -
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/MediaStoreImporter( 5239): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5381): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5381): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5381): TurnFileToMediaUriService [checkFileExistence]
,D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/ActionCombine( 5409): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/RemoteViews( 1220): setHTCTheme(com.htc.updater,true,33751145)
,D/PMS     (  958): acquireWL(35dadcbc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,D/PMS     (  958): releaseWL(35dadcbc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/PMS     (  958): acquireWL(12d97445): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
I/RemoteViews( 1220): apply : com.htc.updater 1 11 2 36
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/MediaStoreImporter( 5239): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,D/PMS     (  958): releaseWL(12d97445): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5381): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5381): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5381): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma),
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/FindExtension( 1220): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/ThreadedRenderer( 1220): Defer allocateBuffers to drawing time
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/MediaStoreImporter( 5239): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5381): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5381): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5381): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/PMS     (  958): acquireWL(2a93b366): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
D/PMS     (  958): releaseWL(2a93b366): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/ActivityManager(  958): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5455 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/Process (  958): killProcessQuiet, pid=4979
I/ActivityManager(  958): Killing 4979:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PhoneMonitor( 5455): Register our PhoneStateListener
,I/ActivityManager(  958): Recipient 4979,
,D/Process (  958): killProcessQuiet, pid=4599,
I/ActivityManager(  958): Killing 4599:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 5455): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 5455): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  958): Recipient 4599
,D/WifiService(  958): Client connection lost with reason: 4
,D/GCM     ( 1881): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 4346): Loading module com.google.android.gms.kids from APK com.google.android.gms,
I/Kids    ( 4346): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/ActivityManager(  958): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5479 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5479): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5479): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 5479): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 5322): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 5322): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 5479): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml,
I/Babel_SMS( 5479): MmsConfig.loadFromDatabase
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5479, uid=10112, userID:0,
,D/Messaging( 5322): supportCMAS(SIE)/init? false/true
,D/MmsConfig( 5322): networkCode: 
D/MessageCustFlag( 5322): sku_id=118
E/Babel_SMS( 5479): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5479): MmsConfig.loadFromResources,
D/MmsConfig( 5322): SIE smsPri: null
D/MmsConfig( 5322): networkCode: 
E/Babel_SMS( 5479): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5479): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,D/MmsConfig( 5322): packageName: com.htc.vvm.att does not exist
,D/Messaging( 5322): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 5322): startAsyncQueryReports ---,
D/MmsAsyncWorkHandler( 5322): 
D/MmsAsyncWorkHandler( 5322): HM tk = 20001
D/ReportIndicatorCache( 5322): MSG_QUERY_REPORTS >>
D/SettingsManager( 5322): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@3c3900e8,
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1525):  slotId = -1000
D/MmsSmsV2Provider( 1525): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 5322): [DraftCache/1] DraftCache.constructor,
D/DraftCache( 5322): [DraftCache/1] refresh
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 89
,D/AccFlag ( 1525): sku_id=118
I/Messaging( 5322): mccmnc> 
,D/DraftCache( 5322): [DraftCache/116] rebuildCache
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1525):  slotId = -1000
D/MmsSmsV2Provider( 1525): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MmsConfig( 5322): networkCode: 
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 89
D/MmsSmsV2Provider( 1525):  slotId = -1000
D/MmsSmsV2Provider( 1525): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 5322): ViewCache CreatePreloadOnlyConversationList
,I/art     (  958): Explicit concurrent mark sweep GC freed 11548(599KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.198ms total 141.346ms
,W/Settings( 5479): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Messaging( 5322): mNeedToUpdateDate2: false
,D/MessageCustFlag( 5322): sense_version=6.0
D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/MmsSmsV2Provider( 1525):  slotId = -1000
D/MmsSmsV2Provider( 1525): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Jerry   ( 5322): start to preload cursor >>>>>>>
,D/PhoneStorageUtil( 5322): HtcWrapEnvironment.getSupportedStorages() >1,
D/PhoneStorageUtil( 5322): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5322): createReceiver
,D/Messaging( 5322): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,I/Babel_Crash( 5479): startup - clean
D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/Jerry   ( 1525): URI_DRAFT
,D/TelephUtils( 1525): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 89,
V/MmsProvider( 1525): Update uri=content://mms, match=0
V/MmsProvider( 1525): selection=st=129 AND m_type!=134
D/DraftCache( 5322): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 5322): [DraftCache/116] rebuildCache time: 11
,D/MmsAsyncWorkHandler( 5322): 
D/MmsAsyncWorkHandler( 5322): HM tk = 20002
D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/MmsSmsV2Provider( 1525):  slotId = -1000
,D/Messaging( 5322): Reset downloading state: 0
,V/MmsSystemEventReceiver( 5322): TransactionService is going to be woken up.
,V/TransactionService( 5322): 1-Creating TransactionService
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
,D/AccFlag ( 1525): sku_id=118
D/Messaging( 5322): ViewCache CreatePreload
D/Messaging( 5322): ViewCache CreatePreloadOnlyMultipleOpsList
,I/Babel   ( 5479): deleted: false for 0
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 89
D/AccFlag ( 1525): sku_id=118
,V/TransactionService( 5322): onStartCommand: 1
D/MmsSystemEventReceiver( 5322): unRegisterForConnectionStateChanges
,V/TransactionService( 5322): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5322): Loading previous transactions.
,D/Cust_MMSMS( 5322): _has_set_default_values_2=true,
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/AccFlag ( 1525): device_type: 1
,D/MsgPreferenceUtils( 5322): def_index: 0
,D/TransactionService( 5322): Force clearing mTransactionList,
D/TransactionService( 5322): Force set service start id to 1
V/TransactionService( 5322): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5322): unRegisterForConnectionStateChanges
V/TransactionService( 5322): Destroying TransactionService
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5479, uid=10112, userID:0
D/TransactionService( 5322): stopSelfResult: true, mLastHandledServiceId: 1
,D/MsgPreferenceUtils( 5322): globalIndex = 1
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5479, uid=10112, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5479, uid=10112, userID:0
V/TransactionService( 5322): 4-Handling incoming message: { when=-1ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5479, uid=10112, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5479, uid=10112, userID:0,
,D/MsgPreferenceUtils( 5322): phone state: true
D/MsgPreferenceUtils( 5322): sd state: false
D/MsgPreferenceUtils( 5322): vIndex = 0
,D/PMS     (  958): acquireWL(3f2e7de4): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5479 10112 null
,I/ActivityManager(  958): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5537 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,W/VideoCapabilities( 5479): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5479): Unsupported mime video/x-ms-wmv
,W/Utils   ( 5479): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 5479): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5479): Unsupported mime audio/x-ms-wma,
,W/AudioCapabilities( 5479): Unsupported mime audio/qcelp
,W/VideoCapabilities( 5479): Unsupported mime video/x-ms-wmv,
,I/VideoCapabilities( 5479): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5479): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5479): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5479): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5479): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager(  958): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/vclib   ( 5479): onServiceConnected,
,W/Babel   ( 5479): Attempted to change video mute state without an active call.,
,W/ResourcesManager( 5479): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5479): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Gmail   ( 5537): getAccountsCursor,
,W/GAV2    ( 5537): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=5537, uid=10106, userID:0
,W/ActivityManager(  958): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found,
,W/ActivityManager(  958): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/ActivityManager(  958): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5537, uid=10106, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5537, uid=10106, userID:0
,E/Gmail   ( 5537): Error finding the version of the Email provider.....
E/Gmail   ( 5537): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5537): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5537): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5537): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5537): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5537): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5537): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 5537): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5537): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5537): Observing account changes for notifications
,I/Gmail   ( 5537): getAccountsCursor
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/GCM     ( 1881): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1881): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4346): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4346, uid=10024, userID:0
,E/MDM     ( 1814): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4346): Restart initialization of location,
,E/SQLiteLog( 5537): (283) recovered 1516 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/JNIHelp ( 5479): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/Gmail   ( 5537): notifyAccountChanged,
,I/Gmail   ( 5537): getAccountsCursor
I/Gmail   ( 5537): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5537): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5537): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5537): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/System  ( 5479): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5479): Installed default security provider GmsCore_OpenSSL
,I/art     ( 1881): Explicit concurrent mark sweep GC freed 11197(551KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 1.050ms total 55.183ms
,I/Gmail   ( 5537): master sync=false, engine sync=true,
,D/DFPI.PIReciver( 5308): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5308): onHandleIntent
,I/DFPI.ApkInstallService( 5308): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5308): check CID = HTC__102,
,I/DFPI.ApkInstallService( 5308): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,E/PhoneInterfaceManager( 1525): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/SoundPicker( 5381): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5381): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5381): TurnFileToMediaUriService fromMediaScanned = true
I/ActivityManager(  958): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/SoundPicker( 5381): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
W/VideoCapabilities( 5479): Unrecognized profile 2130706433 for video/avc
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5381): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
W/VideoCapabilities( 5479): Unrecognized profile 2130706433 for video/avc
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
W/VideoCapabilities( 5479): Unrecognized profile 2130706433 for video/avc
I/Gmail   ( 5537): getAccountsCursor
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 5479): connection state changed from UNKNOWN to DISCONNECTED
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
I/ActivityManager(  958): Resuming delayed broadcast
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/Gmail   ( 5537): master sync=false, engine sync=true
,D/DFPI.PIReciver( 5308): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,I/ActivityManager(  958): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/DFPI.ApkInstallService( 5308): onHandleIntent
,I/DFPI.ApkInstallService( 5308): Media Scan Finished Case 
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/DFPI.ApkInstallService( 5308): check CID = HTC__102,
I/DFPI.ApkInstallService( 5308): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  958): Resuming delayed broadcast
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30,
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,D/PMS     (  958): releaseWL(3f2e7de4): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/SoundPicker( 5381): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,D/DFPI.PIReciver( 5308): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/NotifUtils( 5537): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/DFPI.ApkInstallService( 5308): onHandleIntent
I/DFPI.ApkInstallService( 5308): Media Scan Finished Case ,
I/SoundPicker( 5381): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
D/DFPI.ApkInstallService( 5308): check CID = HTC__102
I/DFPI.ApkInstallService( 5308): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5381): SoundPickerReceiver [onReceive] startService
,I/art     ( 5381): Explicit concurrent mark sweep GC freed 13334(835KB) AllocSpace objects, 2(40KB) LOS objects, 87% free, 303KB/2MB, paused 312us total 35.253ms
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/NotifUtils( 5537): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/MediaStoreImporter( 5239): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  958): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5608 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5381): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5381): TurnFileToMediaUriService [turnFileUriIntoMediaUri],
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3,
,W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
,I/SoundPicker( 5381): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,W/ResourcesManager( 5608): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/MediaStoreImporter( 5239): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/CalendarApplication( 5608): onCreate,
,D/ProviderChangeReceiver( 5608): ---------------------------------------------------
D/ProviderChangeReceiver( 5608): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/PMS     (  958): acquireWL(2b90413f): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5479 10112 null
,D/HtcAlertService( 5608): start to updateAlertNotification!
,I/ActivityManager(  958): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5633 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,D/HtcAlertService( 5608): No fired or scheduled alerts
D/HtcAlertUtils( 5608): -- cancelReminderNotification --
,D/PMS     (  958): releaseWL(2b90413f): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/HtcAlertUtils( 5608): broadcastExistReminder!
,D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/art     (  958): Explicit concurrent mark sweep GC freed 8996(445KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.550ms total 138ms
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
I/MediaStoreImporter( 5239): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  958): Killing 5021:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=5021
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5021
,D/WifiService(  958): Client connection lost with reason: 4
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5381): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5381): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5381): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5381): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5381): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5381): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98,
I/SoundPicker( 5381): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5381): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  958): Killing 4181:com.android.settings/1000 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=4181
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 4181
,D/LocationManagerService(  958): getProviders()=[passive]
,I/ActivityManager(  958): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5660 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,D/Process (  958): killProcessQuiet, pid=5053
I/ActivityManager(  958): Killing 5053:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  958): Recipient 5053
,D/Process (  958): killProcessQuiet, pid=5101,
I/ActivityManager(  958): Killing 5101:com.htc.sense.news/u0a74 (adj 15): empty #17
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
,I/ActivityManager(  958): Recipient 5101,
,I/[PluginManager]RegisterService( 1498): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1498): handle notify Blinkfeed plugin client changed,
,I/ActivityManager(  958): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5683 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/art     (  408): Explicit concurrent mark sweep GC freed 8652(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 250us total 33.339ms,
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 169us total 23.333ms,
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 151us total 21.489ms
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5683): -onCreate(),
,V/Settings:HtcSettingsApplication( 5683): [5683/5683] onCreate(),
,I/ActivityManager(  958): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5707 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  958): Killing 5128:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=5128
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/Settings:HtcWirelessFeatureFlags( 5683): id/is att sku: 118/false,
,I/ActivityManager(  958): Recipient 5128
,E/Settings:HtcWrapHeaderInfo( 5683): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5683): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 5683): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5683): isSupportMusicChannel(): false
,V/AlarmManager(  958): sending alarm PendingIntent{41211d3: PendingIntentRecord{19521110 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1457427864014, Int=0
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportHomeButton]support         :false
,I/ActivityManager(  958): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 5683): isSupportVoWifi: null
E/ActivityThread( 5683): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5683): The wrap header doesn't exist in header list.,
E/Settings:HtcWrapHeaderInfo( 5683): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5683): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5683): [supportHomeButton]support         :false
,I/ActivityManager(  958): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 5683): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5683): isSupportVoWifi: null
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5707, uid=10072, userID:0,
,W/global  ( 5707): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5707): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 5707): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5707): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5707): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  958): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5748 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 5707): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5707): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5707, uid=10072, userID:0
,W/ResourcesManager( 5748): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5748): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5748): VM with version 2.1.0 has multidex support,
I/MultiDex( 5748): install
I/MultiDex( 5748): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 5707): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 5707): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5707): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 5748): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PackageBroadcastService( 4346): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5707): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  958): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5776 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/PackageBroadcastService( 4346): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  958): Killing 5157:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=5157
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ActivityThread( 5748): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5748): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f1a6a24: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5748): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  958): Recipient 5157
,D/PMS     (  958): acquireWL(3b5315c3): PARTIAL_WAKE_LOCK  Icing 0x1 4346 10024 WorkSource{10024 com.google.android.gms}
,I/Icing   ( 4346): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5776): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PMS     (  958): releaseWL(3b5315c3): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  958): acquireWL(3f389e6c): PARTIAL_WAKE_LOCK  AsyncService 0x1 5776 10167 null,
,D/PMS     (  958): releaseWL(3f389e6c): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  958): acquireWL(29ba08ca): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5776 10167 null
,I/UpdateIcingCorporaServi( 5633): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
,I/WSP     ( 1498): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/PMS     (  958): releaseWL(29ba08ca): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
D/WeatherUtility( 1498): Weather sync is On
,I/WSP     ( 1498): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Mar 08 11:04:24 CET 2016
,W/WSP     ( 1498): [Receiver] can't get active network info,
,I/Task_Calendar( 4828): Set ICALENDAR_UID to sync_data7 due to SDK_INT is 21
,I/HtcModeClient( 3265): handler message = 4011,
E/HtcModeClient( 3265): Check connection and retry 6 times.
,I/ActivityManager(  958): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5819 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,V/WSP     ( 1498): [SyncService] no data connection, stop sync service,
D/TodoTaskshortcut( 4828): update TASK shortcut>
,I/ActivityManager(  958): Killing 5077:com.htc.bgp/u0a11 (adj 15): empty #17
,D/Process (  958): killProcessQuiet, pid=5077
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,V/Finsky  ( 5707): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/UpdateIcingCorporaServi( 5633): UpdateCorporaTask done [took 132 ms] updated apps [took 131 ms] 
,I/ActivityManager(  958): Recipient 5077
,D/Process (  958): killProcessQuiet, pid=5204,
I/ActivityManager(  958): Killing 5204:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5204
,D/WifiService(  958): Client connection lost with reason: 4
,D/SyncApplication( 5819): Loading default preferences,
,W/Resources( 5819): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,E/WifiTrafficPoller(  958): ADD_CLIENT: 6,
D/WifiService(  958): New client listening to asynchronous messages
,D/Finsky  ( 5707): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
V/AlarmManager(  958): sending alarm PendingIntent{182c536e: PendingIntentRecord{15f3a0f com.android.vending startService}}, i=null, t=0, cnt=1, w=1457427865244, Int=0
,D/SyncApplication( 5819): Overriding preferences with custom values,
,D/SyncApplication( 5819): Updating preferences succeeded
,E/SyncApplication( 5819): Application created.,
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/VolumeInfo( 5819): Unable to read mount points
W/VolumeInfo( 5819): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5819): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5819): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5819): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5819): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5819): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5819): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5819): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5819): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5819): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5819): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5819): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5819): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5819): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5819): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5819): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5819): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5819): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5819): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5819): 	... 13 more
V/VolumeInfo( 5819): Found 0 mount point(s)
,V/VolumeInfo( 5819): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,I/CalendarDefines( 5819): getNewCalendarAuthority()...
,D/VolumeInfo( 5819): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5819, uid=10005, userID:0,
W/PackageManager(  958): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 5819): enableAppOperation()+
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5819, uid=10005, userID:0
W/PackageManager(  958): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/VolumeInfo( 5819): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355},
W/VolumeInfo( 5819): Can not create volume ID for unmounted volume null
,D/SyncApplication( 5819): enableAppOperation()-
D/HTCUtilities( 5819): isNeorSinged() + 
,D/HTCUtilities( 5819): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 5819): isNeorSinged() return false
I/GLSUser ( 1881): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1881): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1881): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1881): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/CDMountReceiver( 5819): whether to enable CD Auto-mount: true
D/CDMountReceiver( 5819): showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,I/ActionCombine( 5819): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,W/Finsky  ( 5707): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/CDMountReceiver( 5819): enable CD Auto-mount: true,
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
D/PMS     (  958): releaseWL(531bd63): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10005}
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HTCUtilities( 5819): enable auto-mount
,D/HTCUtilities( 5819): enable auto-mount
,D/PMS     (  958): acquireWL(2b3d6191): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5239 10159 null
,I/HtcMountManagerAdapter( 5819): mHtcMountManager is  null
,I/HtcMountManagerAdapter( 5819): mStorageManager is  not null
I/HtcMountManagerAdapter( 5819): mHtcMountManager is  null
,I/HtcMountManagerAdapter( 5819): mStorageManager is  not null
,D/VoldConnector(  958): SND -> {21 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
,D/MountService(  958): mountISO: /system/etc/PCTOOL.ISO
,D/VoldConnector(  958): SND -> {22 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
,D/MountService(  958): mountISO: /system/etc/PCTOOL.ISO
,I/RemoteViews( 1220): apply : com.nero.android.htc.sync 0 16 12 38
,I/GLSUser ( 1881): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1881): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1881): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1881): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1220): apply : com.nero.android.htc.sync 0 13 3 53,
,I/art     (  958): Explicit concurrent mark sweep GC freed 11907(582KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.417ms total 147.614ms
V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5239, uid=10159, userID:0
,I/MusicLeanback( 5239): Conditions not met for autocaching. okToAttempt=false,
D/PMS     (  958): releaseWL(2b3d6191): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 5239): Stop autocaching.
V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1881): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1881): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4346): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4346, uid=10024, userID:0,
I/GLSUser ( 1881): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1881): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1881): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1881): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/MDM     ( 1814): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4346): Restart initialization of location
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/GmsUtils( 5239): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5239): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Finsky  ( 5707): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,E/AndroidHttpClient( 5707): Leak found
E/AndroidHttpClient( 5707): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5707): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5707): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5707): 	,at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5707): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5707): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5707): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5707): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5707): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5707): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5707): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5707): 	at android.os.Looper.loop(Looper.java:155),
E/AndroidHttpClient( 5707): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5707): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5707): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5707): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5707): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1881): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1881): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1881): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1881): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5707): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 5707): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,D/Finsky  ( 5707): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 5707): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1),
,D/Finsky  ( 5707): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive
,I/ActivityManager(  958): Killing 5274:com.htc.task.gtask/u0a66 (adj 15): empty #17
,D/DeviceConnectionService( 1814): client connected with version: 7571000
D/Process (  958): killProcessQuiet, pid=5274
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5274
,I/ActivityManager(  958): Waited long enough for: ServiceRecord{2d621ea5 u0 com.htc.club/com.mcrm.autonotification.NotificationService},
,I/GAV2    ( 5537): Thread[GAThread,5,main]: No campaign data found.,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4346, uid=10024, userID:0,
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4346, uid=10024, userID:0
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4346, uid=10024, userID:0
,I/CheckinService( 4346): Done disabling old GoogleServicesFramework version
,D/AutoSetting( 1498): service - handleMessage() stop self,
,D/AutoSetting( 1498): service - onDestroy() END
,D/AutoSetting( 1498): service - handleMessage() quit looper
,I/HtcModeClient( 3265): handler message = 4011,
E/HtcModeClient( 3265): Check connection and retry 7 times.
,D/Process (  958): killProcessQuiet, pid=5409
,I/ActivityManager(  958): Killing 5409:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5409,
,D/Process (  958): killProcessQuiet, pid=5455
,I/ActivityManager(  958): Killing 5455:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5455,
,W/MediaManager( 5183): [DualLensScanUtil],	mmpCursor count is 0
,D/Process (  958): killProcessQuiet, pid=5322,
I/ActivityManager(  958): Killing 5322:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5322
,I/ActivityManager(  958): Killing 5308:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
,D/Process (  958): killProcessQuiet, pid=5308
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5308,
,I/ActivityManager(  958): Waited long enough for: ServiceRecord{29e45f65 u0 com.htc.musicenhancer/.EnhancerService},
,I/HtcModeClient( 3265): handler message = 4011
,E/HtcModeClient( 3265): Check connection and retry 8 times.
,W/Atfwd_Sendcmd(  445): AtCmdFwd service not published, waiting... retryCnt : 5
,I/HtcModeClient( 3265): handler message = 4011,
E/HtcModeClient( 3265): Check connection and retry 9 times.,
,D/PMS     (  958): acquireWL(ad83963): PARTIAL_WAKE_LOCK  *alarm* 0x1 958 1000 WorkSource{10024},
D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
V/AlarmManager(  958): sending alarm PendingIntent{51ec960: PendingIntentRecord{331e3f45 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=83316, Int=0
D/libc    ( 1881): [NET] android_getaddrinfofornet-, err=8
D/PMS     (  958): acquireWL(2fb72e19): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1881): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1881): [NET] android_getaddrinfo_proxy+
V/AlarmManager(  958): sending alarm PendingIntent{358b08bf: PendingIntentRecord{2b971b8c com.android.vending startService}}, i=null, t=0, cnt=1, w=1457427880677, Int=0
D/libc    ( 1881): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
V/AlarmManager(  958): sending alarm PendingIntent{340392d5: PendingIntentRecord{22009aea android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=85225, Int=0
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
V/AlarmManager(  958): sending alarm PendingIntent{247171db: PendingIntentRecord{3f606478 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=85685, Int=0
D/libc    ( 1881): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, err=8
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  958): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  958): [NET] android_getaddrinfo_proxy+
D/libc    (  958): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
,D/libc    (  958): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  958): releaseWL(ad83963): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  958): releaseWL(2fb72e19): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/Finsky  ( 5707): [577] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 5707): [1] 5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 3265): handler message = 4011,
E/HtcModeClient( 3265): Check connection and retry 10 times.
,I/HtcModeClient( 3265): handler message = 4011,
,E/HtcModeClient( 3265): Check connection and retry 11 times.
,D/PMS     (  958): acquireWL(1b5c478d): PARTIAL_WAKE_LOCK  Icing 0x1 4346 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  958): releaseWL(1b5c478d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(30fa4153): PARTIAL_WAKE_LOCK  Icing 0x1 4346 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(30fa4153): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(3e0fdb45): PARTIAL_WAKE_LOCK  Icing 0x1 4346 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(3e0fdb45): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(1dee87cb): PARTIAL_WAKE_LOCK  Icing 0x1 4346 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(1dee87cb): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/HtcModeClient( 3265): handler message = 4011
,E/HtcModeClient( 3265): Check connection and retry 12 times.
,I/HtcModeClient( 3265): handler message = 4011
,E/HtcModeClient( 3265): Check connection and retry 12 times. Stop service and kill this process.
D/HtcModeClient( 3265): Don't start project servcice
,D/HtcModeClient( 3265): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3265): connectState: CONNECTION_READY = false
,D/SilentMusic( 3265): call stop
D/HtcModeClient( 3265): close connection
W/HtcModeClient( 3265): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3265): read the terminate packet, so break
,D/Process (  958): killProcessQuiet, pid=3265
I/ActivityManager(  958): Killing 3265:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ClockController( 1220): schedule update now=1457427900021 next=59979,
,I/Clock   ( 1220): updateClock:10:05 Europe/Warsaw,
I/Clock   ( 1220): updateClock:10:05 Europe/Warsaw
I/Clock   ( 1220): updateClock:10:05 Europe/Warsaw
,I/ActivityManager(  958): Recipient 3265
,D/PMS     (  958): acquireWL(3df1dba8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 958 1000 WorkSource{1000}
V/AlarmManager(  958): sending alarm PendingIntent{28b02468: PendingIntentRecord{e876081 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=106143, Int=0
,D/PMS     (  958): releaseWL(3df1dba8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1220): Weather sync is On,
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,I/ActivityManager(  958): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5879 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  958): acquireWL(1cd7e6c1): PARTIAL_WAKE_LOCK  *alarm* 0x1 958 1000 WorkSource{10076}
V/AlarmManager(  958): sending alarm PendingIntent{a823e66: PendingIntentRecord{115bd5a7 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457427901135, Int=60000
D/PMS     (  958): releaseWL(1cd7e6c1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 5879): SMSBackupAgentService started,
D/SMSBackup( 5879): Checking restore status
,D/SMSBackup( 5879): Restore complete,
D/SMSBackup( 5879): cancelCheckAlarm
,D/SMSBackup( 5879): SMSBackupAgentService completed: completed in 0.0 seconds,
,I/ActivityManager(  958): Killing 5381:com.htc.sdm/u0a79 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=5381
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5381,
,I/PMS     (  958): Going to sleep due to screen timeout (uid 1000)...,
I/SensorManager(  958): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@25fa7940
,W/SensorService(  958): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  958): disable: get sensor name = Accelerometer Sensor
W/SensorService(  958): pid=958, uid=1000
W/SensorService(  958): Active sensors: size = 4
W/SensorService(  958): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  958): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  958): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  958): Significant Motion (handle=0x0000000d, connections=1)
W/PMN     (  958): goingToSleep
W/SensorService(  958): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@25fa7940, eanble = 0, strlen(mName) = 91
W/SensorService(  958): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  958): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@cd8754d
W/SensorService(  958): Listener[1] = com.htc.smartdim.sensor_eye@1c68ccc9
W/SensorService(  958): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1220): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMS     (  958): mWirelessDisplayManager is null
,D/PMS     (  958): acquireWL(32bb2dfd): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 958 1000 null
W/PMS     (  958): mWirelessDisplayManager is still null
,W/PMN     (  958): goingToSleep done
I/PMS     (  958): Sleeping (uid 1000)...
D/XAN-DPS (  958): prepareColorFade 1
,W/HtcSystemUPManager(  958): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/AlarmManager(  958): ACTION_SCREEN_ON
,I/AlarmManager(  958): [AlarmQueuing] recover blocked alarms,
I/AlarmManager(  958): [AlarmQueuing] done recovering
,I/AlarmManager(  958): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  958): [AlarmQueuing] done EPS screen off alarm recovering
I/ActivityManager(  958): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5901 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/Adreno-EGL(  958): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  958): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  958): Build Date: 03/09/15 Mon
I/Adreno-EGL(  958): Local Branch: 
I/Adreno-EGL(  958): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  958): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
,I/Adreno-EGL(  958):                  d74aa161a12b9c6fc6332151
,D/PMS     (  958): releaseWL(32bb2dfd): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/WifiStateMachine(  958): handleMessage: E msg.what=131167,
E/WifiStateMachine(  958): processMsg: InitialState
E/WifiStateMachine(  958):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  958):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState,
,V/SRS_Proc(  402): ParamSet string: screen_state=on
,E/audio_a2dp_hw(  402): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  958): handleMessage: E msg.what=155650
D/WifiController(  958): processMsg: ApStaDisabledState
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
,D/NetworkPolicy(  958): updateScreenOn: false
V/NetworkPolicy(  958): updateIfacesLocked()
D/WifiStateMachine(  958): getWifiLinkLayerStats: WIFI is not enbled
D/NetworkManagementService(  958): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiStateMachine(  958): backgroundScan enabled=false startBackgroundScanIfNeeded:false
W/ResourcesManager( 5901): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/WifiStateMachine(  958): handleScreenStateChanged Exit: true
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131154
E/WifiStateMachine(  958): processMsg: InitialState
E/WifiStateMachine(  958):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131127
E/WifiStateMachine(  958): processMsg: InitialState
,E/WifiStateMachine(  958):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
,E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131129
E/WifiStateMachine(  958): processMsg: InitialState
E/WifiStateMachine(  958):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  958): handleMessage: X
D/GpsLocationProvider(  958): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1220): receive(android.intent.action.SCREEN_ON,1,false)
,I/CalendarProvider2( 5901): Created com.android.providers.calendar.CalendarAlarmManager@7ea65da(com.htc.providers.calendar.HtcCalendarProvider@2a71fa0b)
,D/CalendarProvider2( 5901): wait start:true
,D/PMS     (  958): acquireWL(140d0d16): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  958): acquireWL(388f7697): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  958): releaseWL(140d0d16): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(388f7697): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/AlarmManager(  958): ACTION_SCREEN_OFF,
I/AlarmManager(  958): [AlarmQueuing] screen off now: 
,I/AlarmManager(  958): [AlarmQueuing] data connection: true
D/WifiDataStallTracker(  958): stopDataStallAlarm 
I/AlarmManager(  958): [AlarmQueuing] wifi connection: false
E/WifiDataStallTracker(  958): ENABLE_DATA_MONITOR_POLL false Token 0
E/WifiStateMachine(  958): handleMessage: E msg.what=131167
E/WifiStateMachine(  958): processMsg: InitialState
E/WifiStateMachine(  958):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  958):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiStateMachine(  958): getWifiLinkLayerStats: WIFI is not enbled
E/WifiStateMachine(  958): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiDisplayAdapter(  958): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  958):     Client/Owner: Client
D/WifiDisplayAdapter(  958):     GroupId: 
D/WifiDisplayAdapter(  958):     Passphrase: 
D/WifiDisplayAdapter(  958):     SessionId: 0
D/WifiDisplayAdapter(  958):     IP Address: }
D/WifiStateMachine(  958): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  958): handleScreenStateChanged Exit: false
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131154
E/WifiStateMachine(  958): processMsg: InitialState
V/SRS_Proc(  402): ParamSet string: screen_state=off
E/audio_a2dp_hw(  402): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  958):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  958): handleMessage: X
,D/WifiController(  958): handleMessage: E msg.what=155651
D/NetworkPolicy(  958): updateScreenOn: false
D/WifiController(  958): processMsg: ApStaDisabledState
V/NetworkPolicy(  958): updateIfacesLocked()
D/WifiController(  958): processMsg: DefaultState
D/NetworkManagementService(  958): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiController(  958): handleMessage: X
,D/XAN-DPS (  958): prepareColorFade done
D/XAN-DPS (  958): setBrightness to 0
,D/CalendarProvider2( 5901): wait end:false
,I/SensorManager(  958): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@cd8754d
W/SensorService(  958): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  958): disable: get sensor name = CM32181 Light sensor
I/SensorManager( 1220): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@2f125f86, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
,I/DisplayManagerService(  958): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS},
V/ActivityManager(  958): Display changed displayId=0
W/SensorService(  958): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  958): enable: get sensor name = hTC Gesture Motion HIDI
D/DotMatrix( 1307): [EventService]  onDisplayChanged: 0
W/SensorService(  958): pid=958, uid=1000
W/SensorService(  958): Active sensors: size = 3
W/SensorService(  958): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  958): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  958): Significant Motion (handle=0x0000000d, connections=1)
,W/SensorService(  958): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@cd8754d, eanble = 0, strlen(mName) = 66
W/SensorService(  958): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  958): Listener[0] = com.htc.smartdim.sensor_eye@1c68ccc9
W/SensorService(  958): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1307): [EventService] mbHDMIConnect: false, mCoverOn:false
,W/SensorService(  958): pid=1220, uid=10041
W/SensorService(  958): Active sensors: size = 4
W/SensorService(  958): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  958): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  958): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  958): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
W/SensorService(  958): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@2f125f86, eanble = 1, strlen(mName) = 57
W/SensorService(  958): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  958): Listener[0] = com.htc.smartdim.sensor_eye@1c68ccc9
W/SensorService(  958): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@2f125f86
W/SensorService(  958): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  958): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5932 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/GpsLocationProvider(  958): receive broadcast intent, action: android.intent.action.SCREEN_OFF,
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1525): start background delete task...
,I/IntentController( 1220): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1525): size: 0 , 0,
,D/ContactMessageStore( 1525): Background delete complete
,I/RemoteViews( 1220): setHTCTheme(com.htc.updater,true,33751145),
,I/RemoteViews( 1220): apply : com.htc.updater 0 11 1 36,
,W/ContextImpl( 5932): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,I/art     (  958): Explicit concurrent mark sweep GC freed 23722(1106KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 18MB/27MB, paused 1.745ms total 177.080ms
,D/PowerUsageList:PowerUsageHelper( 5932): MY_DEBUG = false
,D/PMS     (  958): acquireWL(132b50f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms},
W/ContextImpl( 5932): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  958): releaseWL(132b50f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(1730a8ee): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  958): releaseWL(1730a8ee): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(944a18f): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5932 1000 null
,D/SmartSyncUtils( 5932): isEpsOn(), nState = 0
,D/PMS     (  958): releaseWL(944a18f): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartDim(  958): Init customizeScreenOffDelayClass error
W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 5932): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5932): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 5932): isEpsOn(), nState = 0,
D/SmartSyncUtils( 5932): isEpsOn(), nState = 0
,W/ContextImpl( 5932): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  958): Setting HAL interactive mode to false
D/SurfaceControl(  958): Excessive delay in setPowerMode(): 302ms
D/PMS     (  958): Setting HAL interactive mode to false done
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  958): Setting HAL auto-suspend mode to true
D/PMS     (  958): Setting HAL auto-suspend mode done
,D/HABCtrl (  958): TPE algorithm. remove timeout.
,D/PMS     (  958): OOBE c monitor 11
,W/HtcSystemUPManager(  958): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
I/InputMethodManagerService(  958): screenObserver, isScreenOn=false
D/StatusBarManagerService(  958): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  958): Disable input method client, pid=3103
,W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/InputManager(  958): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
D/PMS     (  958): acquireWL(3e0265fa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
I/SensorManager(  958): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@1c68ccc9
W/SensorService(  958): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  958): disable: get sensor name = Accelerometer Sensor
I/IntentController( 1220): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/BatteryService(  958): n_update end
I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
D/PMS     (  958): releaseWL(3e0265fa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NfcService( 1541): ScreenObserver: OFF
I/PowerUsageList:PowerUsageHelper( 5932): PowerProfile::POWER_SCREEN_FULL = 154.8
D/NfcService( 1541): applyRouting - 0
,W/SensorService(  958): pid=958, uid=1000
W/SensorService(  958): Active sensors: size = 3
,D/PMS     (  958): acquireWL(3b73c7ab): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1541 1027 null
W/SensorService(  958): CM36686 Proximity sensor (handle=0x00000004, connections=1)
D/PMS     (  958): releaseWL(3b73c7ab): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/SensorService(  958): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  958): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  958): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1c68ccc9, eanble = 0, strlen(mName) = 36
W/SensorService(  958): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  958): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2f125f86
W/SensorService(  958): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  958): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  958): disable: get sensor name = CM36686 Proximity sensor
D/NfcService( 1541): applyRouting -2
D/NfcService( 1541): applyRouting
D/NfcService( 1541): Ignore this applyRouting...
W/SensorService(  958): pid=958, uid=1000
W/SensorService(  958): Active sensors: size = 2
W/SensorService(  958): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  958): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  958): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1c68ccc9, eanble = 0, strlen(mName) = 36
W/SensorService(  958): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  958): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2f125f86
W/SensorService(  958): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  958): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@1c68ccc9
,D/PowerUsageList:BatterySipperExt( 5932): gen(), null == sipper.uidObj, userId = 0
,I/ActivityManager(  958): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5966 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,E/ActivityThread(  958): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@337a9fce that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  958): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@337a9fce that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  958): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  958): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  958): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  958): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  958): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  958): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
,E/ActivityThread(  958): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  958): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  958): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  958): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  958): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  958): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  958): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  958): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  958): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  958): ,	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  958): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  958): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  958): updateBatteryInfo
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  958): plugged=true pluggin=true,
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/PMS     (  958): runPSCheck
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  958): Checking...
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/HtcPowerSaver(  958): >> updateStatus
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): handleMessage: E msg.what=155652
,I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  958): processMsg: ApStaDisabledState
I/HtcPowerSaver(  958): << updateStatus
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
I/ClockController( 1220): stop clock update:screen off
,D/PowerUsageService( 5932): calcPower(), no data,
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/PowerUsageList:PowerUsageHelper( 5932): MY_DEBUG = false,
,D/Process (  958): killProcessQuiet, pid=5608,
I/ActivityManager(  958): Killing 5608:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 5932): getMobilePolicyEnabled, result = true
,D/WifiService(  958): New client listening to asynchronous messages
E/WifiTrafficPoller(  958): ADD_CLIENT: 7
,I/ActivityManager(  958): Recipient 5608
,D/PMS     (  958): releaseWL(12f7dee1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  958): Killing 5660:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=5660
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5660
,I/CalendarProvider2( 5901): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 5901): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  958): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5990 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,D/Process (  958): killProcessQuiet, pid=5683
I/ActivityManager(  958): Killing 5683:com.android.settings/1000 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5683
,W/ResourcesManager( 5990): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/CalendarApplication( 5990): onCreate
,D/ProviderChangeReceiver( 5990): ---------------------------------------------------
,D/ProviderChangeReceiver( 5990): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  958): killProcessQuiet, pid=5776
I/ActivityManager(  958): Killing 5776:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 5990): start to updateAlertNotification!,
,I/ActivityManager(  958): Recipient 5776
,D/HtcAlertService( 5990): No fired or scheduled alerts,
D/HtcAlertUtils( 5990): -- cancelReminderNotification --
,D/HtcAlertUtils( 5990): broadcastExistReminder!,
,D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
,D/HtcUPManager( 1220): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  445): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  958): killProcessQuiet, pid=5354,
I/ActivityManager(  958): Killing 5354:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5354,
,D/PMS     (  958): acquireWL(30644e08): PARTIAL_WAKE_LOCK  *alarm* 0x1 958 1000 WorkSource{1000},
V/AlarmManager(  958): sending alarm PendingIntent{3500e7c6: PendingIntentRecord{21253387 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457427918454, Int=0
D/PMS     (  958): acquireWL(cabd9a1): PARTIAL_WAKE_LOCK  *backup* 0x1 958 1000 null
V/AlarmManager(  958): sending alarm PendingIntent{13f442b4: PendingIntentRecord{331e3f45 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=127118, Int=0
,D/PMS     (  958): acquireWL(368b6edd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  958): releaseWL(30644e08): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1881): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1881): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1881): [NET] android_getaddrinfo_proxy+
D/libc    ( 1881): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
W/BackupManagerService(  958): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1881): [NET] android_getaddrinfo_proxy-, NODATA
E/BackupManagerService(  958): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  958): releaseWL(cabd9a1): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  958): releaseWL(368b6edd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  445): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  445): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  958): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  958): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/PMS     (  958): acquireWL(1113ba52): PARTIAL_WAKE_LOCK  *alarm* 0x1 958 1000 WorkSource{10024},
V/AlarmManager(  958): sending alarm PendingIntent{35978123: PendingIntentRecord{3eecd620 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457427936554, Int=1800000,
V/AlarmManager(  958): sending alarm PendingIntent{30d51bd9: PendingIntentRecord{1c0f299e com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143525, Int=0
,V/AlarmManager(  958): sending alarm PendingIntent{247171db: PendingIntentRecord{3f606478 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=146851, Int=0
,V/AlarmManager(  958): sending alarm PendingIntent{1f570c7f: PendingIntentRecord{719344c android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=160982, Int=0
,D/PMS     (  958): acquireWL(32729c95): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4346 10024 WorkSource{10024 com.google.android.gms},
,D/libc    (  958): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, err=8
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024,
D/libc    (  958): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  958): [NET] android_getaddrinfo_proxy+
D/libc    (  958): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    (  958): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  958): acquireWL(3759f19b): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4346 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  958): releaseWL(1113ba52): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  958): releaseWL(32729c95): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 4346): Aggregate from 1457426136480 (log), 1457426136480 (data)
,D/PMS     (  958): releaseWL(3759f19b): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  445): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  958): acquireWL(25dc0c77): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
,D/UsbnetService(  958): BroadcastReceiver::onReceive+
I/BatteryService(  958): n_update end
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/PMS     (  958): releaseWL(25dc0c77): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): handleMessage: E msg.what=155652
D/HtcPowerSaver(  958): updateBatteryInfo
D/WifiController(  958): processMsg: ApStaDisabledState
,D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  958): processMsg: DefaultState
D/PMS     (  958): runPSCheck
D/WifiController(  958): handleMessage: X
D/HtcPowerSaver(  958): Checking...
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  958): >> updateStatus
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  958): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1525): switchBindHtcMsgCursor: null
,D/PMS     (  958): acquireWL(587c0e4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 958 1000 WorkSource{1000}
V/AlarmManager(  958): sending alarm PendingIntent{28b02468: PendingIntentRecord{e876081 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=166143, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{beac94d: PendingIntentRecord{1adb5c02 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186635, Int=0
,D/PMS     (  958): acquireWL(30faf913): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(30faf913): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(587c0e4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1220): Weather sync is On,
,W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  445): AtCmdFwd service not published, waiting... retryCnt : 5,
,TIME-OUT KILL (timeout was 150000ms),E/cutils-trace( 6017): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6017): ====startRecUseTime====
D/htc.customization.log.level( 6017):  is 
W/CustomizationLogLevel( 6017): Level value is invalid, use default level 2
D/CustomizationManager( 6017):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 6017): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6017): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6017): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6017): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6017): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6017): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6017): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6017): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6017): Parsing tag category name = system
I/CustomizationCIDLoader( 6017): Parsing tag category name = application
I/CustomizationCIDLoader( 6017): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6017): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6017): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6017): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6017): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6017): add string-array item, value = 42507
I/CustomizationCIDLoader( 6017): add string-array item, value = 21902
I/CustomizationCIDLoader( 6017): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6017): add string-array item, value = 23420
I/CustomizationCIDLoader( 6017): add string-array item, value = 22299
I/CustomizationCIDLoader( 6017): add string-array item, value = 24002
I/CustomizationCIDLoader( 6017): add string-array item, value = 23210
I/CustomizationCIDLoader( 6017): add string-array item, value = 23205
I/CustomizationCIDLoader( 6017): add string-array item, value = 23806
I/CustomizationCIDLoader( 6017): add string-array item, value = 23430
I/CustomizationCIDLoader( 6017): add string-array item, value = 23408
I/CustomizationCIDLoader( 6017): add string-array item, value = 27205
I/CustomizationCIDLoader( 6017): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6017): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6017): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6017): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6017): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6017): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6017): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6017): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6017): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6017): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6017): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6017): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6017):  Read CID file spent 0.112 (s)
D/CustomizationManager( 6017):  All configurations done spent 0.112 (s)
D/PackageManager(  958): deletePackageAsUser: pkg=com.example.hello, pid=6017, uid=2000 userid=0
D/Process (  958): killProcessQuiet, pid=3103
I/ActivityManager(  958): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
I/ActivityManager(  958): Killing 3103:com.example.hello/u0a374 (adj 0): stop com.example.hello
W/PackageSettings(  958): Skipping PackageSetting{238685ad com.test.thalitest/10366} due to missing metadata
I/ActivityManager(  958): Recipient 3103
I/WindowState(  958): WIN DEATH: Window{38affe0f u0 com.example.hello/com.example.hello.MainActivity}
E/InputEventReceiver( 1375): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1e0fa007 uid 10374 pid 3103} (c)'
I/WindowState(  958): WIN DEATH: Window{130b59f5 u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager(  958):   Force finishing activity ActivityRecord{3f79ea36 u0 com.example.hello/.MainActivity t12}
W/ActivityManager(  958): Spurious death for ProcessRecord{a720750 3103:com.example.hello/u0a374}, curProc for 3103: null
I/ActivityManager(  958): Force stopping com.example.hello appid=10374 user=0: pkg removed
D/DotMatrix( 1307): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1307): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
D/AccTypeManager( 1685): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  958): Cannot find grip_rejection_width, use default value instead
D/PMS     (  958): acquireWL(35a7364e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1685): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1814): Ignoring removeGeofence because network location is disabled.
D/PMS     (  958): releaseWL(35a7364e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/VoicemailCleanupService( 1655): Cleaning up data for package: com.example.hello
I/[PluginManager]RegisterService( 1498): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
I/art     ( 1577): Explicit concurrent mark sweep GC freed 3147(171KB) AllocSpace objects, 3(244KB) LOS objects, 34% free, 29MB/45MB, paused 916us total 66.901ms
D/Prism.PackageStateRece_( 1577): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1577): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1577): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1685): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1498): handle notify Blinkfeed plugin client changed
D/PhoneApp( 1525): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/Launcher( 1577): Deferring update until onResume
D/Launcher( 1577): waitUntilResume // bindAppsRemoved
E/ExternalAccountType( 1685): Unsupported attribute readOnly
I/ActivityManager(  958): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6037 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/InputMethodManagerService(  958): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/PackageManager(  958): Unable to load service info ResolveInfo{380af22d com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  958): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  958): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  958): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  958): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  958): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  958): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  958): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  958): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  958): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  958): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  958): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/art     (  958): Explicit concurrent mark sweep GC freed 22280(1711KB) AllocSpace objects, 5(556KB) LOS objects, 33% free, 18MB/27MB, paused 1.593ms total 187.465ms
W/asset   (  958): Copying FileAsset 0x55b363c210 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/JobSchedulerService(  958): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  958): removeObsoleteFile: deleting file=12_task.xml
D/TaskPersister(  958): removeObsoleteFile: deleting file=12_task_thumbnail.png
W/ContextImpl( 6037): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  958): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
W/ResourcesManager(  958): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/StatusBarManagerService(  958): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
I/ActivityManager(  958): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=6059 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/FindExtension( 1577): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1577): Defer allocateBuffers to drawing time
D/Process (  958): killProcessQuiet, pid=5633
I/ActivityManager(  958): Killing 5633:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/InputMethodManagerService(  958): Got RemoteException sending setActive(false) notification to pid 3103 uid 10374
D/StatusBarManagerService(  958): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
I/ActivityManager(  958): Recipient 5633
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 6059): -onCreate()
V/Settings:HtcSettingsApplication( 6059): [6059/6059] onCreate()
D/Process (  958): killProcessQuiet, pid=4828
I/ActivityManager(  958): Killing 4828:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/Settings:HtcWirelessFeatureFlags( 6059): id/is att sku: 118/false
I/ActivityManager(  958): Recipient 4828
E/Settings:HtcWrapHeaderInfo( 6059): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6059): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 6059): updateDevelopment, bPrefShow = true
E/SQLiteLog( 1881): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1881): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x55b2f7d0e0
E/AndroidRuntime( 1881): FATAL EXCEPTION: main
E/AndroidRuntime( 1881): Process: com.google.process.gapps, PID: 1881
E/AndroidRuntime( 1881): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1881): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1881): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1881): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1881): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1881): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1881): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1881): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1881): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1881): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1881): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1881): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1881): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1881): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1881): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1881): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1881): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1881): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1881): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1881): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1881): 	... 9 more
E/ActivityManager(  958): App crashed! Process: com.google.process.gapps
E/Settings:HtcUmcWidgetEnabler( 6059): isSupportMusicChannel(): false
D/Process ( 1881): killProcess, pid=1881
E/DropBoxManagerService(  958): Can't write: system_app_crash
E/DropBoxManagerService(  958): java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  958): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  958): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  958): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  958): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  958): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  958): 	... 5 more
D/Process ( 1881): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportHomeButton]support         :false
E/Settings:HtcVoWifiWidgetEnabler( 6059): isSupportVoWifi: null
I/ActivityManager(  958): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 6059): Failed to find provider info for com.htc.vowifi
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6059): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 6059): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 6059): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6059): [supportHomeButton]support         :false
I/ActivityManager(  958): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 6059): isSupportVoWifi: null
E/ActivityThread( 6059): Failed to find provider info for com.htc.vowifi
I/ActivityManager(  958): Recipient 1881
I/ActivityManager(  958): Process com.google.process.gapps (pid 1881) has died
W/ActivityManager(  958): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 1000ms
W/ActivityManager(  958): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
W/ActivityManager(  958): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 21000ms
W/ActivityManager(  958): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
I/ActivityManager(  958): Start proc com.google.process.gapps for service com.google.android.gms/.gcm.http.GoogleHttpService: pid=6092 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ResourcesManager( 6092): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6092): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6092): VM with version 2.1.0 has multidex support
I/MultiDex( 6092): install
I/MultiDex( 6092): VM has multidex support, MultiDex support library is disabled.
I/GservicesProvider( 6092): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 6092): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 6092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6092): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 6092): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 6092): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 6092): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 6092): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 6092): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 6092): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 6092): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 6092): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 6092): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6092): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6092): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 6092): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6092): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6092): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 6092): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6092): FATAL EXCEPTION: main
E/AndroidRuntime( 6092): Process: com.google.process.gapps, PID: 6092
E/AndroidRuntime( 6092): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6092): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 6092): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 6092): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 6092): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 6092): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 6092): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6092): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6092): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 6092): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6092): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6092): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 6092): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6092): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6092): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 6092): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 6092): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 6092): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 6092): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 6092): 	... 11 more
E/DropBoxManagerService(  958): Can't write: system_app_crash
E/DropBoxManagerService(  958): java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  958): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  958): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  958): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  958): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  958): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  958): 	... 5 more
E/ActivityManager(  958): App crashed! Process: com.google.process.gapps
D/Process ( 6092): killProcess, pid=6092
D/Process ( 6092): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  958): Recipient 6092
I/ActivityManager(  958): Process com.google.process.gapps (pid 6092) has died
W/ActivityManager(  958): Service crashed 2 times, stopping: ServiceRecord{20932e73 u0 com.google.android.gms/.gcm.http.GoogleHttpService}
W/ActivityManager(  958): Service crashed 2 times, stopping: ServiceRecord{112c60ef u0 com.google.android.gms/.gcm.GcmService}
W/ActivityManager(  958): Service crashed 2 times, stopping: ServiceRecord{9239d77 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
W/ActivityManager(  958): Service crashed 2 times, stopping: ServiceRecord{4f07cc7 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
I/Prism.ItemManager( 1577): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1577): loadItems() com.htc.launcher.pageview.WidgetManager@2d6e4ff +
I/Prism.WidgetManager( 1577): onLoadItems() +
W/ResourcesManager( 1577): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.

```
